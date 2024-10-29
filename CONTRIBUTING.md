
# Contributing to an AI-Powered Haircut Recommendation System

Welcome to the **AI-Powered Haircut Recommendation System**! We’re thrilled to have you participate in developing this project, especially during Hacktoberfest! Your contributions will help make our hairstyle recommendation system smarter, more accurate, and more enjoyable for users. Please review this guide to get started.

---

## Getting Started

### 1. Fork the Repository
Start by forking the repository to create your own copy of the project.

### 2. Clone Your Fork
Clone the forked repository to your local machine:
```bash
git clone https://github.com/your-username/haircut-recommendation-system.git
cd haircut-recommendation-system
```

### 3. Set Up the Environment
Install the required dependencies to run the project locally:

- **Python Dependencies**:
  ```bash
  pip install -r requirements.txt
  ```
  
- **JavaScript Dependencies** (Frontend):
  ```bash
  cd frontend
  npm install
  ```

- **Database Setup**:
  Configure MongoDB or PostgreSQL to store user data and hairstyle recommendations.

### 4. Create a New Branch
Create a new branch for each feature or bug fix you're working on:
```bash
git checkout -b feature/your-feature-name
```

## Contributing Guidelines

### Issue Selection
- Look through the [Issues](https://github.com/shouryamanekar/haircut-recommendation-system/issues) tab to find tasks labelled as `hacktoberfest`, `good first issue`, or `help wanted`.
- If you'd like to work on an issue, please feel free to comment on it to let us know you're taking it on.

### Code Standards
Please follow these coding conventions for consistency:
- **Python** (Backend): Follow PEP 8 standards. Use `black` or `flake8` for linting.
- **JavaScript** (Frontend): Use ESLint to ensure consistency.
- **Naming**: Use descriptive names for variables, functions, and commits.
- **Documentation**: Document your code where necessary, especially functions or methods that might not be self-explanatory.

### Testing
Ensure any features or fixes include relevant tests to verify functionality. For Python, use `unittest` or `pytest`. For JavaScript, consider using `Jest` or a similar testing library.

### Commit Messages
Write clear, concise commit messages:
- **Format**: Use the format `[type]: description`.
- **Types**: `feat` (feature), `fix` (bug fix), `docs` (documentation changes), `style` (formatting, missing semi-colons), `refactor` (code changes that neither fix a bug nor add a feature), `test` (adding or updating tests), `chore` (updating build tasks, package manager configs).
  
Example:
```bash
git commit -m "feat: add face shape classifier using CNN model."
```

### Pull Requests
1. **Push Changes**: Once your changes are complete, push them to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

2. **Open a Pull Request**: Go to the original repository and open a pull request (PR) from your forked branch. Provide a clear and concise description of what your PR accomplishes.

3. **Link to Issues**: If your PR addresses an issue, include `Closes #issue-number` in the PR description.

4. **Reviews**: Be open to feedback! Maintainers may request changes to ensure that all contributions meet project standards.

---

## Hacktoberfest Guidelines

- **Quality Contributions**: Hacktoberfest emphasizes quality over quantity. Please make sure each PR is meaningful and contributes to the project's improvement.
- **Avoid Spam**: PRs that are irrelevant or spammy may be marked as invalid, which can impact your Hacktoberfest completion status.
- **Labeling**: We'll label eligible Hacktoberfest contributions, so make sure your contributions align with project goals!

## Community and Support

If you have any questions or need clarification, feel free to:
- Comment on the issue or PR.
- Join discussions on our [Discussions](https://github.com/shouryamanekar/haircut-recommendation-system/discussions) page.

---

## Code of Conduct

We're committed to fostering a welcoming and inclusive environment for everyone. Please read and adhere to our [Code of Conduct](CODE_OF_CONDUCT.md).

Thank you for helping us build a smarter, user-friendly AI-powered haircut recommendation system! Your efforts make a difference.
Happy Hacking, and Happy Hacktoberfest!
