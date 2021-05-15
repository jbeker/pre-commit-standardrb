# pre-commit-standardrb

This is a plugin for [pre-commit](https://pre-commit.com) that will run [Standard, a Ruby style guide, linter, and formatter](https://github.com/testdouble/standard).

### pre-commit

[https://github.com/pre-commit/pre-commit](https://github.com/pre-commit/pre-commit)

### standardrb

[https://github.com/testdouble/standard](https://github.com/testdouble/standard)

## Using standardrb with pre-commit

    - repo: https://github.com/jalessio/pre-commit-standardrb
      rev: ''  # Use the sha / tag you want to point at
      hooks:
        - id: standardrb
