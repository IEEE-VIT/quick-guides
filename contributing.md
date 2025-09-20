# Contribution Guidelines

Welcome! We are excited that you are interested in contributing to our project. This document provides guidelines and best practices to follow when contributing.

---

## 1. How to Contribute

We welcome contributions in various forms, including:

-   Reporting bugs
-   Suggesting new features
-   Improving documentation
-   Writing code

To ensure a smooth collaboration, please follow the guidelines below.

---

## 2. Reporting Bugs and Suggesting Features (Issues)

If you find a bug, have a feature request, or want to suggest an improvement, please open an "issue". Issues are a great way to track tasks and discussions.

### Before Opening an Issue:

-   **Search existing issues:** Make sure a similar issue has not already been opened.
-   **Provide details:** If you are reporting a bug, include steps to reproduce it. For feature requests, explain the problem you are trying to solve.

### Opening an Issue:

-   Use the provided issue templates if available.
-   Be clear and concise in your description.
-   Add appropriate labels to categorize the issue (e.g., "bug", "enhancement").

---

## 3. Your First Code Contribution

Ready to contribute code? Here is how to get started:

### a. Setting Up the Project

1.  **Fork the repository:** This creates your own copy of the project.
2.  **Clone your fork:** Download your forked repository to your local machine.
    ```bash
    git clone https://github.com/YOUR_USERNAME/repository-name.git
    ```
3.  **Create a branch:** Create a new branch for your changes. A good branch name is descriptive of the feature or fix you are working on.
    ```bash
    git checkout -b your-branch-name
    ```
    *Valid branch names:* `fix-authentication-bug`, `add-user-profile-feature`
    *Invalid branch names:* `my-changes`, `test-branch`

### b. Making Changes and Committing

1.  **Make your changes:** Write your code and test it thoroughly.
2.  **Commit your changes:** Save your changes with a clear and descriptive commit message.

#### Commit Message Guidelines

-   A good commit message helps everyone understand the changes you made.
-   Always write it in **imperative tense** (e.g., “Add feature”, “Fix bug”) instead of past tense (“Added”, “Fixed”).  

For small changes, you can use a single-line message:
    ```bash
    git commit -m "fix: Correct a typo in the documentation"
    ```
    A common format is `<type>: <subject>`, where `type` can be `feat` (feature), `fix` (bug fix), `docs` (documentation), `refactor`, etc.

-   For larger changes, it is better to write a more detailed message. When you run `git commit` without `-m`, a text editor will open for you to write a longer message.
    ```
    A brief summary of the commit (50-70 characters)

    A more detailed explanation of the changes, if necessary.
    Explain the "why" behind your changes, not just the "what".
    ```

#### Squashing Commits

-   Before you open a pull request, it is a good practice to combine multiple small commits into a single, logical commit. This is called "squashing".
-   You can use interactive rebase to squash your commits:
    ```bash
    # Replace 'N' with the number of commits you want to squash
    git rebase -i HEAD~N
    ```
-   This will open a text editor where you can choose which commits to squash.

### c. Submitting Your Contribution (Pull Requests)

1.  **Push your changes:** Upload your changes to your forked repository.
    ```bash
    git push origin your-branch-name
    ```
2.  **Open a Pull Request (PR):** Go to the original repository on GitHub and open a pull request from your branch to the main branch of the project.
3.  **Describe your PR:** Write a clear description of the changes you have made. If your PR fixes an issue, link to that issue.
4.  **Wait for review:** Project maintainers will review your code and may ask for changes. Be prepared to discuss your work and make adjustments.

---

## 4. Code of Conduct

-   **Be respectful:** Treat everyone with respect. Healthy debates are encouraged, but be kind.
-   **Be clear:** Communicate clearly and concisely. Provide context when needed.
-   **No harassment:** Harassment and exclusionary behavior are not acceptable.

---

## 5. Coding Style

-   Follow the existing coding style of the project.
-   Write clean, maintainable, and testable code.
-   Add comments to your code where necessary to explain complex logic.
-   Ensure that your code is well-documented.
-   Use gender-neutral language in all documentation and comments (e.g., use "they/them" instead of "he/she").
