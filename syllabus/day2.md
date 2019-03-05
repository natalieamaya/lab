## 0. [15 minutes] Coding Challenge of the Day
- Work on your own to write a function that randomizes this list: ['falafel', 'shwarma', 'maqlouba', 'hubezi', 'lentils'];

## 1. [45 minutes] Problem-solving methodology lecture
- 30 minutes discussing problem-solving as a discipline
- 10 minutes with Mahd

## 2. [15 minutes] Get setup with Git
- Setup git: https://help.github.com/en/articles/set-up-git
`sudo apt install git` You'll have to enter your linux password and hit `y` once or twice.

## 3. [30 minutes] Get access to weekly syllabus and homework
- Go home: `cd ~`
- Make a new directory called projects in ~ 
`mkdir projects`
`cd projects`
- Fork my github repository: https://github.com/onelovelyname/lab (https://help.github.com/en/articles/fork-a-repo)
- Clone your fork of my repo: `git clone https://github.com/YOUR_NAME/lab`
- Add remote upstream (my repo) for your fork: `git remote add upstream https://github.com/onelovelyname/lab`
	* See https://help.github.com/en/articles/configuring-a-remote-for-a-fork
- Take a look at the syllabus in sublime

## BREAK (10 minutes)

## 4. [1 hour] Collaboration on Code of Conduct
- We will review the Code of Conduct together to make sure we all understand the values and goals of this course. You can make suggestions for guidelines by submitting pull requests to my repository. Each person will submit one pull request that I will merge.
### Steps:
0. Sync your fork with my repo: https://help.github.com/en/articles/syncing-a-fork 
	* `git fetch upstream` 
	* `git checkout master` 
	* `git merge upstream/master`
1. Make sure that the Code of Conduct file is open in your Sublime text editor
2. Make a change to the file. You can suggest new guidelines. When we are all satisfied, add your name to the document in your text editor. Then, commit your changes: `git add` `git commit`
*Make sure to put a good commit message!*
3. Fetch any changes from my repo: https://help.github.com/en/articles/syncing-a-fork
4. Then, push your changes to your remote origin: `git push origin master`
5. Finally, submit a Pull Request to my repository. Congratulations, you've submitted your first PR!

## BREAK FOR MOVEMENT (5 minutes)

## 5. [1 hour] Review functions
- randomizeSeating function 
- Functions worksheet from homework: each group will present their function