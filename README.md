Good start — this is already clear and nicely minimal. I’ve expanded it into a complete, course-ready README that:

- Covers everything in your script
- Keeps your simple teaching style
- Adds only what’s necessary (no clutter)
- Works cleanly for Mac + Windows beginners
- Introduces pnpm, Flyway, Docker, pgAdmin, GitHub Desktop

⸻

Here is your finished file:

⸻

AWS Full-Stack Cloud Development

Initial Setup

To get started you will need the following software installed:

- Google Chrome
- Node.js
- Git (including Git Credential Manager)
- Visual Studio Code
- AWS CLI
- AWS CDK
- pnpm (package manager)

Later on in the course we will also use:

- PostgreSQL tools (pgAdmin)
- Redgate Flyway (database versioning)
- Docker
- GitHub Desktop

For now, focus on the core tools above.

⸻

Mac Setup

1. Install Homebrew

Go to:

https://brew.sh

Follow the instructions to install Homebrew.

⸻

2. Install Core Software

Open a terminal and run:

brew install git
brew install node
brew install awscli
brew install pnpm
brew install flyway
brew install --cask google-chrome
brew install --cask visual-studio-code
brew install --cask git-credential-manager
brew install --cask github
brew install --cask pgadmin4
brew install --cask docker

⸻

3. Install AWS CDK

Open a new terminal and run:

npm install -g aws-cdk

⸻

4. Configure Git

git-credential-manager configure
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

⸻

5. Start Docker

Open Docker Desktop once after installation and let it finish setting up.

⸻

Windows Setup

1. Open PowerShell (Admin)

Right-click Start → Windows Terminal (Admin) or PowerShell (Admin).

⸻

2. Allow Script Execution

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

⸻

3. Install Core Software

Run:

winget install Google.Chrome
winget install OpenJS.NodeJS
winget install Git.Git
winget install Microsoft.VisualStudioCode
winget install Amazon.AWSCLI
winget install pnpm.pnpm
winget install Redgate.Flyway
winget install GitHub.GitHubDesktop
winget install Docker.DockerDesktop
winget install pgAdmin.pgAdmin4
winget install GitCredentialManager.GitCredentialManager

⸻

4. Install AWS CDK

Open a new terminal and run:

npm install -g aws-cdk

⸻

5. Configure Git

git-credential-manager configure
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

⸻

6. Start Docker

Open Docker Desktop once after installation and allow it to complete setup.

⸻

Verify Your Installation

Run the following commands to check everything is installed:

node -v
npm -v
pnpm -v
git --version
aws --version
cdk --version
flyway -v

⸻

Notes

- If a command is not found, close and reopen your terminal
- Docker may take a few minutes to initialise the first time
- You do not need to configure AWS yet — we will do that later in the course

⸻

If you want, next step I can tighten this further into a one-page “student quick start” version or a slide-friendly version for your course intro.
