**github cheat sheet**
 
when you make a new repo on github.com you need to add the remote repo to your local folder
 
open git bash
 
navigate to where you want your project (cd Desktop/projects)
 
make a new folder for new project ('mkdir' will create a new folder, 'touch' will create a new file)
 
mkdir new-project
 
cd new-project
 
git init (this will initialize empty git repo on your computer, so it can keep track of any changes)
 
git branch -M main (here we are just changing the name of our branch from master to main, it is the more updated way)
 
git remote add origin https://github.com/username/repo-name.git (adds the remote repo to your local folder, you can copy and paste this line from github.com after you create a new repo)
    
 
-----------
 
When you are ready to send your work to the world...
 
(make sure your files are saved)
 
 
git add . (this adds everything in the current directory and below, to the staging area)
 
git commit -m "your commit message. for codewars I put the name and level of kata. for projects i will put what i changed for example - added css" 
 
git push --set--upstream origin main
 
 
-- for existing repos, that have already been initialized..
 
after you save your files go to gitBash and navigate to the folder of your project. (or right click the folder on your desktop or file explorer and click 'Git Bash Here')
 
git add .

git commit -m "message here"

git push
 
 
https://ohshitgit.com/ - this site will help if you run into any issues

some helpful keyboard shortcuts.

just to be clear the plus sign just means and. 

alt + z - word wrap (makes all the text fit inside your screen)

control + a - highlights all text

control + / - will turn highlighted text into a comment. if not highlighted it will comment the current line.

alt + tab - shift between applications 

alt + shift + tab - same as above but backwards

in git bash: 

control + insert - copy (insert is usually above backspace and my keyboard makes me hit another key, fn to get to insert)

shift + insert - paste 
