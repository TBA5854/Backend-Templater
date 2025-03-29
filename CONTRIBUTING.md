# Contributions Guide

Thank you for contributing to this project! Please follow the guidelines below to ensure a smooth collaboration.

## Forking and Branching
1. **Fork the Repository**: Click the fork button on GitHub to create your own copy of the repository.
2. **Clone the Repository**: Clone your fork to your local machine using:
   ```sh
   git clone https://github.com/TBA5854/Backend-Templater-Cli.git
   ```
3. **Create a New Branch**: Name your branch based on the language and framework you are working on.
   ```sh
   git checkout -b language-framework
   ```
   Example: `ts-express`, `py-django`, `dart-flutter`

## Making Changes
1. Ensure your changes align with the project’s coding standards.
2. Run tests (if applicable) before pushing.
3. Write meaningful commit messages following the conventional commit format:
   ```sh
   git commit -m "feat: added feature X to Y in language-framework"
   git commit -m "fix: resolved bug in Z"
   git commit -m "chore: updated dependencies"
   ```
   **Types of commit messages:**
   - `feat`: Introducing a new feature
   - `fix`: Bug fixes
   - `chore`: Maintenance and dependencies updates
   - `docs`: Documentation updates
   - `refactor`: Code changes that do not add new features or fix bugs
   - `test`: Adding or improving tests

## Pushing and Creating a Pull Request
1. Push your branch to your fork:
   ```sh
   git push origin language-framework
   ```
2. Create a pull request:
   - Navigate to the original repository.
   - Click **New Pull Request**.
   - Select your branch and describe your changes.
   
## Review Process
- Maintain clean and readable code.
- Respond to requested changes promptly.
- Keep your branch updated with the latest main branch changes:
  ```sh
  git fetch upstream
  git merge upstream/main
  ```

## Code of Conduct
Be respectful and constructive in discussions.

Happy coding!

