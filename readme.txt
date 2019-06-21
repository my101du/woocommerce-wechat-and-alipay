=== WordPress WooCommerce 微信支付插件 ===
Contributors: XunhuWeb
Donate link: http://www.wpweixin.net/product/201.html
Tags:wechat,微信,微信支付,weixin,wechatpay, wordpress plugin, payments, wechat payments, woocommerce
Requires at least: 4.0
Stable tag: 1.8.4
Tested up to: 4.9.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

真正可用的微信支付插件,支持PC扫码支付,支持退款,支持汇率.

== Description ==

二维码正常显示，真正可用的微信支付插件,支持PC扫码支付,支持退款,支持汇率，需要开通腾讯官方微信支付商户，如需H5支付和微信红包推广，请购买企业版：<a href="https://www.wpweixin.net/product/201.html" target="_blank">WordPress WooCommerce微信支付红包版</a>


= Features for Enterprise version: =

* WooCommerce子插件，完美兼容
* 在WooCommerce添加微信支付网关
* 支持汇率换算，需要手动设置汇率
* PC端支持微信扫码支付
* 微信端支持公众号支付(需购买企业版)
* 手机浏览器支持H5支付(需购买企业版)
* 微信红包促销功能(需购买企业版)
* 红包推广：分享产品,产品被购买获得红包(需购买企业版)
* 红包返现：微信支付成功送红包，刺激下单支付(需购买企业版)
* 微信自动登录,并且同步微信头像(需购买<a href="https://www.wpweixin.net/product/1067.html" target="_blank">微信登录插件</a>)
* 退款功能，直接退款到微信零钱或银行卡
* 微信地址同步到收货地址(需购买企业版)
* 跨域共享，多个网站共用一个微信支付账户(需购买企业版)
* 适合任意WooCommerce主题
* 演示站点：<a href="http://demo.xunhunet.com/" target="_blank">http://demo.xunhunet.com/</a>
* 帮助文档：<a href="https://www.wpweixin.net/blog/312.html" target="_blank">https://www.wpweixin.net/blog/312.html</a>


= Support Mail: =
* Mailbox: jeff@xunhuweb.com

== Installation ==
1.  Install WooCommerce plugin and configure your store (if you haven't done so already - http://wordpress.org/plugins/woocommerce/).
2.  Install "WeChatPay for WooCommerce" wordpress plugin just like any other Wordpress plugin.
3.  Activate.
4. Setup your weChat application id, merchant id, key, throuth <strong>Woocommerce -> Settings -> Payment Gateways -> WeChatPay</strong>.
   You can apply wechat payment through https://pay.weixin.qq.com/wxzf_guide/index.shtml
5. If the main currency of your store is not Chinese Yuan, please also set the exchange rate so that weChat can convert the price to Chinese Yuan.
6. Help documentation:http://www.wpweixin.net/blog/192.html

== Screenshots  ==
1. WeChat settings page in CN
2. Checkout with option for wechat payment.
3. Order pay screen, including QR code of wechat  and payment amount.
4. Pay screen in weChat
5. weChat mobile Screenshots
6. weChat mobile Screenshots
7. weChat mobile Screenshots



== Remove plugin ==
1. Deactivate plugin through the 'Plugins' menu in WordPress
2. Delete plugin through the 'Plugins' menu in WordPress


== Frequently Asked Questions ==
1. Q:我微信支付账户有未结算余额，为什么不能发红包？A:微信支付规定，红包必须先充值才能发送，不能使用账户余额。
2. Q:随机红包，能发0.01元吗？一个微信号能收到几次红包? A:微信支付红包规定，红包最少1元起。目前一个微信号分享朋友圈只能获得一个红包
3. More questions please send a message to Jeff@xunhuweb.com consulting


== Upgrade Notice == 
* Updated once a month

== Changelog ==
= 1.8.4 =
* [Fixed] 兼容最新的woocommerce3.2.X，老用户不用更新

= 1.8.2 =
* [Fixed] 兼容最新的woocommerce3.1.X，WooCommerce老用户不用更新

= 1.8.1 =
* [Added] 稳定版本，重构二维码显示问题

= 1.6 =
* [Added] WeChat automatic login，and synchronize avatar and nickname

= 1.5 =
* [Added] Red envelope used for sales promotion;Red envelope got at random for sharing the product among the Moments.Red envelope of cashback: the amount of cashback will be sent directly after the payment in a red envelope.

= 1.3 =
* [Added] Currency conversion with manual setting of exchange rate,Support H5 In-App Web-based Payment (Official Account Payment)

= 1.0 =
* [Added] Initial Version.

