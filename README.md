[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15300260&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

**Answers**
Windows 11 operating system installed through these steps:

System requirement check: To ensure my hardware/pc meets the minimum requirements.

Download and Installation of the system: Downloading of an ISO file.

Installation of Media: mounting of the ISO file.

Start Installation: Restarted my computer with the installation media inserted, and boot from it. .

Follow and Complete Setup Wizard: I set up settings like langauge, time zone and added user accounts

Complete: Once installation is finished, PC restarted.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

**Answers**

Download: I went to the official visual studio site and selected a suitable installer for my operating system (Windows 11) and downloaded it

Run Installer: Once the download completes, run the installer.

Follow and Complete Setup Wizard: Follow the prompts in the setup wizard to install VS Code with default settings.

Launch VS Code: After installation, launch Visual Studio Code from your desktop or applications menu.

Extensions (Optional): Customize VS Code by installing extensions for programming languages, themes, and additional features via the Extensions view (Ctrl+Shift+X).

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com


   **Answers**

### Install Git and Configure it on Your Local Machine

1. **Download Git:**
   - Go to the [Git official website](https://git-scm.com/) and download the installer for your operating system (Windows, macOS, Linux).

2. **Install Git:**
   - Run the installer and follow the installation steps with default settings unless you have specific preferences.

3. **Configure Git:**
   - Open a terminal (Command Prompt on Windows, Terminal on macOS/Linux).
   - Set your username and email address (used for your Git commits):
     ```
     git config --global user.name "Your Name"
     git config --global user.email "your.email@example.com"

### Create a GitHub Account

1. **Sign Up for GitHub:**
   - Go to [GitHub's website](https://github.com/) and sign up for a new account.

### Initialize a Git Repository for Your Project

1. **Create a New Directory:**
   - Create a new directory (folder) on your local machine where you want to store your project.

2. **Initialize Git Repository:**
   - Open a terminal and navigate to your project directory:
     ```
     cd path/to/your/project
     ```
   - Initialize a new Git repository:
     ```
     git init
     ```

### Make Your First Commit

1. **Create a New File or Modify an Existing One:**
   - Create a new file or modify an existing file within your project directory.

2. **Add Files to Staging Area:**
   - Stage the changes you want to commit:
     ```
     git add .   // Adds all changes
     git add filename   // Adds specific file
     ```

3. **Commit Changes:**
   - Commit your changes with a descriptive message:
     ```
     git commit -m "Initial commit"
     ```

### Connect Your Local Repository to GitHub

1. **Create a New Repository on GitHub:**
   - Log into your GitHub account and create a new repository. You can choose to initialize it with a README file if you wish.

Test repo: https://github.com/mmanape-l/Testing.git

   (CHATGPT.COM,https://chatgpt.com/)

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  To set up your development environment for Python:

1. **Install Python**:
   - Download and run the Python installer from the official website.
   - Ensure Python is added to PATH during installation.

2. **Verify Installation**:
   - Open a terminal and check Python version with `python --version`.

3. **Install Necessary Tools**:
   - Choose and install an IDE or text editor for Python development.
   - Verify `pip` installation with `pip --version`.

4. **Optional: Virtual Environment**:
   - Set up a virtual environment with `python -m venv env`.
   - Activate it with `source env/bin/activate` (on macOS/Linux) or `.\env\Scripts\activate` (on Windows).

5. **Install Python Libraries**:
   - Use `pip` to install required Python packages: `pip install package-name`.

6. **Configuration**:
   - Adjust Python path environment variables if needed for your IDE or editor.

7. **Test Setup**:
   - Create a test script (`hello.py`) and run it to ensure everything works.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

**Answer**

Download get-pip.py script from https://bootstrap.pypa.io/get-pip.py.
Open a terminal and navigate to the directory containing get-pip.py.
Run python get-pip.py.
General Steps for Package Managers:

Research: Identify the appropriate package manager for your programming language or system (e.g., npm for Node.js, Composer for PHP).
Download: Visit the official website or repository for your package manager and follow their installation instructions.
Verify Installation: After installation, verify by running the package manager's version command (e.g., npm --version, composer --version).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   **Answer**

   Download MySQL:

Go to the MySQL Community Downloads page.
Choose the appropriate version for your operating system (Windows, macOS, Linux).
Download the installer.
Install MySQL:

Run the downloaded installer.
Follow the installation wizard's prompts. Customize settings like installation location and configuration options as needed.
Set a root password during installation for MySQL server administration.
Configure MySQL:

Start the MySQL server after installation completes.
Configure MySQL server settings if necessary, such as port number, data directory, etc.
Optionally, configure remote access and user permissions based on your project requirements.
Verify Installation:

Open a terminal or command prompt and type mysql -u root -p. Enter your root password when prompted.
This command opens the MySQL command-line client, indicating MySQL is installed and running.
Additional Tools (Optional):

Install MySQL Workbench or another MySQL client for graphical database management and development.

(ChatGPT)

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

**Answer**

Currently have the following extensions installed
Dart, Flutter, Live Share, MySQL, Postman, Pylance, Python, Python Debugger 

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

**Answer**

My SQL did not include the workbench package, and so I had to install that differently, however it works now.

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
