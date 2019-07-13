一键脚本安装shadowsocks/shadowsocksR/V2Ray + 开启bbr
---

一键脚本搭建shadowsocks/shadowsocksR/V2Ray + 设置开启自启动 + 升级内核&开启bbr加速。

## 教程如何访问
因为这个脚本，[flyzy小站](https://www.flyzy2005.com)已经被GFW拉入黑名单了，直接DNS污染了，国内无法访问。

如果有翻墙方法，自然可以直接访问（目前flyzy2005.com已加入GFWList）。如果还在墙内，可以参考[flyzy小站最新访问方式与镜像网站地址](https://flyzyblog.com/way-to-flyzy2005/)访问教程，科学上网吧！

## 支持系统
CentOS 6+

Debian 7+

Ubuntu 12+

## 使用教程
一键搭建ss/ssr：[一键脚本搭建shadowsocks+开启bbr](https://www.flyzy2005.com/fan-qiang/shadowsocks/install-shadowsocks-in-one-command/)

一键搭建V2Ray：[一键脚本搭建V2Ray+配置与优化](https://www.flyzy2005.com/v2ray/how-to-build-v2ray/)

或者参考：[Wiki](https://github.com/flyzy2005/ss-fly/wiki)

## 交流群
flyzy小站交流群：http://t.me/flyzyxiaozhan

搬瓦工用户交流群：https://t.me/banwagongusers


## 详细步骤
## 腾讯云注册
1.微信扫码登陆，实名认证，需要填写手机号，身份证号，最后需要用微信支付扫码支付0.01元微信认证，0.01元会直接存入腾讯云账户余额中

2.选择云服务器，点击新建实例，在列表上选择需要的网络地区，系统选择Ubuntu Server，公网宽带选10M上下，数量选1台，时长选1个月，点击付款
3.实例创建后默认是普通IP，此时在IP一栏可将普通IP转换为弹性公网IP，每个账号在每个区域下最多可申请20个弹性公网IP，每个实例只能绑定一个IP，要换IP则需在公网IP处解绑IP再重新绑定新的IP，
4.登陆服务器
    登陆之前先重置密码，此密码为服务器的登陆密码（不是腾讯云的登陆密码）


## 安装VPN SS


