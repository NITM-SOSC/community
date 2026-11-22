# Your First Open-Source Contribution

<div align="center">

**YOUR JOURNEY INTO OPEN SOURCE STARTS HERE.**

A practical guide to making your first contribution to an open-source project.

*Explore. Learn. Experiment. Contribute.*

</div>

---

## 01 / Welcome to Open Source

Everyone starts somewhere.

You don't need to be an experienced developer, know multiple programming languages or have an impressive GitHub profile to contribute to open source.

You just need curiosity, a willingness to learn and the courage to make your first contribution.

At **NITM-SOSC**, we believe that the best way to understand technology is to explore it, experiment with it and build with it.

This guide will walk you through your first open-source contribution, from finding a project to getting your Pull Request merged.

**What you'll accomplish:**

- Discover an open-source project.
- Understand issues and contribution opportunities.
- Learn the Git and GitHub workflow.
- Make changes to a project.
- Submit your first Pull Request.
- Understand code reviews and collaboration.

---

## 02 / What Is Open Source?

Open-source software is software whose source code is made available under a licence that allows people to use, study, modify and redistribute it under specified conditions.

Instead of working in isolation, developers collaborate to improve software that others can use.

You can contribute by:

| Contribution | Example |
|---|---|
| Code | Fix bugs or implement features |
| Documentation | Improve README files and guides |
| Testing | Identify bugs and write tests |
| Design | Improve interfaces and accessibility |
| Research | Explore technologies and document findings |
| Community | Help newcomers and review contributions |

You don't have to start by writing hundreds of lines of code.

A meaningful contribution can begin with correcting a single mistake in documentation.

---

## 03 / Set Up Your Environment

Before contributing, prepare your development environment.

### A. Create a GitHub Account

If you don't already have one, create an account:

https://github.com/

Complete your profile with a username, profile picture and a short description of your interests.

### B. Install Git

Git is a distributed version control system used to track changes in source code.

Download Git:

https://git-scm.com/downloads

Verify your installation:

```bash
git --version
```

### C. Configure Git

Set your name and email address:

```bash
git config --global user.name "Your Name"

git config --global user.email "your-email@example.com"
```

Check your configuration:

```bash
git config --global --list
```

### D. Choose a Code Editor

You can use any editor you prefer.

Some popular options:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Vim](https://www.vim.org/)
- [Neovim](https://neovim.io/)
- [Zed](https://zed.dev/)

---

## 04 / Find Your First Project

Start by exploring projects that interest you.

You can discover projects through:

- [NITM-SOSC Repositories](https://github.com/orgs/NITM-SOSC/repositories)
- [GitHub Explore](https://github.com/explore)
- [GitHub Topics](https://github.com/topics)
- [Good First Issues](https://goodfirstissue.dev/)

### Look for beginner-friendly issues

GitHub repositories often use labels to identify contribution opportunities.

| Label | Meaning |
|---|---|
| `good first issue` | Suitable for newcomers |
| `help wanted` | Maintainers need contributors |
| `documentation` | Documentation improvements |
| `bug` | Something needs fixing |
| `enhancement` | Feature improvements |

### Before starting

1. Read the issue description.
2. Understand the expected outcome.
3. Check whether someone is already working on it.
4. Review the project's contribution guidelines.
5. Comment on the issue if you intend to work on it.

**Important:** Don't randomly modify a project without understanding its purpose and contribution requirements.

---

## 05 / Understand the GitHub Workflow

Most collaborative open-source projects follow a workflow involving four important concepts.

| Concept | Explanation |
|---|---|
| Repository | The project's source code and files |
| Fork | Your own copy of another repository |
| Branch | An independent line of development |
| Pull Request | A proposal to merge your changes into the original project |

The typical workflow looks like this:

```text
Original Repository
        |
        v
       Fork
        |
        v
   Your GitHub Account
        |
        v
       Clone
        |
        v
   Create a Branch
        |
        v
    Make Changes
        |
        v
      Commit
        |
        v
       Push
        |
        v
   Pull Request
        |
        v
   Code Review
        |
        v
      Merged
```

---

## 06 / Fork the Repository

Once you've selected a project:

1. Open its GitHub repository.
2. Click the **Fork** button.
3. Select your personal GitHub account.
4. Create the fork.

You now have your own copy of the original project.

You can make changes to your fork without directly modifying the original repository.

---

## 07 / Clone Your Fork

Cloning downloads your fork onto your local computer.

Open your terminal:

```bash
git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git
```

Navigate into the project:

```bash
cd REPOSITORY-NAME
```

Your local directory now contains the project's files.

### Connect the original repository

Add the original project as an upstream remote:

```bash
git remote add upstream https://github.com/ORIGINAL-OWNER/REPOSITORY-NAME.git
```

Check your remotes:

```bash
git remote -v
```

You should see:

- `origin` — Your fork.
- `upstream` — The original repository.

This helps you keep your fork synchronised with the original project.

---

## 08 / Create a New Branch

Never make your contribution directly on the main branch unless the project explicitly instructs otherwise.

Create a separate branch:

```bash
git checkout -b feature/your-contribution
```

Examples:

```bash
git checkout -b docs/improve-readme

git checkout -b fix/login-error

git checkout -b feature/add-search
```

A descriptive branch name makes your work easier to understand and review.

---

## 09 / Make Your First Changes

Open the project in your preferred code editor.

For Visual Studio Code:

```bash
code .
```

Explore the project structure and understand the relevant files before modifying anything.

Follow these principles:

- Read existing code before changing it.
- Follow the project's coding conventions.
- Keep your changes focused.
- Avoid unrelated modifications.
- Add tests where appropriate.
- Update documentation when necessary.

### Inspect your changes

Check the modified files:

```bash
git status
```

Review the actual differences:

```bash
git diff
```

Make sure your changes do exactly what you intended.

---

## 10 / Commit Your Changes

A commit records a snapshot of your work.

Stage your changes:

```bash
git add .
```

Create a descriptive commit:

```bash
git commit -m "docs: improve installation guide"
```

### Recommended commit message conventions

| Prefix | Usage |
|---|---|
| `feat:` | New functionality |
| `fix:` | Bug fixes |
| `docs:` | Documentation |
| `refactor:` | Code restructuring |
| `test:` | Testing changes |
| `chore:` | Maintenance tasks |

Use meaningful messages instead of vague descriptions such as `update`, `changes` or `final`.

---

## 11 / Push Your Changes

Push your branch to your fork:

```bash
git push -u origin feature/your-contribution
```

Your branch is now available on GitHub.

Open your fork in your browser.

GitHub may display a notification suggesting that you create a Pull Request.

---

## 12 / Create Your First Pull Request

A Pull Request (PR) is a proposal to merge your changes into the original repository.

Follow these steps:

1. Open your fork.
2. Select **Compare & pull request**.
3. Check the base repository.
4. Select the appropriate target branch.
5. Add a descriptive title.
6. Explain what you changed and why.
7. Reference the related issue, if applicable.
8. Submit your Pull Request.

### Example Pull Request

**Title:**

`docs: improve project installation instructions`

**Description:**

```text
## What does this PR do?

Improves the installation documentation.

## Changes made

- Clarified installation requirements.
- Added missing setup instructions.
- Improved command formatting.

## Related Issue

Closes #12
```

Always follow the target repository's Pull Request template when one is provided.

---

## 13 / Understand Code Reviews

Your Pull Request may be reviewed by project maintainers.

They might:

- Approve your changes.
- Ask questions.
- Suggest improvements.
- Request additional modifications.

If changes are requested, make them on the same branch.

For example:

```bash
git add .
git commit -m "fix: address review feedback"
git push
```

Your Pull Request will automatically receive the new commits.

Be patient and constructive throughout the review process.

A code review is an opportunity to learn, not a competition.

---

## 14 / Keep Your Fork Updated

Before starting another contribution, synchronise your local main branch with the original repository.

```bash
git checkout main

git fetch upstream

git merge upstream/main

git push origin main
```

If the original repository uses a different default branch, replace `main` with that branch name.

Always check the project's instructions before updating your fork.

---

## 15 / Your First Contribution Checklist

Use this checklist to track your progress.

- [ ] Created a GitHub account.
- [ ] Installed Git.
- [ ] Configured Git.
- [ ] Found an open-source project.
- [ ] Selected an appropriate issue.
- [ ] Forked the repository.
- [ ] Cloned my fork.
- [ ] Created a new branch.
- [ ] Made and tested changes.
- [ ] Committed my changes.
- [ ] Pushed my branch.
- [ ] Opened a Pull Request.
- [ ] Responded to review feedback.

<details>
<summary><strong>What if my first Pull Request gets rejected?</strong></summary>

That's completely normal.

Not every Pull Request gets merged. Sometimes a proposed change is unnecessary, outside the project's scope or implemented differently from what maintainers expect.

Read the feedback, understand the reasoning and use it to improve your next contribution.

A rejected Pull Request does not make your effort worthless.

</details>

---

## 16 / Continue Learning

Here are some useful resources for developing your open-source skills.

| Resource | What you'll learn |
|---|---|
| [GitHub Skills](https://skills.github.com/) | Interactive GitHub learning |
| [Git Documentation](https://git-scm.com/doc) | Git fundamentals |
| [GitHub Docs](https://docs.github.com/) | GitHub collaboration |
| [First Contributions](https://firstcontributions.github.io/) | First Pull Request walkthrough |
| [Open Source Guides](https://opensource.guide/) | Understanding open source |
| [GitHub Explore](https://github.com/explore) | Discovering projects |

---

## 17 / Your Journey Starts Here

Your first contribution might be a documentation correction, a small bug fix or a new feature.

What matters is that you start.

Explore projects. Ask questions. Experiment with ideas. Collaborate with others.

The open-source ecosystem grows because people are willing to share what they know and learn from what others build.

**You don't have to be an expert to contribute. You become better by contributing.**

---

<div align="center">

### NITM-SOSC

**Learn Independently · Build Collaboratively · Contribute Globally**

<sub>An independent, student-led open-source community</sub>

<sub>National Institute of Technology Manipur · India</sub>

</div>
