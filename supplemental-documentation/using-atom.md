# Using Atom to Add a New Question

This guide will walk you through the process of adding a new question
to this repository using the Atom text editor. Atom is available for free
[here](https://atom.io) and works on OS X, Windows, and Linux.

Once you have Atom installed and opened, you'll be ready to create your new
question.

## Add your project to Atom

To get started, you'll want to add this repository to Atom as a new project.

Right-click the Tree View on the left side of the screen (under the "Projects"
header), then choose "Add Project Folder" (pictured below).

If you don't see the Tree View when you open Atom, you can toggle its visibility
using the keyboard shortcut `Ctrl-\` on Windows and Linux or `Cmd-\` on OS X.

![Adding a new project folder in Atom.][add-project]

A dialog should appear asking you to select a folder.

Navigate to where you stored your clone of this repository (the directory is
probably named `software-interview-prep`), select the folder, and accept
(hit "Select Folder").

![Selecting the correct project directory.][select-project-folder]

## Add a new HTML file for your question

Now that you've added this repository to Atom as a project, you can create a
new `.html` file with your question.

Expand the tree view of this project so that it looks something like the picture below.
You'll want to expand until you can see the contents of the `views/questions` directory:

![Expanded tree view of this repository in Atom.][expand-tree-view]

Depending on whether your question is a whiteboard question or a technical question,
you'll add a new file to either the `views/questions/whiteboard` directory or
the `views/questions/technical` directory. For this example, we'll add a
new whiteboard question.


[add-project]: images/editor-atom/add-project.png
[select-project-folder]: images/editor-atom/select-project-folder.png
[expand-tree-view]: images/editor-atom/expand-tree-view.png
