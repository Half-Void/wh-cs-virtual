# create a new repository on the command line
echo "# wh-cs-virtual" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Half-Void/wh-cs-virtual.git
git push -u origin master

# push an existing repository from the command line
git remote add origin https://github.com/Half-Void/wh-cs-virtual.git
git push -u origin master

# User other way SSH git@github.com:Half-Void/wh-cs-virtual.git
