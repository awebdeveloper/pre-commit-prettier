Tslint for pre-commit
========================

Mirror of Tslint package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For Tslint: see https://github.com/palantir/tslint


### Using Tslint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/awebdeveloper/pre-commit-tslint/
        sha: ''  # Use the sha or tag you want to point at
        hooks:
        -   id: tslint
