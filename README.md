# Learn Python

## Day 0 - Setup

### Overview

* [Miniconda](https://docs.conda.io/en/latest/miniconda.html) - open-source package management system and environment management system
* [Jupyter](https://jupyter.org/) - web-based interactive development environment

### Computer setup tasks

Download and install the following software:

1. [Miniconda](https://conda.io/projects/conda/en/latest/user-guide/install/macos.html)
1. [JupyterLab](https://jupyter.org/install)

## Day 1 - Crash course and cheatsheets

* [Python crash course](https://www.freecodecamp.org/news/python-crash-course/)
* [Python cheatsheets](https://ehmatthes.github.io/pcc/cheatsheets/README.html)

## Day 2 - Project and account setup

### Topics

* Where to find help - where?
* Terminal and commands - [iTerm2](https://iterm2.com/)
* macOS package management - [Homebrew](https://brew.sh/)

### Python Documentation

To do add links here...

### Computer setup tasks

Download and install the following applications:

1. [iTerm2](https://iterm2.com/)
1. [Homebrew](https://brew.sh/)

## Day 3 - Git setup and pushing changes

Typically when setting up a new project this would be the first step. To gently indroduce you to new concepts I've waited until day 3 to introduce this.

### Topics

* Version control and source repositories - [Git](https://git-scm.com/)
* Code sharing, issue tracking - [GitHub](https://github.com/), [GitLab](https://about.gitlab.com/), [BitBucket](https://bitbucket.org/)

### Account and authentication setup tasks

1. If needed brew install Git `brew install git`
1. Create a [GitLab](https://about.gitlab.com/) account
1. [Generate an SSH key pair](https://docs.gitlab.com/ee/ssh/#generate-an-ssh-key-pair)
1. [Add the public SSH key to your GitLab account](https://docs.gitlab.com/ee/ssh/#add-an-ssh-key-to-your-gitlab-account)
1. [Verify that you can connect](https://docs.gitlab.com/ee/ssh/#verify-that-you-can-connect)

### Computer setup tasks

1. Download and install [GitHub Desktop](https://desktop.github.com/)
1. Install [GitLens Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

### Repository setup tasks

1. Initialise a local Git repository `git init` - _if needed install Git_
1. Create a remote Git repository on [GitLab](https://about.gitlab.com/)
1. Add the remote repository to our project `git remote add origin https://github.com/mattvick/learn-python.git`
1. Add a `.gitignore` file to tell Git to [ignore certain files](https://help.github.com/articles/ignoring-files/) `echo ".DS_Store" >> .gitignore`
1. Add a read me file `echo "# Learn Python" >> README.md`
1. Add all changes in the working directory to Git's staging area `git add .`

### Commit and push changes

1. Commit changes to Git with a message `git commit -m "Initial commit"`
1. Push changes to GitLab `git push -u origin master`

### Using GitHub Desktop

1. Viewing file diffs (changes) 
1. Commit and push changes
1. Pulling changes

## Day 4 - OpenAI
