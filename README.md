xJavaFxTool是使用javaFx开发的实用小工具集，目前项目刚刚建立，利用业余时间把工作中遇到的一些问题总结起来，打包进小工具集中，供大家参考和使用，里面包含了javaFx的一些功能的示例，如布局、国际化、第三方UI库（controlsfx、JFoenix等）、外部jar包加载（插件机制）等一些常用功能，想学习javaFx的同学可以参考参考。

下载试用地址为xJavaFxTool.jar（可直接运行），开发环境为jdk1.8，基于maven，代码中使用Lombok插件，请自行安装，依赖的xcore包请见我的开源项目下载（本版本为开发版，不想独立分离，后期发布会分离开，请见谅。），支持插件开发，将插件jar包放至根目录libs下即可自动加载（插件开发示例见开源项目xJavaFxPlugIn，目前刚刚搭建，后续会持续更新）；

目前集成的小工具有：

1、FileCopy：文件复制（支持自动调度拷贝功能）；

2、CronExpBuilder：Cron表达式生成器；

3、CharacterConverter：编码转换；

4、EncryptAndDecrypt：加密解密；

5、TimeTool：Time转换；

6、LinuxPathToWindowsPath：路径转换；

7、QRCodeBuilder：二维码生成工具（自动生成、加入logo、截图识别、自定义格式）；

8、IdCardGenerator：身份证生成器；

9、RegexTester：正则表达式生成工具；

10、ShortURL：网址缩短（目前支持百度、新浪、缩我等短网址缩短）；

11、EscapeCharacter：转义字符（支持Html、XML、Java、JavaScript、CSV、Sql）；

12、ZHConverter：字符串转换（使用hanlp开源工具，实现拼音、简体-繁体、简体-臺灣正體、简体-香港繁體、繁體-臺灣正體、繁體-香港繁體、香港繁體-臺灣正體、数字金额-大写金额等直接的转换）；

13、Mq调试工具（目前仅支持ActiveMq）；

14、Http调试工具（支持自定义发送数据、header和cookie）；

15、json格式化编辑工具；

项目刚刚启动，以后会陆续添加新工具，欢迎大家参与其中，多提提意见，谢谢。
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/文件复制.png "文件复制.png")
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/Cron表达式生成器.png "Cron表达式生成器.png")
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/Mq调试工具.png "Mq调试工具.png")
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/正则表达式生成工具.png "正则表达式生成工具.png")
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/二维码生成工具.png "二维码生成工具.png")
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/json格式化编辑工具.png "json格式化编辑工具.png")
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/网址缩短.png "网址缩短.png")
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/字符串转换.png "字符串转换.png")
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/Http调试工具.png "Http调试工具.png")
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/编码转换.png "编码转换.png")
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/转义字符.png "转义字符.png")
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/加密解密.png "加密解密.png")
![输入图片说明](https://git.oschina.net/zhuifeng335/xJavaFxTool/raw/master/images/Time转换.png "Time转换.png")