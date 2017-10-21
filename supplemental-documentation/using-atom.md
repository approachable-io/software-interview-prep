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

Right-click the question directory (`whiteboard` in our case) and choose "New File":

![Adding a new file to a directory in Atom.][add-new-file]

Enter the new filename in the dialog that appears.
The filename should be the name of your question, with words separated by dashes,
ending with `.html`:

![Naming the new file.][name-new-file]

## Adding your finished question to the list

Once you've finished writing the HTML file for your new question, you should see
that your file's color has changed to green in the tree view:

![A completed question in an HTML file.](finished-question)

The last step is to add your question to the main list. If you wrote a whiteboard
question, this list will be in `views/questions/whiteboard.html`; technical
questions go in `views/questions/technical.html`.

Open the relevant file (for us, it's `whiteboard.html`) and find the `<h1>`
element with the text "Software Interview Whiteboard Questions" or
"Software Interview Technical Questions".

Underneath this header (still inside the `.text-container` div), add a new link
(`<a>`) that leads to your project. The new element should follow the pattern
shown below (which matches the existing link elements in the file). Note the
`href` value of the link:

![Adding your question to the general list. The link tag should follow the same format as the others in the file.][add-question-to-list]

## Next steps

Now you're ready to stage and commit your changes and submit a pull request!
Return to the main guide (README.md) for instructions on how to do this.



[add-project]: images/editor-atom/add-project.png
[select-project-folder]: images/editor-atom/select-project-folder.png
[expand-tree-view]: images/editor-atom/expand-tree-view.png
[add-new-file]: images/editor-atom/add-new-file.png
[name-new-file]: images/editor-atom/name-new-file.png
[finished-question]: images/editor-atom/finished-question.png
[add-question-to-list]: images/editor-atom/add-question-to-list.png
