# Attack Modifier Basics

## [原项目地址](https://github.com/NotThorny/AttackModifier/tree/master)

## 安装`MavenMaven`
[点击查看MavenMaven安装方法](https://blog.csdn.net/qq_38190185/article/details/115921070),配置环境变量之后，即可以使用以下方法进行编译，自动安装失败的可以使用手动安装(本人就是没法使用自动安装。)

##  安装依赖（任选其一）

### 自动安装

* 编译`mvn clean compile`
* 打包`mvn clean package`
* 如果不出意外，你可以在`\target`找到jar文件了。

### * 手动安装
* [点击下载“grasscutter-1.3.1.jar”](https://github.com/Grasscutters/Grasscutter/releases/download/v1.3.1/grasscutter-1.3.1.jar)

* 下载完成后把`grasscutter-1.3.1.jar`复制成三份。

* 分别重命名：
* `grasscutter-1.3.1.jar`

* `grasscutter-1.3.1-javadoc.jar`

* `grasscutter-1.3.1-sources.jar`

* 把这三个文件复制到`C:\Users\ZhiYu\.m2\repository\xyz\grasscutters\grasscutter\1.3.1\`文件夹下

* 然后根目录执行`mvn package`，你可以在`\target`找到jar文件了。

#### * 此项目只是增加了更多角色的魔改，无其他任何更改，有其他需求，请自行前往官方项目查看。