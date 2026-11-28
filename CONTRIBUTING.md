# Contributing Guidelines

Thank you for considering contributing to **my-agent-demo**! We welcome contributions of all kinds, including bug reports, feature requests, documentation improvements, and code changes.

## Getting Started

1. **Fork the repository**
   Click the **Fork** button at the top right of the repository page.

2. **Clone your fork**
   ```bash
   git clone https://github.com/<your-username>/my-agent-demo.git
   cd my-agent-demo
   ```

3. **Create a new branch**
   ```bash
   git checkout -b <feature-or-fix-name>
   ```

4. **Make your changes**
   - Follow the existing code style (PEP8 for Python, etc.).
   - Ensure the project builds and tests pass.

5. **Commit your changes**
   ```bash
   git add .
   git commit -m "Brief description of changes"
   ```

6. **Push to your fork**
   ```bash
   git push origin <feature-or-fix-name>
   ```

7. **Open a Pull Request**
   - Navigate to the original repository and click **New Pull Request**.
   - Provide a clear title and description of your changes.
   - Reference any related issues (e.g., `closes #12`).

## Code Style

- Use **PEP8** guidelines for Python code.
- Run `flake8` and `black` before submitting.
- Include docstrings for all public functions and classes.

## Testing

- Add unit tests for new functionality.
- Run existing tests with:
  ```bash
  pytest
  ```
- Ensure coverage does not decrease.

## Documentation

- Update the `README.md` or other docs if your change affects usage.
- Use clear, concise language.

## Issues

- Search existing issues before opening a new one.
- Provide a clear description, steps to reproduce, and expected vs. actual behavior.

## Thank You!

Your contributions help make this project better for everyone. Happy coding!
