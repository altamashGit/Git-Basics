##  Starting Your Git Journey – Let’s Talk About Init, Add, Status and Commit

## Step 1: Initialize Your Project (git init)

Think of this as telling Git, "Hey, start keeping an eye on this folder."

Open your project folder in the terminal.
Run this command:

        mkdir my-project
        cd my-project
        git init

# You’ll see something like this:
       
        Initialized empty Git repository in /path/to/your/project/.git/

![Screenshot from 2025-01-15 16-14-32](https://github.com/user-attachments/assets/16831737-f78d-4f74-8d7c-af01ad5afcbe)

✨ Now Git is paying attention to your project. It created a hidden .git folder to track changes behind the scenes. 🎉

# what happend behind when you enter this command....?

When you run the git init command in a directory, it creates a new, empty Git repository within that directory by generating a hidden.
git folder which stores all the necessary metadata to track changes to your files.

***********************************************************************************************************************************************


## Step 2: Stage Your Files (git add)

Okay, so you’ve got your project initialized. Now let’s say you create a file, like this:


                echo "Hello, Git!" > index.html


Git doesn’t automatically track this file. You need to tell Git, "Hey, I want you to keep an eye on this file." That’s what git add is for. You’re staging your changes so they’re ready to be saved.

Here’s how you do it:
                
                git add index.html

If you want to stage everything in your project (like multiple files or folders), just run:

                git add .


# ✨ What’s happening?
Think of git add like packing your changes into a box and saying,
"These are the files I want to commit next." Until you stage them, Git doesn’t include them in the next step.
