梯子的正确打开方式

1.远端 vps ，首先购买一个vps（4.99 $/Mon,折合31块人民币，可以支付宝），在购买的主机上面安装一个v2ray,具体见下面的帖子
（如果是windous步骤2就不用看了，步骤1即可搞定）
https://github.com/xiaoming2028/FreePAC/wiki
（远端的配置使用了自动安装脚本，不用进行配置，按照帖子配置即可）

2.本地（Ubuntu为例），如果在内网，得先通过云盘或者其他方式下载一个v2ray（linux版本的）客户端
找到的一个云盘分享链接: https://pan.baidu.com/s/165ln8Wlmzza2dRca-46aog 提取码: am8h

3.本地安装好客户端进行配置，/etc/v2ray/config.json ，配置浏览器（FireFox）代理，见以下帖子
https://unixetc.com/post/v2ray-client-configuration-example-in-ubuntu/
配置文件中特别提到的几个配置项，IP、Port -- 来自购买VPS的网站，如HostWinds、id 来自服务端的/etc/v2ray/config.json，所以两个配置文件都打开看一下，
参考帖子即可配置完成。


几个命令
service v2ray stop
service v2ray start
service v2ray status
