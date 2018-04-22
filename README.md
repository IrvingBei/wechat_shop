
# 小程序服务端 server_api

使用数据库管理工具 adminer 导入数据 wechat_shop.sql

    1、App/Common/Conf/db.php 数据库连接参数修改；

    2、App/Api/Conf/config.php 微信小程序的appid、secret、mchid、key、notify_url，SELF_ROOT的参数修改；

    3、ThinkPHP\Library\Vendor\wxpay\lib\WxPay.Config.php  微信小程序的appid、appsecret、mchid、key参数修改；

    4、ThinkPHP\Library\Vendor\WeiXinpay\lib\WxPay.Config.php  微信小程序的appid、appsecret、mchid、key、notify_url参数修改；

    5、App/Api/Controller/WxPayController.class.php 50行修改链接


    后台登录地址： youname.com/index.php/admin  用户名是admin，密码是123456


服务端源码：https://github.com/tekintian/wechat_shop/server_api


# 小程序源码目录 wxss_src

小程序配置方法：

wxss_src/app.js
配置 hostUrl、 ceshiUrl 为你安装的服务端的URL地址


腾讯云解决方案分配的域名
wxss_src/config.js 


小程序源码：https://github.com/tekintian/wechat_shop/wxss_src



