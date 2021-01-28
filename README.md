# MetGroupProject
For our Group project in Research Training
# Getting started with Github
1. Create an account on Github
2. Clone the repository
  - Open a new terminal
  - <code>git clone https://github.com/s1853851/MetGroupProject.git <\code>
  - it will ask you for your username and password for Github
  - after that you should have a folder in your home directory called "MetGroupProject"
  - go into the directory using <code>cd MetGroupProject<\code>
  - if you run <code>git status<\code>, it should say you're on the main branch
# When you want to work on the files in the repo
1. Go into the directory using <code>cd MetGroupProject<\code>
2. Fetch any updates to the files in the repo to your local environment using <code> git pull<\code>
3. Switch to a new branch using <code>git checkout -b NewBranchName<\code> 
  - include your name in the branch name so we can keep track which branch belongs to whom
  - you can switch between existing branches using <code>git checkout BranchName<\code>
  - you can go back to the main branch using <code>git checkout -m<\code>
4. Use <code>git push --set-upstream origin NewBranchName<\code> to make sure that the Github repo knows there's a new branch to track
5. You can check if your branch is up-to-date with your local copy using <code>git status<\code>
  - this shows you if you have any new, modified or deleted files in your local copy that you haven't committed and uploaded to Github yet
6. If other people are working on your branch (which shouldn't happen often), use <code>git pull<\code>

