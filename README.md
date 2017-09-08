# H5 + Vue2.0 全家桶打造的一个音乐播放器

> 其实就是一个练手的东西

### Elevator Music Player

> 因为我室友嘲讽我说我听的曲子都是电梯里才会放的歌曲，所以起了个这个名字，还请不要在意。


![picture](https://github.com/Incisa/MusicPlayer/blob/master/static/all1.png?raw=true)


### 注明

* 数据来自于 QQ 音乐，歌单和歌词数据由于限制，利用 axios 做了一层 server 代理，修改请求 header 模拟 QQ 网站发送请求。Github 部署的 page 页面上并没有 server 做代理转发，所以歌单和歌词数据属于挂掉状态。当然也可以做一个假数据保证观赏性（歌单数据可以，歌词就放过我吧。

* 功能尚未开发完整，其中包括排行的二级路由页面、搜索页面播放列表页面等等。

### bug 修复

* 底栏播放器会遮挡歌单歌手页面的最后一行数据的问题。

* 歌曲拖拽更改播放进度范围过小导致拖拽失败原因。

* 多次点击下一首的加载问题。
