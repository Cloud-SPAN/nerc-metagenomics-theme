# Overview

The software and data used for cloud based analysis during the course are hosted on an Amazon Web Services (AWS) Machine Image (AMI) instance. A copy of such instance that requires no previous setup by you will be made available to you at no cost by the Cloud-SPAN team. **Windows users** will need to install Git for Windows on their laptop or desktop machine as described below. Git includes the tool **Git Bash** which will enable Windows user attendees to use a Unix-like shell environment to access their AMI. (Such an environment is available by default for Linux and Mac users.) 

Due to the need to both follow the instructor in zoom and perform analysis, **tablets** and **ipads are not suitable** for using during this course. Having a second screen is not necessary for this course, however if you have access to this, this may make it easier to follow along. We will be using a web version of the integrative genomics viewer (IGV), alongside using zoom and connecting to the AMI, and so having both an up to date browser and a stable internet connection is important.


## Installing Git Bash in your Windows personal computer

Attendees using a Windows laptop or desktop must install **Git Bash** prior to the course, as instructed below. Git Bash is a command-line interface (CLI), also known as a **shell** or **terminal**, which will enable you to access your AMI from your personal computer. Attendees using a Linux or Mac OS X computer **do not need to install** any additional software, but only open a terminal running the Bash shell. 

The steps below correspond to the installation of Git for Windows version 2.33.1 from scratch. The installation of a more recent version, or updating a previously installed version, may show different wording in the screen messages mentioned below or may vary slightly in the number of steps to follow. Just choose as many of the options below as possible. 
- Download the [Git for Windows installer](https://gitforwindows.org/) which installs both Git and Git Bash. 
- Once the installer is downloaded, double click on it and **follow** the **next steps**, wherein you will be asked some questions and to select an option. **Each question** will be displayed at the top of a small window and **is shown below** in *Italics*, and the selection to be made in **bold**. So, in the screen-window showing the question:
- The app you're trying to install isn't a Microsoft-verified app ..?
  - Click on **Install anyway**
- Do you want to allow this app to make changes to your device?
  - Click on **Yes**
- *GNU General Public License*
  - click on **Next**.
- *Select Destination Location*
  - click on **Next** (don't change the location shown).
- *Select Components*
  - select (click on) **Additional Icons** and then click on **Next**.
- *Select Start Menu Folder*
  - click on **Next** (don't change the folder name shown).
- *Choosing the default editor used by Git*
  - select **Use the nano editor by default** and click on **Next**. **NB**: you may need to click on the dropdown menu (a small icon like this 🔻or this 🔽 on the right of the default option shown) and to **scroll up** with the mouse to see this option.

  <img src="../fig/icon-git-bash2.png" alt="GIT BASH terminal" width="50"/> 

- *Adjusting the name of the initial branch in new repositories*
  - keep the selected (or select the) option  **Let Git decide** and click on **Next**.
- *Adjusting your PATH environment*
  - keep the selected, *Recommended* option **Git from the command line and also from 3rd-party software**, or selec it, and click on **Next**. NB: if this option is not selected, some programs that you need for the course will not work properly. If this happens rerun the installer and select the appropriate option.
- *Choosing the SSH executable*
  - keep the selected (or select the) option **Use bundled OpenSSH** and click on **Next**.
- *Choosing HTTPS transport backend*
  - keep the selected (or select the) option **Use the OpenSSL library** and click on **Next**.
- *Configuring the line ending conversions*
  - keep the selected (or select the) option **Checkout Windows-style, commit Unix-style line endings** and click on **Next**.
- *Configuring the terminal emulator to use with Git Bash*
  - keep the selected (or select the) option **Use MinTTy (the default terminal of MSYS2)** and click on **Next**.
- *Choose the default behaviour of `git pull`*
  - keep the selected (or select the) option **Default (fast-forward or merge)** and click on **Next**. 
- *Choose a credential helper*
  - keep the selected (or select the) option **Git Credential Manager Core** and click on **Next**.
- *Configuring extra options*
  - keep the selected option and click on **Next**.
- *Configuring experimental options*
  - click on **Install**.
- Click on **Finish**.

**To run** Git Bash, double click on the Git Bash icon in your Desktop screen.

**To exit** Git Bash, press Ctrl-d, that is pressing the keys Ctrl and d simultaneously.




