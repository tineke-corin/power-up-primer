# power-up-primer
A git primer for the power-up workshop

## Getting started with Git
1. Install Git on your computer

This will depend on what kind of system you're using. Check this page
for links to installers for Windows, MacOS, and Linux:
https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

2. Create an account account on GitHub

Hit the 'sign up' button at the top right on github.com, and follow the
instructions.

3. Set up your Git configuration

This just sets your name, username and preferences.
https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup

4. Clone this repository

This is just a good way to practise! You don't need to have an account
on Github for this step.

On this repository, click the 'Code' button.  This opens a popup with
3 different ways to clone the repo.  Copy the HTTPS value.

On your computer, navigate to a place where you want the code to sit.

Run the command `git clone <repo>` where <repo> is what you copied
in the previous step.

The `git clone` command will prompt you for your GitHub username
and password.

The output should say `Cloning into 'power-up-primer'...`.  Once it is
done, you should have a directory called 'power-up-primer', that contains
the contents of this repo :tada:

## Adding your own work
1. Create your own repository

In GitHub, navigate to Your Repositories, and click the 'New' button.
* Set a name (this needs to be unique within your account).
* Choose whether it should be public or private.
* Always add a README file!
* If you know what you're going to build, select a template .gitignore file.
* Click on 'Create repository'

2. Clone your repository

Your new repository will have a URL to clone it with, just like this one.
Clone it in the same way.

3. Make some changes to your code

For an easy start, try editing your README.md file.

4. Commit your changes

Run `git commit -a`.  The `-a` flag means 'all changes'.
Git will open up a prompt where you can edit the commit message. Once you
save that message in the editor where you're editing it, git will 
create the commit.

5. Push your changes to GitHub

Run `git push`.  This will push that commit up to GitHub.

6. View your changes

If you changed the README, it'll be really easy to see the changes - just
go to your repo on GitHub.com and refresh the page.

7. Congratulations!

You just started your Git/GitHub journey! :tada: There is loads more to learn
but these basics will get you far.

Your next step is to do some reading about how Git works, and learn
about branches.

This book is a great resource: https://git-scm.com/book/en/v2

GitHub also has really good resources: https://docs.github.com/en/get-started/quickstart/hello-world

But most of all: practise!
