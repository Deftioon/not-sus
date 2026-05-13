# This project is not sus at all!

## Getting Started

You can either contribute this by pinging me and giving me the text file, or by contributing through git. This file introduces how to contribute through git.

To contribute to this project through git, you will need a GitHub account and have installed git.

### Creating a Github Account

You can find instructions here:

>https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github

I do recommend reading the tutorial fully, though that is not needed.

### Installing Git

You can find instructions on installing Git here:

>https://git-scm.com/install/

## Working on the files

This section covers how to work on the files and syncing them with collaborators. You will need to open the command line (Press `Win + R` on windows and type `cmd`, then press enter).

### Cloning the Repository

First we clone the repo. We do this by doing, in the terminal, 

```
git clone https://github.com/Deftioon/not-sus.git
```

On windows, we might prefer to do instead,

```
cd %userprofile%
cd Documents
git clone https://github.com/Deftioon/not-sus.git
```

Where each line is ran as a separate command.

Then you will be able to find the folder. If you ran the second version, you will find it in `C:\Users\YOURNAME\Documents`, e.g. `C:\Users\Bob\Documents`, which is just your pinned `Documents` folder.

### Pulling changes

Files do not sync automatically. You can sync your files to the main repository on github by going, if on windows, to `C:\Users\YOURNAME\not-sus` or `C:\Users\YOURNAME\Documents\not-sus`. For the latter, this will be the `not-sus` folder in the `Documents` folder.

Then, run the command

```
git pull origin main
```

After this, you want to create your own branch by doing

```
git checkout -b NAME
```

Where you can name your branch anything you like.

### Editing the files

From here, you can freely do anything to the files as you please. 

### Pushing changes

So now you have edited the file. How do I make my changes go to the main repository? We push the changes.

First, we must commit them. Run

```
git add -A
git commit -m "MESSAGE"
```

Where you can put your own message.

Then, finally, run

```
git push origin NAME
```

Where `NAME` is the name of the branch we created earlier.