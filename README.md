# 沉浸式网安初体验：“小海豹学钓鱼”

## ——网络安全体验区体验策划

## 1. 设计要求

> 与网络安全专业相关的小游戏，与新生以及家长互动，感受专业特点与魅力。例如：在一台电脑上输入内容，另一台电脑能够获取该电脑上输入的内容。

## 2. 体验环境

- 外部环境：迎新点，紫菘路演区

- 电脑环境：

  Kali Linux虚拟机：配有USB无线网卡，安装花生壳

  主机：安装花生壳

## 3. 体验内容

1. 参与体验的新生扫描二维码，进入钓鱼页面；

   ![宣传海报](https://s2.loli.net/2022/08/13/qfoOwhlvJEFy6BH.jpg)

2. 新生在该页面（仿智慧华中大统一登陆界面）输入账号密码，点击登录即被钓鱼；

   ![](https://s2.loli.net/2022/08/13/cM5WNdpKTbCy4zO.png)

3. 新生查看主机处，被钓鱼的账号输入数据（基于安全性考虑，密码不作传输）；

   ![image-20220813220743786](https://s2.loli.net/2022/08/13/8FQGnhmlVKuU9Yq.png)

4. 新生设备上页面自动导航为预先设定的静态博客页面。

   ![image-20220813221010092](https://s2.loli.net/2022/08/13/8HwqsUbSg6OexGK.png)

5. 游戏流程结束。

6. 补充：可使用解密脚本对密码进行解密。

## 4. 体验准备流程

准备阶段：

1. 复制指定页面（如智慧华中大）到Linux下自定文件夹；
2. 按需修改该页面，着重修改提交回的表单消息；
3. 下载、安装、注册花生壳，绑定主机与账号，开通内网穿透；
4. 在网上部署指定重定向游戏结束页面；
5. 使用setoolkit发布钓鱼攻击页面。

部署阶段：

1. 使用setoolkit部署钓鱼网址；
2. 调整花生壳内网穿透参数（随网络环境变化而变化）；
3. 开启花生壳内网穿透。

## 5. 备忘录

钓鱼网站公网网址：https://57u585q613.zicp.fun/

钓鱼网站本地位置：/var/www/SmartHUST/

重定向指向页面：https://wyywwi.github.io/post/forfreshman/

海报设计：https://www.canva.cn/design/DAFJNAM6-ps/uLgqHySeFrxGIRhYrcrG0Q/edit?utm_content=DAFJNAM6-ps&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

解密JavaScript脚本位置：/home/kali/Downloads/




