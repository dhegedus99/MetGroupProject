# MetGroupProject
For our Group project in Research Training

**Use the TopographyNotebook and WindNotebook for collaborative code - I combined all previous code from the other notebooks**

**NOTE: If you have been working in a separate notebook to write your code, before you copy everything into the TopographyNotebook and WindNotebook, use <code>git rebase origin/main</code> to update the version you see on your branch to avoid merge conflicts.** (You do this while being on your own branch)

If you have any questions, issues or git gives you any errors let me know and I can probably help, but this is all I could remember off the top of my head.
# Getting started with Github
1. Create an account on Github
2. Clone the repository
  - Open a new terminal
  - <code>git clone https://github.com/s1853851/MetGroupProject.git </code>
  - it will ask you for your username and password for Github
  - after that you should have a folder in your home directory called "MetGroupProject"
  - go into the directory using <code>cd MetGroupProject</code>
  - if you run <code>git status</code>, it should say you're on the main branch
# When you want to work on the files in the repo
1. Go into the directory using <code>cd MetGroupProject</code>
2. Fetch any updates to the files in the repo to your local environment using <code> git pull</code>
3. Switch to a new branch using <code>git checkout -b NewBranchName</code> 
  - include your name in the branch name so we can keep track which branch belongs to whom
  - you can switch between existing branches using <code>git checkout BranchName</code>
  - you can go back to the main branch using <code>git checkout main</code>
4. Use <code>git push --set-upstream origin NewBranchName</code> to make sure that the Github repo knows there's a new branch to track
  - you can use this after you have made al of your edits to the files, then it will also give you a link to create a pull request on Github (see next heading)
5. You can check if your branch is up-to-date with your local copy using <code>git status</code>
  - this shows you if you have any new, modified or deleted files in your local copy that you haven't committed and uploaded to Github yet
6. If other people are working on your branch (which shouldn't happen often), use <code>git pull</code> before starting any new work
7. You can freely work on the notebooks you want, add or delete files
8. When you're done with your work, do <code>git status</code> in the terminal (after <code>cd MetGroupProject</code>)
  - this shows you all the changes you have made to the files in the repo (lists the filenames you have modified, added or deleted)
9. Add all the files you want using <code>git add filename</code>
  - if you do <code>git status</code> now, the file should be listed under "Changes to be committed"
10. Commit the files using <code>git commit -m "Message about the file" </code>
  - the message should be short but descriptive of the changes you have made to the file
  - if you do <code>git status</code> now, it should say "Your branch is ahead of 'origin/Branchname' by 1 commit"
11. Push the changes to the Github repo to updatethe files on there using <code>git push</code>
  - if you do <code>git status</code> now, it should say "Your branch is up to date with 'origin/Branchname'."

# When you are finished with the task and want to merge the branch you have with the master branch
1. Create a pull requestfor your branch on github so others can review it and merge it accordingly
  - make sure you have pushed everything to your branch with <code>git push</code> and created an upstream for your branch
  - alternatively you can go to the Github repo, and create a pull request for your branch under the branches tab
Or (try to use Pull requests, but this is an alternative):
1. Assuming you are in your branch, use <code>git checkout main</code> to switch to the main branch
2. Update the main branch in case any changes have been made there using <code>git pull origin main</code>
3. Merge your branch using <code>git merge Branchname</code>
  - in Noteable, a weird new page comes up, type in a commit message then using F10, save and exit
4. <code>git push origin main</code> to update the main repo
