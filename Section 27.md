What is version control?
When we create checkpoints to our file so that we can retrieve back
---

    git init //to initialise git

    ls -a //to see hidden files

    git status //to see staging area red shows that we are still not in staging area

    git add filename //this will add our file to staging area and if we check git status it will show green color

    git commit -m "any message" //this will commit our file as version control

    git log //to show all commits

    git add . //to add everything to staging area

    git diff filename //to check differnce b/w current and old file red are deleted and green are added

    git checkout filename //to revert back to previous version


---

Till now we done is from working: directory -> staging area -> local repository
now we are creating a remote repository on github

    git remote add origin repoaddress //connect local with remote repository
