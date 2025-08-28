# Contributing Guidelines

Thank you for considering contributing to the **not-mt** organization!  
We welcome all contributions, whether it's code, documentation, testing, or feedback.  
This document outlines the process to help ensure contributions are smooth, consistent, and maintainable.

---

## 📌 How to Contribute

1. **Find an Issue**
   - Check the repository’s [Issues](../../issues) tab.
   - Look for issues labeled `good first issue`, `help wanted`, or other tags.
   - If you’d like to propose something new, please open an issue first to discuss it.

2. **Fork and Branch**
   - Fork the repository.
   - Clone your fork locally.
   - Create a feature branch using [Conventional Commit](https://www.conventionalcommits.org/) conventions:
     ```
     <type>/<short-description>
     ```
     Examples:
     - `feat/add-config-loader`
     - `fix/handle-null-values`
     - `docs/update-readme`
     - `chore/ci-improvements`

   - If working on an issue, you may prefix with the issue number:
     - `feat/#123-add-codecov-integration`

3. **Make Your Changes**
   - Write clean, well-documented, and tested code.
   - Follow the style and structure of the repository.
   - Ensure your changes pass all tests and linting.

4. **Commit Your Changes**
   - Use **Conventional Commits** format:
     ```
     <type>(optional-scope): <short summary>
     ```
     Examples:
     - `feat(config): add YAML config loader`
     - `fix(api): handle missing authentication headers`
     - `docs: update contributing guidelines`
     - `chore(ci): add Codecov integration`

   - Common commit types:
     - `feat`: A new feature
     - `fix`: A bug fix
     - `docs`: Documentation changes
     - `style`: Code style/formatting (no functional changes)
     - `refactor`: Code refactoring
     - `test`: Adding or fixing tests
     - `chore`: Maintenance, CI/CD, dependencies

5. **Push and Open a Pull Request**
   - Push your branch to your fork.
   - Open a Pull Request (PR) to the main repository.
   - Use a clear title and description.
   - Reference related issues (e.g., `Closes #123`).

---

## ✅ Code Quality

- Follow [PEP 8](https://peps.python.org/pep-0008/) for Python code.
- Write [Google-style docstrings](https://google.github.io/styleguide/pyguide.html#38-comments-and-docstrings).
- Ensure all functions and classes have docstrings.
- Run the test suite locally before opening a PR.
- Keep PRs focused and small for easier review.

---

## 🔄 Review Process

- Maintainers will review PRs for correctness, clarity, and alignment with project goals.
- You may be asked to make changes — this is normal and part of collaboration.
- Once approved, your PR will be merged.

---

## 📦 Release Management

- Releases are automated with [Semantic Versioning](https://semver.org/) and [Conventional Commits](https://www.conventionalcommits.org/).
- Commit messages drive version bumps and changelog entries.
- Do not manually update version numbers — automation will handle it.

---

## 📝 License

By contributing, you agree that your contributions will be licensed under the repository’s license (usually MIT or Apache 2.0).

---

## 💬 Questions?

If you’re unsure about anything:
- Open a [Discussion](../../discussions) in the repository.
- Or ask in the issue you’re working on.

We’re glad you’re here, and we look forward to your contributions! 🚀
