# Contributing Guidelines

Thank you for considering contributing to **my-agent-demo**! We welcome contributions from the community and aim to make the process as smooth as possible. Please follow the guidelines below to help us maintain a high-quality codebase.

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Submitting Pull Requests](#submitting-pull-requests)
- [Development Setup](#development-setup)
- [Commit Message Guidelines](#commit-message-guidelines)
- [License](#license)

## Code of Conduct
Please note that this project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How to Contribute
### Reporting Bugs
- **Search existing issues** before opening a new one to avoid duplicates.
- Include a clear title, steps to reproduce, expected behavior, actual behavior, and any relevant logs or screenshots.

### Suggesting Enhancements
- Open an issue describing the proposed change.
- Explain why the change is needed and any potential impact.

### Submitting Pull Requests
1. **Fork the repository** and clone your fork locally.
2. **Create a new branch** for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** and ensure the code follows the existing style.
4. **Write tests** if applicable and ensure all existing tests pass.
5. **Commit your changes** using clear, descriptive commit messages (see below).
6. **Push** your branch to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
7. Open a **Pull Request** against the `main` branch of this repository.
   - Provide a concise description of the changes.
   - Reference any related issue numbers (e.g., `closes #12`).
   - Ensure the PR passes all CI checks.

## Development Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/my-agent-demo.git
   cd my-agent-demo
   ```
2. **Install dependencies** (if any). This project currently has no external dependencies, but if you add any, list the installation steps here.
3. **Run tests** (if applicable):
   ```bash
   # Example command
   pytest
   ```

## Commit Message Guidelines
- Use the **imperative mood** (e.g., "Add feature X", "Fix bug Y").
- Keep the subject line under 50 characters.
- Separate the subject from the body with a blank line.
- Explain **what** and **why** in the body if the change is not obvious.

## License
By contributing, you agree that your contributions will be licensed under the same license as the project (MIT License).

---

Thank you for your contributions!