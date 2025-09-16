git version
git config --global user.name"your name"
git config --global user.name"your email"
git config --list
mkdir vsc-demo
cd vcs-demo
echo"Hello,version control">file1.txt
git init
git status
git add file1.txt
git commit -m"first commit - added file1.txt"
echo "Adding second line to file1">>file1.txt
git status
git diff
git add file1.txt
git comit -m"update file1 with second line"
git log --oneline
git branch new-feature
git checkout new-feature
echo"Feature branch update" >> feature.txt
git add feature.txt
git commit -m "Added feature.txt in new feature branch"
git checout master
git merge new-feature# demo
