# Project 

https://github.com/chiraggarg357/medusa-task-day2.git

# Installing Medusa CLI and Setting Up a New Medusa Store

ON WSL(windows subsystem for linux)
## Step 1: check Node.js Installation

To check if Node.js is installed on your system, use the following command:


node -v

## Step 2: Install Yarn
Medusa uses Yarn as its package manager. If you don’t have Yarn installed,install it using npm

npm install -g yarn

checking Yarn's version:

yarn -v

## Step 3: Install Medusa CLI Globally
install Medusa CLI globally using Yarn:

yarn global add @medusajs/medusa-cli


This command installs Medusa CLI globally on your system, making it accessible from any directory.

##  Step 4: Verify Medusa CLI Installation
check its version:
medusa --version

## Step 5: Create a New Medusa Store
Now that Medusa CLI is installed, you can create a new Medusa store project:

medusa new my-medusa-store



## Step 6: Install Project Dependencies
Medusa will automatically install all required dependencies for your project.

npm audit fix

This will fix non-breaking vulnerabilities.


npm audit fix --force

## Step 7: Set Up the Database
Medusa will prompt you to set up a PostgreSQL database with credentials.


## Step 8: Start the Medusa Project
After the database setup is complete, you can navigate to your project directory and start the development server

cd my-medusa-store


medusa develop


This command starts your Medusa store.
