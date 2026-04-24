<!-- ? ############################################# -->
<!-- ? Header -->

<h1 align="center">

![nlobby4][logo]![contributing][banner]

</h1>

<!-- ? ############################################# -->
<!-- ? Main Area -->

**Thank you for your interest in contributing!**

If you have questions, want to suggest features or report bugs, please open a
issue. Even if you don't want to contribute code, you can still help by
providing feedback and sharing your ideas.

> [!IMPORTANT]
>
> **Verify that your contribution is not already being worked on** by checking
> the open and closed issues as well as current pull requests. If a similar
> issue or pull request already exists, please comment on it or add a reaction
> to show your support.

---

If you want to contribute, please follow these guidelines to ensure a smooth
contribution process:

- **Open an issue** to discuss your proposed changes before you start working on
  them. This prevents duplicate work and allows maintainers to provide feedback
  early on.
- **Fork the repository** and create your branch from `main` using conventional
  branch naming based on the type of change you are making:

  ```bash
  # e.g. "feat/feature-name" or "fix/bug-description"
  git switch -c type/short-description
  ```

  If you are an organization member with write access, you can create a branch
  directly in the repository.

- **Use the dev container** during development if it is provided.
- **Add tests** for new features or bug fixes when possible and applicable.
- **Rebase your branch** on `main` before opening a pull request to keep history
  clean and resolve conflicts early:

  ```bash
  git pull --rebase origin main
  ```

- **Open a pull request** on GitHub with a clear description of your changes.
- **Update the PR title** to a
  [conventional commit](https://www.conventionalcommits.org/) message, this will
  be the squashed commit message when the PR is merged. The description will be
  included in the next release changelog.
- **Keep pull requests focused** to one concern which will make the review
  process faster and easier.
- **Delete your local branch** after your pull request has been merged to keep
  your repository clean:

  ```bash
  git branch -d type/short-description
  ```

- **Follow the [Code of Conduct](./CODE_OF_CONDUCT.md)**

---

<!-- ? ############################################# -->
<!-- ? Footer -->

<div align="right">

![footer][footer]

</div>

<!-- ? ############################################# -->
<!-- ? References -->

[logo]:
  https://media.githubusercontent.com/media/nlobby4/organization/refs/heads/main/project/repo/contributing/logo-contributing.png
[banner]:
  https://media.githubusercontent.com/media/nlobby4/organization/refs/heads/main/project/repo/contributing/banner-contributing.png
[footer]:
  https://media.githubusercontent.com/media/nlobby4/organization/refs/heads/main/project/repo/contributing/footer-contributing.png
