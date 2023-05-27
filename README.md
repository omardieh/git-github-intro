# Basic Git Commands Exercise

## Initialize a Git Repository

- Create a new folder for your project.
- Open your command line interface (CLI) or terminal.
- Navigate to the project folder using the `cd` command.
- Type the command: `git init`
- This command initializes a new Git repository in your project folder.

## Create an HTML File

- Use a text editor or Integrated Development Environment (IDE) to create a new file named `index.html` within your project folder.
- Write some HTML code to create a basic webpage structure.

## Check the Status

- In your CLI or terminal, type the command: `git status`
- Git will show the status of your repository, indicating any changes made and untracked files.

## Add Files to the Staging Area

- Type the command: `git add index.html`
- This command adds the `index.html` file to the staging area to prepare for a commit.

## Remove Files from the Staging Area

- If you accidentally added a file to the staging area and want to remove it, use this command.
- Type the command: `git rm --cached <filename>` (replace `<filename>` with the file you want to remove)
- This command removes the file from the staging area, but keeps it in your working directory.

## Commit Changes

- Type the command: `git commit -m "Initial commit"`
- This command commits your changes to the repository, with a descriptive message explaining the commit.

## View Commit History

- Type the command: `git log`
- Git will display a log of all your commits, including commit hashes, authors, dates, and commit messages.

## Push Changes to a Remote Repository

- Create a remote repository on a Git hosting platform (e.g., GitHub).
- Connect your local repository to the remote repository.
- Type the command: `git push origin master`
- This command pushes your local commits to the remote repository's master branch.

## Create and Switch to a New Branch

- Type the command: `git checkout -b feature`
- This command creates a new branch named `feature` and switches to it, allowing you to work on a separate feature.

## Make Changes and Commit

- Modify the `index.html` file, add new features, or make any desired changes.
- Add and commit the changes using the `git add` and `git commit` commands.

## Push the New Branch

- Type the command: `git push origin feature`
- This command pushes the changes in the `feature` branch to the remote repository.

## Clone the Remote Repository

- Find the Git repository URL of your project (e.g., from GitHub).
- Open your CLI or terminal.
- Navigate to the desired location where you want to clone the repository.
- Type the command: `git clone <repository-url>` (replace `<repository-url>` with the actual URL)
- This command creates a local copy of the remote repository on your computer.

Congratulations! You've completed the exercise, covering basic Git commands in a web development scenario. Remember to practice these commands regularly to become more comfortable with version control and collaboration using Git. Happy coding!
