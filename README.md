# ColorStackBU GitHub Demo
In this GitHub demo you will learn how to:
- Clone a GitHub repository onto your local machine
- Create branches
- Commit and push changes from your local machine to the GitHub repository
- Create pull requests on GitHub to merge branches with the main branch
- Pull changes from the remote repository to your local machine

Find a group of two for this demo to practice collaborating on a repository. If you cannot find a group, you can do this demo alone, although it is designed for a group. 

At the end of the demo, you will need Python to run the final code after everything is merged. This is **not required** for any of the steps except for the very last one so you can understand how GitHub works just fine without it, but if you would like to download it you can do so at https://www.python.org/downloads/.
## Group instructions
### Step 1: Setup repository
- Group member 1: press the green button in the top right that says `Use this template` and then click `Create a new repository`. Give it the name `github-demo` and click `Create repository`.
- Group member 1: go to the repo `Settings` > `Collaborators` > `Add people` and type in group member 2's GitHub email.
- Group member 2: accept this invitation in your email and visit the repository.
### Step 2: Clone repository
Both team members:
- Click the green `Code` button and copy the URL it shows.
- Open the command line choose a folder of choice to download the repository in (navigate folders in the command line with `cd <folder-name>` or make a new one with `mkdir <folder-name>`).
  - Once you are in the folder of your choice, clone the repository with `git clone <url>` with the URL you just copied.
  - Cloning will create a new folder called `github-demo`. Go into it with the command `cd github-demo`.
### Step 3: Create branches
#### Helpful commands
`git switch -c <name>` - creates and switches to a new branch
- Group member 1: create and switch to a new branch with the name `branch1`.
- Group member 2: create and switch to a new branch with the name `branch2`.
### Step 4: Make changes
- Open `main.py` on your local machine.
  - On Windows, you may use the command `notepad main.py`.
  - On other operating systems, you may use the command `nano main.py`.
- Group member 1: set `string1` equal to `"Hello"`.
- Group member 2: set `string2` equal to `"World"`.
- Save and close the file.
### Step 5: Commit and push changes
#### Helpful commands
`git add .` - stage changed files\
`git commit -m "<msg>"` - commit staged files with a message\
`git push origin <branch-name>` - pushes your commits to a branch on the remote repository

Both group members:
- Stage your changed files.
- Commit your changes with the message `"Add Hello"` or `"Add World"` depending on which one you added.
- Push your commit to the branch you are on.
### Step 6: Merge branches to the main branch with pull requests
Both group members on one person's computer:
- On the GitHub repository, you should see two popups that say there were recent pushes to branches with a green button to make a pull request.
  - Click this button and then click `Create pull request`.
  - Make sure there are no merge conflicts. If there are, an error was made somewhere.
  - Click `Merge pull request`.
  - Repeat for the other pull request.
### Step 7: Pull changes
#### Helpful commands
`git pull` - pull changes from the remote repository\
`git switch <name>` - switches to a different branch

Both group members:
- Switch to the `main` branch.
- Pull changes

You should now have the updated `main.py` script with both changes to add `"Hello"` and `"World"`. If you have Python installed, run `python .\main.py` on Windows or `python ./main.py` if not on Windows. The command line should print out `Hello World`.

#### Congratulations! Your group has completed the GitHub demo.
## Solo instructions
### Step 1: Setup repository
- Press the green button in the top right that says `Use this template` and then click `Create a new repository`. Give it the name `github-demo` and click `Create repository`.
### Step 2: Clone repository
- Click the green `Code` button and copy the URL it shows.
- Open the command line choose a folder of choice to download the repository in (navigate folders in the command line with `cd <folder-name>` or make a new one one with `mkdir <folder-name>`).
  - Once you are in the folder of your choice, clone the repository with `git clone <url>` with the URL you just copied.
  - Cloning will create a new folder called `github-demo`. Go into it with the command `cd github-demo`.
### Step 3: Create branches
#### Helpful commands
`git branch <name>` - creates a new branch
- Create a new branch with the name `branch1`.
- Create a new branch with the name `branch2`.
### Step 4: Make changes, commit, and push
#### Helpful commands
`git switch <name>` - switches to a different branch\
`git add .` - stage changed files\
`git commit -m "<msg>"` - commit staged files with a message\
`git push origin <branch-name>` - pushes your commits to a branch on the remote repository

- Open `main.py` on your local machine.
  - On Windows, you may use the command `notepad main.py`.
  - On other operating systems, you may use the command `nano main.py`.
- Switch to `branch1`.
- In `main.py`, set `string1` equal to `"Hello"` and save the file.
- Stage your files, commit with message `"Add Hello"`, and push.
- Switch to `branch2`.
- In `main.py`, set `string2` equal to `"World"` and save the file.
- Stage your files, commit with message `"Add World"`, and push.
### Step 5: Merge branches to the main branch with pull requests
- On the GitHub repository, you should see two popups that say there were recent pushes to branches with a green button to make a pull request.
  - Click this button and then click `Create pull request`.
  - Make sure there are no merge conflicts. If there are, an error was made somewhere.
  - Click `Merge pull request`.
  - Repeat for the other pull request.
### Step 6: Pull changes
#### Helpful commands
`git pull` - pull changes from the remote repository\
`git switch <name>` - switches to a different branch

- Switch to the `main` branch.
- Pull changes

You should now have the updated `main.py` script with both changes to add `"Hello"` and `"World"`. If you have Python installed, run `python .\main.py` on Windows or `python ./main.py` if not on Windows. The command line should print out `Hello World`.

#### Congratulations! You have completed the GitHub demo.
