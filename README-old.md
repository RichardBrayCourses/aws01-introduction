# Aws Full-Stack Cloud Development

# Initial Setup

To get started you will need the following software installed:

- Google Chrome
- Node.js
- git (including the git credential manager)
- Visual Studio Code
- AWS CLI
- AWS CDK

Later on in the course we will install other software, e.g. PostgreSQL client tools and Redgate Flyway for database versioning ... but for now this is all you need to get started with the first few sections.

## Mac Setup

Firstly go to

```
brew.sh
```

and follow the instructions for installing homebrew.

Then use homebrew to install whichever packages you don't already have. Here are the commands.

```
  brew install --cask google-chrome
  brew install node
  brew install git
  brew install --cask git-credential-manager
  brew install --cask visual-studio-code
  brew install awscli
```

then in a new terminal (to get the correct PATH)

```
  npm install -g aws-cdk
  git-credential-manager configure
  git config --global user.name "Your Name"
  git config --global user.email "you@example.com"
```

## Windows setup

Open a new powershell terminal in admin mode and use winget to install whichever packages you don't already have. Here are the commands.

```
  Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
  winget install Google.Chrome
  winget install OpenJS.NodeJS
  winget install Git.Git
  winget install Microsoft.VisualStudioCode
  winget install Amazon.AWSCLI

```

then in a new terminal (to get the correct PATH)

```
  npm install -g aws-cdk
  git config --global user.name "Your Name"
  git config --global user.email "you@example.com"
```
