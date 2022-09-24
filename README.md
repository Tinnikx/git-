# git提交本地代码到空仓库步骤
## 1. 在GitHub中新建一个空仓库, 并保存此仓库在github中的clone地址, 例: git@github.com:Tinnikx/springboot-demo.git
## 2. 在本地代码文件夹中使用git可视化工具
### 1. git init
### 2. git commit -m "first commit"
### 3. git remote add origin git@github.com:Tinnikx/springboot-demo.git
### 4. git pull
### 5. git rebase origin/master master
### 6. git push -u origin master
