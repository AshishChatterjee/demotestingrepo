…or create a new repository on the command line

echo "# demotestingrepo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/AshishChatterjee/demotestingrepo.git
git push -u origin main


…or push an existing repository from the command line
git remote add origin https://github.com/AshishChatterjee/ashishchatterjee.in.git
git branch -M main
git push -u origin main


git config --global user.email "ashishchatterjee139@gmail.com"
git config --global user.name "AshishChatterjee"
git add .
git commit -m "Back Testing message"
git push origin main
Referal link
https://graphite.dev/guides/how-to-push-code-from-vscode-to-github


Some Other Git Commands

cd path/to/your/project
git remote add origin https://github.com/username/repository.git
git remote -v
git add .
git commit -m "Back Testing message"
git push origin main



git init
echo "# MESSAGE" >> README.md
git add README.md
all files
git add .
git commit -m "message"
git push -u origin master


Branch Creation
https://www.geeksforgeeks.org/how-to-create-a-new-branch-in-git-and-push-the-code/

git branch <Branch name> 
git checkout -b <new_branch_name>
git push <remote_name> <branch_name>
git pull origin master
