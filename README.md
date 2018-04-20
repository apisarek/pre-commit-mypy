mypy mirror
===========

Mirror of mypy package for pre-commit

For pre-commit: see https://github.com/pre-commit/pre-commit

For mypy: see http://mypy.readthedocs.io/en/latest/index.html


### Using mypy with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/apisarek/pre-commit-mypy
        sha: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: mypy

You may override options with ```args``` property of the
hook in your config.
