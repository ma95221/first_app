2020-01-15
创建develop分支，切换到develop分支，然后push到远端仓库中，远端仓库里就有了develop分支。
git branch develop
git checkout develop // 切换当前分支为develop
     
git merge master // 把master分支的代码合并到当前分支（develop）

git push origin master:develop   // GitHub上并没有develop分支，执行这句命令后会自动创建一个GitHub develop分支