OS X Setup
==========

* [Start a terminal](#starting-a-terminal)
* [Make sure Java is installed](#making-sure-java-is-installed)
* [Get Leiningen installed](#installing-leiningen)
* [Test installation](#testing-your-setup)

## Starting a terminal

For these instructions, and for much of the class, you will need to have a terminal, or command line, open. This is a text-based interface to talk to your computer, and you can open it by running Terminal.app, which is found under `/Applications/Utilities`. If you have never used the terminal before, you may want to spend some time [reading up on command-line basics](http://blog.teamtreehouse.com/command-line-basics).

Go ahead and open your terminal now. It should look something like this:

![blank terminal](img/os_x/blank_terminal.png)

The prompt (where you will type your commands) may look different: it usually shows the computer name and user name, as well as the folder or directory you are currently in.

For the rest of this setup, I will tell you to run commands in your terminal. When I say that, I mean "type the command into the terminal and press the Return key."

## Making sure Java is installed

Run `java -version` in your terminal. If you do not have Java installed, OS X will prompt you to install it. Follow all of the directions OS X gives you, then return to this part of the tutorial and run `java -version` again.

If Java is installed, you will see something like this in your terminal:

![Java version](img/os_x/java_version.png)

The details of Java's version may differ from what you see above; that is perfectly fine. If the command line tells says something like `command not found` that means you don't have java installed. Go [here](http://www.oracle.com/technetwork/java/javase/downloads/index.html) and click **JDK Download** to install the java development environment

## Installing Leiningen

Leiningen is a tool used on the command line to manage Clojure projects. **You only need to install Leiningen if you are in track 2.**

To install `lein`, execute the following commands in your terminal. You will be prompted to enter your password.

```bash
curl https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein > lein
sudo mkdir -p /usr/local/bin/
sudo mv lein /usr/local/bin/lein
sudo chmod a+x /usr/local/bin/lein
cd $HOME
echo 'PATH=$PATH:/usr/local/bin' >> .bashrc
source .bashrc
```

After you run the above commands, run the `lein version` command. It should take a while to run, as it will download some resources it needs the first time. If it completes successfully, you are golden! If not, ask an instructor for help.

## Installing NightCode
Nightcode will be where you will be actually doing you Clojure programming! 

![Nightcode IDE](https://sekao.net/nightcode/screenshot.png)   

Go to the [NightCode site](https://sekao.net/nightcode/). On the page there, click on `Free Download (Version 1.0.1)` and you will download a `.jar` file. 

There should now be a file named `nightcode-1.0.1-standalone.jar` in your Downloads folder, move it to your Applications folder.

You should be able to open NightCode by just double clicking on `nightcode-1.0.1-standalone.jar` but if that doesn't work you will need to open the terminal(see above) and type `java -jar <path to nightcode download>`. Here is an example, if you have downloaded Nightcode to `~/tools/nightcode`, you would type the following in the terminal.

```
java -jar ~/tools/nightcode/nightcode-1.0.1-standalone.jar
```

## Cloning a git Repository
git is a neat tool that is sort of like dropbox for code. It allows many people to collaborate on projects and make their code open to the rest of the world! We have prepared some code for both track 1 and track 2 that will run the lessons you will be using. The process of getting this code is called *cloning* and Nightcode has some nice tools that makes that process super easy! You will need to open NightCode and follow these instructions. 


 1. Click `New Project`
 2. Select a folder location for your project, type in your project name (say CBB) in the `File Name` form and click `Save`.
 3. On the `Specify Project Type` screen, click `Download`. 
 4. If you are in **track 1**, type in `https://github.com/clojurebridge-boston/track1-turtles.git` where it says `git address`.
 5. If you are in **track 2**, type in `https://github.com/clojurebridge-boston/track2-functional.git` where it says `git address`.


That should be it!

## Try the koans

If you're a track 2 student, try to tackle running the [koans](koans.md).
