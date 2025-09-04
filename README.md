This is my very first repo created by myself, I think.
It's about hands on practice of
-Creating new repo on github
-Create ssh key(also set passphrase )
    #ssh-keygen
    #ssh-keygen -t ed25519
    #ls ~/.ssh
    #cat ~/.ssh/id_ed25519.pub
    -set ssh key on github account
    https://github.com/settings/keys
-Clone repo to local machine
    #git clone git@github.com:randomcodebys/first-repo-for-practice.git 
-Configure git with user name and email
    #git config --global user.name "myname"
    #git config --global user.email "myemailaddress" 
-Create a new branch named feature/new-feature from the main branch. 
    -In this step, I had some issue.My terminal showed current branch of repo, since I cloned the repo, it shows main, so I thought I was on main branch ,and I created new branch like this.
-Create txt file in that branch
    #touch feature.txt
    -write some text
    #vi feature.txt
-Commit to local repo
    #git status
    #git add feature.txt 
    #git commit -m"create text file and 1st commit"
-Push to remote repo
    #git push -u origin feature/new-feature
-Create PR to review and merge
    -At that time I realized that I don't have main branch yet on remote repo,I created new branch ,main and then made some changes in txt file and push again.This time its ok to create pull request.
    I reviewed by myself and merged to main branch.

-Collaboration with classmate
    -I asked my classmate to create new file and create PR.
    -I shared my git repo
    https://github.com/randomcodebys/first-repo-for-practice
    -And I review PR and merge to main branch.

-Create README.md file on main branch
