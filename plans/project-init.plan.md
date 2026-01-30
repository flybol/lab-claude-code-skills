

初始化仓库
```shell
echo "# claude-code-skills-lib" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin ${REPOSITORY_URL}
git push -u origin master
```