# COMP3104 Group Assignment

## Project Overview

This repository contains the COMP3104 DevOps group assignment. It shows Git version control, branching strategies, collab through GitHub, and continuous integration using the GitHub Actions.

## Group Members

- **Team Leader:** Ethan Dennis — [EthanD42](https://github.com/EthanD42)
- **Team Member 2:** Ethan Dennis Second Account - [jackb42043](https://github.com/jackb42043)

## Branching Strategy

Each account works on a separate branch. Changes are merged into `main` through pull requests.

## Project Goals

The goal of this project is to show  how Git and GitHub can be used to manage software development work. It also shows how separate branches, pull requests, and automated workflows help keep changes organized and make it easier to check code before merging.

## CI/CD

GitHub Actions will be configured to auto run when changes are pushed to the repository.

## Branches

Each account has its own branch to work on its changes before merging them into `main`.

- `101579407-Ethan` — Ethan Dennis's main account.
- `Ethan-account2` — Ethan Dennis's second account.

## GitHub Actions

The repository has a GitHub Actions workflow that runs when changes are pushed to the configured branches or when a pull request is made to `main`. It prints messages to show that the workflow has run.

The workflow file is located at `.github/workflows/ci.yml`.

## Benefits of Version Control

Version control helps developers keep track of changes made to a project over time. Branches allow team members to work on separate features without immediately changing the main branch. Pull requests also give team members a chance to review changes before they are merged, helping keep the project organized.

## Pull Request Template

The repository also has a pull request template to help keep pull requests organized and make it easier to check changes before merging them. It is located at `.github/PULL_REQUEST_TEMPLATE.md`.