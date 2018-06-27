[Task A](taskA.md) [Task B](taskB.md) [Task C](taskC.md)
# Task B

## Task B1
Visual Studio Code is used for creating websites, native and language-specific programs. VSCode has support for multiple different languages, that you can use to write programs. Such as HTML, JavaScript, CSS, C#, Python, C, C++, PHP, Java and Ruby and many many more. You can debug and test most console applications inside VSCode. But you may need to install an extension  However you cannot test or debug HTMl inside VSCode (because HTML requires a browser to view). You can install an extention called Live Server which allows you to run your HTML, CSS and JavaScript (Front-End Website) in a server like enviroment using your localhost (127.0.0.1.) address. This extension shows whether your website will run as expected on a server.

## Task B2
VSCode is used to create websites and applications. VSCode is very easy to use. When you open VSCode the first page to open is the welcome page. On the welcome page you can open your recent files or a folder, or create a file. There is also links underneath the help section of the welcome page. On the left hand side, there is a toolbar. This is where you view your files and folders, add extension and also debug your application.

There are three main extensions that is a must have for VSCode:
1. Live Server
2. GitLens 
3. C#

Live Server allows you to run your website in a server like enviroment. GitLens supercharges Git and show you when was the last commit when you hover over any line in your code. GitLens allows you to see when the code block was last changed when, who did the change and where. The C# extension allows you to write C# applications/programs. C# gives light weight tool support for .Net core. C# also gives you support for project.json and csproj projects for Windows, macOS, and Linux.

### How to install Extensions
To install extensions click on the 5th icon down form the top icon on your toolbar. This will show you a searchbar, installed extensions and recommended extensions. Now click on the searchbar to search for an extension you want to download and install. Than click on the extension than click the install button. Once it has installed click the reload button whihc reloads the page and enables the extension.
<br>
**Example of installing Extensions. Im installing Live Server but works the same way for all extensions**
<br>
<figure class="taskb_container">
  <video class="taskb-vid" width="620" height="540" border="5" autoplay="true" loop="true">
    <source src="videos/extension-install.mp4" type="video/mp4">
  </video>
</figure>

### Basic Commands
There are a lot of basic commands that make creating applications and website easy. There is a plug-in which is already pre-installed for HTML, XML, and XSL files in VSCode called Emmet. Emmet allows you to create HTML content quickly. The most common command is `shift-1-tab` This gives you a HTML template. There are alot more commands the emmet provides, Heres a link to see and read all of the emmet commands <a href="https://docs.emmet.io/cheat-sheet/">Emmet Commands Link Cheat Sheet.</a> When you want get into a folder you can use the terminal to locate and get into the folder. Once you are in the folder you can open your current folder with the `code .` command. This opens your current folder in VSCode. There are alot of other commands that VSCode has.

### Bash Terminal
When you installed Homebrew it all ready installed Git Bash on the macOS terminal. So VSCode already has git bash (which is the macOS terminal) as the default terminal to use. So you don't need to go and chnage your default terminal settings.

## Task B3
To test a web page go into your HTML file and press command-o then command-l to open live server or click the liver server button. This will open your website in your default browser, hopefully Google Chrome. Right click on the browser and select inspect. You can now make changes. Please note  changes made through inspector will not be saved.
<br>
**Example of using Live Server and Inspect Element**
<br>
<figure class="taskb_container">
  <video class="taskb-vid" width="620" height="540" border="5" autoplay="true" loop="true">
    <source src="videos/inspect-live.mp4" type="video/mp4">
  </video>
</figure>

The debugger in VSCode only shows output not input. To debug a console application that takes user input you need to change "console": "internalConsole"; to "console": "externalTerminal";. This will output the program through the macOS terminal when debugging.
<br>
**Example of changing the console**
<br>
<figure class="taskb_container">
  <video class="taskb-vid" width="620" height="540" border="5" autoplay="true" loop="true">
    <source src="videos/terminal.mp4" type="video/mp4">
  </video>
</figure>

**Debugger Video and Output Example**
<figure class="taskb_container">
  <video class="taskb-vid" width="620" height="540" border="5" autoplay="true" loop="true">
    <source src="videos/debugger.mp4" type="video/mp4">
  </video>
</figure>
### Break Points
A break point is an intentional stopping or pausing place in a program. This is put inplace for debugging purposes. Not for Web use.
<br>
To add break points to your program hover your mouse cursor over the line you would like to add your break point. Select the circle on the left of the line number.
<br>
**Example of adding a Break Point**
<br>
<figure class="taskb_container">
  <video class="taskb-vid" width="620" height="540" border="5" autoplay="true" loop="true">
    <source src="videos/Break-Point.mp4" type="video/mp4">
  </video>
</figure>

## Task B4
### Atom 
Atom is a text and source code editor that was developed by Github. It was released on the 26 Feburary 2016, and is under the MIT license. Atom is cross-platform so it works on Windows, macOS and Linux. 
<br>
**There are four reason to use Atom:**

1. Real Open Source
Since it was Built by Github which is on the precepts of open source it gives a much greater likelihood of being maintained in the future.

2. Entire view layer is customizable
Atom has a more coherent theming scheme than VSCode. So this make the general apperance and much more a whole lot easier to customize.

3. Second Best Plug-in Support
There are thousands of packages available that are intergrated into Atom.

4. Language Support
Atom has a very wide library of languages, it isn't locked down to only some languages. Also and equal amount of code linters and style utilities available in Atom.
<br>
**Reasons not to use Atom (and use VSCode):** 

1. VSCode supports breakpoints and debugging for a handful of languages in Node. Which makes it easier to debug programs in VSCode than Atom.

2. VSCode loads a lot faster than Atom. Atom is a lot heavier than VSCode because Atom supports alot more languages than VSCode.

3. VSCode has very good autocomplete functionality. This is a huge advantage for rapid development.

### Sublime Text 2
Sublime Text 2 is a proprietary cross-platform (Windows, macOS, Linux) source code editor. It uses a Python application type interface. Sublime Text 2 offers support for a lot of programming languages and markup languages. Functions can be added to Sublime Text 2 through users plug-ins.
<br>
**Reason to use Sublime Text 2**

1. Great Symbol Analysis
When you open a project it automatically runs a process called symbol analysis. This finds key words in your code/program. This is good because you press Cmd + Shift + R and search for class names and so one. This is good if you want to know where each variable in your program is located for an example.

2. Super Fast
Sublime Text 2 has been tested and is the fastest source code editor. With Sublime Text 2 native app is written in C++ itd footprint is much lower, giving faster loads.

3. Better Vim Bindings
Sublime Text 2 has better vim bindings than VSCode and the user often write faster code. Sublime Text 2 offers vim bindings straight out of the box aso you don't need to go and install a vim bindings plugin.
<br>
**Reasons not to use Sublime Text 2 (and use VSCode):**

1. VSCode has an amazing Toolbar
VSCode's toolbar is very good because it allows user to have more flexibility for when they want to create or change files. VSCode's tollbar also has everthing you need, and is visible at all times which is nice for when you are creating apllications and want to see you files for an example.

2. Debugger
VSCode's built-in debugger is probably the best debugger around. It has support for certain languages, but allows yout o ajust the debugger terminal to the way you want it. You can debug most applications throughthe debugger without havimg to leave VSCode. 


<link href="styles.css" rel="stylesheet">
