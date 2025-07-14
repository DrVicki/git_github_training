# Set Up GitHub

1. Create a GitHub account at
https://github.com
2. Create a new repository on GitHub

3. Connect Local Repository to GitHub

Link your local repository to the GitHub repository:

```bash
git remote add origin
https://github.com/yourusername/your-repo-name.git
git branch -M main
git push -u origin main
```

4. Push Changes to GitHub

After making local changes and committing, push to GitHub:

```bash
git push origin main
```

5. Pull Changes from GitHub

To get changes from GitHub:

```bash
git pull origin main
```

6. Clone a Repository

To clone an existing GitHub repository:

```bash
git clone
https://github.com/username/repository-name.git
```

7. Fork a Repository

1. On GitHub, navigate to the repository you want to fork
2. Click the "Fork" button in the top-right corner

8. Creating Pull Requests

1. Make changes in your forked repository
2. Go to the original repository on GitHub
3. Click "New pull request"
4. Select your fork and branch
5. Add a title and description
6. Click "Create pull request"
