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

<link href="styles.css" rel="stylesheet">
