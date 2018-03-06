## Task 1 - install node.js in your local machine
🎯 After completing this issue you should upload an image in the terminal or command line with the version of node.js



### Installation steps for Ubuntu

1. Open the Terminal app and type `sudo apt-get update`
2. Open the Terminal app and type `sudo apt-get install nodejs`
3. to install package manager for node `sudo apt-get install npm`
4. To check the installation happen correctly , Run `nodejs -v` on a terminal

wooh! you have completed the Issue #1. Please check the **commit the screenshot** section now.

<hr>

### Installation steps for Mac
Homebrew handles downloading, unpacking and installing Node and NPM on your system. The whole process (after you have XCode and Homebrew installed) should only take you a few minutes.

1. Open the Terminal app and type `brew install node`.
2. To see if Node is installed, type `node -v` in Terminal. This should print the version number (ex. v0.10.31)
3. To see if NPM is installed, type `npm -v` in Terminal. This should print the version number (ex. 4.27) 

wooh! You have completed the Issue #1. Please check the **commit the screenshot** section now.

<hr>

### Installation steps for Windows

1. Download the Windows installer from the Nodes.js® web site.
2. Run the installer (the .msi file you downloaded in the previous step.)
3. Follow the prompts in the installer (Accept the license agreement, click the NEXT button a bunch of times and accept the default installation settings).
4. Restart your computer. You won’t be able to run Node.js® until you restart your computer.
5. Test Node. open the Windows Command Prompt, Powershell and type `node -v`. This should print a version number. (ex: v0.10.35)
6. Test NPM. To see if NPM is installed, type `npm -v` in Terminal. This should print NPM’s version number (ex: 1.4.28)

wooh! You have completed the Issue #1. Please check the **commit the screenshot** section now.

<hr>

### If your OS is not even one of these.

please check this [document](https://nodejs.org/en/download/package-manager/) 

If you were able to complete the issue, please check the **Submit your results** section now.


<hr>


## Submit your results
* Once you done with the issue, run `node -v` command in terminal & get a screenshot with the version number.
* Now you have to upload it to thus repository.
* Don’t worry I will teach you, how to push into GiHub.

Easy steps

* Save the screenshot to the root directory you cloned
* open git BASH in windows or terminal in linux/mac in the cloned root directory.
* Set the your email for git (only for one time) `git config --global user.email "yourEmail@example.com"`
* Enter these commands
  * `git add --all`
  * `git commit -m "issue 1 completed"`
  * `git push -u origin master`

Now create a pull request mention `@omalperera` to review your code & merge your request.
[How to create a pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/)