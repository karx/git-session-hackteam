## Notes for Ankit about Session 1

* Step 1: Make a repo on Github
* Step 2: Come inside the folder where all the files to be pushed are available
Step 3: Come inside that folder through command prompt
Step 4: Run Git command: git init
* After running the above command, Git will start tracking your currently focused folder
Step 5: Go to your Github and copy the URL of your repo where you want to push your files
Step 6: Come back to command prompt and run the Git command: git remote add origin [URL]
Step 7: Now do changes or create a new file in your folder
Step 8: After making changes, run: git add .
* The above command "git add ." will bring all the files in the staging area present in that folder
* If you want any specific file to add not all the files then run:
* git add [fileName along with extention]
* Step 9: Now run the commit command to make the file ready for pushing on Github
* git commit -m "committing message"
* Step 10: Finally for pushing, git push -u origin master [URL]
* You have to mention the URL for the first time only for a specific repo and folder. Next time onword only run:
* git push