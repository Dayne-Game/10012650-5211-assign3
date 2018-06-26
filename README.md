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

# .Net Core
.Net Core is an open source, cross platform (meaning it works on Windows, Mac and Linux) .Net Platform. .Net Core is used to create we apps, microservices, libraries and console applications. .Net core 1.0 was annouched an released on June 27th 2016, with the latest version now being 2.1 which was shipped/released May 30th, 2018. The primary languages used in .Net core are C# and Visual Basic.

## Requirements:
 - .Net Core 2.X is only supported on macOS 10.12 (Sierra) or Later
 - .Net Core 1.X is supported on macOS 10.12 (Sierra) and 10.11 (El Capitan)

You can use any editor to develop .Net Core applications, but if you want an intergrated development enviroment download <a href="https://visualstudio.microsoft.com/vs/mac/" target="_blank">Visual Studio for Mac</a>

## Installing .Net Core
<figure class="video_container">
  <video width="420" height="340" border="5" autoplay="true" loop="true">
    <source src="videos/dotnet-install.mp4" type="video/mp4">
  </video>
</figure>
To install .Net Core you can simply use homebrew like the other applications.
Step 1: Copy and paste this command `brew cask install dotnet-sdk` in your terminal and press enter. (Open terminal by pressing command-spacebar and type terminal than press enter). .Net Core should start installing.

Step 2: Towards the end of the installation your are prompt for your computer password (not Apple ID Password) at `Password: 🔑` and press enter. Installation should continue and finish shortly.

Step 3: Once the installation finishes close your current terminal and open a new one. By either clicking launchpad than Other than Terminal, or command-spacebar and type terminal than press enter. This gives your a new refreshed terminal so you can run .Net Core.

Step 4: In your terminal type `cd Desktop` and press enter. You are now on your desktop. Now type `git init myApp` and press enter. You have just created a folder that has git installed. Now go into that folder by typing `cd myApp` and press enter. You are now in your myApp folder. Now type `dotnet new console` and press enter. Now this may take a while but it just restores dotnet and installs packages in your .csproj file, but you don't need to worry about this.

Your terminal should look like this (without the restore):
<br>
`users-Mac:~ username$ cd Desktop` 
<br>
`users-Mac:desktop username$ git init myApp`
<br>
`users-Mac:desktop username$ cd myApp`
<br>
`users-Mac:myApp username$ dotnet new console`


**Optional**
Step 5: This step is optional, but when you typed `dotnet new console` after it has finished you can type `code .` Which opens the folder in Visual Studio Code. Whne you do this is installs some debugging tools for .Net Core.


<link href="styles.css" rel="stylesheet">
 