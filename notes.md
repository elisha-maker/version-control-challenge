# Study Notes: Git and GitHub Basics

## What Is Version Control?

Version control is a system that records changes to files over time. It allows you to:

- Track what was changed, when, and by whom
- Revert files back to a previous state
- Compare changes over time
- Collaborate with others without overwriting each other's work

## Git Basics

Git is a distributed version control system that runs on your local machine.

### Key Concepts

- **Repository (repo):** A folder tracked by Git that stores your project files and their history.
- **Commit:** A snapshot of your project at a specific point in time.
- **Branch:** A separate line of development that lets you work on features without affecting the main code.
- **Merge:** Combining changes from one branch into another.

### Common Git Commands

| Command | Description |
|---------|-------------|
| `git init` | Initialize a new Git repository |
| `git clone <url>` | Copy a remote repository to your machine |
| `git status` | Check the current state of your files |
| `git add <file>` | Stage a file for the next commit |
| `git commit -m "message"` | Save staged changes with a message |
| `git push` | Upload commits to a remote repository |
| `git pull` | Download and merge changes from a remote |

## GitHub Workflow

GitHub is an online platform for hosting Git repositories. A typical workflow includes:

1. **Clone** the repository to your local machine
2. **Create a branch** for your changes
3. **Make changes** and commit them with clear messages
4. **Push** your branch to GitHub
5. **Open a pull request** to propose merging your changes
6. **Review** the changes and merge the pull request

## Best Practices

- Write clear, descriptive commit messages
- Commit often with small, focused changes
- Use branches for new features or fixes
- Review your own work before merging
