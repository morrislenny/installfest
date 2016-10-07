Ubuntu Setup
==========

* Start a terminal
* Install Java if needed
* Get Nightcode installed
* Test installation

## Starting a terminal

For these instructions you will need to have a terminal, or command line, open. This is a text-based interface to talk to your computer, and you can open it by clicking "Dash Home" and typing `Terminal`. You can also open a terminal at any time by pressing `CTRL-ALT-T`. If you have never used the terminal before, you may want to spend some time [reading up on command-line basics](http://blog.teamtreehouse.com/command-line-basics).

Go ahead and open your terminal now. It should look something like this:

![blank terminal](img/ubuntu/blank_terminal.png)

The prompt (where you will type your commands) may look different: it usually shows the computer name and user name, as well as the folder or directory you are currently in.

For the rest of this setup, I will tell you to run commands in your terminal. When I say that, I mean "type the command into the terminal and press the Return key."

## Making sure Java is installed

Run `java -version` in your terminal. If you do not have Java installed, Ubuntu will prompt you to install it. It should look something like this:

![no java](img/ubuntu/no_java.png)

Follow all of the directions Ubuntu gives you, selecting the package "openjdk-8jre-headless" then return to this part of the tutorial and run `java -version` again. You should see that Java 8 is installed now. 

<!--
If Java is installed, you will see something like this in your terminal:

![Java version](img/ubuntu/java_version.png)

The details of Java's version may differ from what you see above; that is perfectly fine.
-->

## Installing Nightcode

Nightcode is a Clojure IDE (Integrated Development Environment, which means that it is a text editor, like Word, only specialized for writing programs) that comes bundled with other tools useful for 
working with Clojure. 

![Nightcode IDE](img/nightcode.png)

Note that we will be using Nightcode **1.3.2**, not any of the later versions of Nightcode. 

To download and install Nightcode 1.3.2, go to [https://github.com/oakes/Nightcode/releases/tag/1.3.2](https://github.com/oakes/Nightcode/releases/tag/1.3.2). 
Under Downloads, click on **nightcode-1.3.2-standalone.jar**. 
Once it downloads, you might want to drag it into your `Programs` folder or any other place where it would be convenient to access it later (you also might want to create a folder for Clojure work and put it there). 
After you move it, double-click on it to start. 

You may get a message indicating that this type of files may be harmful for your computer and asking you if you still would like to run it. Allow running it. If you get a message that the firewall has blocked some of its features, click "allow access". 

Once Nightcode is successfully installed, it will start and look like the picture above (only without all the code).

Now follow to instructions for your track to get the Clojure project you will be working on: 

- [Track 1: turtles](setup_track1.md).
- [Track 2: Clojure koans](setup_track2.md). 
