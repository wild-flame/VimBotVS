# VimBotVS

BotVS rsync plugin for VIM

## Install 

### 直接安装

直接下载复制到插件目录即可, 保存时Vim可自动同步策略源码的服务端

### 或 using vundle 

在`.vimrc` 配置文件里添加

```
Bundle 'botvs/VimBotVS'
```

之后 `:BundleInstall` 即可

## Auto sync when strategy saved

使用方法

安装对应编辑器插件后，在策略页面选择「远程编辑」，下载保存策略源码, 并插入密钥到本地源码第一行, 保存即可自动同步。

![](http://7xi2n7.com1.z0.glb.clouddn.com/d3ae82f66f84ab57cfe29e128d98b74d3f54dc43.png)

当你保存带有token标识的策略源文件时, 该源文件会自动同步上传到BotVS服务器



