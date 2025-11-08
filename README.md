# GitHub Action TypeScript Template

<p align="center">

[![Copier](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-black.json&style=for-the-badge)](https://github.com/copier-org/copier)
[![Build Status](https://img.shields.io/github/actions/workflow/status/brpaz/copier-github-action-ts/ci.yml?branch=main&style=for-the-badge)](https://github.com/brpaz/copier-github-action-ts/actions)

</p>

> A template for building GitHub Actions using TypeScript, Nix.

## 📦 What is included?

- [Nix](https://nixos.org/) and [Devenv](https://devenv.sh/) for managing the development environment and dependencies.
- [PNPM](https://pnpm.io/) for fast and efficient package management.
- [TSDown](https://github.com/ulixee/tsdown) for bundling the TypeScript code.
- [ESLint](https://eslint.org/) and [Prettier](https://prettier.io/) for code quality and formatting.
- [Husky](https://typicode.github.io/husky/#/) for managing Git commit hooks.
- [Actionlint](https://github.com/rhysd/actionlint) for linting GitHub Actions workflow files.
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for consistent commit messages.

## 🚀 Getting Started

### Pre-Requisites

This template is built with [Copier](https://copier.readthedocs.io/en/stable/), a Python based project templating tool.

To install copier on your system, follow the instructions at [Copier Website](https://copier.readthedocs.io/en/stable/#installation)

### Usage

To create a new project using this template, run the following command:

```bash
copier copy gh:brpaz/github-action-ts-template /path/to/your/new/project
```

And answer the prompts to customize your new project.

## 🗒️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.