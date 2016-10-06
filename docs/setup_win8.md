Windows 8 (and higher) Setup
===============

* Get Java installed
* Get Nightcode installed
* Test installation

<!--
## Starting a command prompt

For these instructions, and for much of the class, you will need to have a command prompt open. This is a text-based interface to talk to your computer. Go to the "Windows" screen (the "Start Screen") and type "command". Choose the "Command Prompt" program, like in this screenshot:

![Starting a command prompt](img/win8/starting-command-prompt.png)

When you choose "Command Prompt," your screen should look similar to this:

![Command prompt](img/win8/command-prompt.png)

If you have never used the command prompt before, you may want to spend some time [reading up on command prompt basics](http://dosprompt.info/). For the rest of this setup, I will tell you to run commands in your command prompt. When I say that, I mean "type the command into the command prompt and press the Return key."

On other operating systems, the command prompt is called the terminal. We will use the terms terminal, command prompt, and command line interchangably.
-->

## Installing Java

Go to [Oracle Java Development Kit (JDK) 8 download site](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html). You should see a screen like the following:

![First page of Java download](img/win/java-download1.png)

Click the button above "Java Platform (JDK)," as you can see in the above picture. Then you will come to a page that will have the following table on it:

![Second page of Java download](img/win/java-download2.png)

Click the radio button to accept the license agreement, and then download one of the two Windows choices. If you are running 32-bit Windows, choose "Windows x86." If you are running 64-bit Windows, choose "Windows x64."

If you do not know if you are running 32-bit or 64-bit Windows, go to the "Windows" screen (the "Start Screen") and type "system." Choose "System." (If that does not work, type "Control Panel" and choose "System" from the Control Panel screen.) You should see a window like the following:

![Windows My Computer properties](img/win8/system-properties.png)

You should see if you are running 32- or 64-bit Windows beside "System Type."

Once you have downloaded the right Java version, run the executable you downloaded to install Java. Follow the installation wizard.

Note: when you are asked for a name of the folder that Java would be installed in, make sure that the suggested folder name has no spaces in it. If there are spaces, replace them with underscores. 

## Installing Nightcode

Nightcode is a Clojure IDE that comes bundled with other tools in the
clojure development stack. 

![Nightcode IDE](https://sekao.net/nightcode/screenshot.png)

To download and install Nightcode, go to [https://sekao.net/nightcode/](https://sekao.net/nightcode/), scroll down a bit to **Download Version 2.1.5** and click on the Windows icon. This will download an installer `Nightcode-2.1.5.exe`. Double-click on it to start. 

You may get a message indicating that this type of files may be harmful for your computer and asking you if you still would like to run it. Allow running it. If you get a message that the firewall has blocked some of its features, click "allow access". 

Once Nightcode is successfully installed, it will start and look like the picture above (only without all the code). 

Now follow to instructions for your track to get the Clojure project you will be working on: 

- [Track 1: turtles](setup_track1.md).
- [Track 2: Clojure koans](setup_track2.md). 


