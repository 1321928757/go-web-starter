# go-web-starter

`go-web-starter` 是一个基于form 和 `gin` 框架的脚手架，方便用户快速的编写curd操作。



## 目录结构

```
project
├───app
│   ├───common
│   │   ├───request
│   │   └───response
│   ├───controller
│   ├───dao
│   ├───middleware
│   └───service
├───bootstrap
├───config
│   └───fileDriver
├───docs
├───global
├───model
├───routes
├───static
├───storage
│   ├───app
│   │   └───public
│   │       └───local
│   │           └───test
│   └───logs
├───test
└───utils
    └───storage
        ├───cos
        ├───kodo
        ├───local
        └───oss
```

## 实现的功能

• 自定义参数校验规则与校验失败响应  

• Gin路由服务初始化，优雅关闭  

• viper配置统一管理  

• Jwt令牌生成，校验，续签，黑名单  

• 文件存储（支持本地，七牛云Kodo，阿里云Oss，腾讯云Cos等存储服务，支持扩展） 

• Redis分布式锁  

• 邮件服务  


## 安装和使用

### 安装

```
go mod tidy
```



### 运行

```
go run main.go
```



## 技术架构



## 联系方式

如果您有任何问题或建议,请联系作者QQ1321928757。