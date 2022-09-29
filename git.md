## Git常用命令

- 设置Git名称和邮箱
```javascript
git config --global user.name "name"
git config --global user.email "email"
```
- 初始化Git仓库或者克隆仓库。克隆长裤会在当前文件夹下创建新的文件夹，里面包含.git,而git init会在当前文件夹下面创建.git仓库。

```javascript
git init
git clone https://github.com/some_respository/
```

- 添加文件进入仓库,可以在仓库的根目录下添加.gitignored文件，里面标注忽略管理的文件或者文件夹。

``` c
git add . # add all files to the repository
git add directory # add directory to repository
git add file # add file to repository
```
- 查看更改前后的区别,尽量每一次提交前都运行git diff HEAD 命令查看差别。

```c
git diff # all the files difference
git diff directory # the files in this directory
git diff HEAD # the difference in the working tree
```
