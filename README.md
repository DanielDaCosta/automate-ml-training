# Automating ML model training using GitHub actions
Repo used as module for automating ML projects training using GitHub actions.

# Details

- Uses Flake8 for linting. Stop the build if there are Python syntax errors or undefined names
- Runs ```python train.py``` file for training ML model.
- Saves metrix.txt and confusion_matrix.png in GitHub for display.

# Usage

Copy and paste repo into your new project. Updates happens in:
```yml
  push:
    branches: [ master ]
  pull_request:
    branches: [ master ]
```

# Acknowledgments
- https://github.com/iterative/cml_base_case
- https://towardsdatascience.com/what-data-scientists-need-to-know-about-devops-2f8bc6660284
