```
必须先连接到公司内网(指北京办公室)才可以翻墙。
```
### chrome浏览器
```
1. 必须使用chrome浏览器
2. 安装chrome浏览器
```

### SwitchySharp下载地址
[下载地址](http://7xsmxt.com1.z0.glb.clouddn.com/chrome-plugin/SwitchySharp.crx)
```
http://7xsmxt.com1.z0.glb.clouddn.com/chrome-plugin/SwitchySharp.crx
```

### 安装插件
![chrome安装插件](http://7xsmxt.com1.z0.glb.clouddn.com/switchysharp/01.png)
![chrome安装插件](http://7xsmxt.com1.z0.glb.clouddn.com/switchysharp/02.png)
![chrome安装插件](http://7xsmxt.com1.z0.glb.clouddn.com/switchysharp/03.png)
```
点击添加扩展程序后，插件就安装好了。安装好后会自动跳转到SwitchySharp插件的配置页。
如果没有跳转到该配置页，可以按如下方式找到配置的地方。
```
![chrome安装插件](http://7xsmxt.com1.z0.glb.clouddn.com/switchysharp/04.png)

### SwitchySharp配置
##### 情景模式配置
![chrome安装插件](http://7xsmxt.com1.z0.glb.clouddn.com/switchysharp/05.png)

```
情景模式名称可以任意填写。HTTP代理：192.168.10.199端口：10086其他不用填写，然后点击保存。
```
##### 切换规则配置
```
点击切换规则
```
![chrome安装插件](http://7xsmxt.com1.z0.glb.clouddn.com/switchysharp/06.png)
```
按照上面的截图添加即可。其中“规则列表URL”为：
https://raw.githubusercontent.com/hanqin/switchysharp-rule-list/master/switchysharp_rule_list.txt[此文件维护的是可以通过该代理访问的网站]情景模式选择上面创建的情景模式。
然后保存即可。
然后，勾选“自动切换模式”
```
![chrome安装插件](http://7xsmxt.com1.z0.glb.clouddn.com/switchysharp/07.png)

现在就可以访问谷歌、Facebook等墙外网站了。

```
如果有些国外网站无法访问可以反馈给秦汉或者运维人员，我们会更新“规则列表URL”，更新后正常就可以访问了。
当然也可以自己添加规则。```
##### 自定义规则
![chrome安装插件](http://7xsmxt.com1.z0.glb.clouddn.com/switchysharp/08.png)
![chrome安装插件](http://7xsmxt.com1.z0.glb.clouddn.com/switchysharp/09.png)

```
其中规则名称可以任意填写，URL模式一般会自动生成，也可以自己手动配置。情景模式选择自己创建的名称即可。
```