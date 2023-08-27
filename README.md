# Problem Set 1: Getting Started

In this problem set you will do the following:

* Let me know more about youself, your background, and your interest in programming and computer science.
* Practice working with Slack, the app you will use to ask questions in this class instead of using email.
* Log into the remote linux server you will be using to do most of your work for this class.
* Try out the unix commands you will learn this week in class.

To receive full credit you must:

* Submit the PDF from Part 1 to Canvas.
* Complete the course survey from Part 2.
* Post a message on Slack for Part 3.
* Submit the screen capture video from Part 6 to Canvas.

**All components of this problem set are due by Friday, September 1, by 11:59pm Boston time.**

*Note: Please don't try to commit changes to the repo. Homework should be turned in via Canvas for this class.*
---

### Part 1: Make a personalized slide

1. Using PowerPoint, Keynote, or Google Slides, create a single-page landscape mode **PDF** that contains the following information.

* Your name as it appears in Canvas.
* The name you prefer to be called.
* A recent photo of you to help me learn what you look like.

2. Submit this **PDF** to Canvas for Problem Set 1. *Note: You will not get full credit if you submit a PowerPoint or a link to a Google Slides presentation. You must submit a **PDF**.*

### Part 2: Take the course survey
[Take this short survey.](https://forms.gle/mgVFe6LHbTUw1xpL6)

### Part 3: Get started on Slack
[Follow this link to join the Slack organization for this class](https://join.slack.com/t/csci2349textp-swy7447/shared_invite/zt-21lk8o7lf-RvjgY9hkt0f35gz9N0MTgQ). Create your account if you don't have one and feel free to use a pseudonym for your username. Then post a message in the #general channel. Don't forget to @prudhome if you need my attention.

### Part 4: Log into our remote linux server
You should have received an email from our systems administrator, Phil Temples, with a username and password for the CS Lab server. If you have not received this email yet, email me (prudhome@bc.edu) right away. You will be using a program called ssh to access our linux server. Mac users already have ssh installed as part of the Terminal application. Windows users will have to jump through hoops to get access to ssh. Please see the instructions below under Windows Users.


#### 4a. Mac Users
Launch the Terminal application. If you are not sure how to find the Terminal application, you can find it by going up to the magnifying glass in the upper right corner of your screen and then entering "Terminal" in the search bar. The Terminal app will show up in a list of things matching your search. Click on it, and the Terminal app will launch. You can now follow the instructions in 4c, below.


#### 4b. Windows Users

One of the following things should get ssh ready to go. Unfortunately, since Windows machines are all different, depending on how the manufacturer of the computer decided to configure things, there's no way for me to know which of the following will work for you.

* Check to see if you have SSH already installed on your computer. [Follow these instructions to open a cmd window](https://en.wikiversity.org/wiki/Command_Prompt/Open), and then type `ssh`. If it says something like "command not found" then you don't already have ssh installed. If it says something like "usage: blah blah...", then you do have ssh installed. Proceed to 4c, below.
* If that didn't work, Install the Windows Linux Subsystem [as described here](https://learn.microsoft.com/en-us/windows/wsl/install).
* If you aren't able to install Windows Linux Subsystem yourself, go to the [help center in O'Neill Library](https://libguides.bc.edu/oneill-tech-help) and tell them you need to install or activate the Windows Linux Subsystem on your computer.
* If they can't help you, see if you can install the [Windows Terminal](https://learn.microsoft.com/en-us/windows/terminal/).
* If none of the above options works, see me.

#### 4c. Using ssh to connect to the linux server.
After getting yourself a terminal with the Terminal, WLS, cmd, or Windows Terminal, you should see a prompt. This is what it looks like on Mac:

1. If you are off campus connect to the VPN.
2. Connect to our linux server by typing the following, replacing `yourusername` with your user name (i.e., what comes before the @ in your BC email address when it's not your full name; in my case, it's `prudhome`).

```
ssh yourusername@cslab.bc.edu
```
You are now connected to the CS departmnt's linux server.

### Part 5: Try out some unix commands!
You will be using the commands that were demonstrated in class on Wednesday, but you can find information about these commands in the readings and try this our yourself. If you have already taken Computer Systems, this should all be review.

1. Print out your current directory.
2. List the contents of your current directory.
3. Use `echo` to print out the words "Hello, World!" and direct it to a new file called `newfile.txt`.
4. Create a new directory called `my_files`.
5. List the contents of `my_files`.
6. Move `newfile.txt` to the `my_files` directory.
7. Move into the `my_files` directory.
8. Print out the current directory.
9. Make a copy of `newfile.txt` called `newfile_cooy.txt`.
10. Make a new directory inside `my_files` called `copies`.
11. Move `newfile_copy.txt` to `copies`.
12. List the contents of the `copies` directory.
13. Go back to your home directory.
14. Create a `.tgz` file that contains the contenbts of the `my_files` directory called `my_files.tgz`.
15. In your home directory, create a directory called `jumk`, and move everything you've created into that directory.


### Part 6: Create a screen capture video

Once you've practiced all the commands above, and you feel like you can do everything without looking and thinking, start from command 1, 
and take a video of your screen showing you executing all the commands from 1 to 14. (Don't do commnand 15!) The TAs will watch the video, 
and they will check in your home directories to see if you did everything correctly. Submit the video to canvas.

[Instructions for different ways to do video screen capture on Mac.](https://support.apple.com/en-us/HT208721)

[Instructions for different ways to do video screen capture on Windows.](https://www.zdnet.com/article/how-to-screen-record-in-windows-10-or-windows-11/)

---

**Reminder:** To receive full credit you must

* Submit the slide from Part 1 to Canvas.
* Complete the course survey from Part 2.
* Post a message on Slack for Part 3.
* Submit the screen capture video to Canvas.

**All components of this problem set are due by Friday, September 1, by 11:59pm Boston time.**

---

