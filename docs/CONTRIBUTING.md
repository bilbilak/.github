# Contribution Guide

We appreciate your interest in contributing to this project! This document outlines the process for submitting code, documentation, or other types of contributions. Please read and follow these guidelines to ensure a smooth collaboration with the project maintainers.

Before participating in the project, please read our [Code of Conduct](https://github.com/bilbilak/.github/blob/main/docs/CODE_OF_CONDUCT.md). By engaging with this repository and its respective community, you agree to abide by its terms.

## 💻 Setting up your development environment

1. [Fork](https://repath.to/fork) the project on _GitHub_ to your own account.
    - If you are new to forking repositories, you can find a detailed guide on forking [here](https://docs.github.com/en/get-started/quickstart/fork-a-repo).
2. Clone your fork to your local development environment:
    ```
    git clone git@github.com:bilbilak/{project}.git
    cd {project}
    ```
3. Make sure you have the necessary tools installed — the required runtime and build toolchain, plus any dependencies the project needs.

**NOTE:** If you'd like to contribute to our documentation, please use [MyRepos](https://myrepos.branchable.com) tool to clone the project's _Wiki_. You can initiate the clone by running `mr checkout` as configured in the `.mrconfig` file. This will create the sub-repository under the `docs/wiki/` directory, separate from the main repository. To interact with this sub-repository, it's important to familiarize yourself with other `mr` commands.

## 📐 Coding conventions and best practices

When contributing to this project, please adhere to the following guidelines:

1. **Coding Conventions:** Follow the project's established coding conventions to keep the codebase consistent, readable, and maintainable. Before submitting, run the project's configured formatter and linter — address any issues or warnings they report. Each project may have its own language-specific style guide with detailed guidance. Commit messages must follow [Conventional Commits](https://www.conventionalcommits.org/) with a [gitmoji](https://gitmoji.dev/) prefix.
2. **Code Refactoring:** Consider using refactoring techniques to improve the structure of existing code without changing its behavior. Familiarize yourself with various design patterns that can make your code more efficient, scalable, and maintainable. You can find comprehensive guides and examples at [Refactoring Guru](https://refactoring.guru/).
3. **Cross-Platform Compatibility:** Ensure your code is portable across the target platforms the project supports. Avoid platform-specific APIs or assumptions unless properly guarded.
4. **Performance Optimization:** Write efficient code. Avoid unnecessary computation, prefer appropriate data structures, and leverage the language's concurrency or parallelism primitives when applicable. Use the project's profiling or benchmarking tools to measure performance objectively.
5. **Testing:** For each functionality you add or change, include corresponding tests. Run the project's test suite before submitting to ensure your changes pass and don't introduce regressions. Follow the testing patterns and conventions established in the project.

## 📤 Submitting your contribution

1. Create a new branch for your contribution:
    ```
    git checkout -b feature/{your-feature}
    ```
2. Make your changes and commit them with a descriptive message:
    ```
    git add .
    git commit -m "Add a brief description of your changes"
    ```
    - Writing clear and concise commit messages is important. For tips on how to write good commit messages, you can refer to [this guide](https://chris.beams.io/posts/git-commit/) tailored for projects following the _Gitflow_ approach.
3. Push your changes to your fork on _GitHub_:
    ```
    git push origin feature/{your-feature}
    ```
4. Create a pull request on the project's _GitHub_ repository, comparing the project's `develop` branch with your feature branch.
5. Fill out the pull request template with a description of your changes, and reference any relevant issues or discussions.

## 🧐 Review process

After submitting your pull request, the project maintainers will review your contribution. They may request changes or provide feedback before merging your changes into the development branch. Please be patient and address any comments or concerns raised by the maintainers.

<br>

💖 Thank you for your contribution! Your collaboration helps improve the project for everyone.
