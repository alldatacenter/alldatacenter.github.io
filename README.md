## AllData  Website

该项目保留了用于构建 AllData 官方网站的所有资源，服务于 https://github.com/AllDataTeam/alldata

## 条件

AllData 网站基于 Docusaurus 。如果您的 Docusaurus 版本低于 2.0.0，请升级到 2.0.0。另请确保您的Node版本为 14.x。

### 安装

```
$ yarn / npm i
```

### 本地启动

```
$ yarn start / npm run start / npx docusaurus start [--port 3111 ] [--host localhost ] 默认端口为 3000
```

此命令启动本地开发服务器并打开浏览器窗口。大多数更改都会实时预览，而无需重新启动服务器。

### 编译

```
$ yarn build / npm run build
```

此命令将静态内容生成到 build 目录中，并且可以使用任何静态内容托管服务提供服务。
```
