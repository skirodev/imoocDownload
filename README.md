# imoocDownload
###慕课网视频下载小程序
node + express  
利用慕课网的api 生成视频下载链接  
然后在前台显示出来
###Start
```
$ node ./bin/www
然后浏览器打开 localhost:5000
```
正常情况 右击 链接点 链接另存为 就能在浏览器里下载了  
这样下载能保持文件名正常  
如果用迅雷，文件名会变成 H.mp4 需要手动改文件名  
不过用迅雷可以批量下载，右击链接，选择 迅雷批量下载链接 就行了。

PS: routes/index.js 里的cookie需要改成你的慕课网的cookie
