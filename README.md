# Setup

## Setup Environment

### Install homebrew
1. Install via 
   ```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```
2. If this is a fresh install and you don't have your path setup properly, you can follow the installation "next steps" which are already customized for you, or you can manually add the following paths to your ~/.bashrc or ~/.zshrc
3. Ensure you have installed brew correctly:
   ```brew --version```
4. Ensure everything is configured correctly:
   ```brew doctor```

### Install node.js
1. Install NVM:
   ```brew install nvm```
2. Create directory for NVM
   ```mkdir ~/.nvm```
3. Follow the installation "next steps" which are already customized for you, or you can manually add the following paths to your ~/.bashrc or ~/.zshrc
4. Kill and reopen terminal
5. Ensure you have installed NVM correctly:
   ```nvm -v```
6. Install node version 16:
   ```nvm install 16```
7. Set default node version to use it everywhere:
   ```nvm alias default 16```
8. Use the default version:
   ```nvm use```
9. Kill and reopen terminal
5. Ensure you have installed node correctly:
   ```node -v```

## Setup Applications
1. Microsoft Teams (get ready your account and let me know)
2. Sublime Merge (or other Git platform of your preference)
3. Visual Studio Code (or other code editing platform of your preference)
