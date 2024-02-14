Part 1. GIT/GITHUB/VSCODE
GIT:
- download GIT FROM https://git-scm.com/download/mac
- to check if it was installed type git--version in the terminal
- to create a branch type the command checkout -b branch name
 - -b creates and opens the new branch, if you don't wish to jump to the new branch, remove the -b
- In order to create a file, you can choose vi, vim or nano to be the editor 
- once you are done editing the file, type the command git add . which will add all the files that you recently worked on in the folder and will arrange them in heirarchy
- once you are done with that, commit the file to save all changes with the command, git commit -m "a message for the commot" p.s. you need to have a message when committing
- once that is done, you can push the new changes to your remote repository with the command. git push origin main. Instead of main you can write the name of your target branch 
- in order to make sure that the changes are saved on your remote directory, go to github and create a pull request
- once you merge your changes to the branch of your choice, go back to your terminal and type the command git pull origin main, this will sync the local and remote repositories. 

GITHUB:
- create an account on www.github.com 
- In order to create a new repository, click on the + at top-right corner of the screen
- give it a name, select public / private and choose to add a readme.md file
- click on create repository
- to add files, you can click add and choose to create a file or upload a file
- to upload a file, you have to select the file that you want to upload when the pop-up appears and click upload
- if you create a new file, you can name it and write whatever you want and save it by committing it to the main or any other branch of your choice
- If you work with the terminal and commit the changes to github, open the repository
- click on pull requests and compare and pull the chnages or click on new pull request and commit the changes to the main branch 

VSCODE:
- download VS code from https://code.visualstudio.com
- open the app and click on either open which will allow you to open any repository or files that are saved in your device or click on new file to open new file
- you can install extensions to help you work better. To install extensions, you should click on the tetris box type of icon on the left side of the screen, it will open up a little tab where you can search for extensions that you could install. I reccommend Wakatime, it sends you weekly report of the time you spent on VS CODE. Some things in report are time, projects, languages, etc. 
- to use the terminal within the app, in the menu click on terminal and then click on new which will open up a new terminal for you. 
- to run the code, go to the menu and click on Run. 

Part 2. Definition
- Branch - a moveable pointer to one of the 
- Clone - is used to make a copy of an existing repository at a new location
- Commit - capture the state of the file at that point in time
- Fetch - downloads commits or files from a remote repository to a local repository
- GIT - a program/protocol that we use to track file changes
- Github - hosts a remote repository
- Merge - combine multiple commits into one branch
- Merge Conflict - happens when git can not automatically resolve difference between two commits
- Push - uploads local repository content to remote repository
- Pull - gets and downloads content from remote repository and syncs the local repository with remote repository
- Remote - common repository that is used to store data which can act as a backup in case something goes wrong with the files in local repository
- Repository - a place where you can store you files and folders. 


Resources :
www.github.com
past lectures of IT114
google for defintions
