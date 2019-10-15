## 开始前的准备
+ 一台Linux服务器或者VPS（远程需求），作者用的是CentOS 7。
+ 一台写代码的设备（Windows或者Mac），作者使用Windows 10（1803）。
+ 一颗学习的💗
  
## step.1 在服务器上安装数据库
这一点的话，请自行百度，教程很多，就不赘述了。


## step.2 在工作机上安装Visual Studio Code(VSC) 以及.Net Core SDK
同样这一步也请百度。简单的很。

## step.3 使用VSC创建项目
首先先对项目有个初步的规划，本次教程使用分层架构，方便读者理清脉络。第一次使用分层架构的也别担心。

`
model(数据模型-类库)
entity(数据库操作-类库)
netnote(项目)
`
首先先通过终端来生成项目以及类库

```
Add-Migration Init//初始化
```

