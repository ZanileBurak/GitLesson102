# Ctrl+Future Training: Github Fundamentals  
## Training to introduce the cohorts on how to push from a local envoriment to Github.  
## Cannon Linux Commands  
- Create a directory: **mkdir** name of the directory.  
- Change directory: **cd** name of the directory . This command helps you to move from one directory to another.  
- To create a file: **touch** name of the file. This command helps you to create a file within the directory.  
- To list the contents of the file: **ls**  
- To remove a file: **rm** file name  
- To remove a empty directory: **rmdir** name of the directory  
## Download Gitbash  
- https://git-scm.com/downloads  
## Configure Gitbash  
- **git config --global user.name "your name"**  
- **git config --global email.name "your email"**  
## Prepare your working environment  
- **mkdir website**  
- **cd website**  
- **git init**  
- **touch index.html**  
- **vim index.htm** (to add a comment to the html file)  
## Clone your repository  
- **git remote add origin (your repo url https format)**  
## Push from your local environment to Github  
- **git status** - This helps to check to files on the staging area.  
- **git add index.html** -This adds your files to the staging area.
- **git commit -m "Commit Message" - Commit command helps you take a snapshot of what you do at the moment of time**
- **git push origin main**
  
