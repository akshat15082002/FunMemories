# MACS DTU Website

<img alt="MACS-logo" src="./assets/logos/MACS-logo.jpg">

# Guidlines before editing into this repo

1. Clone this repo
2. git clone "https://github.com/MACS-DTU/macsweb.git"
3. Create a branch\
    Change to the repository directory on your computer (if you are not already there):\
    Now create a branch using the git switch command:\
    `git switch -c your-new-branch-name`
4. Make necessary changes and add those changes\
    `git add --a`\
    Now commit those changes using the git commit command:\
    `git commit -m "message you wanna give"`
5. Push changes to GitHub\
    Push your changes using the command git push:\
    `git push -u origin your-branch-name`
6. Submit your changes for review\
    If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.\
    Now submit the pull request.

### Doubt : 

I have made a new branch. I have done some changes in it . now I saw that someone has done changes in the main branch. now what should i do so that none of the data gets lost. 

### Ans: 

1. First ensure that you are in your branch
2. git fetch
3. git merge origin/main
4. git add --a
5. git commit -m "your-message"
6. git push origin your-branch