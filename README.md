# 写在最前
这个项目完全是为了学习python，学习了原AutoXue的项目。
因为原作者没有更新，因此拿来作为研究学习之用，请遵守开源许可协议。严禁用于商业用途，禁止使用进行任何盈利活动。对一切非法使用所产生的后果，本人概不负责。

积分有排名，学习无止境， 积分只是手段，学习才是目的。
学习应该成为常态、成为习惯，同志们日常学习还请通过学习APP来操作，通过学习充实自己、提高认识、武装头脑，拓宽思路、拓展视野、解决本领恐慌，从而提高个人的综合素质和业务能力，进一步激发做好各项工作的热情和积极性，做工作生活的务实者、勇于担当的行动者。 把为人民着想、为人民谋利记在心里，把工作实效、群众口碑放在心上，更好地将“学习强国”APP运用到实际工作中去，实实在在地学、踏踏实实地用，使其发挥出应有的作用。

# 编写目的
软件通过模拟器模拟人工操作，一是可以让爱好APP测试编程的同志们一起学习测试编程经验；二是通过模拟操作，让更多同志看到学习方法和操作方法，从而提高自主学习效率。

针对测试过程中出现问题或者学习经验分享，可以加tg群共同交流，一起提高学习效率，巩固学习成果，群：https://t.me/Autoxue_Chat

# 特别感谢
首先感谢【九月】兄弟提供的配置客户端，降低了使用门槛；感谢【特别的人】兄弟对测试支持；感谢【不知道】兄弟协助解决了大量难点。

# 测试方法，一定要先读！！本程序配置比较简单，但绝对不是傻瓜安装，务必认真以及耐心阅读以下11条，磨刀不误砍柴工，按照下述10条，加上你的耐心，一定能运行成功。Good Luck！

1、安装雷电模拟器，雷电模拟器建议用4.0版本，下载地址：https://dl.softmgr.qq.com/original/game/ldinst_4.0.40_20201111.exe   安装模拟器后，建议将模拟器设置分辨率为手机版900*1600。

2、模拟器安装学xi强国APP，建议使用最新版本(2.19或者2.20)，下载地址：https://dl.pconline.com.cn/download/2269849.html

3、打开文件夹AutoXue Config，利用exe程序进行一键配置。

    配置完成后运行xuexi文件夹中的autoxue.exe，如果运行正常，忽略2.1和2.2；如果运行失败，请手动配置，参考2.1,2.2：

    2.1、安装ADB，并配置环境变量。adb安装教程：https://www.cnblogs.com/tangbohu2008/p/9475092.html; 如果配置完成环境变量，命令行cmd窗口输入adb version 会有版本号显示。建议将安装好的adb.exe复制，粘贴覆到盖雷电目录下，保持adb.exe版本一致。
    
    2.2、配置学xi强guo用户名和密码，打开文件夹config，使用notepad++打开default.ini，可以看到[usernames]项目，根据用户配置示例，按照示例说明可以配置用户；在[COMMON]项目下，添加模拟器路径；配置完成后，保存文件，注意：一定要以utf-8编码格式保存。所以强烈建议采用notepad++编辑，notepad++下载地址：https://dl.pconline.com.cn/html_2/1/117/id=10699&pn=0.html

4、在模拟器内第一次运行学习强国APP，会有各种新手提示，必须手动提前登录点掉各种提示，提示在主要在答题界面、百灵视频界面、得分界面等等，把学习强国APP新手提示刷没，否则app的操作提示会导致程序崩溃；

5、请保持运行程序的目录结构，xuexi文件夹下的exe文件单独挪动位置会导致运行失败。如果需要把程序放在桌面，可以新建快捷方式到桌面。

6、为了防止大规模使用和商业化代学，项目暂时不开源；python程序编译后总是被360误报，建议添加信任列表或者做个艰难的决定，卸载360（这种流氓+垃圾软件不要也罢）；目前采用win10自带defender检测没问题。群内大量用户测试也没有问题，放心使用。

7、模拟器运行十分卡顿的问题，大概率因为没有打开VT，参看教程：https://www.yeshen.com/faqs/SklVHWleZ

8、关于定时启动，每天到点自己执行学习任务，建议设定任务计划，同时一定要将【起始于】参数配置为exe所在目录。参考：https://blog.csdn.net/vic0228/article/details/61914425

9、不要同时插着手机又开模拟器，二选其一。不要开代理运行，很多代理会占用adb通讯端口，导致atx初始化链接失败。

10、关于个性化配置，比如每周答题可以下拉，订阅可以打开之类的，请打开default.ini文件，逐条阅读，里面的配置信息可以帮你实现很多很多个性化功能。特别提示，default.ini文件中的每行文字，以“;”开头的，都是注释文字，是不生效的，特别是用户名配置，一定要去掉“;”才能生效。

11、如果你不用模拟器，改用手机学习，可以打开config文件夹里的default.ini文件，将emulatorused设置为disable；
