# Contributing to {{ cookiecutter.package_distribution_name }}

## Set up for development

```bash
python -m pip install -e .
```

## Run the tests

```bash
python -c "from {{ cookiecutter.package_import_name }} import greet; print(greet('Hee'))"
```

Hello, Hee!

## Send a change

1. Create a branch from `main` and commit your change there.
2. Push the branch to GitHub.
3. Open a pull request into `main` and wait for a review.
