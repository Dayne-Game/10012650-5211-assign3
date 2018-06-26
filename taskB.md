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

## Task B3
To test a web page go into your HTML file and press command-o then command-l to open live serv or click the liver server button. This will open your website in your default browser, hopefully Google Chrome. Right click on the browser and select inspect. You can now make changes. Please not changes made through inspector will not be saved.
<br>
**Example of using Live Server and Inspect Element**
<figure class="taskb_container">
  <video class="taskb-vid" width="620" height="540" border="5" autoplay="true" loop="true">
    <source src="videos/inspect-live.mp4" type="video/mp4">
  </video>
</figure>

The debugger in VSCode only shows output not input. To debug a console application that takes user input you need to change "console": "internalConsole"; to "console": "externalTerminal";. This will output the program through the macOS terminal when debugging.
<br>
**Example of changing the console**
<figure class="taskb_container">
  <video class="taskb-vid" width="620" height="540" border="5" autoplay="true" loop="true">
    <source src="videos/terminal.mp4" type="video/mp4">
  </video>
</figure>

### Break Points
A break point is an intentional stopping or pausing place in a program. This is put inplace for debugging purposes. Not for Web use.
<br>
To add break points to your program hover your mouse cursor over the line you would like to add your break point. Select the circle on the left of the line number.
<br>
**Example of adding a Break Point**
<figure class="taskb_container">
  <video class="taskb-vid" width="620" height="540" border="5" autoplay="true" loop="true">
    <source src="videos/Break-Point.mp4" type="video/mp4">
  </video>
</figure>

<link href="styles.css" rel="stylesheet">
