#### 说明

* 适合一键下载到package目录下，用于openwrt编译


* 两位L大库里都删除了某软件，作为搬运工，passwall的依赖一并找齐了


1、 lede/package$下运行 或者openwrt/package$下运行


```bash
 git clonehttps://github.com/wwz09/packages-bak.git
```

 2、 或者添加下面代码到 openwrt 或lede源码根目录feeds.conf.default文件
 
```bash
 src-git kenzo https://github.com/wwz09/packages-bak
```

 
    


