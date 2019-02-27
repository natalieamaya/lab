#Welcome to day 1 of the Coding Academy!

Please boot your laptop using the Ubuntu installation we did on Wednesday.

##1. Install Sublime for linux https://www.sublimetext.com/docs/3/linux_repositories.html
- Install Package control: https://packagecontrol.io/installation
Install console in Sublime: https://calebgrove.com/articles/js-console-sublime-text
The console requires a Node.js install: https://github.com/nodesource/distributions/blob/master/README.md#installation-instructions

##2. Get setup with Github
- Setup git: https://help.github.com/en/articles/set-up-git

- Don't forget to set up authentication to GitHub from Git: https://help.github.com/en/articles/set-up-git#next-steps-authenticating-with-github-from-git

##3. Get access to weekly syllabus and homework
- Go home: cd ~
- Make a new directory called projects in ~ 
`mkdir projects`
`cd projects`
- Fork my github repository: https://github.com/onelovelyname/lab
- Clone your fork of my repo: `git clone https://github.com/YOUR_NAME/lab`
- Sync your fork with my repo: https://help.github.com/en/articles/fork-a-repo#step-3-configure-git-to-sync-your-fork-with-the-original-spoon-knife-repository
- Take a look at the syllabus in sublime

##4. Collaboration on Code of Conduct
- We will review the Code of Conduct together to make sure we all understand the values and goals of this course. You can make suggestions for guidelines by submitting pull requests to my repository. Each person will submit one pull request that I will merge.
### Steps:
1. Make sure that the Code of Conduct file is open in your Sublime text editor
2. Make a change to the file. You can suggest new guidelines. When we are all satisfied, add your name to the document in your text editor. Then, commit your changes: `git add` `git commit`
*Make sure to put a good commit message!*
3. Fetch any changes from my repo: https://help.github.com/en/articles/syncing-a-fork
4. Then, push your changes to your remote origin: `git push origin master`
4. Finally, submit a Pull Request to my repository. Congratulations, you've submitted your first PR!

##5. Discussion on Data Types: 6 primitives + objects/symbols
- Let's write some live code: Randomize seating in the room so that students from each school are sitting together.
- Learn data types, variable declaration, function declaration, loops
- And now, your turn to write a function

```
function randomizeSeating(names) {

	// your code here:

}
```

[optional] 5. Configure your bash profile to make use of shortcuts
- Create alias in ~/.bash_profile: `alias lab='cd ~/Desktop/projects/lab’`
- To see current path, use `pwd`  