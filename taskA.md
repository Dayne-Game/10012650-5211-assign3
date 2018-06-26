[Task A](taskA.md) [Task B](taskB.md) [Task C](taskC.md)
# Visual Studio Code
Visual Studio Code is an open-source code editor for MacOS, Windows and Linux. Visual Studio Code is a simplicit code editor with IntelliSense for code completion and debugging. VSCode has a delightful edit-build-debug cycle, so you don't have to fiddle around as much in your enviroment, which gives you a lot more time porgramming/coding.

VSCode is designed to make coding and debugging easy, and has support for hundreds of different languages. VSCode is based of Electron. Electron is a framework which is used to deploy Node.js for desktop running (Desktop Applications).

## Visual Studio Installation Requirements
MacOS Requirements:
- 10.9 or later

## Visual Studio Code Installation
The easiest way to install VSCode is through Homebrew.

### What is Homebrew?
Homebrew is a free and open-source software package management system that simplifies the installation of software on Apple's macOS operating system. 

---

### Installing Homebrew
<figure class="video_container">
  <video width="420" height="340" border="5" autoplay="true" loop="true">
    <source src="videos/hombrew-install.mp4" type="video/mp4">
  </video>
</figure>
Step 1: Press Command-spacebar to open Spotlight and start typing `terminal` than press enter

Step 2: In your terminal to install homebrew copy and paste the command below into your terminal prompt and press enter

`
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" 
`

You will then need to input your computer password (not Apple ID Password) prompt at `Password: 🔑` (in the terminal). Than wait until homebrew is installed. 

When homebrew is installed you can enter `brew -v` to see its version, by doing this also shows you that homebrew has successfully installed on your computer. Since we now have homebrew installed we can download a whole lot of applications through the terminal. This makes installation quick and easy. You can now go onto Step 2: Installing VSCode.

***When you install Homebrew. Homebrew installs Xcode Command Line tools. Which installs Git, so you don't need to install git.(Git is a requirement for Visual Studio Code) this will be explained in the Git Section***

---

### Step 2: Installing VSCode
<figure class="video_container">
  <video width="420" height="340" border="5" autoplay="true" loop="true">
    <source src="videos/VSCODE.mp4" type="video/mp4">
  </video>
</figure>
Once Homebrew is installed copy and paste this command `brew cask install visual-studio-code` inside the terminal and press enter.

***If you have closed/exited Terminal press command-spacebar and search terminal and press enter to open up terminal again***

VSCode should start installing. You will than be asked for your Password (Computer Password not Apple ID Password) prompt at `Password: 🔑` towards the end of the installation.

---

<link href="styles.css" rel="stylesheet">