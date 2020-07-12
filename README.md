## How-to-Push-Any-Project-to-GitHub
How-to-Push-Any-Project-to-GitHub

# Goto --->  https://github.com/session

Enter Username & Password

Username: kgsharathkumar

Password: XXXXXXXX

If asked Verification code, Please check your mail and Enter the Verification code. 

Once Login Sucessfully!

# Step 1: Create A repositary by click new button 
  
Add following details -

  1. Repository Name
  
  2. Description
  
  3. Choose public/ private option, If you choose public-Visible to everyone.
  
  4. Add Initialize this repository with a README
  
  5. Add .gitignore (It's depends on your projects belongs to Java, android, python, ada, c, c++, c#...etc)
  
  6. Add Lincense
  
  Finally Click on Create Repositary Button.
  
# Step 2: Open GitBash command prompt

If you not installed GitBash download from mentioned link - https://git-scm.com/downloads

# Step 3: Execute Git commands in Gitbash cmd prompt

 Goto inside location of the project folder
 
 For Example If Your project is located in D drive, Then choose below commend
 
 cd <SPACE>d:
 
 cd <SPACE> Path-Of-Project
  
 Use below commands in gitBash
 

Use below commands in gitBash
# …or create a new repository on the command line

echo "# PushKitKotlin" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/kgsharathkumar/How-to-Push-Any-Project-to-GitHub.git

git push -u origin master
                
# …or push an existing repository from the command line

git remote add origin https://github.com/kgsharathkumar/How-to-Push-Any-Project-to-GitHub.git

git push -u origin master

git add .

git commit -m "First commit"

git push origin master 


or use below command if you found any error like ##### rejected master -> master (non-fast-forward)

git push --force https://github.com/kgsharathkumar/How-to-Push-Any-Project-to-GitHub.git


  
 
  

