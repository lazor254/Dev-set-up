[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15262579&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

I will be setting up my environment in windows 10 operating system because my computer does not support windows 11 


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

I followed all the steps to install visual studio:
here are the codes to confirm it: i did run this in my cmd terminal: code --version, and below was the output

 C:\Users\wizard>code --version
1.90.1
611f9bfce64f25108829dd295f54a6894e87339d
x64

C:\Users\wizard>



3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Successfully installed both git and created a github account. here are the codes that i did run to confirm they are fully installed and configured into my system:


wizard@DESKTOP-NICKFRT MINGW64 ~ (master)
$ git --version
git version 2.45.2.windows.1

wizard@DESKTOP-NICKFRT MINGW64 ~ (master)
$ git config --global user.name
lazor254

wizard@DESKTOP-NICKFRT MINGW64 ~ (master)
$ git config --global user.email
edwinigunza22@gmail.com

wizard@DESKTOP-NICKFRT MINGW64 ~ (master)
$ git branch

wizard@DESKTOP-NICKFRT MINGW64 ~ (master)
$





4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

I also installed python and added to path:
 here is the confirmation from my git terminal:

 wizard@DESKTOP-NICKFRT MINGW64 ~ (master)
$ python --version
Python 3.12.4

as shown above i did run the command to check python version


5. Install Package Managers:
   If applicable, install package managers like pip (Python).


wizard@DESKTOP-NICKFRT MINGW64 ~ (master)
$ pip --version
pip 24.0 from C:\Users\wizard\AppData\Local\Programs\Python\Python312\Lib\site-packages\pip (python 3.12)

wizard@DESKTOP-NICKFRT MINGW64 ~ (master)
$

as shown above i did run the command to check pip version


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

I installed mysql without difficulties cause i reserched alot before getting down to installation. below output confirms successfull installation

wizard@DESKTOP-NICKFRT MINGW64 ~ (master)
$ mysql --version
C:\Program Files\MySQL\MySQL Server 8.0\bin\mysql.exe  Ver 8.0.37 for Win64 on x86_64 (MySQL Community Server - GPL)

wizard@DESKTOP-NICKFRT MINGW64 ~ (master)
$


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
   
i like simplicity so i will leave these behind

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 


I have documented my set up and here is the link to it

https://docs.google.com/document/d/1ob1HJXGM4JJVyi5eSaXFq4esWSjsNxfCfKSpjXuRDO8/edit



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
