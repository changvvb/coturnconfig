## 这个是coturn的相关配置

### 1.安装coturn
参考 https://github.com/coturn/coturn
```bash
$ git clone https://github.com/coturn/coturn.git
$ cd coturn
$ ./configure
$ make
$ sudo make install
```
### 2.下载与部署
```bash
$ git clone git@github.com:changvvb/coturnconfig.git
$ cd coturnconfig
```
### 3.配置IP地址
打开 turnserver_start 更改IP地址

### 4.部署相关配置配置文件
```bash
	$ sudo ./deploy
```

### 5.启动服务
```bash
$ ./turnserver_start
```
