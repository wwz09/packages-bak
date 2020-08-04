#### 说明
* 本包备份于kenzok8大的库,非常感谢
* 适合一键下载到package目录下，用于openwrt编译
* [passwall依赖库下载链接，注意！在openwrt或者lean源码下编译passwall，要下载此依赖库](https://github.com/kenzok8/small.git)
 


1、 lede/package$下运行 或者openwrt/package$下运行


```bash
 git clone https://github.com/wwz09/packages-bak.git
```

 2、 或者添加下面代码到 openwrt 或lede源码根目录feeds.conf.default文件
 
```bash
 src-git kenzo https://github.com/wwz09/packages-bak.git
```

 3、 passwall依赖
 
 ```bash
 src-git small https://github.com/kenzok8/small
 ```
 

