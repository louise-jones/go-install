golang环境一键安装
------

### 特性
* 支持自定义版本。   
* 支持 **Linux / MacOS / FreeBSD** 等系统。

### 注意
* 必须在 **root** 用户下执行脚本。

## 安装
###
```sh
$ curl https://raw.githubusercontent.com/louise-jones/go-install/master/install.sh | sh
```
or
```sh
$ wget -qO- https://raw.githubusercontent.com/louise-jones/go-install/master/install.sh | sh
```

### 自定义版本   
* ***MY_DIY_GO_VERSION*** 是自定义版本号, 例如： ***1.11.10***
```sh
$ curl -SL https://raw.githubusercontent.com/louise-jones/go-install/master/install.sh | sh /dev/stdin MY_DIY_GO_VERSION
```
or
```sh
$ wget -qO- https://raw.githubusercontent.com/louise-jones/go-install/master/install.sh | sh /dev/stdin MY_DIY_GO_VERSION
```

### 离线执行
保存脚本并且命名为 **install.sh** 。   
执行脚本安装最新版 Go 语言。
```sh
$ sh install.sh

# 自定义版本   
$ sh install.sh 1.11.10   
```
  
如果你给脚本可执行权限，那么同时可以自定义 Go 语言版本。  
```sh
# 添加可执行权限
$ chmod +x install.sh   

# 最新版
$ ./install.sh

# 自定义版本
$ ./install.sh 1.11.10
```

### 作者
Author: minigeek   
Email : louise.jones.minigeek@gmail.com   
Link  : https://minigeek.blog.csdn.net/