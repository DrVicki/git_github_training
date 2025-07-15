# Learn Git

1. ## Install Git

First, you need to install Git on your computer.

### Go to your terminal as learned in README.

- For Windows: Download and install from
https://git-scm.com/download/win
- For macOS: On terminsal, install using Homebrew with `brew install git`
- For Linux: On terminal, use your package manager, e.g., `sudo apt-get install git`

2. ## Configure Git

After installation, configure your Git identity. ***You are still on your terminal.***

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

3. ## Create a Local Repository

Let's create a new project and initialize a Git repository. ***You are still on your terminal.***

```bash
mkdir my_project
cd my_project
git init
```

4. ## Make Changes and Commit

Create a file and make your first commit. ***You are still on your terminal.***

```bash
echo "# My Project" > README.md
git add README.md
git commit -m "Initial commit: Add README"
```

5. ## Viewing History

To see your commit history. ***You are still on your terminal.***

```bash
git log
```

6. ## Create Branches

Create and switch to a new branch. ***You are still on your terminal.***

```bash
git branch feature-branch
git checkout feature-branch
```

Or use the shorthand:

```bash
git checkout -b feature-branch
```

7. ## Merge Branches

After making changes in your feature branch, merge it back to main. ***You are still on your terminal.***

```bash
git checkout main
git merge feature-branch
```


Fantastic!!!

### NOTE
You might want to practice this several times, using a differrent project directory name, until you feel comfortable and understand what is happening.
