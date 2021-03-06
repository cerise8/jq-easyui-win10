EasyUI Windows8 Style Themes
================

我的第一个开源项目，就是一套简洁的蓝色细边框windows8 Metro风格的jQuery EasyUI皮肤。源于在使用jQuery EasyUI时发现官方提供的几套皮肤跟项目协调的不是很完美，我们的项目有点Metro小清新风，于是我就在开发中陆需修改了自带皮肤样式。此项目纯属雕虫小技（见谅），虽然简单但对我而言意义非同寻常了，以后可能还会修改或添加个性化功能，放上不久，对于GitHub和开源还在摸索中......

说明
----------------------
基于jQuery EasyUI 1.4.4，只包括对窗口的修改，包括继承自window的组件。其他组件样式基本不变。

使用
----------------------
直接导入本主题内themes/metro-solidBlue/easyui.css以及themes/icons，themes/icons.css文件替换即可.  
温馨提示:只需要替换核心的easyui.css文件即可  

**CSS**  
```html
<link rel="stylesheet" type="text/css" href="easyui-1.4.4/themes/metro-blue/easyui.css">
<link rel="stylesheet" type="text/css" href="easyui-1.4.4/themes/icon.css">
```

**JS**  
```html
<script src="http://libs.baidu.com/jquery/2.0.0/jquery.min.js"></script>
<script type="text/javascript" src="easyui-1.4.4/jquery.easyui.min.js"></script>
<script type="text/javascript" src="easyui-1.4.4/locale/easyui-lang-zh_CN.js"></script>
```

图示
----------------------
**window**  
![windows样式](http://dunizb.b0.upaiyun.com/p/eui-solid-blue/window.PNG "windows样式")  

**Tabs**  
![Tabs样式](http://dunizb.b0.upaiyun.com/p/eui-solid-blue/tabs.PNG "Tabs样式")

**panel**  
![panel样式](http://dunizb.b0.upaiyun.com/p/eui-solid-blue/panel.PNG "panel样式")

**dialog**  
![dialog样式](http://dunizb.b0.upaiyun.com/p/eui-solid-blue/dialog.PNG "dialog对话框样式")

**确认**  
![确认样式](http://dunizb.b0.upaiyun.com/p/eui-solid-blue/确认.PNG  "确认对话框样式")


更新记录
----------------------
**2015-12-27**  
 1. 修改alert、dialig组件确定按钮栏的背景为白色

**2015-12-06**  
 1. 新增诺干图标icon（icon自定义很方便，本次更新的图标比较粗糙，可自行替换）
 2. 样式优化

**2014-10-27**  
 1. 修正组件的icon错位的问题
 2. 去掉了窗口标题栏的背景条，改为白色无边框

**2014-10-23**  
 1. 修正$.messager.show组件的关闭按钮超出边框的问题