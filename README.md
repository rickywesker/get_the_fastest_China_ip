## Get the fastest China IP address from multiple websites
## 从网上爬取中国ip，ping之后选取速度最快的

#### 需求性：中国大陆境外使用国内的音乐软件（网易云、虾米、QQ等）因为海外地区没有版权无法播放
#### 根属性：不在中国大陆境内
#### 解决力：翻墙回国内 || 网上找代理服务器
#### 损益比：两个方法都能解决问题，但是市面上的选择太多且不知道网速如何要逐个去试，麻烦


    瞎逼逼完了就随便讲一下这几行垃圾代码能干嘛吧：<br>
    首先，有一个小爬虫从三个网站爬了大概N个ip和对应的端口（N可以自己改），<br>
    然后，逐个ping这些ip，用正则获得平均响应时间，<br>
    最后，比较出响应时间最少的ip并print它的ip、端口<br>
    （p.s. 快代理有毒！ping的ip速度最快的是它，但是放到网易云里不能用！唉写了就写了当作练手吧...）<br>
    
