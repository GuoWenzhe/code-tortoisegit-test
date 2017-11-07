#...or create a new repository on the command line

echo "# code-tortoisegit-test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/GuoWenzhe/code-tortoisegit-test.git
git push -u origin master

#...or push an existing repository from the command line

git remote add origin https://github.com/GuoWenzhe/code-tortoisegit-test.git
git push -u origin master
