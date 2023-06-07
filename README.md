
第一步
yum update -y  #CentOS

第二步
yum install -y curl  #CentOS

第三步   先安装1    后安装2 （每次安装完重启一次服务器）  重装 
Trojan Panel面板 --1--mysql 
```
source <(curl -L https://github.com/trojanpanel/install-script/raw/main/install_script.sh)
```
这是另外一种面板
trojan面板（这个面板是最简单的）
```
source <(curl -sL https://git.io/trojan-install)
```
第四步     
bbr加速  --
```
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh 
```
第3.9步
warp（解锁奈非+GPT）   先解锁
```
wget -N https://raw.githubusercontent.com/fscarmen/warp/main/menu.sh && bash menu.sh
```


解锁顺序是1.1.3       解锁成功了 的标志（会出现美国...）成功后--装BBR
我知道你输入的3个1   是卡了  那 3 是哪一个命令   明白了不 欧克欧克  卡了




第3.5步 --去前端后台（8888） 测试
登录面板试试   还没有重启  忘记了??
 

CF https端口：2053，2083，2087，2096，8443，     443（这个这段时间老是出错，尽量别用443）

CF http端口：2052，2082，2086，2095，80，8080，8880

来WARP OK 

那现在 用BBR？？？对    BBR是数据加速用的
现在怎么选着   1    这个BBR 干嘛的

BBR跟WARP  随便哪个先后   这个没有关系

  解锁后是会降速 会将多少？？？  这个不一定   很多机场主都是解锁后搞中专   中转是提速用的
那我们 也用CF 中转 提速？？ 
