# Mad9013 Week5 - Content Module

---
## Topics:
* Background-images
* CSS colours
* text shadow
* Media queries
* Pseudo-elements
* Pseudo-classes
* CSS variables
* CSS Specificity

---
## Useful videos:
* [pseudo-elements vs pseudo-classes video](https://www.youtube.com/watch?v=0VDx1570X3U)
* [pseudo-elements after and before video](https://www.youtube.com/watch?v=9chejj2-x8s)
* [@supports video](https://www.youtube.com/watch?v=p9fyYspw1YI)
* [Media queries](https://www.youtube.com/watch?v=RuYG3RjjhaU&list=PLyuRouwmQCjl4wTSNbb8RTKZuyMhoIxBe&index=58)
* [:not video](https://www.youtube.com/watch?v=u9SmKI7BXl4)
* [CSS variables video](https://www.youtube.com/watch?v=xeMMAx7hWYQ)
* [The C in CSS stands for Cascade](https://www.youtube.com/embed/PigxOyVDIQg)
* [specificity](https://www.youtube.com/embed/Kz_S4Nk4qyI)

---
[Git Command Cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf) 
---


---
## Git Workflow - basic workflow
1. Set up your repository. Here are some instructions: [Setting up a Github Repository](https://jackgarrard.github.io/mad9013/assignments/github-setup.html)
2. Create some code
3. Open your terminal (CMD, Git Bash) in your repository (e.g. C:\Users\Jack\Documents\code\week5)
4. Use the command `git status` to look for any changes in your repo
5. use `git add -A` to stage all changes 
6. Use `git commit -m"`_your message here_`"` to commit your changes
7. use `git push -u origin master` to push your changes to your online repo

## Git Workflow - creating a new branch locally and pushing it to origin
1. Create a new branch called 'gh-pages' with this command: `git checkout -b gh-pages`
2. Push this new branch to origin with: `git push origin gh-pages`

## Git Workflow - creating a new branch onliine and fetching it locally
1. Go to your repo on Github.com and create a new branch called 'gh-pages'
2. Open your terminal (CMD, Git Bash) in your repository (e.g. C:\Users\Jack\Documents\code\week5)
3. Run this command to fetch the new branch from origin `git fetch`
4. Run this command to view all branches (local and remote) `git branch -a`
5. Switch to the new branch with this command `git checkout gh-pages`

## Git workflow - merging changes between two branches
1. To view all branches available locally use this command: `git branch`
...The branch with an asterisks (`*`) next to it indicates the branch you are currently on
2. Switch from 'master' branch to 'gh-pages' branch with this command: `git checkout gh-pages`
3. Update the 'gh-pages' branch with content from 'master' with this command: `git merge master`
4. Push changes to gh-pages origin: `git push -u origin gh-pages`
5. Switch back to 'master' branch: `git checkout master`
