# begingit
learn hot to use git and github

I use git bash on windows  
First, go to the folder you want to start using git
type "git bash" on the address bar ,then git bash will start from that folder
or you can start git bash and then use the cd code
but I use another way because my folder path is not easy to type manually

git status
git init
git remote add origin https://github.com/sirapat-tm/begingit.git
git remote -v
git commit -m "start using git"

try to add some file
git add data.csv
git status
git commit -m "add file"
git push origin master

done now you local file is on github
you might need to setup you github account first

git config --global user.name "your_name"
git config --global user.email "your@email.com"

sourse
https://www.androidthai.in.th/git-and-github-article/191-github-on-vs-code.html
https://www.memo8.com/git-basic-command/
