# Setting Up Trusted Publishing

## On GitHub

1. Repository Settings
2. Environments
3. Create New Environment
    1. `testpypi` or `pypi`
    2. Enable required reviewers and pick someone (save after this or it gets reset during the next step)
    3. Add branch/tag restriction
    4. Set this as you want: I went with `v*` for tags

## On PyPI

1. Go to Account Settings
2. Choose "Publishing" in the sidebar
3. Add a new pending publisher
    1. PyPI project name as you wish
    2. Owner and Respository name as required
    3. Workflow name `release.yaml`
    4. Environment name `testpypi` or `pypi`
