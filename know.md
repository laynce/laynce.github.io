# 常用信息整理
### nodeJS发布[包地址](https://nodejs.org/download/release/v18.18.0/)
  - nvm安装nodejs时若对应版本nodejs为空目录，可下载对应版本的nodejs包拷贝进去-
------------------------------------
### vue2的devTools浏览器扩展程序安装
  - [vue-devtools](https://bgithub.xyz/vuejs/devtools)下载源码，使用yarn install
  - 进入shell-chrome目录下，修改manifest.json文件的background对象下persistent值为true
  - yarn run build
  - 若安装失败，切换yarn 镜像源为淘宝
  - 安装成功后，chrome扩展程序加载扩展程序(devtools-v6\packages\shell-chrome)
