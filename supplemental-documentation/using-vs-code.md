# Using Visual Studio Code to Add a New Question

This guide will walk you through the process of adding a new question
to this repository using the Visual Studio Code editor. VS Code is available for free
[here](https://code.visualstudio.com/) and works on Windows, OS X, and Linux.

Once you have VS Code installed and opened, you'll be ready to create your new
question.

### Add your project to VS Code

To get started, you'll want to add this repository to VS Code as a new project.

When you first open VS Code, by default, you will be shown a "Welcome" screen.  If you have already cloned your repository simply choose "Open folder..." and select the directory you are working in.

![Opening a new project folder in VS Code from Welcome][welcome-add]

If you don't see the Welcome screen when you open VS Code, you can open a folder by accessing the File menu or activating the keyboard shortcut `CTRL+K CTRL+O` on Windows.

![Opening a new project folder in VS Code from file menu][file-add-folder]

A dialog should appear asking you to select a folder.

Navigate to where you stored your clone of this repository (the directory is
probably named `software-interview-prep`), select the folder, and accept
(hit "Select Folder").

![Selecting the correct project directory.][select-project-folder]

### Add a new HTML file for your question

Now that you've added this repository to VS Code as a project, you can create a
new `.html` file with your question.

Expand the tree view of this project in the Explorer so that it looks something like the picture below.  If you do not see the Explorer you can use the shortcut `CTRL+Shift+E` and it should appear.
You'll want to expand until you can see the contents of the `views/questions` directory:

![Expanded Explorer view of this repository in VS Code.][expand-view-explorer]

Depending on whether your question is a whiteboard question or a technical question,
you'll add a new file to either the `views/questions/whiteboard` directory or
the `views/questions/technical` directory. For this example, we'll add a
new technical question.

Right-click the question directory (`technical` in our case) and choose "New File":

![Adding a new file to a directory in VS Code.][add-new-file]

Enter the new filename in the dialog that appears.
The filename should be the name of your question, with words separated by dashes,
ending with `.html`:

![Naming the new file.][name-new-file]

### Adding your finished question to the list

Once you've finished writing the HTML file for your new question, you should see your source control shows changes on the left hand menu:

![Changes shown in source control.][source-control]

The last step is to add your question to the main list. If you wrote a whiteboard
question, this list will be in `views/whiteboard.html`; technical
questions go in `views/technical.html`.

Open the relevant file (for us, it's `technical.html`) and find the `<h1>`
element with the text "Software Interview Whiteboard Questions" or
"Software Interview Technical Questions".

Underneath this header (still inside the `.text-container` div), add a new link
(`<a>`) that leads to your project. The new element should follow the pattern
shown below (which matches the existing link elements in the file). Note the
`href` value of the link:

![Adding your question to the general list. The link tag should follow the same format as the others in the file.][add-question-to-list]

### Next steps

Now you're ready to stage and commit your changes and submit a pull request!
Return to the [main guide](../README.md) for instructions on how to do this.


[welcome-add]: ../images/editor-vs-code/welcome-add.png
[file-add-folder]: ../images/editor-vs-code/file-add-folder.png
[select-project-folder]: ../images/editor-atom/select-project-folder.png
[expand-view-explorer]: ../images/editor-vs-code/expand-view-explorer.png
[add-new-file]: ../images/editor-vs-code/add-new-file.png
[name-new-file]: ../images/editor-vs-code/name-new-file.png
[source-control]: ../images/editor-vs-code/source-control.png
[finished-question]: ../images/editor-vs-code/finished-question.png
[add-question-to-list]: ../images/editor-vs-code/add-question-to-list.png
