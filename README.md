[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15273905&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Solutions

1. Select Your Operating System (OS)
Download and Install Windows 11
Go to the Windows 11 download page: Windows 11 Download
Click on "Download now" under the Windows 11 Installation Assistant.
Run the downloaded Installation Assistant and follow the on-screen instructions.
Restart your computer when prompted to complete the installation.

2. Install a Text Editor or Integrated Development Environment (IDE)
Download and Install Visual Studio Code
Go to the Visual Studio Code download page: Visual Studio Code Download
Choose your operating system and click the corresponding download button.
Run the installer and follow the setup instructions.
Launch Visual Studio Code once the installation is complete.

3. Set Up Version Control System
Install Git and Configure It
Download Git: Go to Git Downloads and download the installer for Windows.
Run the Git installer and follow the setup instructions.
Open Git Bash from the Start menu.
Configure Git with your username and email:
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com
Create a GitHub Account
Go to GitHub: GitHub
Click "Sign up" and follow the instructions to create a new account.
Initialize a Git Repository and Make Your First Commit
Open Git Bash and navigate to your project directory.
Initialize a new Git repository:
git init
git add .
git commit -m "Initial commit"

4. Install Necessary Programming Languages and Runtimes
Install Python
Go to the Python downloads page: Python Download
Download the installer for the latest version of Python.
Run the installer and ensure you check the box to "Add Python to PATH."
Complete the installation by following the on-screen instructions.

5. Install Package Managers
Install pip (Python)
Open a command prompt.
Check if pip is already installed:
pip --version
python get-pip.py

6. Configure a Database (MySQL)
Download and Install MySQL
Go to the MySQL Installer download page: MySQL Installer
Download the MySQL Installer.
Run the installer and choose the "Server Only" setup type.
Follow the setup instructions, configuring the root password and other settings as needed.

7. Set Up Development Environments and Virtualization (Optional)
Using Docker
Download Docker Desktop: Docker Download
Run the installer and follow the instructions.
Launch Docker Desktop and sign in with your Docker account.

8. Explore Extensions and Plugins
Enhancing Visual Studio Code
Open Visual Studio Code.
Go to the Extensions view by clicking the Extensions icon in the Activity Bar.
Search for and install extensions such as:
Python
GitLens
Prettier - Code formatter
ESLint

9. Document Your Setup
Create a document using a text editor or word processor.
Outline each step you took to set up your development environment.
Include details on configurations, customizations, and any troubleshooting steps.
Save the document and consider sharing it with your team or future self for reference.

Sample project initialized with git :

> git config --global user.name "GivenTerbulance"
> git config --global user.name "GivenTerbulance"
> mkdir assignment1 
> cd assignment1 
> git clone https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-GivenTerbulance.git
>cd se-assignment-1-setting-up-your-developer-environment-GivenTerbulance
>code . 

edit the README.md file on Visual Studio code 
Then go back to git bash to stage and commit it 

>git add README.md
>git commit -m "commiting a repo"
>git branch -m main
>git remote -v
>git push -u origin main 
The assignment will be finally pushed to github
