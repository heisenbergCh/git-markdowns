从本地向Gitlab上传文件

> 前提：
>
> 1.确保需要上传的文件夹内没有以前设置的Git，删除原有的.git文件夹

一、克隆远程库到本地

`git clone git clone git@10.14.4.180:ProjectCapabilityAssessment/jinfazhou.git`

`git@10.14.4.180:ProjectCapabilityAssessment/jinfazhou.git`是自己的远程库地址

二、将需要上传的项目文件夹拖入克隆的文件夹下，与`.git`文件夹相同路径

三、在终端或Git Bash中进入克隆文件夹下（一般是自己的名字），执行：

```git
git add .
git commit -m "initial commit"
git git push 别名（可以用网址代替） 分支名（一般为master）
```

四、完成

