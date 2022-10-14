# Attack Modifier Basics

## 编译方法

##  安装依赖
* 手动安装
* [grasscutter-1.3.1.jar](https://github.com/Grasscutters/Grasscutter/releases/download/v1.3.1/grasscutter-1.3.1.jar)

* 下载完成后把`grasscutter-1.3.1.jar`复制成三份。

* 分别重命名：
* `grasscutter-1.3.1.jar`

* `grasscutter-1.3.1-javadoc.jar`

* `grasscutter-1.3.1-sources.jar`

* 把这三个文件复制到`C:\Users\ZhiYu\.m2\repository\xyz\grasscutters\grasscutter\1.3.1\`文件夹下

* 然后根目录执行`mvn package`，你可以在`\target`找到jar文件了。

## 自动安装依赖

* 编译`mvn clean compile`
* 打包`mvn clean package`

* [原项目地址](https://github.com/NotThorny/AttackModifier/tree/master)