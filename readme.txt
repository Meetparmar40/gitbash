commands:-
open file : - code <file_name>
add to status : - git add <file_name>
add all the files in folder to status : - git add .
commit the file : - git commit -m "text you want to write"
check which files are in status : - git status
check log of the git (commited files) : - git log
to check the changes made in file : - git diff <file_name>
to roll back to the previous save point : - git checkout <file_ywname>

Remove file from staging area: 
git rm --cached -r <file_name / . (dot)>
--cached : - tells to remove only from staging area and not from local directory
-r : (recursive) used to remove directory or sturecture of directories inside each other


How to push files in repositories?
git remote add <name> address of repo
    ex :- git remote add origin https://github.com/Meetparmar40/gitbash.git
    name is prefered as origin
git remote add origin https://github.com/Meetparmar40/gitbash.git

gitignore:-

    there are some files which we dont want to be publically available for 
    security or other reasons
    for that we use gitignore files
    + Make a gitignore file, and open it    