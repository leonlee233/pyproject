## git的学习日记

git版本控制
git只关心文件数据的整体是否发生变化
其他的文件系统关心具体文件内的差异
git的所有文件都只包含三种状态

已提交：committed：
这个文件已经被安全的提交到本地的数据库中

已修改：modified：
这个文件被改动了，但是还未保存到本地数据库内

已暂存：staged
已经把文件保存在了下次提交需要保存的清单中





git的版本查看
```bash
git --version
```

git的帮助文档
```bash
git --help
```

使用git config更改你自己的用户名和电子邮件地址
```bash
git config --global user.name "leonlee233" 
```
```bash
git config --global user.email leonlee233@qq.com
```
设置好上述的两个字段之后可以通过如下命令来测试
```bash
git config --get
```


可以初始化现在的项目
```bash
git init
```
当初始化完成了之后当前目录下会出现.git的目录
并且将git所需的数据和资源全都存放在这个仓库中

```bash
git add .
```

```bash
git commit -m "msg"
```

```bash

```
```bash

```
```bash

```
```bash

```