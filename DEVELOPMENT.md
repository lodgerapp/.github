# Development Guidelines
Welcome to the Lodger Projects development guidelines! This document provides an overview of our development process and best practices to ensure smooth collaboration.

## Project Management
We handle our software tasks via GitHub Projects. Start a "Feature Request" on the Lodger GitHub Discussion before a pull request, enabling thorough consideration of potential changes.

## Pull Requests ("PR")
We actively welcome your pull requests. The general process is as follows:

1. Fork the repo and create your branch from `staging` (usually named `patch-%the number of PRs you've already made%`)
2. If you've added code that should be tested, add some test examples.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. Finally, ensure to describe your pull request.

## Commiting
All our projects follow the [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) guidelines. To standardize your commit messages, please adhere to the following steps:

1. Make sure your shell path is in the root directory of the project you're working on.
2. It is advisable to have [Commitizen / cz-cli](https://github.com/commitizen/cz-cli) installed on your local machine, if it isn't already.
3. Run `cz`. The prompt will generate your commit by guiding you through the following stages:
    1. Select the type of change.
    2. Type the scope. This is either `global` for project-wide changes or one of the packages's name (e.g. "web", "mobile", "api", "typescript", etc).
    3. Write a short, imperative tense description of the change (e.g. "add|create|update|remove button" instead of "added|created|updated|removed button").
    4. If the above was not sufficient, you may now write a longer description of your change (otherwise press enter to leave blank).
    5. 'y' or 'n' for whether there are any breaking changes (e.g. changing the props of a component, changing the JSON structure of an API response).
    6. 'y' or 'n' for whether this change affects an open issue, if positive you will be prompted to enter the issue number.

    Your commit should something like this:

    ```
    <type>[optional scope]: <description>
    [optional body]
    [optional footer(s)]
    ```
4. our commit message has now been created, you may push to your fork and open a pull request (read above for "PR" instructions).