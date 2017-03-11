# Getting the Track 2 project: Clojure koans. 

## Cloning the koans project from a git repository

Git is a neat tool that is sort of like dropbox for code. It allows many people to collaborate on projects and make their code open to the rest of the world! We have prepared some code for that will run the lessons you will be using. The process of getting this code is called *cloning* and Nightcode has some nice tools that makes that process super easy! You will need to open NightCode and follow these instructions. 


 1. Go to Start menu, select "Clone from Git": ![Clone from Git menu](img/git.png). 
2. It will open a window asking for `git address`. Copy this address `https://github.com/clojurebridge-minneapolis/clojure-koans.git` and press `enter`.
3. You will be asked to select a folder location for your project. You can use an existing folder or create a new one. 
4. You will see a message "Cloning". Once the project is cloned, it will open in the left navigation bar of Nightcode. You can click on arrows to open folders and double-click files to open them in Nightcode. 

That should be it!

## Verifying that your project works

To run the Koans, do the following

 1. In the Nightcode project files panel on the left, select the file *src/koans/01_equalities.clj*. This will open the file in the editing panel.
 2. Click `Run with REPL`
 3. Click `Reload`, You will see an assertion failure like the one below

 ```
 ExceptionInfo We shall contemplate truth by testing reality, via equality
 (= __ true)  clojure.core/ex-info (core.clj:4327)
 ```
 
 4. Modify the code in the file as below and click `Save`, then click `Reload`
 
 ```
 "We shall contemplate truth by testing reality, via equality"
 (= true true)
 ```
 
 You will now see that this assertion passed successfully, and you get a failure on the next assertion.

If this works -- congratulations, you are ready for Saturday coding! If you are running into any issues or have questions, please ask a mentor (in person, on slack, or by email, depending on where you are working on the installation). 

