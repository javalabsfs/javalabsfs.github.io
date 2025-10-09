---
layout: doc
title: 4 Lab tasks
order: 4
previous: /vscode/
next: /
---

Now that you have completed the setup, it is time to put it to the test.

---

Here are the lab explanations one more time:

## What is a lab?
A lab is a programming assignment. You will receive a lab every Thursday, 2PM which you must complete until Friday, 2PM. Exceptions may occur due to e.g. national holidays.

## How are we going to use Git and GitHub?
We will post the labs on GitHub which you can access via invitation links that we will send you. When you open such a link, a personalised repository/instance of the lab will be generated for you. You will be cloning this repository to your computer, making changes to the provided code or uploading new code, and sending the changes to the remote repository on GitHub. Do not forget about the last step as we cannot see any changes you make to the repository on your computer.

---

## The actual lab

1. get your lab 0 by clicking [here](https://guthib.com/)
2. clone it to your computer using `git clone`
3. open it (the folder) in VSCode

## Task 1
Open `student.txt` and and replace the dummy information with yours, i.e. your full name, GitHub username, and matriculation number.

## Task 2
Create an (extremely simple!) Java file called `HelloWorld.java` that simply has one main method which prints `"Hello world!"` to `System.out`. You can write the code for this yourself, or copy it from the Moodle course or the internet. Make sure you save the file in the lab 0 folder since that is the only one being tracked by Git.

---

Once you are done,
1. `git add` the files you modified/created
2. `git commit -m` your changes with a meaningful commit message
3. `git push` to the remote repository

Refer back to [the previous page]({{ "/git/#basic-git-commands" | relative_url }}) for details on the commands.

Double-check if your push was successful by opening your lab 0 on the GitHub website.

The tutors will only be able to see what you push to the remote repository. They will never see changes you make on your computer unless you commit and push them.

---

Also, remember — Google is a programmer’s best friend! Learning how to effectively search for solutions is a key skill. If you have a question, chances are someone else has had the same issue. With proper searching, you'll often find the answer you need. :)

Enjoy your journey into the world of programming, and don’t be afraid to explore and experiment along the way!
