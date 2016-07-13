##Pre

[环境的配置工作](http://blog.csdn.net/u013278099/article/details/51451889)

### 遇到的一些问题

1.react-native run-android <br/><br/>
 ![gradle](http://thumbnail0.baidupcs.com/thumbnail/392383d3f1f31204ecfd2b726d4b6a75?fid=2299077220-250528-36176424076056&time=1468378800&rt=pr&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-w8zklJo8tT2s1H9fm8e%2fBKhWAJA%3d&expires=8h&chkbd=0&chkv=0&dp-logid=4510325800655642832&dp-callid=0&size=c1920_u1080&quality=90)<br/><br/>
 
由于被墙的原因，提示连不上服务器。如下图<br/><br/>
![gradle-faild](http://thumbnail0.baidupcs.com/thumbnail/8a80e98c926d4151f20fa8e45bc1fcff?fid=2299077220-250528-1059835242846841&time=1468378800&rt=pr&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-gv58ITv2Blf6BF9HghjsAJhIjak%3d&expires=8h&chkbd=0&chkv=0&dp-logid=4510325800655642832&dp-callid=0&size=c1920_u1080&quality=90)<br/><br/>

解决方案：下载gradle离线包，安装找到gradle-2.4-all.zip后下载等待完成。然后将zip包放进如下路径的乱码文件夹子目录中，子目录<br/><br/>
![gradle-install](http://thumbnail0.baidupcs.com/thumbnail/b49d85c0d722d8ccd40aaeca87779b6c?fid=2299077220-250528-550917057282082&time=1468378800&rt=pr&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-vJQRTkbDjPPyZnYkr5TvJcenvd4%3d&expires=8h&chkbd=0&chkv=0&dp-logid=4510874116090986393&dp-callid=0&size=c1920_u1080&quality=90)<br/><br/>

2 然后重新运行命令react-native run-android 又遇到如下问题<br/>
![environment variable](http://thumbnail0.baidupcs.com/thumbnail/f340549ffca9bd74e5028ee030a37c20?fid=2299077220-250528-1026933355060702&time=1468378800&rt=pr&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-5qsLMA%2fR2p1zuC7qmH2wmhpPkCg%3d&expires=8h&chkbd=0&chkv=0&dp-logid=4510325800655642832&dp-callid=0&size=c1920_u1080&quality=100)<br/><br/>

需配置环境变量，可参照([demo](http://blog.csdn.net/hpli148/article/details/7580055))<br/>

3 重新运行命令react-native run-android 遇到如下问题<br/>
![update sdk](http://thumbnail0.baidupcs.com/thumbnail/4ef238f815c0530e1695f089d3baf6f2?fid=2299077220-250528-636143448131596&time=1468378800&rt=pr&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-T2vtOBXFhoXax%2ftYY3qsIVcljlY%3d&expires=8h&chkbd=0&chkv=0&dp-logid=4510325800655642832&dp-callid=0&size=c1920_u1080&quality=90)<br/><br/>
需更新sdk，如图<br/>
![update](http://thumbnail0.baidupcs.com/thumbnail/c0f66cea2b4a157b9c0720fac4e43c47?fid=2299077220-250528-1046417304802961&time=1468378800&rt=pr&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-Q6NjxsMx4LzsWljL0MJR2ZQVL8A%3d&expires=8h&chkbd=0&chkv=0&dp-logid=4510758372676656737&dp-callid=0&size=c1920_u1080&quality=90)<br/>

4 重新运行命令react-native run-android 遇到如下问题<br/>
![not find ](http://thumbnail0.baidupcs.com/thumbnail/4b29f291baa4abb065786056e3ec5e8d?fid=2299077220-250528-3887062478496&time=1468378800&rt=pr&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-zSAqeojCv4tULd6gLOp1rEfl4Rs%3d&expires=8h&chkbd=0&chkv=0&dp-logid=4510758372676656737&dp-callid=0&size=c1920_u1080&quality=90)<br/>
找不到 tools.jar  需在系统变量中添加classpath指向jdk下的tools.jar,然后重启下电脑.可参照([demo](http://bbs.reactnative.cn/topic/95/solved-react-native-run-android%E6%97%B6%E6%8A%A5%E9%94%99-could-not-find-tools-jar/2))<br/>

##install command 
 
 [install](http://facebook.github.io/react-native/docs/getting-started.html#testing-your-react-native-installation)

 
 

   



