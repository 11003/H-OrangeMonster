# OrangeMonster_reference






1. [XS](#XS)
2. [SM](#SM)
3. [MD](#MD)
4. [媒体查询](#媒体查询)
5. [栅格系统](#栅格系统)




















### XS

![](https://gss0.baidu.com/-Po3dSag_xI4khGko9WTAnF6hhy/zhidao/pic/item/2e2eb9389b504fc28ed59baee9dde71191ef6d96.jpg)



### SM

![](https://gss0.baidu.com/-Po3dSag_xI4khGko9WTAnF6hhy/zhidao/pic/item/d439b6003af33a87dacf2bb1ca5c10385243b5fe.jpg)



### MD

![](https://gss0.baidu.com/-Po3dSag_xI4khGko9WTAnF6hhy/zhidao/pic/item/902397dda144ad341a35ac2cdca20cf430ad8596.jpg)



## 媒体查询

在栅格系统中，我们在 ```Less``` 文件中使用以下媒体查询（media query）来创建关键的分界点阈值。


	超小屏幕（手机，小于 768px）
	没有任何媒体查询相关的代码，因为这在 Bootstrap 中是默认的（还记得 Bootstrap 是移动设备优先的吗？）

	小屏幕（平板，大于等于 768px） 
	@media (min-width: @screen-sm-min) { ... }

	中等屏幕（桌面显示器，大于等于 992px） 
	@media (min-width: @screen-md-min) { ... }

	大屏幕（大桌面显示器，大于等于 1200px） 
	@media (min-width: @screen-lg-min) { ... }


	@media (max-width: @screen-xs-max) { ... }
	@media (min-width: @screen-sm-min) and (max-width: @screen-sm-max) { ... }
	@media (min-width: @screen-md-min) and (max-width: @screen-md-max) { ... }
	@media (min-width: @screen-lg-min) { ... }



##栅格参数

![](https://gss0.baidu.com/-vo3dSag_xI4khGko9WTAnF6hhy/zhidao/pic/item/b03533fa828ba61e2d4ddd844d34970a314e59fd.jpg)



>参考
![Bootstrap](https://v3.bootcss.com/css/)
