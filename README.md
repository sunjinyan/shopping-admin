#online-store

node版本： 14.14.0
npm版本: npm@8.19.2
cnpm版本: npm@6.1.1


下载cnpm
https://developer.aliyun.com/mirror/NPM

npm install -g cnpm@6.1.1  --registry=http://registry.npmmirror.com


npm fund

cnpm install

cnpm run dev

```

   cnpm报错：Error: Cannot find module ‘diagnostics_channel‘

    原因：cnpm版本太高了，npm全局安装的cnpm是最新版的，所以卸载原来的cnpm再装一个指定版本即可

    卸载cnpm:

    npm uninstall -g cnpm

    安装指定版本：6.1.1

    npm install cnpm@6.1.1 -g

```

```
config\index.js中的port字段是端口号，可以修改为指定所需的字段
```

 http://localhost:8090