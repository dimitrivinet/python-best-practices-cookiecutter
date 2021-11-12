# {{cookiecutter.project_name}}

## Setup

```sh
# Activate virtual environment
source .venv/bin/activate

# Setup pre-commit and pre-push hooks
python3 -m  pre-commit install -t pre-commit
python3 -m  pre-commit install -t pre-push
```

## Credits

This package was created with Cookiecutter and the [dimitrivinet/python-best-practices-cookiecutter](https://github.com/dimitrivinet/python-best-practices-cookiecutter) project template forked from [sourcery-ai/python-best-practices-cookiecutter](https://github.com/sourcery-ai/python-best-practices-cookiecutter).
