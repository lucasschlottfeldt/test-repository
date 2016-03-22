echo "# test-repository" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/lucasschlottfeldt/test-repository.git
git push -u origin master
