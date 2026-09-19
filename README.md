# 让iOS导入的第三方铃声也可以用上“与铃声同步”的震动

我开发了个在线工具
可以把导入的音乐变成震动
节奏还是卡的挺准的
然后生成的文件可以导入系统
实现自定义铃声的震动
但是你要可以用Filza才可以
首先我们准备好要制作的音频文件
然后你可以[在这里在线使用](https://link.3ceng.cn/view/5584e5eb)
也可以下载仓库里面的html
然后上传音频
你如果已经有震动了
请根据下文中的路径提取plist
然后附加到加导入已有plist那里
那些参数一般默认就可以
然后点击开始转换
然后就可以点击下载plist
如果后缀有个xml
给它删掉
OK我们把这个plist命名成UserGeneratedVibrationPatterns.plist
然后覆盖/var/mobile/Media/Vibrations/UserGeneratedVibrationPatterns.plist
OK

现在去设置里选择你的声音和震动吧