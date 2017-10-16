# software-interview-prep
Approachable IO website to help those prepping for interviewing while allowing anyone to practice their skills by making Pull Requests.

## Contribute an interview question
If you're a Git/Github expert, feel free to skip some sections. If you have never made a Pull Request before, check out our [getting-started](https://github.com/approachable-io/getting-started) guide which will show you how to create your Github account and make your first Open Source contribution. The following guide assumes you have already taken those steps. If you have that down, let's jump into sharing your interview question!

### Install Git
Here is a detailed explanation of [how to install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Fork the project
A fork is a copy of a project. In this case, you will be copying the project [software-interview-prep](https://github.com/approachable-io/software-interview-prep), making a change to that copy, and then making a Pull Request - a request for the original product to incorporate your changes.

Click the `Fork` button in the top right corner of the screen to fork the repository.

![Fork Github Repository](images/github-fork-repository.png)

If everything goes smoothly it should look like this for a few seconds

![Forking Load Screen](images/forking-load-screen.png)

And then it should look like this ![After Fork Screen](images/after-fork-screen.png)

The difference between the repository you started with and this new repository is that your username should appear in the top left. If your username is `grace-hopper`, it should say something like `grace-hopper / software-interview-prep` and the line below it should read `forked from approachable-io / software-interview-prep`.

### Clone the fork

Once you've forked the repo, you need to be able to edit it on your local machine.

To do this, click on the green clone or download button, and click the clipboard to copy the repo URL.

![Copy Clone URL](images/command-line/get-clone-url.png)

In this picture, you can see that the clone is using SSH format (git@github.com:\<user\>/\<repo\>.git). You may also 
use 
the HTTPS format if you prefer (https://github.com/\<user\>/\<repo\>).

Once you have that copied, open your command line (cmd.exe on Windows, Terminal on macOS, and if you use linux you'll
 know where it is), `cd` to the directory you want to clone the repo into. For me it will be `~` (`/home/redxtech/`).

Once you're in your desired directory, run this command:
```bash
$ git clone git@github.com:redxtech/when.git
```
That will be cloned into a directory called `when`. If I wanted to make it a different directory, I would run this 
command:
```bash
$ git clone git@github.com:redxtech/when.git ~/cloned-folder
```

Once it finishes, you can `cd` into the directory with `$ cd when`.

### Install dependencies

Typically, most software projects will have dependencies that need to be installed before you can begin to work on 
the project. This will most likely be mentioned in the README of the project, but if not, you will have to explore 
and find out yourself. Most node/js projects will use npm as the package manager, so you can just run `$ npm install`
 (or `$ yarn`) and it will install everything for you (provided you have node & npm or yarn installed on your 
 computer already). Most python projects will have a requirements.txt file with all of the packages needed. You can 
 install these with `$ pip install -r requirements.txt`. Some projects don't have any dependencies at all This differs
 based on what languages the projects use, and who writes them, so reading the README is the best way to find out.

## Want to contribute in another way?
Anyone can help make this project better - check out [issues](https://github.com/approachable-io/approachable-io/issues)!
