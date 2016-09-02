# BC Rest 平台

## 检出并编译源代码的步骤
1. 按 [bc-framework/README.md](https://github.com/bcsoft/bc-framework/blob/master/README.md) 的说明检出并编译安装 [BC 平台](https://github.com/bcsoft/bc-framework)

2. 检出 BC Rest 平台源码并编译安装
```
$ git clone https://github.com/bcsoft/bc-rest.git
$ cd bc-rest
$ git submodule init
$ git submodule update
$ cd bom
$ mvn install
$ cd ..
$ mvn install -
$ mvn installN
```