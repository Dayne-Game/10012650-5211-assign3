[Task A](taskA.md) [Task B](taskB.md) [Task C](taskC.md)

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
<br>
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
<br>
Step 5: This step is optional, but when you typed `dotnet new console` after it has finished you can type `code .` Which opens the folder in Visual Studio Code. When you do this is installs some debugging tools for .Net Core.

## .Net Core commands (Common Commands That I Use)
- `dotnet new console` This creates a new console application is the dierctory that you are in.
- `dotnet restore` Restores the dependencies for a given application.
- `dotnet build` Builds a .NET Core application.
- `dotnet run` Runs the application from source.

---

# Git

## How to install Git 
Since we installed Homebrew. Homebrew install a thing called Xcode Command Line Tools, This has git installed so we don't need to go to the git website to download this. This is why Homebrew is quick and easy for installing applications at half the speed of usuallly doing it the Windows way.

## What is Git
Git is a version control system that tracks and makes changes to computer files from multiple users/groups. When users use git they usually upload there work to websites like Github and Bitbucket.

## Git Branching
Git branches represent an independent line of developement. Branches serves as the edit/stage/commit process. Git branches help teams of people know who did what. For example you might have a Front-End Team branch and a Back-End Team branch. So everthing the Front-End Team commits and uploads has there team name all over it so people know they did that work.

## Git Merging
Merging puts all multiple sequences of commits into one unified history. Git merge is usually used to combine two branchs into one. This is also used during SCRUM do when two teams (branches) finishes a task they can merge it together. Example: You have a front-end website and a back-end website, right now they are completely two different parts. `git merge master` merges the front-end website and the back-end website together to create one whole website. 

## Commit Messages
Commit messages are very important and need to be decriptive. When you change something in your application or program, and push it to Github(for example) you type in a commit message. This message should contain every change you made throughout that commit. The reasoning for this is because when other team members look at this they want to know what changes have been made or added. Doing this avoids confusion from within the team and other team mates from doing the same change you have done. Git commit messages also help for when you want to know what stage you are at with your program.

## Git Commands (Command Commands That I Use)
- `git add .` Add all files to a staging index
- `git commit -m "<your message>"` Commit your code change
- `git remote add origin <url>` Links your folder on your computer to a reposititory on website like Github
- `git push origin master` Push changes through Master Branch
- `git clone <url>` Downloads the repositiory of that url onto your machine
- `git pull` Pull all the latest stuff from remote branch into your local branch
- `git add YOUR_FILE` Add just that one file to staging index
- `git branch` To see what branch you are in.
- `git merge master` Merges multiple branches into one branch.

<link href="styles.css" rel="stylesheet">
