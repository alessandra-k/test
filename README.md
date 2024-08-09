# Marking Management System

## Overview
The Marking Management System is a Java-based tool designed to streamline the grading process for professors, allowing them to import, manage, and export student grades efficiently.

## Prerequisites
To run this application, you need the following:
- **Java Runtime Environment (JRE) 8 or later** installed on your system.

## Installation Instructions

### 1. Install Java
If you do not already have Java installed on your computer, follow these steps:

#### Windows:
1. Visit the [Java SE Downloads page](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
2. Download the appropriate version for your operating system (Windows x64 Installer).
3. Run the installer and follow the on-screen instructions to complete the installation.

#### macOS:
1. Visit the [Java SE Downloads page](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
2. Download the appropriate version for your operating system (macOS Installer).
3. Open the `.dmg` file and follow the instructions to install Java.

#### Linux:
1. Open your terminal.
2. Use the package manager for your Linux distribution to install Java (e.g., `sudo apt install openjdk-11-jdk` for Ubuntu/Debian).

### 2. Verify Java Installation
After installation, verify that Java is correctly installed:

1. Open a command prompt (Windows) or terminal (macOS/Linux).
2. Type the following command:
   java -version
3.	You should see output indicating the installed version of Java. Ensure it is version 8 or later.

### 3.	Add Java to the PATH

#### On Windows:
1.	Open the Start Search, type in "env", and select "Edit the system environment variables".
2.	In the System Properties window, click on the "Environment Variables" button.
3.	In the Environment Variables window, find the "Path" variable in the "System variables" section, and select it. Then click "Edit".
4.	In the Edit Environment Variable window, click "New" and add the path to your Java bin directory (e.g., C:\Program Files\Java\jdk-11.0.2\bin).
5.	Click "OK" on all windows to apply the changes.

#### On macOS/Linux:
1.	Open a terminal.
2.	Use a text editor to open your shell configuration file (like .bash_profile, .bashrc, .zshrc, or .profile): nano ~/.bash_profile
3.	Add the following line to the file: export PATH=$PATH:/Library/Java/JavaVirtualMachines/jdk-11.0.2.jdk/Contents/Home/bin
(Adjust the path according to your Java installation.)
4.	Save the file and close the text editor.
5.	Run the following command to apply the changes:  source ~/.bash_profile


### 4.	Run the Application

#### 1.	Save the JAR File:
Obtain the Grading_System-0.0.1-SNAPSHOT-jar-with-dependencies.jar file from your provided source and save it in a directory in your computer.

#### 2.	Run the JAR File:
- Open the command prompt or terminal.
- Navigate to the directory where the JAR file is located using the cd command. For example:
cd path\to\your\jar\directory
- Run the JAR file with the following command:
java -jar Grading_System-0.0.1-SNAPSHOT-jar-with-dependencies.jar


### 5.	Usage
Once the application is running, you can start using the Marking Management System by following the USER GUIDE. The application allows you to:
- Import CSV files with student and assignment data.
- Enter and manage grades.
- Export the grades as a formatted CSV and Json file.

