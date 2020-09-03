# m3u8视频下载合并器
一款只需要输入m3u8的网址即可完成视频下载、解密和合并操作的工具

[1.0的蓝奏云下载地址](https://www.lanzous.com/i8ov2mh)

[github地址](https://github.com/Stars-One/M3u8Downloader)

1.0以上的新版本不再免费发布,请自行编译打包

或者是[点击打赏](http://stars-one.site:9091/donate/2)获取软件

## 程序说明
- [x] 采用多线程下载，可有效的提高下载速度
- [x] 内置解密程序，当视频采用了加密可以自动解密
- [ ] 优化多线程下载 
- [ ] 根据已下载好的m3u8文件和key文件，对合并本地的ts文件进行解密和合并操作
- [ ] 在线更新
- [ ] 多视频同时下载（目前还存在有Bug，界面进度会乱，为了稳定，目前推荐每次下载一个视频）

## 运行说明

需要java1.8环境

详情请查看[软件配置说明](http://stars-one.site:9091/appDesc)

## 使用说明

程序只需要输入m3u8的在线地址,之后即可下载并解密合并成一个mp4文件,由于软件的下载的问题,下载过程中某些ts文件不完整,从而会导致之后合并的mp4少一些片段,**完美主义者勿用**

通过`猫抓`Chrome插件或者F12进入浏览器调试模式，找到具体的m3u8地址（关于获取m3u8地址的详细操作，请参考百度，这里不再赘述）

在程序输入获得的m3u8文件的在线地址，之后，软件会通过此地址进行下载m3u8文件、key文件（如果有加密的haunted）和ts文件，并进行解密合并，最后会输出一个mp4格式的文件。

## 截图
由于时间关系，没有截取下载的全部过程

![](https://img2018.cnblogs.com/blog/1210268/202001/1210268-20200115195555735-821306910.gif)
