---
title: GitHub Desktop
---
# GitHub Desktop (DVCS) - Exercise (2 Marks)

# Using GitHub Desktop

Follow these steps to create a repository for your Visual Studio solution.

- Create a new blank Visual Studio solution in your local GitHub folder (under My Documents) and name it DVCS Exercise and check Create new Git repository. Then add a web application in your solution folder, naming it as DVCS_Website. Select Web Forms and ensure Authentication is Individaul User Accounts. Turn off Host in cloud. When you are done, close down Visual Studio, saving all your changes.
- Drag the solution folder onto GitHub Desktop. This will allow you to add your repository folder into the list of repositories in github DeskTop. Make sure that you a .gitignore file in your repository folder.
- Commit your visual studio files and solution.
- Publish the repository to GitHub (you must leave it as a **public** repository for this execise only). This will sync its contents with your GitHub account.
- Test that you did it correctly
    - Log off of your current computer, and log onto a different computer.
    - Using GitHub Desktop, clone your repository.
    - Open the solution and press CTRL + F5. If you did everything right, it should build and launch in the browser.
- Through your browser on GitHub.com, ensure that your repository has a README file. Click the green Create ReadMe.md file button. Add your name to this file. Commit the changes.
- Open your Visual Studio solution – "DVCS Exercise.sln" – and modify your Site.master file by putting your name in the navigation bar (replacing the "Application name").

    ```html
    <a class="navbar-brand" runat="server" href="~/">Application name</a>
    ```
    
- Commit your local changes, and synchronize your local and remote repositories.
- Make five other changes to your solution (add web pages, etc.), committing each change separately. Be sure to use meaningful commit messages.

# Matching

Match the following descriptions of the GitHub Desktop user-interface with the labels on the screen-shot. Place your answers in the `ReadMe.md` file of your repository for this exercise. Clearly identify your question number and your answer.

1. Commits History/Changes
2. Sync (push/pull) with Origin
3. Alterations of committed item
4. General Operational Tools for Maintenance
5. Change branch
6. Current (selection of) repository

![](./dvcs/new_desktop_jan2018.png)

# Short Answer & Multiple Choice

Supply or identify the following short answer/multiple-choice questions. Place your answers in the `ReadMe.md` file of your repository for this exercise. Clearly identify your question number and your answer.

1. Under which menu item is the Show in Explorer option. ____________________________
1. Under which menu item can you Add or Clone repositories. ____________________________
1. Under which menu item can you open your Command Prompt. ____________________________
1. List the four views that you can change to under View.
1. List the two items you can edit under Repository → Repository settings ...
1. A remote repository is ________.
    1. A code repository that is on your local computer.
    1. A database that is seldom used/accessed by an application (typically, a dormant web application).
    1. A code repository that is not on your local computer.
    1. A code repository that is kept in a location outside the continental USA.
1. A local repository is ________.
    1. A code repository that is on your local computer.
    1. A database whose connection string specifies `data-source="."`.
    1. A code repository that is not on your local computer.
    1. A code repository that is kept in a location inside the continental USA.
1. The remote repository that you synchronize with referred to as _________.
    1. upstream
    1. downstream
    1. origin
    1. clone
1. When you make a local copy of a GitHub repository, you are effectively ______ that repository.
    1. forking
    1. cloning
    1. copying
    1. replacing
1. What is the order of Git tasks that are done when performing a sync in GitHub Desktop?
    1. push, fetch, pull
    1. fetch, merge, push
    1. push, pull, clean
1. The git pull command is equivalent to _______.
    1. `git fetch` and then `git merge`
    1. `git pull` and then `git fetch`
    1. `git get` and then `git pull`
    1. `git fetch` and then `git pull`
1. Which command is used to create a git repository?
    1. `git repo`
    1. `git pull`
    1. `git clone`
    1. `git init`
1. Which command is used to stage files for a commit?
    1. `git pull`
    1. `git add .`
    1. `git push`
    1. `git init`
1. Which of the following best describes what it means to stage files for a commit?
    1. To stage files for a commit means to remove them from tracking in preparation for a commit.
    1. Staging files for a commit means to identify files that may be new, modified, or deleted and marking those as being ready to commit.
    1. Staging files for a commit means that the files are stashed so that they will be remembered after performing a pull and push.
    1. To stage files for a commit means to change the files prior to committing them.
1. Which command saves a snapshot of the changes to files in the repository?
    1. `git commit -m "Commit message"`
    1. `git save -m "Save message"`
    1. `git push`
    1. `git pull`
1. Which of the following best describes what `git commit` does?
    1. Confirms the deletion of files in the repository history.
    1. Prepare files for being added (tracked) in the repository.
    1. Record a snapshot of the changes that have happened in the repository since the last commit.
    1. It performs transactional processing to synchronize remote and local repositories.
    1. Reverses the previous snapshot of the state of the repository so that you can "undo" the edits of your source code.
