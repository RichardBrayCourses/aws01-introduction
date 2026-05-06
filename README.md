# Aws Full-Stack Cloud Development

# Initial Setup

To get started you will need the following software installed:

- Google Chrome
- Node.js
- git (including the git credential manager)
- Visual Studio Code
- AWS Command Line Interface ("CLI")
- AWS CDK Command Line Interface
- pnpm (package manager)

Later on in the course we will also use:

- PostgreSQL tools (pgAdmin)
- Redgate Flyway (database versioning)
- Docker

For now, lets focus on the core tools above.

## Mac Setup

## Step 1 - install homebrew

Firstly go to

```
brew.sh
```

and follow the instructions for installing homebrew.

## Step 2 - update your shell startup file

Once homebrew is installed you **must update your shell startup file**

Enter this command into a terminal to find out which shell you are using

```
echo $SHELL
```

If it replies "/bin/zsh" you are using zsh ... so enter this command into your terminal to update the startup file

```
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
```

If it replies "/bin/bash" you are using the bash shell ... so enter this command into your terminal to update the startup file

```
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.bash_profile
```

## Step 3 - install software for course

Then use homebrew to install whichever packages you don't already have. Here are the commands.

```
  brew install --cask google-chrome
  brew install git
  brew install node
  brew install --cask git-credential-manager
  brew install --cask visual-studio-code
  brew install awscli
  brew install aws-cdk
  brew install pnpm
```

## Step 4 - essential software configuration

Open in a NEW terminal (to get the correct PATH) and enter the following commands:

```
  git-credential-manager configure
  git config --global user.name "Your Name"
  git config --global user.email "you@example.com"
```

Open Docker Desktop once after installation and let it finish setting up.

## Windows setup

Open a new powershell terminal in admin mode and use winget to install whichever packages you don't already have. Here are the commands.

```
  Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
  winget install Google.Chrome
  winget install Git.Git
  winget install OpenJS.NodeJS
  winget install GitCredentialManager.GitCredentialManager
  winget install Microsoft.VisualStudioCode
  winget install Amazon.AWSCLI
  winget install pnpm.pnpm
```

then in a new terminal (to get the correct PATH)

```
  npm install -g aws-cdk
  git-credential-manager configure
  git config --global user.name "Your Name"
  git config --global user.email "you@example.com"
```

Open Docker Desktop once after installation and allow it to complete setup.

## Notes

- You do not need to configure AWS yet — we will do that later in the course
