[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15277749&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:
Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Objective: Download and install Windows 11.

Go to the Windows 11 download page.
Click on the "Download Now" button under the "Windows 11 Installation Assistant".
Run the downloaded file and follow the on-screen instructions to install Windows 11.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
Objective: Download and install Visual Studio Code.

Visit the Visual Studio Code download page.
Choose the installer for Windows and download it.
Run the installer and follow the on-screen instructions to complete the installation
3. Set Up Version Control System:
Objective: Download and install Visual Studio Code.
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   Objective: Install Git, create a GitHub account, initialize a Git repository, and make your first commit.

Install Git:

Go to the Git download page.
Download the installer and run it.
Follow the default settings during the installation process.

Configure Git:

Open a terminal (Command Prompt or PowerShell or gitbash).
Set your username and email:
bash
Copy code
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

  Create a GitHub Account:

Visit GitHub and sign up for a free account.
Initialize a Git Repository:

Create a new folder for your project.
Navigate to the folder in the terminal.
Initialize a Git repository:
bash
Copy code
git init
Make Your First Commit:

Create a README file:
bash
Copy code
echo "# My First Project" > README.md
Add the file to the staging area:
bash
Copy code
git add README.md
Commit the file:
bash
Copy code
git commit -m "Initial commit"
4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  Objective: Install Python.

Visit the Python download page.
Download the latest version for Windows.
Run the installer and ensure you check the option "Add Python to PATH".
Follow the on-screen instructions to complete the installation.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

Objective: Install pip for Python.

Pip is installed by default with Python. You can verify the installation:
bash
Copy code
pip --version
6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Visit the MySQL download page.
Download the MySQL Installer.
Run the installer and follow the on-screen instructions to install MySQL.
7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Objective: Consider using Docker or virtual machines.

Install Docker:

Visit the Docker download page.
Download and install Docker Desktop for Windows.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

Objective: Enhance Visual Studio Code functionality.

Open Visual Studio Code.
Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or pressing Ctrl+Shift+X.
Search for and install the following recommended extensions:
Python
GitLens
Prettier - Code formatter
Docker
9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 


# Developer Environment Setup Documentation

## Objective
This document outlines the steps taken to set up an efficient developer environment for software engineering projects. It includes detailed instructions, configurations, customizations, and troubleshooting steps encountered during the process.

## Table of Contents
1. [Select Your Operating System (OS)](#1-select-your-operating-system-os)
2. [Install a Text Editor or Integrated Development Environment (IDE)](#2-install-a-text-editor-or-integrated-development-environment-ide)
3. [Set Up Version Control System](#3-set-up-version-control-system)
4. [Install Necessary Programming Languages and Runtimes](#4-install-necessary-programming-languages-and-runtimes)
5. [Install Package Managers](#5-install-package-managers)
6. [Configure a Database (MySQL)](#6-configure-a-database-mysql)
7. [Set Up Development Environments and Virtualization (Optional)](#7-set-up-development-environments-and-virtualization-optional)
8. [Explore Extensions and Plugins](#8-explore-extensions-and-plugins)
9. [Document Your Setup](#9-document-your-setup)

## 1. Select Your Operating System (OS)

### Objective
Download and install Windows 11.

### Steps
1. Visit the [Windows 11 download page](https://www.microsoft.com/software-download/windows11).
2. Click on the "Download Now" button under the "Windows 11 Installation Assistant".
3. Run the downloaded file and follow the on-screen instructions to install Windows 11.

### Troubleshooting
- **Issue:** Installation assistant not starting.
  - **Solution:** Restart the computer and run the assistant as an administrator.

---

## 2. Install a Text Editor or Integrated Development Environment (IDE)

### Objective
Download and install Visual Studio Code.

### Steps
1. Visit the [Visual Studio Code download page](https://code.visualstudio.com/Download).
2. Choose the installer for Windows and download it.
3. Run the installer and follow the on-screen instructions to complete the installation.

### Troubleshooting
- **Issue:** Visual Studio Code installation fails.
  - **Solution:** Ensure all previous versions of Visual Studio Code are uninstalled before attempting a new installation.

---

## 3. Set Up Version Control System

### Objective
Install Git, create a GitHub account, initialize a Git repository, and make your first commit.

### Steps
1. **Install Git:**
   - Go to the [Git download page](https://git-scm.com/download/win).
   - Download the installer and run it.
   - Follow the default settings during the installation process.

2. **Configure Git:**
   - Open a terminal (Command Prompt or PowerShell).
   - Set your username and email:
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "your-email@example.com"
     ```

3. **Create a GitHub Account:**
   - Visit [GitHub](https://github.com) and sign up for a free account.

4. **Initialize a Git Repository:**
   - Create a new folder for your project.
   - Navigate to the folder in the terminal.
   - Initialize a Git repository:
     ```bash
     git init
     ```

5. **Make Your First Commit:**
   - Create a README file:
     ```bash
     echo "# My First Project" > README.md
     ```
   - Add the file to the staging area:
     ```bash
     git add README.md
     ```
   - Commit the file:
     ```bash
     git commit -m "Initial commit"
     ```

### Troubleshooting
- **Issue:** Git installation fails.
  - **Solution:** Ensure that all other Git processes are closed and try reinstalling.
- **Issue:** Unable to configure Git with username and email.
  - **Solution:** Verify syntax and ensure that Git is correctly installed by running `git --version`.

---

## 4. Install Necessary Programming Languages and Runtimes

### Objective
Install Python.

### Steps
1. Visit the [Python download page](https://www.python.org/downloads/).
2. Download the latest version for Windows.
3. Run the installer and ensure you check the option "Add Python to PATH".
4. Follow the on-screen instructions to complete the installation.

### Troubleshooting
- **Issue:** Python installation fails.
  - **Solution:** Ensure there are no previous versions of Python installed and that all related processes are closed.

---

## 5. Install Package Managers

### Objective
Install pip for Python.

### Steps
1. Pip is installed by default with Python. You can verify the installation:
   ```bash
   pip --version
   ```

### Troubleshooting
- **Issue:** Pip command not recognized.
  - **Solution:** Ensure Python was installed with the "Add Python to PATH" option enabled.

---

## 6. Configure a Database (MySQL)

### Objective
Download and install MySQL.

### Steps
1. Visit the [MySQL download page](https://dev.mysql.com/downloads/windows/installer/5.7.html).
2. Download the MySQL Installer.
3. Run the installer and follow the on-screen instructions to install MySQL.

### Troubleshooting
- **Issue:** MySQL installation fails.
  - **Solution:** Check for any existing MySQL installations and ensure they are uninstalled completely before reinstalling.

---

## 7. Set Up Development Environments and Virtualization (Optional)

### Objective
Consider using Docker or virtual machines.

### Steps
1. **Install Docker:**
   - Visit the [Docker download page](https://www.docker.com/products/docker-desktop).
   - Download and install Docker Desktop for Windows.

2. **Set up a virtual machine:**
   - Consider using tools like VirtualBox or VMware if needed for virtualization.

### Troubleshooting
- **Issue:** Docker fails to start.
  - **Solution:** Ensure that virtualization is enabled in the BIOS settings.

---

## 8. Explore Extensions and Plugins

### Objective
Enhance Visual Studio Code functionality.

### Steps
1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or pressing `Ctrl+Shift+X`.
3. Search for and install the following recommended extensions:
   - Python
   - GitLens
   - Prettier - Code formatter
   - Docker

### Troubleshooting
- **Issue:** Extensions fail to install.
  - **Solution:** Ensure you have a stable internet connection and retry the installation.

---

## 9. Document Your Setup

### Objective
Create a comprehensive document outlining your setup process.

### Steps
1. **Document Setup Steps:**
   - Use a text editor or word processor to write down each step you took, including configurations and customizations.
   

2. **Reflect on Challenges:**
   - Write a section about any challenges you faced during the setup.
   - Describe how you overcame these challenges.

### Sample Reflection
During the setup, I faced several challenges. One major challenge was configuring Git for the first time. Initially, I struggled with setting the global username and email, but I overcame this by following detailed online tutorials. Additionally, installing MySQL required careful attention to ensure all components were correctly set up. By reading through the official MySQL documentation and community forums, I was able to resolve these issues.

---

## Deliverables

1. **Documentation:**
   - Save your setup steps and reflections in a document file (e.g., Word or PDF).

2. **GitHub Repository:**
   - Push your sample project to GitHub:
     ```bash
     git remote add origin https://github.com/yourusername/your-repo.git
     git branch -M main
     git push -u origin main
     ```


#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
