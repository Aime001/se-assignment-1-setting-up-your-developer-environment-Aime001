[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15316163&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

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

Setting Up Your Developer Environment
Table of Contents
1.	Install Windows 11
2.	Install Visual Studio Code
3.	Set Up Version Control System (Git)
4.	Configure a Database (MySQL)
5. Install Python and Necessary Tools
________________________________________
1. Install Windows 11
Prerequisites:
•	Compatible PC meeting Windows 11 system requirements.
•	Stable internet connection.
•	Sufficient storage space.
Steps:
1.	Check System Requirements:
o	Ensure your PC meets the Windows 11 system requirements.
2.	Backup Important Data (Optional but Recommended):
o	Back up your important files before installation.
3.	Download Windows 11 ISO:
o	Visit the official Microsoft Windows 11 download page or use the Media Creation Tool.
4.	Create Installation Media:
o	Use Rufus or similar tools to create a bootable USB drive with the Windows 11 ISO.
5.	Install Windows 11:
o	Boot from the USB drive, follow on-screen instructions to install Windows 11.
________________________________________
2. Install Visual Studio Code
Steps:
1.	Download Visual Studio Code:
o	Visit the Visual Studio Code website.
o	Download the installer for Windows.
2.	Run the Installer:
o	Double-click the downloaded .exe file to start the installation.
3.	Install Visual Studio Code:
o	Follow the installation prompts, selecting default options as necessary.
4.	Launch Visual Studio Code:
o	After installation, launch VS Code from the Start Menu or Desktop.
5.	Extensions:
o	Install extensions for your preferred programming languages and tools.
________________________________________
3. Set Up Version Control System (Git)
Steps:
1.	Install Git:
o	Download Git from the Git website.
o	Run the installer and follow the installation prompts.
2.	Configure Git:
o	Set your username and email using git config --global user.name "Your Name" and git config --global user.email "your.email@example.com".
3.	Create a GitHub Account:
o	Visit GitHub and sign up for an account if you don't have one.
4.	Initialize a Git Repository:
o	Navigate to your project directory, run git init to initialize a new Git repository.
5.	Make Your First Commit:
o	Add files using git add and commit changes using git commit -m "Initial commit".
6.	Connect to GitHub:
o	Create a new repository on GitHub.
o	Link your local repository to GitHub using git remote add origin https://github.com/your-username/your-repository.git.
________________________________________
4. Configure a Database (MySQL)
Steps:
1.	Download MySQL:
o	Visit the MySQL Community Downloads page.
o	Download the MySQL Community Server installer for your operating system.
2.	Run MySQL Installer:
o	Execute the downloaded installer and follow the installation prompts.
3.	Configure MySQL:
o	Set a root password during installation or configuration.
4.	Start MySQL Server:
o	Start MySQL Server using services (services.msc on Windows) or terminal (sudo systemctl start mysql on Linux).
5.	Verify Installation:
o	Open MySQL Shell (mysql -u root -p) and check the MySQL version using SELECT VERSION();.


5. Step-by-Step Guide to Install Python and Necessary Tools:

Step 1: Download Python
1.	Visit the Python Website:
o	Go to Python's official website.
2.	Download Python Installer:
o	Click on the "Downloads" tab and download the latest version of Python that is suitable for your operating system (Windows, macOS, or Linux).
Step 2: Run Python Installer
1.	Run the Installer:
o	Once the download is complete, locate the downloaded installer file (*.exe for Windows, .pkg for macOS, or use package manager for Linux).
o	Double-click the installer to start the installation process.
Step 3: Install Python
1.	Configure Installation:
o	During installation, ensure you select the option to add Python to your system PATH. This option is typically available in the installer.
2.	Customize Installation (Optional):
o	You may choose to customize the installation by selecting optional features or adjusting the installation location.
3.	Complete Installation:
o	Follow the on-screen instructions to complete the installation.
Step 4: Verify Python Installation
1.	Open Command Prompt or Terminal:
o	Open a command prompt on Windows (cmd) or terminal on macOS/Linux.
2.	Check Python Version:
o	Type python --version or python3 --version (depending on your system configuration) to verify that Python has been installed correctly.
Step 5: Install Necessary Tools
1.	Install Python Packages:
o	Use pip, the Python package installer, to install necessary packages. For example, to install numpy, you would use:
pip install numpy
2.	Install IDE or Code Editor (Optional but Recommended):
o	You can use a code editor or an Integrated Development Environment (IDE) such as Visual Studio Code (already installed) or PyCharm for Python development.
Step 6: Set Up Environment Variables (Windows)
1.	Set PATH Variable:
o	If Python is not automatically added to your PATH during installation, you can add it manually:
	Right-click on "This PC" or "Computer" → Properties → Advanced System Settings → Environment Variables.
	Under "System Variables", find the Path variable and click "Edit".
	Add the path to your Python installation (e.g., C:\Python39\ or similar).
Step 7: Write and Execute Python Code
1.	Write Python Code:
o	Use your preferred code editor or IDE to write Python code.
2.	Run Python Code:
o	Save your Python script with a .py extension and execute it either from the command line (python script.py) or within your IDE.



Reflection on challenges met during the assignment.
1. Installing most of these tools was more challnging, I could forget, the processes because it's my first time doing this.
The solution: I used the videos uploaded on LMS and see how they were doing it, then I did the same.
Thanks to plp team because they have guided me on how to navigate these processes.