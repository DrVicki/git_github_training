# Now It Is Your Turn!

## Let's walk through a scenario where you collaborate on a simple Python project:

1. ## Create a new repository on GitHub called "collaborative-python-project"

2. ## Clone the repository locally:

``git clone https://github.com/yourusername/collaborative-python-project.git cd collaborative-python-project``
   

3. ## Create a Python file:
   ```bash
   echo "def greet(name):
       return f'Hello, {name}!'" > greetings.py
   ```

4. ## Add, commit, and push the file:
   ```bash
   git add greetings.py
   git commit -m "Add greet function"
   git push origin main
   ```

5. ## Create a new branch for a feature:
   ```bash
   git checkout -b add-farewell-function
   ```

6. ## Modify the Python file:
   ```bash
   echo "
   def farewell(name):
       return f'Goodbye, {name}!'" >> greetings.py
   ```

7. ## Commit and push the changes:
   ```bash
   git add greetings.py
   git commit -m "Add farewell function"
   git push origin add-farewell-function
   ```

8. ## Go to GitHub and create a pull request from the `add-farewell-function` branch to `main`

9. ## Review the changes, and if everything looks good, merge the pull request

10. ## Back in your local repository, on your machine, switch to the main branch and pull the changes:
    ```bash
    git checkout main
    git pull origin maingit add .

    ```

This example demonstrates the basic workflow of collaborating on a project using Git and GitHub, including creating branches, making changes, pushing to GitHub, creating pull requests, and merging changes.

### Remember, practice is key to mastering Git and GitHub. Encourage students to experiment with these commands and workflows on their own projects or in group assignments.

# SUBMISSION

1. ## After you have completed the Assignment, and everything looks great on GitHub.com. copy the URL Address to your assignment repository.
2. ## Paste the URL in the Canvas Assignment where indicated.

# Now Celebrate!!!!