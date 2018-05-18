# freeinternals

## 注意
原作者最后一次更新代码大概是在两年前，我想找到原作者的联系方式询问一下他是否还有继续维护这个项目的想法。但是无法找到他的邮箱地址。
我目前打算维护这个项目，不排除会更改项目的名字，但是我会在源代码中保留原作者的信息。

**原作者github地址[Amos](https://github.com/amosshi)**

另外作者提供的可直接双击运行的jar是有问题的，当解析的class文件中包含double类型时会出现无法解析的情况，请直接使用该源码自行编译打包之后使用。

## 项目说明
该项目包含两个部分，一个是JavaClassViewer，也就是本项目的主体，查看class文件的详细信息；
另一个部分是该项目的一个部分BinaryInternalsViewer，该项目的目的仅仅以16进制的方式展示class文件。

## 改动说明

+ 原项目使用的是NetBean目录结构，目前改用Gradle+Intellij模块化的方式对各个模块进行管理

## 运行方式

将项目导入IDE

分别运行

JavaClassViewer.Main#main

或者

BinaryInternalsViewer.Main#main

