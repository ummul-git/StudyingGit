# StudyingGit
Personal purpose
Just to make sure my git is working fine as expected!!!

Basics
******
If you are new to git then u need to setup a account 
If u need to clone the code with SSH then first we need to generate a key 
ssh-keygen

In the local folder u will find the rs_** file and open with notepad and 
copy the SSH Key then go to git and create a new SSHKey and paste it 

After this we need to initialize git 
       git init

To know whether modifications are made in file 
       git status 

To stage the changes from working to staging directory 
       git add .

Commit the changes
       git commit -m"commit message"

Git push on the first time will not work so wew need too give this below command
       git push --set-upstream StudyingGit master
For the second time 
       git push 
         



