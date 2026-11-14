# Beginner Contributor Guide for gz-sim

Welcome! 🎉

This guide is aimed at first‑time contributors to the **gz‑sim** repository. Follow these steps to get set up, make your first contribution, and have a smooth experience.

---

## 1. Prerequisites

- **Operating System**: Linux (Ubuntu 22.04 is recommended) or macOS.
- **Dependencies**:
  - Install ROS 2 (Humble) or the version used by the project.
  - Install Bazel (version 6.x) if you want to build with Bazel, otherwise CMake works as well.
  - Install standard development tools: `git`, `gcc`, `g++`, `cmake`, `python3`.
- **Python packages**: `pip install -r requirements.txt` (if a `requirements.txt` exists in the repo).

---

## 2. Clone the Repository

```bash
git clone https://github.com/patelshivani2283-lab/gz-sim.git
cd gz-sim
```

---

## 3. Create a Feature Branch

```bash
git checkout -b beginner‑guide
```

> **Tip**: Keep branch names short and descriptive, e.g., `doc‑beginner‑guide`.

---

## 4. Make Your First Change

Add a simple documentation file (this one!) or improve the `README.md` with a "Contributing" section.

```bash
# Edit files with your favourite editor, then stage them
git add BEGINNER_GUIDE.md
```

---

## 5. Commit Your Changes

```bash
git commit -m "Add beginner contributor guide"
```

---

## 6. Push the Branch

```bash
git push origin beginner‑guide
```

---

## 7. Open a Pull Request

- Go to the repository on GitHub.
- You should see a prompt to open a PR from your recently pushed branch. Click **"Compare & pull request"**.
- Fill out the PR template:
  - **Title**: `Add beginner contributor guide`
  - **Description**: Explain what you added and why it helps newcomers.
- Add the `documentation` label (if available) and request a review from a maintainer.

---

## 8. Respond to Feedback

Maintainers may ask for small changes. Commit them to the same branch and they will be added to the PR automatically.

---

## 9. Celebrate 🎉

Once your PR is merged, you’ve made your first contribution! Feel free to pick up another issue or suggest new ideas.

---

## Helpful Links

- [GitHub Issues] – Browse existing issues to find something to work on.
- [Project's CONTRIBUTING.md] – (If it exists, read it for style guidelines.)
- [ROS 2 Documentation] – https://docs.ros.org/en/humble/
- [Bazel Documentation] – https://bazel.build/

---

*Happy hacking!*