Windows 7 Setup
===============

* Start a command prompt
* Get Java installed
* Get Nightcode installed
* Test installation

<!--
## Starting a command prompt

For these instructions, and for much of the class, you will need to have a command prompt open. This is a text-based interface to talk to your computer. Go to the Start Menu and type "command" in the search box. Choose the "Command Prompt" program, like in this screenshot:

![Starting a command prompt](img/win7/starting-command-prompt.png)

When you choose "Command Prompt," your screen should look similar to this:

![Command prompt](img/win7/command-prompt.png)

If you have never used the command prompt before, you may want to spend some time [reading up on command prompt basics](http://dosprompt.info/). For the rest of this setup, I will tell you to run commands in your command prompt. When I say that, I mean "type the command into the command prompt and press the Return key."

On other operating systems, the command prompt is called the terminal. We will use the terms terminal, command prompt, and command line interchangably.
-->

## Installing Java

Go to [Oracle Java Development Kit (JDK) 8 download site](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html).  You should see a screen like the following:

![First page of Java download](img/win/java-download1.png)

Click the button above "Java Platform (JDK)," as you can see in the above picture. Then you will come to a page that will have the following table on it:

![Second page of Java download](img/win/java-download2.png)

Click the radio button to accept the license agreement, and then download one of the two Windows choices. If you are running 32-bit Windows, choose "Windows x86." If you are running 64-bit Windows, choose "Windows x64."

If you do not know if you are running 32-bit or 64-bit Windows, go to the Control Panel (Start Menu - Control Panel) and choose "System and Security" and then "System." You should see a window like the following:

![Windows My Computer properties](img/win7/system-properties.png)

You should see if you are running 32- or 64-bit Windows beside "System Type."

Once you have downloaded the right Java version, run the executable you downloaded to by double-clicking on it. Follow the installation wizard.

Note: when you are asked for a name of the folder that Java would be installed in, make sure that the suggested folder name has no spaces in it. If there are spaces, replace them with underscores. 

## Installing Nightcode

Nightcode is a clojure IDE that comes bundled with other tools in the
clojure development stack. 

![Nightcode IDE](https://sekao.net/nightcode/screenshot.png)

# Install Nightcode

Download Nightcode 1.0.1 from the link below into a tools folder like `~/tools/nightcode`

[Nightcode 1.0.1](https://github.com/oakes/Nightcode/releases/download/1.0.1/nightcode-1.0.1-standalone.jar)

Open a command shell and type `java -jar <path to nightcode download>`. For example, if you have downloaded Nightcode to `~/tools/nightcode` type the following in a command shell.

```
java -jar ~/tools/nightcode/nightcode-1.0.1-standalone.jar
```

To open a command shell, (Windows Key + R) and then type `cmd` and enter.

This should start Nightcode.

Now follow to instructions for your track to get the Clojure project you will be working on: 

- [Track 1: turtles](setup_track1.md).
- [Track 2: Clojure koans](setup_track2.md). 



