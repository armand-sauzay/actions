# Repository Name

This repository contains two GitHub Actions: Commitlint Action and Pre-commit Action.

## Commitlint Action

The [Commitlint Action](commitlint/action.yaml) lints commit messages using commitlint. It is set up to run with Node.js version 16 by default, but this can be configured. The action runs on both pull requests and pushes to the main branch.

## Pre-commit Action

The [Pre-commit Action](pre-commit/action.yaml) runs pre-commit in your GitHub Actions workflow. It is set up to run with Python version 3.8 by default, but this can be configured. The action also supports passing extra arguments to pre-commit.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.