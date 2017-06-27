cd ~/desktop #Navigate to my desktop
mkdir GPS 1.1 #Create a folder called GPS 1.1
cd GPS 1.1 #Navigate to new folder
git clone https://github.com/cpcamp2/phase-0-gps-1.git #Clone repository from GitHub
ls 
#List directory contents
cd phase-0-gps-1
#Navigate into repository
touch awesome_page.md
#Create new file awesome_page.md
ls
#List directory contents
git add awesome_page.md
#Stage awesome_page.md
git commit -m "Initial Commit"
#Create a save point in branch
git push origin master
#Push branch to master in GitHub repository
git checkout -b add-command-log
#Create a new branch
subl readme.md
#Content in document