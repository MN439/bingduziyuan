# bingdu
病毒资源库
1.彩虹猫病毒
MD5：19dbec50735b5f2a72d4199c4e184960
英文名称：Trojan.Win32.MEMZ.A（标准）
简介：该病毒属于MBR病毒，从功能上看，它是一款恶作剧病毒，它会修改MBR主引导扇区，以此来破坏电脑的正常启动。在修改MBR后，电脑重启会停留在一个彩虹猫的画面，因此该病毒被称为是彩虹猫病毒。运行该病毒后会出现两次窗口提示，仍然确认运行后即修改MBR，蓝屏前弹出许多页面，鼠标失控，桌面变成通道，蓝屏后无法正常开机，出现彩虹猫。
详细分析：https://www.sohu.com/a/448447210_120054144
样本：https://wwi.lanzoup.com/iz7pf0k6j1wj


2.CIH病毒
MD5：008c786f3c188338d7ae9dd8be8838a6
MD5（源文件）：d30ee3c2d3d9056f0f70fc8d48e61156
英文名称： Virus.Win9x.CIH.1003.A（标准）   
简介：主要作用是感染系统文件，但因为“副作用”——能够破坏计算机硬件而闻名，在每月26日发作（有版本是每年4月26日发作）。
1.0版的完成时间是1998年4月26日, 完成能够感染可执行文件的基本功能，此时病毒的大小是656个字节。

1.1版的完成时间是1998年5月15日, 增加操作系统判断，如果是WinNT，则不运行病毒，此时病毒的大小是796个字节。

1.2版的完成时间是1998年5月21日, 增加删除BIOS和破坏硬盘功能，此时病毒的大小是1003个字节。

1.3版的完成时间是1998年5月24日, 修复感染winzip自解压文件的错误，此时病毒的大小是1010个字节。

1.4版的完成时间是1998年5月31日, 彻底修复感染winzip自解压文件的错误，此时病毒的大小是1019个字节。
注：该样本为CIH1.2版本。
详细分析：https://zhuanlan.zhihu.com/p/50684852
样本： https://wws.lanzoui.com/iLnYKdiov5g
样本（源文件）：https://wwx.lanzoui.com/izYbkwd7csh





3.欢乐时光病毒
MD5：824a05957d9ba7be017fb8a0f80af5b2
英文名称：Email-Worm.VBS.HappyTime.A（标准）
简介：该蠕虫病毒使用 MS Outlook Express 以及 MSMAPI 服务在电子邮件中传播，是用 Visual Basic 脚本语言 （VBS） 编写的。
          蠕虫以 HTML 格式的电子邮件或带有附加 HTML 文件的纯文本消息的形式到达计算机。在第一种情况下，HTML 邮件正文中的脚本代码在邮件打开时自动执行，蠕虫将获得控制权。在另一种情况下，用户必须打开附加的 HTML 文件（双击它）才能激活蠕虫。被激活后，蠕虫不会立即开始传播;而是开始感染计算机。它使用包含内部蠕虫代码的 HTML 文件修改桌面壁纸。如果桌面在感染之前有背景图片，则此图片将显示为受感染HTML的背景，并且在大多数情况下，用户不会明显看出壁纸已更改;因此，每次显示（例如，在 Window 启动时）或刷新桌面时，蠕虫都会获得控制权。
          此外，病毒会感染所有 Windows 文件夹的"WEB"子文件夹中的 HTT 文件。启用 Web 模式时，Windows 使用这些文件自定义资源管理器中视图中的某些文件夹（例如，"程序文件"文件夹）。感染这些文件会导致每次显示特定文件夹时执行蠕虫代码。每次病毒获得控制权时，它都会搜索扩展名为 HTM、HTML、ASP 和 VBS 的文件并感染它们（将自己的代码插入到这些文件中），一次一个文件。一段时间后，计算机上的所有这些文件都会被感染。
详细分析：https://threats.kaspersky.com/en/threat/Email-Worm.VBS.HappyTime/
样本：https://wwx.lanzoux.com/i8ZtPif6t0d






4.爱虫病毒
MD5：8a960cc7c9312bfd0e4309de67587d6a
MD5（源文件）：8ee3d0dd0f4ba11ed85a7bcb2935d2bc
英文名称：Email-Worm.VBS/Win32.LoveLetter.A（标准)
简介：通过Microsoft Outlook电子邮件系统传播，邮件的主题为“I LOVE YOU”，并包含一个附件。一旦在Microsoft Outlook里打开这个邮件，系统就会自动复制并向地址簿中的所有邮件电址发送这个病毒。之后病毒会修改IE起始页指向木马网站并下载木马程序，连接IRC服务进行传播，最后会对系统上的一些文件进行破坏与隐藏。
详细分析：https://threats.kaspersky.com/en ... orm.VBS.LoveLetter/
样本：https://wws.lanzoui.com/ikKjPdhrb3g
样本（源文件）：https://wwx.lanzoui.com/imT4Kwd82za




5.女鬼病毒
MD5：7873127a0bcef06cb96fb1e42aff137b
英文名称：Virus.Win32.Starfiled.A（标准）
简介：恶作剧程序，用女鬼图片吓人。
样本：https://wwi.lanzoup.com/ihLTz0atja4d（图片比较恐怖，暂不附上）


6.Windows XP Horror病毒
MD5：063ea883f8c67d3bb22e0a465136ca4c
英文名称：Virus.Win32.Induc.A（标准）
简介：伪装成XP升级包，运行后改MBR，出现很多恐怖画面。
样本：https://wws.lanzoui.com/iw4zXdnszod
图片：https://www.bilibili.com/video/BV1Gf4y1m7zk/ 有兴趣可自行欣赏

7.暴风一号病毒
MD5：3509431b942232f5c50863baaa02d900
英文名称：Worm.VBS.AutoRun（标准）
简介：由 VBS 脚本编写，采用加密和自变形手段，并且通过U盘传播的恶意脚本蠕虫病毒。病毒行为有自变形、自复制、改注册表、遍历文件夹、关闭弹出光驱、锁定计算机、进程异常，且弹出恐吓图片。
样本：https://wws.lanzoui.com/ibnBkdhrb4h



8.苏拉病毒
MD5：4be31e7d4791907dfb19cc46f0c1e4fd
MD5（源文件）：42af19d515107a4fac82502ed55c7ad4
英文名称：Virus.Win32.Sola.A（标准）
简介：中毒后不能重启电脑，无法进入安全模式启动系统查杀病毒。只能回答问题，并且要回答对一定分数才能自动清除病毒，否则进一步破坏系统，使用户不得不重新安装计算机。答错题就会被破坏系统。
样本：https://wws.lanzoui.com/iACFYdhrcva
样本（源文件）：https://wwx.lanzoui.com/i2jbsw6ytfg



9.滑稽病毒
MD5：815b63b8bc28ae052029f8cbdd7098ce
英文名称：Virus.Win32.Blamon（标准）
简介：恶搞程序，源自B站某UP主制作，启动会全屏乱弹滑稽表情，图标被篡改。
样本：https://wws.lanzoui.com/isHcCdhrbud



10.中华黑豹病毒
MD5：eda588c0ee78b585f645aa42eff1e57a
英文名称：Trojan.Win32.FormatAll.V（标准）
简介：故意恶搞，且恶搞水平很中二，其源文件（Trojan.Win32.FormatAll.A）是一个利用@echo y|format 指令格式化硬盘的恶意破坏程序。
样本：https://wws.lanzoui.com/ioLLndhrd5a




11.卢本伟病毒
MD5：c71091507f731c203b6c93bc91adedb6
英文名称：Trojan.Win32.Disabler（标准）
简介：纪念卢姥爷的恶搞病毒。
样本：https://wws.lanzoui.com/iuH1Ydhrcmb
图片：https://www.bilibili.com/video/BV14Q4y1P78T/

12.雨云病毒
MD5：0a456ffff1d3fd522457c187ebcf41e4
英文名称：Worm.VBS.yuyun.A / Cantix.A
简介：一个局域网蠕虫病毒，危害较大。
样本：https://wws.lanzoui.com/ia8wwdkqa2b

13.BMW病毒
MD5：1aa4c64363b68622c9426ce96c4186f2
英文名称：TrojanDownloader:Win32.Jadtre.B（Microsoft）
简介：该病毒能够连环感染BIOS(主板芯片程序)、MBR(硬盘主引导区)和Windows系统文件，使受害电脑无论重装系统、格式化硬盘，还是换掉硬盘都无法 彻底清除病毒。
中毒迹象：
          一、Windows系统启动前，电脑屏幕显示"Find it OK!"字样;         

          二、杀毒软件反复提示“硬盘引导区病毒”却无法彻底清除;

          三、浏览器主页被篡改
样本：https://wwx.lanzoux.com/isiO8jrpz0b


14.Disttrack病毒
MD5：b14299fd4d1cbfb4cc7486d978398214/d214c717a357fe3a455610b197c390aa
英文名称：Virus.Win32.disttrackA（标准）/ Virus.Win32.WipMBR.A/ Virus.Win32.EraseMBR.A
简介：执行文件里包含了“wiper”字段，以及“ArabianGulf”字段。这一字段也曾在Flame病毒中出现过，Flame曾被认为是由美国和以色列政府共同研发用以攻击伊朗核能源部门的恶意攻击软件。Shamoon病毒与Flame病毒类似，能够直接将感染用户电脑内的数据发送到网络，而且在传完数据之后恶毒的将电脑上的数据永久删除，甚至包括主引导记录，直接就导致系统瘫痪，不能开机。Shamoon病毒本身的文件大小只有900k，但是内部的资源都是经过完整加密的。
样本：https://wwx.lanzoui.com/isluQliiobc




15.骷髅头病毒
MD5：dffe6e34209cb19ebe720c457a06edd6
英文名称：Trojan:Win32/Dynamer!rfn（Microsoft）
简介：由b站up主天哥制作，运行后修改壁纸为骷髅头，然后和动态的熊猫烧香病毒进行相同的恶搞破坏行为，最后添加新用户进行敲竹杠勒索。
视频资源：https://www.bilibili.com/video/av40010715/（骷髅头视频）
                 https://www.bilibili.com/video/BV1up4y1i7pu/（动态版熊猫烧香，音乐好听）
样本：https://wwi.lanzouo.com/i2UiFzbs0nc

         

二. 蠕虫病毒类
注：本类别中存在许多感染型病毒，严格来说感染型病毒与蠕虫病毒有区别，感染型病毒主要指将自身加入到其它的程序或动态库文件(DLL的一种)中，从而实现随被感染程序同步运行的功能，进而对感染电脑进行破坏和自身传播的病毒，而蠕虫病毒主要指一种可以自我复制，无须人为干预并且通过网络传播的病毒；当这些新的被蠕虫入侵的计算机被控制之后，蠕虫会以这些计算机为宿主继续扫描并感染其他计算机，这种行为会一直延续下去。蠕虫使用这种递归的方法进行传播，按照指数增长的规律分布自己，进而及时控制越来越多的计算机。但为了便于分类，同时考虑到两者具有许多的共同点，就把两者划到了同一类中，不过基于各个杀毒软件的报法，本帖仍将用Virus表示感染型病毒（前一类中Virus也被用来表示部分恶意破坏类病毒），用Worm表示蠕虫病毒。



1.威金感染型病毒 / 熊猫烧香蠕虫病毒
MD5：512301c535c88255c9a252fdf70b7a03
MD5（源文件）：d4a05ada747a970bff6e8c2c59c9b5cd / ad41ec81ab55c17397d3d6039752b0fd
中文名称：同上
英文名称：Virus.Win32.Viking.A（标准） /  Worm.Win32.Fujack.A（标准）
简介：集文件型病毒、蠕虫病毒、病毒下载器于一身，传播能力非常强。该病毒会破坏用户的一些软件，造成它们无法使用，通过感染文件、局域网以及其他病毒下载传播。该病毒还会自动在后台下载并运行“QQ通行证”等其他病毒，窃取用户QQ及网络游戏的账号和密码并发送给黑客。
         值得一提的是，熊猫烧香的大部分代码与威金几乎一致，因此可以看到熊猫烧香的很多报毒名都是Viking（威金），也有很多人认为它就是威金的一个变种。不过熊猫烧香在原有代码的基础上加入了很多自己的炫技代码，比如到处都是熊猫图片等。作者过分地自大和装逼，也是他很快就被抓获的原因之一。
样本：https://wws.lanzoui.com/iim4tdjnv1c 密码：142857
样本（源文件）：https://wwx.lanzoux.com/iJx4njrpz1c / https://wwx.lanzoui.com/iYRNLwd8ldc



2.金猪报喜病毒
MD5：a57db79f11a8c58d27f706bc1fe94e25
中文名称：同上
英文名称：与1相同
简介：熊猫烧香的变种，把熊猫头像换成了金猪头。
样本：https://wwx.lanzoux.com/iGVGGjbpqta




3.冲击波病毒
MD5：fc14eaf932b76c51ebf490105ba843eb
中文名称：冲击波病毒
英文名称：Net-Worm.Win32.Blaster.A（标准）/ Lovesan.A/ Msblast.A
简介：利用在2003年7月21日公布的RPC漏洞进行传播，一旦攻击成功，病毒体将会被传送到对方计算机中进行感染，使系统操作异常、不停重启、甚至导致系统奔溃。
样本：https://wws.lanzoui.com/icImWdq15yj

4.震荡波病毒
MD5（源文件）：2a92da4b5a353ca41de980a49b329e7d
中文名称：震荡波病毒
英文名称：Net-Worm.Win32.Sasser.A（标准）
简介：系统资源被大量占用，有时会弹出RPC服务终止的对话框，并且系统反复重启, 不能收发邮件、不能正常复制文件、无法正常浏览网页，复制粘贴等操作受到严重影响，DNS和IIS服务遭到非法拒绝等。
样本：https://wwx.lanzoui.com/iw5PNwd7cuj


5.Ramnit感染型病毒
MD5（源文件）：68abd642c33f3d62b7f0f92e20b266aa
MD5（衍生物，评论多）：ff5e1f27193ce51eec318714ef038bef
中文名称：同上
英文名称：Virus.Win32.Ramnit/Nimnul.A（标准）
简介：能够感染用户计算机bai系统中的.exe、.dll和.html文件，将自身加密以后缀加到目标文件中。当被感染的文件运行时，该蠕虫会被释放到当前目录并被命名为[InfectedFilename]Srv.exe，然后执行。同时在%\ PR ogramFiles%\目录下增加一个MNetwork目录。感染该病毒的计算机会试图连接到网站，从该网站下载.dll文件注册到系统中。
样本：https://wws.lanzoui.com/iWISddkqa1a


6.磁碟机病毒
MD5：4c36884f0644946344fa847756f4a04e
中文名称：同上
英文名称：Virus.Win32.Xorer.A（标准）
简介：主要通过U盘和局域网ARP攻击传播，感染系统可执行文件，能够利用多种手段终止杀毒软件运行，并可导致被感染计算机系统出现蓝屏、死机等现象。
样本：https://wws.lanzoui.com/ix8qXdkqhvc


7.Pabug蠕虫病毒
MD5：2391109c40ccb0f982b86af86cfbc900
中文名称：AV终结者/ 帕虫病毒
英文名称：Worm.Win32.Pabug（标准）
简介：摧毁用户电脑的安全防御体系，之后“AV终结者”自动连接到指定的网站，大量下载各类木马病毒，盗号木马、广告木马、风险程序。
样本：https://wws.lanzoui.com/i0ZCsdniire


8.机器狗病毒
MD5：e01388a75b670d9cbe54038eec8f5ecb
中文名称：同上
英文名称：Trojan.Win32.Agent（标准）/ Trojan.Peed.Gen / Trojan.DownLoader.31883（大蜘蛛） / Trojan-Downloader ( 0055e3da1 ) （Ikarus）/ Trojan.Win32.Mnless.zpj（瑞星）
简介：能穿透各种还原卡，危害很大。
样本：https://wws.lanzoui.com/iZqYkdnigkf

9.犇牛病毒
MD5：06e74cedc9af89a710ee326e2ac9d5e9
中文名称：同上
英文名称：Win32:Dh-A [Heur]（Avast）/ Spy.Banker.Gen （Avira） / Trojan.MulDrop.30219（Dr.Web） / TrojanDownloader.Agent.OQW（ESET） / Trojan.Win32.Antavka.ji（卡巴斯基） / Win32/Trojan.867（360）
简介：机器狗的一个变种，能拖慢电脑速度，并下载大量木马到电脑进行盗号。
样本：https://wws.lanzoui.com/iFeDtdoj49e



10.极虎蠕虫病毒
MD5：ccbe1775eb280c1b6187628534fc34da
中文名称：同上
英文名称：Worm.Win32.Bototer（标准）/ Win32:AutoRun-BFB（Avast）/ Diliman.B（Avira）/ Win32.WowSub.4
（Dr.Web）/ AutoRun.AntiAV.T（ESET）/ Trojan-Dropper.Win32.Small（Ikarus）/ Trojan.Downloader.9fc（360）
简介：集合了磁碟机、AV终结者、中华吸血鬼、猫癣下载器为一体的混合病毒。
样本：https://wws.lanzoui.com/ivxNddojcle


11.Almanahe感染型病毒
MD5：0e5cde58af173fe7a35e6266f55c9091
中文名称：同上
英文名称：Virus.Win32.Almanahe.A（标准）
简介：本病毒拥有极强的反虚拟机和沙箱技术，且图标伪装效果和感染力很强，会感染exe和scr的大部分文件。
样本：https://wwx.lanzoui.com/iMR3Wqqtpvc




12.ttry蠕虫病毒/incaseformat蠕虫病毒
MD5：dac5f1e894b500e6e467ae5d43b7ae3e


MD5（现爆发样本）：915178156c8caa25b548484c97dd19c1
中文名称：同上
英文名称：Worm.Win32.AutoRun.xxx（标准）
简介：老蠕虫样本，因为代码设定失误，导致原本删除文件的时间被拖后至最近一段时间。
详细分析：https://x.threatbook.cn/nodev4/vb4/article?threatInfoID=3157
样本：https://wws.lanzoui.com/iItGtdpw9wb
样本（现爆发样本）：https://wwx.lanzoux.com/ia6VPki78ha


13.Neshta感染型病毒

MD5：36fd5e09c417c767a952b4609d73a54b
中文名称：同上
英文名称：Virus.Win32.Neshta.A（标准）
简介：会在系统%SystemRoot%目录下释放svchost.com文件，并通过添加注册表的方式确保每个exe文件执行的时候都会先执行这个文件。该病毒还会收集系统信息发送到远程服务器上，如当前安装的软件列表，当前运行的软件列表，以及SMTP邮件账号等。
样本：https://wwx.lanzoux.com/i3NtGif5waf



14.Synaptics感染型病毒
MD5：52edba919646dc8bffb9db9bfd95bbfd
中文名称：同上
英文名称：Virus.Win32.Synaptics.A（标准）
简介：会拦截用户新建Excel文档或者打开Excel文档的行为，并将新建或者打开的Excel文档替换成带有恶意宏代码的文档。
样本：https://wws.lanzoui.com/iluXodpxata


15.Floxif感染型病毒
MD5：8a9ea9c338e14cf0921ca9fe483b5b02
MD5（源文件）：836dbce15f1dfaad3df9f28b24047b41
中文名称：同上
英文名称：Virus.Win32.Floxif / Pioneer.A（标准）
简介：标记了360的数字签名并伪装成360网盾辅助程序，感染可执行文件(.exe)和动态链接库(.dll)文件。
样本：https://wws.lanzoui.com/iDl7wdpxtxi
样本（源文件）：https://wwx.lanzoux.com/i47zAki78jc


16.Cridex蠕虫病毒
MD5：78cc821b5acfc017c855bc7060479f84
中文名称：同上
英文名称：Worm.Win32.Cridex（标准）
简介：能注入explorer。
样本：https://wws.lanzoui.com/iu473dpycdc

17.TYJ蠕虫病毒

MD5：59678e7ed89c0935d61ba0d2249ef10c
中文名称：同上
英文名称：Worm.VBS.TYJ（标准）/ VBS.Dunihi（标准）
简介：兼有蠕虫传播和后门的功能。
样本：https://wws.lanzoui.com/iyXJYfbt53i


18.文件夹蠕虫病毒
MD5：c25ce8475a0ada1b8fbdf8078bf30c1f
中文名称：同上
英文名称：Worm.Win32.Scar（标准）
简介：禁用注册表，任务管理器，所有文件夹变成exe格式，每个盘里有auto文件并自动运行病毒，感染U盘右击打开没用照样感染。
样本：https://www.lanzoux.com/ifaCJfbt54j


19.acad盗图病毒
MD5：802daed715df692cc4f65812ca11795f
中文名称：同上
英文名称：Worm.Win32.ACAD（标准）
简介：专性感染.lsp文件，对电脑本身没有危害，但会危害相关的图片文件。
样本：https://www.lanzoux.com/iEYgpfbtx6j

20.Dorkbot蠕虫病毒
MD5：0d4b7f4c1731c91dff56afce0ecf37c5    98f74b530d4ebf6850c4bc193c558a98
中文名称：同上
英文名称：Worm.Win32.Dorkbot（标准）/ Trojan.Agent.AWYO/ Worm.Win32.Bublik（标准）/ Win32.Trojan.f77（360）/ Trojan.Win32.Bublik.iza（卡巴）
简介：https://www.freebuf.com/articles/network/162324.html （最早可追溯至2012年）
样本：https://www.lanzoux.com/ilQd8h42cgb

21.Sality感染型病毒
MD5：55bfee3915ae84f38fda750587868ae7
MD5（源文件）：bf8af7b28ba7b27fd961b7192ca4a7c3
中文名称：同上
英文名称：Virus.Win32.Sality.A（标准）
简介：Sality家族最早于2003年被发现，随着多年的发展，Sality病毒已逐渐变得愈加顽固，其主要恶意代码体可实现动态、持久、功能齐全的病毒行为。比较新的Sality病毒变种，甚至采用了大量的rootkit技术，以隐藏自己和对抗杀毒产品。病毒运行后，会终止安全相关软件和服务，感染系统内的exe和scr文件。并且注入病毒线程到所有进程中，在后台下载病毒到系统。同时它创建自身拷贝到可移动设备或者网络共享中，以达到传播的目的。此外，部分病毒变种还会收集被感染系统信息，并发送的到指定的网址。
样本：https://www.lanzoux.com/iVzRyh42tna
样本（源文件）：https://wwx.lanzoui.com/i3ggvlkf7zi


22.Conficker蠕虫病毒
MD5：c9e0917fe3231a652c014ad76b55b26a
MD5：1db5476c766555c9995b25d19f97b9bc（源文件）
中文名称：飞客病毒
英文名称：Worm.Win32.Conficker.A（标准）
简介：Conflicker病毒于2008年10月爆发，利用Windows系统的已知MS08-067漏洞大肆传播，甚至能够利用U盘、网络共享等方式传播，当Conflicker病毒进入系统后，首先破坏系统中的默认属性设置，接着会自动搜索局域网内有漏洞的其他电脑，一旦发现存在漏洞的计算机系统，就会激活该漏洞并同感染系统创建链接，最后进行远程感染。

样本：https://www.lanzoux.com/id9jRh42d1c
样本（源文件）：https://wwx.lanzoux.com/ivvLpjznv1e

23.Babonock蠕虫病毒
MD5：8b5c2cbf7d89be0a6eb66ecc29d9f5fd
中文名称：同上
英文名称：Worm.Win32.Babonock.A（标准）
简介：通过U盘传播的老蠕虫病毒。
样本：https://www.lanzoux.com/i2YjWh42cqb

24.愤怒天使感染型病毒
MD5：aec931e484f13e7a89fc9f9d24242546
中文名称：同上
英文名称：Virus.Win32.Madang.A（标准）
简介：病毒会搜索系统中所有磁盘分区中的可执行文件，将其感染，受到感染的可执行文件大小会变大，占用磁盘空间会增大，并且无法正常使用。另外，在病毒感染可执行文件的这个过程中，病毒会给每个受感染的文件做标记，以避免文件被重复感染。
样本：https://wwx.lanzoux.com/ic2tiif5wbg

25.红色代码蠕虫病毒
MD5：6f5767ec5a9cc6f7d195dde3c3939120
中文名称：同上
英文名称：Net-IISWorm.Win32.CodeRed.A（标准）
简介：采用"缓存区溢出"的黑客技术， 利用微软IIS的漏洞进行病毒的感染和传播。该病毒利用HTTP协议, 向IIS服务器的端口80发送一条含有大量乱码的GET请求，目的是造成该系统缓存区溢出， 获得超级用户权限，然后继续使用HTTP 向该系统送出ROOT.EXE木马程序，并在该系统运行，使病毒可以在该系统内存驻留， 并继续感染其他IIS系统。Code Red 在向侵害对象发送GET 乱码时，总是在乱码前加上一个后缀为.ida的文件名，表示它正在请求该文件， 这是红色代码的重要特征。
样本：https://wwx.lanzoux.com/ihfSoif5wdi

26.蓝色代码蠕虫病毒

MD5：d9f17e5c44f981fe11293a607151fc0e:
中文名称：同上
英文名称：Net-Worm.Win32.BlueCode.A（标准）


简介：攻击微软inetifo.exe程序的漏洞，并植入名为SvcHost.EXE的黑客程序运行，该蠕虫病毒将在服务器内存中不断地生成新的线程，最终导致系统运行缓慢，甚至瘫痪。
样本：https://wwx.lanzoux.com/iri0Eifbrij


27.Happy99蠕虫病毒
MD5：162c41323e23af3a3913caf716b189da
中文名称：同上
英文名称：Email-Worm.Win32.Happy.A/Ska.A（标准）
简介：主要以邮件的形式传递，或者从一些程序组中下载到硬盘。执行后，会在打开的窗口上看到一幅节日烟火彩色画面，标题为“Happy New Year 1999！！”。当发送邮件时，另一封邮件也悄悄地发到相同的地址上。邮件中没有文字，只有一个附件：Happy99.exe，它可以使您无法正常收发邮件，直至整个邮件系统瘫痪。 该病毒是一个32位的蠕虫程序。执行Happy99.exe后，会在WINDOWS的系统目录下(SYSTEM目录)创建文件：SKA.EXE和SKA.DLL，其中SKA.EXE 是Happy99.exe的拷贝，而SKA.DLL则被压缩在SKA.EXE文件中。与此同时，将WSOCK32.DLL改名为WSOCK32.SKA，并生成一个与原来WSOCK32.DLL文件大小一致的文件。
样本：https://wwx.lanzoux.com/i9eGbif5wfa


28.Toal蠕虫病毒
MD5：153c98a99367c3971ae3d1648b1b6fa1
中文名称：本拉登病毒
英文名称：Worm.Win32.Toal.A/ Win32.InvictusDLL（标准）
简介：自动与ICQ网络相连，借助自身携带的黑客工具寻找电子邮件地址，确定感染对象后就不断进行自我复制并自动传播，染毒文件的急剧增多会导致计算机运行速度越来越慢，最终导致系统瘫痪。


样本：https://wwx.lanzoux.com/iFyv2jrtx3g


29.Nimda蠕虫病毒
MD5：642a393a5c65d202180df5af06f29c5a
中文名称：同上
英文名称：Net-Worm.Win32.Nimda（标准）
简介：通过email、共享网络资源、IIS服务器、网页浏览传播，修改本地驱动器上的.htm，.html和.asp文件。此病毒可以使IE和Outlook Express加载产生readme.eml病毒文件。
样本：https://wwx.lanzoux.com/iRZDEjbpq9a

30.Zippedfiles蠕虫病毒
MD5：0e10993050e5ed199e90f7372259e44b
中文名称：同上
英文名称：Email-Worm.Win32.ZippedFiles/Explorezip.A（标准）
简介：病毒自身被执行后进入系统，在当前邮件收件箱中寻找邮件地址，然后将自身复制，以邮件附件的形式随邮件信息发送到已找到的邮件地址： Hi <Name of Recipient>!, I received your email and I shall send you a reply ASAP. Till then, take a look at the attached zipped docs. Bye 用户收到如上好像回复信息的邮件，用户名在首列，邮件主题是随机的，但是通常邮件主题是以前发送的email主题。附件使用Winzip图标显示。 病毒进入系统（在Windows95/98或NT的32位操作系统中）运行后，生成SETUP.EXE文件（在Windows目录）和EXPLORE.EXE文件（在WINDOWS\SYSTEM目录）。
样本：https://wwx.lanzoux.com/iyLuCjbpq6h

31.Marburg感染型病毒
MD5：e8e0f1f5305718a03432a09fe38ab007
MD5（源文件）：36acd261d4427e521819cc97f672c4e5
中文名称：同上
英文名称：Virus.Win9x.Marburg.A（标准）
简介：它会自动删除象CHKLIST.MS等MSAV，CPAV在子目录下生成完整性检查的文件，并会自动侦测SCAN，F-PORT等杀毒软件，并躲避它们的检测，对于含有V字母的文件它也不做感染。它的发作条件是文件被感染3个月以后，当你运行这个被感染的可执行文件的时间，如果与此文件的第一次被感染的时间是相同的小时，屏幕上就随机出现的红色圆圈，它的变种还会在WINDOWS下的破坏硬盘文件系统。
样本：https://wwx.lanzoux.com/imIJyjbqfef
样本（源文件）：https://wwx.lanzoui.com/ivWy4wd8dxe


32.Assarm蠕虫病毒
MD5：e3e151ac16581fec619c0d7ae4fba29f
中文名称：同上
英文名称：Email-Worm.Win32.Assarm.A（标准）
简介：此邮件蠕虫会回复Outlook邮件箱中的未读邮件，但假如是周一或周四并且当天的小时数大于5，病毒不会发送邮件。
样本：https://wwx.lanzoux.com/iMNBQjbqn3c

33.3DStars蠕虫病毒
MD5：d738768613c52557157d90c701cecc5e
中文名称：同上
英文名称：Email-Worm.Win32.3DStars.A/B（标准）
简介：暂无。
样本：https://wwx.lanzoux.com/i4zkqjbpqub

34.SmackinBird蠕虫病毒
MD5：30088199a7aeeacbba1b9302c94a5c14
中文名称：同上
英文名称：Worm.JS.SmackinBird.A（标准）
简介：暂无。
样本：https://wwx.lanzoux.com/i4mA4jbpqsj


35.Newley蠕虫病毒
MD5：16f3f44b710ae19f67584917eaca369c
中文名称：同上
英文名称：Worm.VBS.Newley.A（标准）
简介：暂无。
样本：https://wwx.lanzoux.com/iNaJTjbpqri


36.Mydoom蠕虫病毒
MD5：53df39092394741514bc050f3d6a06a9
中文名称：同上
英文名称：Email-Worm.Win32.Mydoom.A（标准）
简介：当用户打开并运行附件内的病毒程序后，病毒就会以用户信箱内的电子邮件地址为目标，伪造邮件的源地址，向外发送大量带有病毒附件的电子邮件，同时在用户主机上留下可以上载并执行任意代码的后门。此病毒本在2004年爆发，但至今仍然十分活跃。
样本：https://wwx.lanzoux.com/iGp0Njbpq7i

37.Bugbear蠕虫病毒
MD5：36acd261d4427e521819cc97f672c4e5
中文名称：怪物病毒
英文名称：Email-Worm.Win32.Tanatos/Bugbear.A（标准）
简介：监控电脑用户的键盘动作，并截获用户的登录名和密码；修改注册表，电脑用户开机时病毒被自动启动。会自动搜索并杀掉它知道的反病毒软件的进程；向外界病毒客户端发送被感染用户的机密信息：如用户名和密码等等。并且，“怪物”病毒会攻击打印机，只要它找到打印机或者网络打印机！就会随机打印二进制代码！
同时，“怪物”病毒具有极强的传播能力。它会利用局域网进行传播，只要是能找到的资源，都会被“怪物”感染，这些被感染的机器只要一启动，病毒就会随之启动。
样本：https://wwx.lanzoux.com/iNwhLjbpq5g

38.Bagle蠕虫病毒
MD5：e65d7ab639a2361493d388e36d1e663a
中文名称：同上
英文名称：Email-Worm.Win32.Bagle.A（标准）
简介：感染了一台计算机之后，便在其TCP端口开启一个后门，远程用户和应用程序利用这个后门得到受感染系统上的数据(包括金融和个人信息在内的任何数据)访问权限。据2005年4月，据一篇文章称，这种蠕虫“通常被那帮为了扬名而不惜一切手段的黑客们称为‘通过恶意软件获利运动’的始作俑者”。
样本：https://wwx.lanzoux.com/iGRocjbpq4f

39.Klez蠕虫病毒   

MD5：f95981829ca660e84f1d33bdfa9e2a28
中文名称：求职信病毒
英文名称：Email-Worm.Win32.Klez.A（标准）
简介：被感染消息的题目与附件的名字是可变的，它利用了一个IE已知的安全漏洞(IFRAME vulnerability)，当一个已经被感染的消息打开时，他将自动启动。它不仅在本地的网络散布并且通过电子邮件消息传播。它会在WINDOWS临时文件夹下建立一个可执行文件，名字为以字母K开头的随意一个的名字( 如KB180.exe )然后把“ Win32.Klez ”病毒写进去，并且启动该病毒。这个病毒在所有可利用的计算机的磁盘上感染大部分的WIN32下的PE格式的可执行程序。
当一个已经感染的文件被启动，这个WORM把自己的一个副本复制到WINDOWNS系统文件夹下，命名为“krn132.exe”，他会把如下键值写入注册表（如下）并且随WINDOWNS一起启动。
    注：邮件正文如下：
I'm sorry to do so,but it's helpless to say sorry. I want a good job,I must support my parents. Now you have seen my technical capabilities. How much my year-salary now? NO more than $5,500. What do you think of this fact? Don't call my names,I have no hostility. Can you help me?
    此内容与求职有关，故被称为“求职信病毒”。
样本：https://wwx.lanzoui.com/i30kLl4tezi



40.火焰蠕虫病毒
MD5：bb5441af1e1741fca600e9c433cb1550
中文名称：同上
英文名称：Worm.Win32.Flame.A/B（标准）
简介：   火焰病毒和熊猫烧香一样也是一种经过多次变种的“蠕虫病毒”变种，2005年10月9日开始肆虐网络，它主要通过下载的档案传染。对计算机程序、系统破坏严重，2007年蔓延全世界，2014年1月被WEB信息安全团队封杀。
          “火焰”病毒的全名为Worm.Win32.Flame，它是一种后门程序和木马病毒，同时又具有蠕虫病毒的特点。只要其背后的操控者发出指令，它就能在网络、移动设备中进行自我复制。一旦电脑系统被感染，病毒将开始一系列复杂的行动，包括监测网络流量、获取截屏画面、记录音频对话、截获键盘输入等。被感染系统中所有的数据都能通过链接传到病毒指定的服务器，让操控者一目了然。据卡巴斯基实验室统计，迄今发现感染该病毒的案例已有500多起，其中主要发生在伊朗、以色列和巴勒斯坦。苏丹、叙利亚、黎巴嫩、沙特阿拉伯、埃及和中国（家庭电脑较多）等国也有个别案例。
        “  火焰”设计极为复杂，能够避过100种防毒软件。感染该病毒的电脑将自动分析自己的网络流量规律，自动录音，记录用户密码和键盘敲击规律，将用户浏览网页、通讯通话、账号密码以至键盘输入等纪录及其他重要文件发送给远程操控病毒的服务器，被认为是迄今为止发现的最大规模和最为复杂的网络攻击病毒。
样本：https://wwx.lanzoui.com/i0vJ1ki76ne



注：火焰病毒因上图中这段代码中的Flame而得名。

41.Sobig蠕虫病毒
MD5：100018b06a74ab304261211ab11d4252
中文名称：巨无霸病毒
英文名称：Email-Worm.Win32.Sobig.A（标准）
简介：通过局域网传播，查找局域网上的所有计算机，并试图将自身写入网上各计算机的启动目录中以进行自启动。该病毒一旦运行，在计算机联网的状态下，就会自动每隔两小时到某一指定网址下载病毒，同时它会查找电脑硬盘上所有邮件地址，向这些地址发送标题如："Re: Movies"、"Re: Sample"等字样的病毒邮件进行邮件传播，该病毒还会每隔两小时到指定网址下载病毒，并将用户的隐私发到指定的邮箱。由于邮件内容的一部分是来自于被感染电脑中的资料，因此有可能泄漏用户的机密文件。
样本：https://wwx.lanzoui.com/igY5Olistcd

42.超级工厂蠕虫病毒
MD5：74ddc49a7c121a61b8d06c03f92d0c13/055a3421813caf77e1387ff77b2e2e28
中文名称：同上
英文名称：Worm.Win32.Stuxnet.A/B（标准）
简介：Stuxnet又名“震网”，是针对微软系统以及西门子工业系统的最新病毒，目前已感染多个国家及地区的工业系统和个人用户，此病毒可通过网络传播，与以往病毒不同，其代码非常精密 　曾造成伊朗核电站推迟发电的全球首个“超级工厂病毒”Stuxnet目前已经侵入我国。瑞星12年9月25日发布的预警显示，国内已有近500万网民及多个行业的领军企业遭Stuxnet蠕虫病毒攻击，而且由于安全制度上的缺失，该病毒还存在很高的大规模传播风险。 　
         据瑞星安全专家介绍，Stuxnet蠕虫病毒是世界上首个专门针对工业控制系统编写的破坏性病毒，能够利用对windows系统和西门子SIMATIC WinCC系统的7个漏洞进行攻击。特别是针对西门子公司的SIMATIC WinCC监控与数据采集 (SCADA) 系统进行攻击，由于该系统在我国的多个重要行业应用广泛，被用来进行钢铁、电力、能源、化工等重要行业的人机交互与监控。 　
        Stuxnet及其变种是一种利用最新的Windows Shell漏洞传播恶意文件的蠕虫。造成这个漏洞的原因是Windows 错误地分析快捷方式，当用户单击特制快捷方式的显示图标时可能执行恶意代码（文件带有.LNK扩展名）。
样本：https://wwx.lanzoui.com/izUxzlit0ra








43.Magistr蠕虫病毒

MD5：ca3a810e952f642bf88a8370c88bd072
中文名称：马吉斯病毒
英文名称：Email-Worm.Win32.Magistr.A（标准）
简介：能够感染WIN95/98/ME系统，并且具有既是病毒又具有蠕虫的特性，与以往众多的病毒通过邮件方式传播有所不同，“马吉斯”除了以电子邮件附件形式传播，还可以以复制文件形式传播。病毒会自动搜索Outlook和Netscape邮箱中的地址簿，并将所有地址保存在Windows目录下Username.Dat文件中，其中Username是机器名。
样本：https://wwx.lanzoui.com/inHTcmaiqkb

44.Tenga蠕虫病毒
MD5：a87c41fd395221baa23f368d7e17da55
中文名称：同上
英文名称：Worm.Win32.Tenga / Gael.3666.A（标准）
简介：病毒特性：Win32.Gael.3666.A是一种感染Win32.PE文件的病毒，将自身附加到原始文件上。         
感染方式：执行时，Gael.3666.A在本地系统中扫描所有文件，并感染找到的Windows PE文件。病毒生成一个名为"CBACK_GAELICUM"的互斥体，以避免病毒的多个副本同时运行。
          传播方式:通过文件感染/网络共享传播，同时在139端口扫描任意IP地址，传播到远程机器，并感染机器上共享中的目标文件。
          危害：下载并运行任意文件：病毒尝试从utenti.lycos.it域下载dl.exe文件文件，并运行它。这个文件被检测出是Win32.Gael!downloader病毒。这个文件，依次从同一个域下载并运行另外两个文件：
§ <root>\GAELICUM.EXE – 一个病毒副本
§ < root>\CBACK.EXE – 后门部分(这个文件检测出是Win32.Gael.A 病毒)
          后门功能：CBACK.EXE  在4321端口打开一个后门，利用Windows command prompt命令从远程机器上接受并运行command命令。它还会发送一个消息，包含打开的端口号，发送到vx9.users.freebsd.at 。
样本：https://wwx.lanzoui.com/iynFgmajq5c

45.Virut感染型病毒

MD5：606a95b422c08c106744a6e312413aab
中文名称：同上
英文名称：Virus.Win32.Virut.A（标准）
简介：感染Virut的主机意味着全盘大部分的可执行文件（主要是exe和scr），以及大量的HTML文档，都会被恶意修改，以追加恶意代码。所以，受感染主机本地的任何一个软件应用，一打开极可能触发Virut运行起来。      Virut的目的在于长期利用受害者主机，窃取用户重要信息，下载并给用户安装不必要的流氓或恶意软件，以赚取软件安装费用，也可做为DDoS终端、发垃圾或钓鱼邮件、成为跳板做欺诈等违法行为。
      详细分析：https://www.cnblogs.com/Mikhail/p/5615286.html
样本：https://wwx.lanzoui.com/iJUQnw3ydre




46.Partie感染型病毒
MD5：cd86b04047ba72d5a4629806d274ad1e
中文名称：同上
英文名称：Virus.Win32.Parite.A（标准）
简介：病毒程序用C++编写，组成的组件是由汇编程序编写的，感染的文件运行后，直接控制病毒生成文件使其将病毒文件写为临时文件并执行它的感染程序，并在逻辑硬盘和局域网里的共享目录里搜索所有.scr和.exe类型的Win32 PE格式文件进行感染。运行时，病毒会附加在Explorer.exe文件上驻留内存。
详细分析：https://blog.csdn.net/weixin_44156885/article/details/111801932
样本：https://wwx.lanzoui.com/i5KEvmajqna



47.HIV感染型病毒
MD5：72ba9635c92450c85c556739ae78507a
中文名称：同上（不是人体免疫缺陷病毒！！）
英文名称：Virus.Win32.HIV.6xxx
简介：此病毒因其提示中含有“这个细胞已经感染HIV”而得名。
          这是一种危险的每进程内存驻留 Win32 病毒，它感染 PE EXE 文件（Windows 应用程序）和 MSI 存档，从 Internet"升级"自身，并拥有电子邮件传播能力。该病毒经过加密，并使用"入口点遮挡"技术将自己隐藏在受感染的文件中。该病毒的长度约为6K（故病毒英文名称后面的数字即为它的感染长度）。该病毒使用反调试技巧，如果系统中检测到 SoftICE 或其他调试器，则会使计算机停止。该病毒还会尝试禁用 Windows 文件保护。为此，它会感染负责文件保护的系统文件：它会覆盖 DEFAILT。包含空数据的 SFC 文件（在 Win98 下）或 SFCFILES.DLL（在 Win2000 下）。此技巧应该在 Win98 下有效，而在 Win2000 下不应有效，因为 Win2000 系统会阻止对 SFCFILES .DLL的访问，或立即从备份中还原它。
         病毒会在当前目录中查找.EXE 文件并感染它们，并将自身写入文件末尾。为了获得控制，病毒不会修改程序启动地址，而是查找标准程序子例程页眉/页脚，并使用JMP_Virus指令修补页脚。因此，病毒无法在运行受感染文件时激活，而是在执行受感染例程时（当相应的分支获得控制时）激活。然后，病毒作为受感染程序的组件保留在内存中，挂接多个文件访问功能，并感染受感染程序访问的 EXE 文件。因此，病毒在Windows内存中处于活动状态，直到受感染的应用程序终止为止。在某些情况下，在NTFS计算机上运行时，病毒会在受感染的文件中创建一个具有"：HIV"名称（"filename.ext：HIV"）的附加NTFS流（ADS），并在那里写入以下"版权"文本：“这个细胞已经感染了HIV病毒，产生：0xNNNNNNNNNN”，其中 NNNNNNNN 是病毒"生成"编号。
        详细分析：https://threats.kaspersky.com/en/threat/Virus.Win32.HIV/
样本：https://wwi.lanzouo.com/i0aFNylg8va

48.中国黑客蠕虫病毒
MD5：bd587a60707832a5ebba769aa919bfe8
中文名称：同上
英文名称：Email-Worm.Win32.Runouce.A / Worm.Win32.Chir.A
简介：该病毒不会感染可执行文件。病毒在被激活的过程中会把病毒体自身复制到 windows 的系统目录中，在windows 9x 系统中复制自身到 windows\system\runouce.exe，在windows 2000和 windows NT系统中复制自身到winnt\system32\runouce.exe，然后运行该程序，并且在注册表中加入成自启动，使病毒体每次开机时都被激活。在windows 98 与windows 95的系统中的偏移地址是 bff70400处。从而病毒通过CreateKernelThread函数建立一个内核线程，该线程的入口地址就是bff70400。这个内核线程调用了WaitForSingleObject函数使自身进入等待状态，来等待父进程的结束信号。如果父进程被结束，则该内核线程立即被唤醒。内核线程马上调用了WinExec函数，来重新启动病毒进程。这样，在杀毒软件杀掉内存中的病毒进程后。病毒马上又被激活。这样造成杀不掉内存中的病毒。在windows 2000操作系统上在explorer中注入线程。在explorer中的线程用来保护病毒进程。如果病毒进程结束，则explorer中的病毒线程重新启动病毒进程。
            病毒通过以上的方法来起到在内存中保护病毒进程的作用。同时病毒通过邮件传染，具备自启动功能，并能够十分有效地利用局域网进行传播。一旦它进入局域网中的某台机器，就会立刻在“网上邻居”中搜索共享文件夹。只要搜索到某个可写共享文件夹，就会生成以被感染机器名开头的.eml文件，因此最后导致局域网的所有机器都成为病毒邮件的“发送基地”。
样本：https://wwa.lanzouv.com/icftg00grhhi
样本（中国黑客2蠕虫病毒，即B变种）：https://wwa.lanzouv.com/icTcv00grhij



49.Naked蠕虫病毒
MD5:9acd3a3298fc73f29cc013f60d5ac433
英文名称：Email-Worm.Win32.Naked（标准）
简介：这是一种 Internet蠕虫病毒，通过受感染的计算机发送受感染的邮件进行传播。在传播时，该蠕虫使用 MS Outlook，并将自身发送到存储在 MS Outlook 通讯簿中的所有地址。蠕虫本身是一个长度约为70K的Win32应用程序，用VisualBasic编写。该病毒不会将自己安装到系统中，也不会触及系统注册表（即不会在其中注册自己）。这是一种"直接操作"的病毒，只有在从受感染邮件中被激活时才会执行其操作。蠕虫会将自身复制到 Windows TEMP 目录，但不使用该副本。运行时，蠕虫会显示一个假窗口，其中包含"Macromedia Flash Player"图片，并显示"正在加载"、"正在加载..."、"正在加载..."——该消息会无限循环。
           窗口中的菜单在被选中时不会调用任何操作，但"帮助"菜单除外。选择它后，"关于Macromedia Flash Player 5..."出现项，当选择该项目时，蠕虫会显示消息框：


蠕虫以电子邮件形式发送自身，并附加了作为蠕虫本身的 EXE 文件。该消息包括：
Attached file name: NakedWife.exe
The Subject: Fw: Naked Wife
Message body:

My wife never look like that! &#128521;

Best Regards,
[CurrentUser]

详细分析：https://threats.kaspersky.com/en/threat/Email-Worm.Win32.Naked/
样本：https://wwi.lanzoup.com/irrq2019rz8b


50.Jeefo感染型病毒
MD5：9e3c13b6556d5636b745d3e466d47467
英文名称：Virus.Win32.Jeefo/Hidrag.A（标准）
简介：该病毒会驻留在内存中，感染32位的exe文件。当病毒运行时，它会创建一个大小约为36K的自身副本，并使用名称svchost.exe将其放置在Windows目录中。接下来病毒则会在系统注册表中注册此文件自动运行项，以活跃状态从C盘开始寻找exe文件并进行感染，整个过程没有明显的表露痕迹。
详细分析：https://www.microsoft.com/en-us/ ... Virus:Win32/Jeefo.A
样本：https://wwi.lanzoup.com/iqu5Q01tuhbe



51.Pikachu蠕虫病毒
MD5：715614e09261b39dfa439fa1326c0cec
英文名称：Email-Worm.Win32.Pikachu.A / Worm.Win32.Pokey.A（标准）
简介：这是一种通过使用 Microsoft Outlook 在互联网上传播的蠕虫，它是用Visual Basic 6.0编写的。它通过电子邮件作为一封信发送，并附有PikachuPokemon.exe。
          当蠕虫启动时，它会将原始 .bat 文件的内容替换为销毁 Windows 主目录和系统目录中的文件的命令。然后，蠕虫会扫描 Microsoft Outlook 通讯簿，并在“发件箱”文件夹中为它遇到的每个地址创建以下邮件：

          在每个字母上，蠕虫以文件“PikachuPokemon.exe”的形式附着自己。因此，每个收到此类信件并无意中启动附件的人都会从通讯簿中向每个收件人发送蠕虫的副本。
样本：https://wwi.lanzoup.com/iH0kq03yrjuj

52.NetSky蠕虫病毒
MD5:e252e39c7b29e56da73ceef8d47fe073
中文名称：天极蠕虫病毒
英文名称：Email-Worm.Win32.Netsky.A（标准）
简介：该病毒于2004年2月16日出现，2月18日出现的B变种具有很大的传播性，后来一位名叫 Sven Jaschan的人被逮捕后承认他创作了NetSky和Sasser蠕虫病毒，出狱后他重新获得了安全行业的工作。有趣的是，NetSky蠕虫病毒的一些其它变种代码中出现了大量侮辱Bagle和Mydoom蠕虫病毒作者的话语，部分变种甚至会查找并移除这两种蠕虫病毒。
          该病毒最初是在众多种子电子邮件中发送的，它会在附加到电子邮件的 ZIP 存档文件中传播自身或作为可执行附件传播，还会将自身复制到所有可用驱动器的共享文件夹中，使其能够在点对点（P2P）和本地网络中传播。当该蠕虫运行时，首先会弹出虚假提示框：
      
然后该蠕虫使用 SERVICES.EXE 名称将自身复制到 Windows 目录，并在系统注册表中为此文件创建启动项。如果蠕虫找到具有“共享”或“共享”名称的文件夹，它将自身复制到该文件夹并改名为一些诱导人打开的文件。如果互联网可用，则蠕虫以电子邮件的形式发出，诱使收件人打开附件。打开后，附加的程序将扫描计算机中的电子邮件地址，并将电子邮件本身发送到找到的所有地址。
    由于该蠕虫附加在许多非法下载音乐的途径中，故Boris Daenen（艺名NetSky）以自己的艺名命名该蠕虫病毒，后沿用至今。
样本：https://wwi.lanzoup.com/iOsvg06sfq1c


三.勒索病毒类


1.WannaCry勒索病毒
MD5：84c82835a5d21bbcf75a61706d8ab549（VT评论多）
MD5：db349b97c37d22f5ea1d1841e3c89eb4（VT评论多）
中文名称：同上
英文名称：Ransom.Win32.WannaCryptor（标准）/ Win32/Trojan.Multi.daf（360）
简介：  勒索病毒界宗师级样本，可以这样说，WannaCry的出现，直接促使了勒索病毒朝着专业化和利益化的方向开始“大规模”发展。
            WannaCry是一种“蠕虫式”的勒索病毒软件（兼有蠕虫的特征，但本质是勒索病毒），利用“EternalBlue”（永恒之蓝）进行传播，以获得自动传播的能力，能够在数小时内感染一个系统内的全部电脑。勒索病毒被漏洞远程执行后，会从资源文件夹下释放一个压缩包，此压缩包会在内存中通过密码：WNcry@2ol7解密并释放文件。这些文件包含了后续弹出勒索框的exe，桌面背景图片的bmp，包含各国语言的勒索字体，还有辅助攻击的两个exe文件。这些文件会释放到了本地目录，并设置为隐藏。（注释：说明一下，“永恒之蓝”是NSA泄露的漏洞利用工具的名称，并不是该病毒的名称#。永恒之蓝”是指NSA泄露的危险漏洞“EternalBlue”，此次的勒索病毒WannaCry是利用该漏洞进行传播的，当然还可能有其他病毒也通过“永恒之蓝”这个漏洞传播。）
            当被该勒索软件入侵后，用户主机系统内的照片、图片、文档、音频、视频等几乎所有类型的文件都将被加密，加密文件的后缀名被统一修改为．WNCRY，并会在桌面弹出勒索对话框，要求受害者支付价值数百美元的比特币到攻击者的比特币钱包，且赎金金额还会随着时间的推移而增加。
样本：https://wwx.lanzoux.com/iXXfjjzmsgf


2.WannaRen勒索病毒
MD5：1de73f49db23cf5cc6e06f47767f7fda
中文名称：同上
英文名称：Ransom.Win32.WannaRen（标准）
简介：  2020年4月，勒索病毒“WannaRen”开始传播，大部分杀毒软件无法拦截，其会加密Windows系统中几乎所有文件，后缀为.WannaRen，赎金为0.05个比特币。
但戏剧性的是，在病毒爆发后不久勒索病毒作者（由易语言等基本确定是国人编写）竟然主动“自首”，将解密密钥发给了一位火绒用户，并要求用户转发给火绒安全实验室，火绒安全收到密钥后紧急制作解密工具。
            2020年4月9日，火绒安全成功制作解密工具，随后“WannaRen”勒索病毒停止传播。
详细报告：http://blog.nsfocus.net/wannaren-report-0409/
样本：https://wwx.lanzoux.com/ihTkcjzmspe


3.Petya勒索病毒
MD5：71b6a493388e7d0b40c83ce903bc6b04
中文名称：同上
英文名称：Ransom.Win32.Petya（标准）
简介：http://it.rising.com.cn/dongtai/18902.html（分析报告）
PS：据虚拟机实验发现，Petya在“磁盘修复”过程中，其实并没有锁住文件。
样本：https://wwx.lanzoux.com/iudX8jzmssh



——————————————————2019十大勒索病毒专题系列————————————————

注：本排名源自腾讯云盘点，由于勒索病毒变种太多且各个杀软报毒高度不统一，故命名时只取最接近广泛认可的报毒名称。



4.Stop/Keypass勒索病毒
MD5：c4391b3b073bb1354afef0f1260b8fb8 / cd8c86863628f4d0c7f54fc3350fb1d9
中文名称：同上
英文名称：Ransom:Win32/STOP.BS!MTB（Microsoft）/ Ransom.Win32.Keypass.A（Microsoft）
简介：该版本病毒相比较于18年11月份开始活跃的DATAWAIT版本，在加密算法和病毒模块有了变化，由于该版本的stop勒索病毒在其基础设施工作正常、联网稳定情况下加密后的文件暂无法解密，我们提醒各政企机构注意防范。
          Stop勒索病毒家族在国内主要通过软件捆绑，垃圾邮件等方式进行传播，加密时通常需要下载其它病毒辅助工作模块。Stop勒索病毒会留下名为_readme.txt的勒索说明文档，勒索980美元，并声称72小时内联系病毒作者将获得50%费用减免。
          Stop勒索病毒还具有以下特性：
1.    加密时，禁用任务管理器、禁用Windows Defender、关闭Windows Defender的实时监控功能 ；（衍生物，如下图所示）





2.    通过修改hosts文件阻止系统访问全球范围内大量安全厂商的网站；
3.    因病毒执行加密时，会造成系统明显卡顿，为掩人耳目，病毒会弹出伪造的Windows 自动更新窗口；



4.    释放一个被人为修改后不显示界面的TeamViewer模块，用来实现对目标电脑的远程控制；
5.    下载AZORult窃密木马，以窃取用户浏览器、邮箱、多个聊天工具的用户名密码。




样本：https://wwx.lanzoui.com/iIcYHljspmf
样本（源文件）：https://wwx.lanzoui.com/iPNujlkf8mb


5.GandCrab勒索病毒
MD5：a635d6a35c2fc054042b6868ef52a0c3
中文名称：同上
英文名称：Ransom.Win32.GandCrab.A（Microsoft/ESET/TrendMicro/GData，标准） / Trojan.Win32.Jorik.sbl（卡巴） / Win32/Trojan.7c2（360）
简介：2018年1月，首次观察到GandCrab勒索病毒感染韩国公司。
          此后，该勒索病毒迅速在全球扩张，包括2018年初的美国受害者，至少8个关键基础设施部门受此影响。因此，GandCrab迅速成为最流行的勒索病毒。估计2018年中期，该勒索病毒已经占据勒索软件市场份额的50%。
          专家估计，GandCrab在全球范围感染超过500000名受害者，造成超过3亿美元的损失。它使用勒索软件即服务（RaaS）的商业模式运营，通过将恶意软件卖给购买勒索病毒服务的合作伙伴，来换取40％的赎金。
          从2018年1月到2019年6月，此勒索病毒多现多个不同的变种。2019年1月，此勒索病毒GandCrab5.1变种版本开始在全球流行，直到2019年6月1日，GandCrab勒索病毒运营团队宣布关闭他们的网站，并声称他们已经赚了20亿美元赎金。
          两周后，Bitdefender与欧州刑警组织、联邦调查局、众多执法部门以及NoMoreRansom机构合作，发布GandCrab勒索病毒的解密工具，可以适用于GandCrab1.0、4.0、5、5.2等版本，此勒索病毒的故事就此结束，加密后的文件，如下所示：


样本：https://wwx.lanzoui.com/iccNAljt1af

6.Sodinokibi勒索病毒
MD5：de35f0262c089cc880fe8cee5d6b0156
中文名称：同上
英文名称：Ransom.Win32.Sodinokibi（标准）
简介：Sodinokibi勒索病毒(也称REvil)，2019年5月24日首次在意大利被发现。          在意大利，它被发现使用RDP攻击方式进行传播感染。这款病毒也被称为GandCrab勒索病毒接班人。短短几个月，它就在全球大范围传播。这款勒索病毒与GandCrab存在很多关联。国外安全研究人员此前已经发布多篇关于这两款勒索病毒相关联的文章。
          Sodinokibi勒索病毒也是采用RaaS模式进行分发和营销，并采用一些免杀技术避免安全软件检测到。它主要利用Oracle WebLogic漏洞、Flash UAF漏洞、网络钓鱼邮件、RDP端口、漏洞利用工具包等方式发起攻击。


样本：https://wwx.lanzoui.com/iKsl2lkfhyh


7.GlobeImposter勒索病毒
MD5：e22638ce44a5f9faf9dd450438c1d492
中文名称：同上
英文名称：Ransom.Win32.GlobeImposter（标准）
简介：https://www.freebuf.com/articles/terminal/210641.html



样本：https://wwx.lanzoui.com/irYgNlkg1ad

8.Crysis勒索病毒

MD5：ebcdda10fdfaa38e417d25977546df4f
中文名称：同上
英文名称：Ransom.Win32.Crysis.A（ESET）/ Trojan-Ransom.Win32.Crusis.b（卡巴）/ Trojan:Win32/Casur.A!cl（Microsoft）
简介：CrySiS勒索病毒，又称Dharma，首次出现于2016年。
          2017年5月，此勒索病毒的万能密钥被公布后，之前样本可以解密，导致此勒索病毒曾消失一段时间，不过随后又马上出现其最新的变种样本，加密后缀为java。
          通过RDP暴力破解的方式进入受害者服务器加密勒索，此勒索病毒加密算法采用AES+RSA方式，导致加密后文件无法解密，在最近一年时间里，这款勒索病毒异常活跃，变种已经达到一百多个。



样本：https://wwx.lanzoui.com/ii186lo7xxi


9.Phobos勒索病毒MD5：f785b1a9a657aca7e70d16ac5effaabd
中文名称：同上
英文名称：Ransom.Win32.Phobos.A（Microsoft，ESET）
简介：https://www.antiy.com/response/20191016.html



样本：https://wwx.lanzoui.com/iHixElpd9oh


10.Ryuk勒索病毒
MD5：6cdcb9f86972efc4cfce4b06b6be053a
中文名称：同上
英文名称：Ransom.Win32.Ryuk（标准）
简介：Ryuk勒索病毒最早于2018年8月被发现，它由俄罗斯黑客团伙GrimSpider幕后操作运营。
          GrimSpider是一个网络犯罪集团，使用Ryuk勒索软件对大型企业及组织进行针对性攻击。C.R.A.M. TG Soft(反恶意软件研究中心)发现Ryuk勒索软件主要是通过利用其他恶意软件如Emotet或TrickBot等银行木马进行传播。
          Emotet和TrickBot银行木马主要用于盗取受害者银行网站登录凭据，同时充当下载器功能，提供下载其它勒索病毒服务。Emotet和TrickBot银行木马传播Ryuk勒索病毒，是因为TrickBot银行木马传播渠道的运营者是俄罗斯黑客团伙WIZARD SPIDER。而GRIM SPIDER是俄罗斯黑客团伙WIZARD SPIDER的部门之一。



样本：https://wwx.lanzoui.com/i8l8olpe4ih


11.Maze勒索病毒
MD5：f5ecda7dd8bb1c514f93c09cea8ae00d
中文名称：迷宫勒索病毒
英文名称：Ransom:Win32/Maze!MSR（Microsoft）/ Ransom.Win32.Maze.A（McAfee，ESET）
简介：Maze（迷宫）勒索病毒，又称Chacha勒索病毒，最早于2019年5月由Malwarebytes安全研究员发现。
          此勒索病毒主要通过各种漏洞利用工具包Fallout、Spelevo，伪装成合法加密货币交换应用程序的假冒站点或挂马网站等方式进行分发传播。最近一段时间里，Proofpoint安全研究人员发现一个新型的黑客组织TA2101，通过垃圾邮件的方式对德国、意大利、美国发起网络攻击，传播Maze(迷宫)勒索病毒。



样本：https://wwx.lanzoui.com/iG6E4lpeghi

12.Buran勒索病毒
MD5：e60e767e33acf49c02568a79d9cbdadd
中文名称：同上
英文名称：Ransom.Win32.Buran（标准）
简介：Buran勒索病毒首次出现于2019年5月，它是一款基于RaaS模式传播的新型勒索病毒。
          Buran在一个著名的俄罗斯论坛中销售。与其他基于RaaS勒索病毒获得30%-40%的收入不同，Buran勒索病毒的作者仅占感染产生的25%收入，安全研究人员认为Buran是Jumper勒索病毒的变种样本，同时VegaLocker勒索病毒是该家族最初的起源，由于其丰厚的利润，使其迅速开始在全球传播感染。
          Buran勒索病毒此前使用RIG Exploit Kit漏洞利用工具包进行传播，其利用了IE的一个比较严重的漏洞CVE-2018-8174。近期发现，此勒索病毒利用IQY(Microsoft Excel Web查询文件)进行传播。



样本：https://wwx.lanzoui.com/iQ4OYlpempc


13.MegaCortex勒索病毒
MD5：e60e767e33acf49c02568a79d9cbdadd
中文名称：同上
英文名称：Ransom.Win32.MegaCortex（标准）
简介：MegeCortex勒索病毒最早于2019年1月份被人在VT上发现。当时，有人在VT上传了一个恶意样本，英国网络安全公司Sophos在5月份发布一个关于MegaCortex勒索病毒的相关分析报告。
          此勒索病毒早期版本与去年流行的SamSam勒索病毒有些类似，都使用了BAT脚本，同时都使用密码参数，两款勒索病毒的负载加载手法类似，不过暂时还没有更多证据证明两款勒索病毒存在关联。
          MegaCortex勒索病毒从1月份被人上传到VT后，网络安全公司Sophos监控到此勒索病毒的数量一直在增加，并对此勒索病毒进行详细分析报道，该勒索病毒曾经对欧州和北美多个行业发起过勒索攻击，并要求支付高额赎金，美国、加拿大、荷兰、爱尔兰、意大利和法国等国家的一些企业网络都曾受到此勒索病毒的攻击。
          2019年8月，MegaCortex勒索病毒V2.0版本被发现，重新设计负载的运行过程，它会自动执行不需要安装密码的要求，作者将密码硬编码在了二进制文件中，同时还加入一些反分析，以及阻止和杀死各种安全产品和服务的功能，此过程在之前的版本中是通过在在每个受害者主机上手动执行相关的批处理脚本来完成的，最新的版本不需要手动执行，都封装在了二进制程序中。



样本：https://wwx.lanzoui.com/iFVZTlpex5i
————————————————我是华丽丽的分割线~~~~~~~——————————————————


14.FRS勒索病毒

MD5：af6d91121887f5bb0a85a06b1ded0db7
中文名称：同上
英文名称：Ransom.Win32.FRSCryptor（标准）
简介：国产勒索病毒，但是很垃圾，因为解密密码本身已经嵌在自带的文本文档里面了。
https://bbs.pediy.com/thread-261074.htm（详细分析）




样本：https://wwx.lanzoui.com/itPwknmqf5g




四.后门病毒类

1.冰河木马
MD5：37fb43a5f78176846d463d906f83b5aa
中文名称：同上
英文名称：Backdoor.Win32.G_Door（标准）
简介：开发于1999年，本为一个强大的远控软件，但因为滥用成为功能强大的病毒。作为后门病毒界的宗师，冰河木马与后来的灰鸽子等病毒成为国产后门病毒的标志和代名词。


木马功能：
1．自动跟踪目标机屏幕变化，同时可以完全模拟键盘及鼠标输入,即在同步被控端屏幕变化的同时，监控端的一切键盘及鼠标操作将反映在被控端屏幕（局域网适用）；
2．记录各种口令信息：包括开机口令、屏保口令、各种共享资源口令及绝大多数在对话框中出现过的口令信息；
3．获取系统信息：包括计算机名、注册公司、当前用户、系统路径、操作系统版本、当前显示分辨率、物理及逻辑磁盘信息等多项系统数据；
4．限制系统功能：包括远程关机、远程重启计算机、锁定鼠标、锁定系统热键及锁定注册表等多项功能限制；
5．远程文件操作：包括创建、上传、下载、复制、删除文件或目录、文件压缩、快速浏览文本文件、远程打开文件（提供了四中不同的打开方式——正常方式、最大化、最小化和隐藏方式）等多项文件操作功能；
6．注册表操作：包括对主键的浏览、增删、复制、重命名和对键值的读写等所有注册表操作功能；
7．发送信息：以四种常用图标向被控端发送简短信息；
8．点对点通讯：以聊天室形式同被控端进行在线交谈。
     冰河木马的服务器端程序为G-server.exe，客户端程序为G-client.exe，默认连接端口为7626。一旦运行G-server，那么该程序就会在C:/Windows/system目录下生成Kernel32.exe和sysexplr.exe，并删除自身。 Kernel32.exe在系统启动时自动加载运行，sysexplr.exe和TXT文件关联。即使你删除了Kernel32.exe，只要你打开 TXT文件，sysexplr.exe就会被激活，它将再次生成Kernel32.exe，这就是冰河屡删不止的原因。
样本：https://wwx.lanzoui.com/iuRNer8xjcj（V2.0）
          https://wwx.lanzoui.com/iGK38r8xjda（V2.2）【含控制端和被控端】




2.灰鸽子后门病毒
MD5：0f2f224513a5b60e70b91f62e6a5f2da
中文名称：同上
英文名称：Backdoor.Win32.Hupigon.A（Microsoft）
简介：后门病毒的集大成者，在国内享有盛名。
          灰鸽子开发于2001年，原本该软件适用于公司和家庭管理，其功能十分强大，不但能监视摄像头、键盘记录、监控桌面、文件操作等。还可以运行后自删除、毫无提示安装等，因早年采用反弹链接这种缺陷设计，使得使用者拥有最高权限，一经破解即无法控制。最终导致被黑客恶意使用。原作者的灰鸽子被误认为是一款集多种控制方式于一体的木马程序。
          病毒构成：
           配置出来的服务端文件文件名为G_Server.exe（这是默认的，当然也可以改变）。然后利用一切办法使用户运行G_Server.exe程序。
           运行过程：
           G_Server.exe运行后将自己拷贝到Windows目录下(98/xp下为系统盘的windows目录，2k/NT下为系统盘的Winnt目录)，然后再从体内释放G_Server.dll和G_Server_Hook.dll到windows目录下。G_Server.exe、G_Server.dll和G_Server_Hook.dll三个文件相互配合组成了灰鸽子服务端， G_Server_Hook.dll负责隐藏灰鸽子。通过截获进程的API调用隐藏灰鸽子的文件、服务的注册表项，甚至是进程中的模块名。截获的函数主要是用来遍历文件、遍历注册表项和遍历进程模块的一些函数。所以，有些时候用户感觉中了毒，但仔细检查却又发现不了什么异常。有些灰鸽子会多释放出一个名为G_ServerKey.dll的文件用来记录键盘操作。注意，G_Server.exe这个名称并不固定，它是可以定制的，比如当定制服务端文件名为A.exe时，生成的文件就是A.exe、A.dll和A_Hook.dll。
           样本：https://wwx.lanzoui.com/iGctGr8ybgb





3.彩虹桥后门病毒
MD5:29b1550a1de57efda52b039aedeb4710
中文名称：同上
英文名称：Backdoor.Win32.Bifrose.A（标准）———源自于原始文件名Bifrost.exe
简介：最初也是作为一款远程控制辅助软件使用，但后来被恶意篡改而成为危害性很大的后门病毒。
功能：
1.远程文件管理{文件管理（包括：一般文件操作、上传、下载、修改、运行等等；文件搜索（自定义扩展名文件搜索）2.远程系统管理（系统信息、进程管理、窗口管理、密码截获、卸载、升级服务端等等）
3.远程屏幕查看（支持鼠标、键盘控制、保存到文件等等）
4.远程摄像头查看（支持保存到文件等等）
5.远程DOS命令（DOS命令用来添加管理员账号等）
6.键盘记录（包括离线键盘记录和在线键盘记录）
7.获得密码（获取内存、保存、默认密码）
8.更改受害者名称
9.复制IP
样本：https://wwx.lanzoui.com/ihSRfvric1e



4.PcClient后门病毒
MD5：203c4f24052a8df191e7c9fdc74a3b38
中文名称：同上
英文名称：Backdoor.Win32.PcClient.A（标准）
简介：于2004年7月9日被发现，可以感染Windows 2000, Windows 95, Windows 98, Windows Me, Windows NT, Windows Server 2003, Windows XP等操作系统，被感染后会有记录键盘鼠标操作，自动重启，下载文件，强行关机等行为。
行为介绍：
1. 在system32目录下创建一个smss.dll文件.
相关信息编辑 语音
· 并将下列参数值添加到注册表启动项:
"PcClient" = "[path to Trojan]"
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run
2. 该木马病毒会尝试以随机的端口以http应用层协议连接预先定义好的网站, 并将被感染机器的用户名, CPU型号, 计算机名等信息发送到连接的主机. 已知的连接网站有:
· saap.meibu.com
· ps7.meibu.com
· net918.dns0755.net
· xjtomb.20cn.com
3. 该木马病毒可以有下列行为:
· 注销当前帐户, 强行关机, 重新启动你的计算机, 下载和运行更多的文件,
· 记录键盘鼠标 行为.
样本：https://wwx.lanzoui.com/i6T6xvric5i


5.Aimrat后门病毒

MD5：db14bd3cb017e67fb12fb8ec0791b5d6
中文名称：同上
英文名称：Backdoor.Win32.Aimrat.A（标准）
简介：暂无。
样本：https://wwx.lanzoui.com/iDRU7vugwji




6.Aimspy后门病毒
MD5：99724fc3358d168c6f3f375ef1b15cbe
中文名称：同上
英文名称：Backdoor.Win32.AimSpy.A（标准）
简介：利用777端口控制的后门病毒。
样本：https://wwx.lanzoui.com/ixSVPq6ihda

7.Ap门后门病毒
MD5：3e07ae209a0e347d05d48320dd6de668
中文名称：同上
英文名称：Backdoor.Win32.Apdoor.A（标准）
简介：
1.本病毒有两部分组成，exe主程序和dll文件。病毒将自己拷贝到系统目录，登记为自启动，文件名称和注册表数据项名称都是随机的。2.挂结Program Manager即eXPlorer.exe的消息派发钩子，将dll文件注入到explorer的地址空间，开辟新的线程。主程序退出。
3.在explorer中每30秒钟向“smart2com.net”发送http请求包“GET /bin/ap216.exe HTTP/1.1”，试图下载病毒ap216.exe到本地运行。
4.病毒使用了“AICORE 08/27/03 19:36:10”作为事件对象的标志。
5.病毒适时监控注册表的run项。如果被修改，立即修复。
样本：https://wwx.lanzoui.com/iK9Zqvzkzqh

8.黑海之窗后门病毒(V1.0.0.1天使娃娃专享版）
MD5：7d8dcebef26d40a717a1dbdf895c8676
中文名称：同上（原始文件名为"黑海之窗.EXE"）
英文名称：Backdoor.Win32.Andover.A（标准）
简介：该后门运行后可以获得cmdshell，利用dos命令对被感染计算机进行远程控制。重启被感染计算机。枚举进程，并终止指定程序进程。可添加、删除、修改自定义的VBS脚本，用于扩充后门没有实现的控制功能。
作者自述：
[原创]黑海之窗

文章标题:[原创]黑海之窗顶部 andyower 发布于:2005-09-2215:09 [楼主][原创]黑海之窗
信息来源：邪恶八进制信息安全团队（www.eviloctal.com）
文章作者：Andyower
  这个东西很久以前就发布过了,当时是让风泽帮发布的~在这里先谢谢了啊~~呵呵~是给菜鸟用的~不适合高手用.还有很多功能没有完善,比如说,TCP/IP筛选,基本上什么都没有做,没时间呀~又没有网.真的实在很郁闷。
  朋友说界面实在很难看,让我重新发布一个,我就在原来的基础上,使用SkinMagic做了界面.哈哈~真的很不错~我给了一篇有关破解SkinMagic的文章,在http://www.eviloctal.com/forum/htm_data/10/0507/12778.html
  有兴趣的可以看一下,对于用vc的人来说,实在很方便很方便~

黑海之窗

主要功能：在得到一个反弹或者连接的shell上，可以简化一些操作

把cmd命令全部转换成为可视化界面。

具体功能就不写了，麻烦，自己试一下就知道了~

TCP/IP筛选部分，等有时间以后就马上动工~

样本：https://wwx.lanzoui.com/iVcSdq6ihjg




9.Poison后门病毒
MD5:b1a85fdd944c21070a0551e8c59a6158
中文名称：毒藤后门病毒
英文名称：Backdoor.Win32.Poison.A（标准）
简介：由后门生成工具 Poison Ivy 生成的后门类木马程序。它通过注入到其他进程中来隐藏自身，允许未经授权的访问和控制受害系统。
样本：https://wwx.lanzoui.com/ilqs7wgp8yf


10.Blastit后门病毒
MD5：068e7d0320cf32ee0816525c88bb9c4f
中文名称：同上
英文名称：Backdoor.Win32.Blastit.A（标准）
简介：后门程序，启动后将自己安装到系统目录下，在后台隐藏运行，并在注册表中添加以下的键值以达到自启动的目的。
1
HKEY_LOCAL_MACHINE\Software\Microsoft
\Windows\Currentversion\Run
"Windows Wininit Command" : WININIT.EXE

2
HKEY_LOCAL_MACHINE\Software\Microsoft
\Windows\Currentversion\Run
Services
"Windows Wininit Command" : WININIT.EXE

修改System.ini中Boot节中的shell项为 EXPLORER.EXE WININIT.EXE
样本：https://wwx.lanzoui.com/iWoMXwgp94b

11.Allaple后门病毒
MD5：c60d1e4c93692a33d93d6c1b8380ab5d
中文名称：同上
英文名称：Backdoor.Win32.Allaple.A（标准）
简介：为了传播，它能够扫描易受多种漏洞攻击的计算机以进行自我传播；它还可以对网络共享密码执行字典攻击。
此外，该蠕虫还会对爱沙尼亚的许多网站进行拒绝服务 (DoS) 攻击。该蠕虫将自身多次复制到硬盘驱动器，并且还会影响 HTML 文件。蠕虫的文件是多态加密的，这意味着蠕虫的每个副本都是不同的。该蠕虫代码唯一不变的方面是其可执行文件的大小 - 57856 字节。
           该后门蠕虫为它在硬盘驱动器上创建的每个自身副本创建一个不同的 CLSID。这些副本的数量可能非常大。蠕虫文件的名称是随机的。蠕虫文件运行后，它通过多态解密器，然后进入代码的静态部分，分配内存缓冲区并将主要蠕虫的代码提取到其中。然后将控制权直接传递给提取的蠕虫代码。获得控制权后，蠕虫会创建一些线程。一个线程扫描易受攻击的计算机（在 TCP 端口 139 和 445 上）并在那里发送漏洞以感染它们。另一个线程扫描所有本地硬盘上的 .HTM 和 .HTML 文件，并通过在那里添加对蠕虫 CLSID 的引用来感染它们。其余线程之一对位于爱沙尼亚的三个网站执行 DoS 攻击，该蠕虫还试图通过对密码进行字典攻击来暴力破解网络共享密码。
样本：https://wwx.lanzoui.com/iSpUawodwri




12.Cabrotor后门病毒
MD5:89f1be754ec6638938f42ee7855d84ad(zip)
中文名称:同上
英文名称：Backdoor.Win32.Cabrotor.A(标准）
简介：一个用 Delphi 编写的 Windows PE EXE 文件，其2.1版本利用了可能提升权限的漏洞。
样本：https://wwx.lanzoui.com/iE554wodwqh


13.Salgorea后门病毒
MD5：14ee3488c6896ca2b26664e61bf6b11a
中文名称：同上
英文名称：Backdoor.Win32.Salgorea.A（标准）
简介：将图标和名称伪装成WinWord.exe，运行后会大量窃取用户账户信息，记录键盘击键信息并将相关信息回传服务器。
样本：https://wwx.lanzoui.com/i8BzHwqe0uh



14.Aspid后门病毒
MD5：e2d20322337d42a9bf8290d1f1c17366
中文名称：同上
英文名称：Backdoor.Win32.Aspid.A（标准）
简介：暂无
样本：https://wwx.lanzoui.com/i8C47wqe0da

15.Nitol后门病毒
MD5：1242cabae9718d87032d5061f720bbf9
中文名称：同上
英文名称：Backdoor.DDoS.Win32.Nitol.A（标准）
简介：Nitol家族的是暴风DDoS家族、鬼影DDoS家族的统称，其功能代码是从网上的同一套源码改造而成，某杀软将其统称为Nitol家族，该家族并没有像常见的DDoS僵尸网络家族那么活跃，Nitol家族有以下2个特点：
1.Nitol家族兼有DDoS 僵尸网络和RAT恶意程序特色
Nitol家族，首先主要是具有DDoS 僵尸网络的DDoS攻击的功能特点。Nitol家族主要实现syn flood、udp flood、http flood、icmp flood、tcp flood、cc flood、dns flood等7种DDoS攻击类型；同时还初步具备RAT 恶意程序的远程cmd、文件更新下载窗口弹出等功能。通过长期的监控和统计分析得知，Nitol家族的幕后操纵者，经常通过远程文件更新下载指令，将部署在HTTP File Server服务器上的各种病毒木马进行远程植入，实现同一台设备被植入多种类型木马，严重危害设备安全。
2.Nitol家族不易被清除
Nitol家族为了长期保持对“肉鸡”的控制权限，研发者使用了lpk.dll劫持技术，lpk.dll劫持技术是目前病毒较常用的一种方法，而正常系统本身也会存在lpk.dll文件，这足以说明这类病毒的危险性。系统本身的lpk.dll文件位于C:\WINDOWS\system32和C:WINDOWS\system\dllcache目录下。lpk.dll病毒的典型特征是感染存在可执行文件的目录，并隐藏自身，删除后又再生成，当同目录中的exe文件运行时，lpk.dll就会被Windows动态链接，从而激活病毒，进而导致不能彻底清除。
详细分析：https://bbs.zkaq.cn/t/3936.html
样本：https://wwi.lanzouo.com/iExylzmnruh



五.宏病毒类
1.梅丽莎宏病毒
MD5：e429025707d8af0054361e7f9bb20767
中文名称：同上
英文名称：Virus.Word.Melissa.A（标准）
简介：1998年春天，由美国人大卫·L·史密斯运用Word的宏运算编写而成，其主要通过邮件传播。邮件的标题通常为“这是给你的资料，不要让任何人看见”，病毒的名称是佛罗里达州的一位舞女的名字。
           该病毒发作时将关闭 Word 的宏病毒防护、打开转换确认、模板保存提示；使“宏”、“安全性”命令不可用，并设置安全性级别为最低。如果当前注册表中“HKEY_CURRENT_USER\Software\Microsoft\Office\”下 Melissa 的值不等于“... by Kwyjibo”，则用 Outlook 给地址簿中前 50 个联系人发 E-mail，其主题为“Important Message From XXX”(XXX 为用户名)，内容为“Here is that document you asked for ... don't show anyone else ;-)”，附件为当前被感染的文档；将注册表中“HKEY_CURRENT_USER\Software\Microsoft\Office\”目录下 Melissa 的值设置为“... by Kwyjibo”。如果当前日期数和当前时间的分钟数相同时，则在文档中输出以下内容“ Twenty-two points, plus triple-word-score, plus fifty points for using all my letters. Game's over. I'm outta here.”
样本：https://wwi.lanzouo.com/i4FXZy86hid


  
2.台湾一号宏病毒
MD5：73f5e352172e416f6a3970132b551dc3   
中文名称：同上
英文名称：Virus.Word.Twno.A（标准）
简介：该病毒是一个加密的宏病毒。在word环境下，它会感染doc和dot文件。在每月13日，若用户使用Word打开一个带毒的文档（模板）时，病毒会被激发，激发时的现象是：在屏幕正中央弹出一个对话框，该对话框提示用户做一个心算题，如做错，它将会无限制地打开文件，直至Word内存不够，Word出错为止；如心算题做对，会提示用户“什么是巨集病毒（宏病毒）？”，回答是“我就是巨集病毒”，再提示用户：“如何预防巨集病毒？”，回答是“不要看我”。
样本：https://wwi.lanzouo.com/iEAPVy86hhc



3.Chaos宏病毒
MD5：002c4c4ab64bc1fec1a19f9c697e71d3
中文名称：混乱病毒
英文名称：Virus.Word.Chaos.A（标准）
简介：病毒行为：
1. 当前秒数为 18 时，重复随机(最少 10 次，最多 30 次)次在代码中插入注释行。
2. 搜寻启动目录，若不存在则在程序目录下创建一个。
3. 在启动目录下生成 word8.dot，其中含有病毒代码，并将此文件添加到加载宏中。
4. 重载 FileNewDefault、FileNew、ToolsMacro、FileTemplates、ViewVBCode、FormatStyle。
样本：https://wwi.lanzouo.com/iGr9xydpebc

4.Alliance宏病毒
MD5：e6f375d351980333c9154770bcc3f400
中文名称：同上
英文名称：Virus.Word.Alliance.A（标准）
简介：感染.DOC 和.DOT 文件，仅在每月的2、7、11 和12 日感染和复制，并且把文件属性中主题设置为“You Have Been Infected by the Alliance”，屏幕显示一个信息窗，提示用户已感染病毒。
样本：https://wwi.lanzouo.com/idxypydpe9a



5.Bithday宏病毒
MD5：96683e60c506266efed0d53850beb24e
中文名称：同上
英文名称：Virus.Word.Birthday.A（标准）
简介：
（以下内容是我自己修改并整合过的德语翻译，，，，，，）
亲爱的PC世界编辑，
   我想向你提一个请求。我今年16岁，是一名学生，我和我的一些同学们读过你们关于Winword病毒（11/95）的文章。我们在计算机系学习，研究了病毒以及病毒的传播方式。然后，我和我的同学们各自制作了好多病毒。有些是关于Excel、WinWord和Access的。到目前为止，我已经推动了病毒的发展，直到我开发了一个带有DOS病毒或病毒的释放器，用于访问Excel。
   现在该是我直言不讳的时候了。我的一个同学偷了我的“病毒源文本”，现在已经在世界上的各种各样的程序中设置了大约10个不同的“宏病毒”——包括互联网上出现的所有项目。正如我发现的那样，它的扩散率非常高（Winword病毒有时仍有邮件功能）。我知道这些病毒是“恶意的”，它能够格式化信息）。我无法告诉你们病毒什么时候会被启动，但应该很快就会开始，因为这些病毒已经在互联网上流传了一个多月了。我希望你能在你的杂志上对这些病毒即将扩散这件事提出警告，因为如果发生了严重的破坏，我可能也要承担后果。附件中包含病毒，将此文档复制到软盘(WinWord 7)上。
   希望你能帮助我解决问题。请原谅我不能打电话透露我的真实姓名，因为这可能导致刑事后果。
                                                                                                                            谨致问候
样本：https://wwi.lanzouo.com/ie2Yzydpeab


6.Thus宏病毒
MD5：7299e870c3a3634a8ef6555300ddb74d
中文名称：同上
英文名称：Virus.Word.Thus.A（标准）
简介：该病毒是一个感染MS Word97/Word2000文档的宏病毒。 该病毒由ThisDocument的模块组成，它使用Document_Open宏, Document_Close 宏和Document_New宏进行感染。它会感染WORD的通用模版（normal.dot）文件，当通用模版被感染后，Word97的宏报警界面失效。该病毒在感染WORD文档前，会检测文档是否已感染病毒，如果文档的注释含有thus.000字串，病毒就不会再感染该文档。该病毒在每年的12月13日发作，当染毒文件被打开，病毒会删除C驱动器的所有文件（包含子目录）。
样本：https://wwa.lanzouv.com/iyGDQ00e3g1a


7.Mailcab宏病毒
MD5：19867b879ff9c9a91d1d038069057241
中文名称：同上
英文名称：Virus.Excel.Mailcab.A（标准）
简介：这是一种可以感染Excel文档并通过电子邮件传播的宏病毒。此病毒运行后会首先创建注册表键值使得在使用Microsoft Office时可以运行宏。之后病毒会将带毒的工作簿拷贝为%AppData%\Microsoft\Excel\XLSTART\K4.xls，这样只要用户打开excel文档，带有病毒的K4.xls就会被执行。此病毒会搜集用户outlook的通讯录、生成并调用VBS脚本向通讯录中的联系人发送带有此病毒的excel文档。此病毒还会将自身拷贝为其它Excel文档中的宏，并将宏命名为“ToDOLE”。
样本：https://wwa.lanzouv.com/imrzFydpecd


8.Sic宏病毒
MD5：ea978e1d137ba86409528b682044ee48
中文名称：同上
英文名称：Virus.Excel.Sic.A（标准）
简介：该宏病毒会阻止用户打开excel文件，而且会自动感染其他的excel文档。它的明显表现就是：每次打开excel文档的时候都会先自动打开一个book1文档，然后提示你打开的excel文档有宏。
样本：https://wwa.lanzouv.com/ib9Kt00e3g3c



9.NetSnake宏病毒
MD5：055ddc696936256ad70050fb5aac21f3
中文名称：同上
英文名称：Virus.Excel.NetSnake.A（标准）
简介：感染类似该宏病毒的主要表现 ：
          1 ) MSExcel . Netsnake 一感染后文件中可见 Pri - vate Sub createcabfile ( ）字样（用记事本打开查找即可见）。Excel 打开中毒后文件时弹出如下提示：“文件“ Normal . dof “己经存在。是否替换原有文件？ " 中毒后机器打开任意 Excel 文档时同时会多打开一个 book1 的空白文档。
          2 ）打开 EXCEL 总报运行时错误 1004 。
          提示框标题： Microsoft Virsual Basic
          提示框内容： 运行时错误‘ 1004 '
                               工作簿内至少含有一张可视工作表。如要隐藏、删除或移动选定的工作表．必须先插入一张新工作表或重新显示一张已被隐藏的工作表。
样本：https://wwa.lanzouv.com/iTmiZ00ezv6h



六.其它补充类

1.Vamson病毒
MD5：09258814f80286358678086fc33bf578
中文名称：同上
英文名称：Trojan:Win32/Vamson.A!rfn（Microsoft） / Rootkit.Win64.Agent.bds（卡巴） 简介：本病毒属于主页保安系列的锁主页驱动，本身比较恶心，保护文件注册表，磁盘。一般动不了他的注册表，也动不了他的文件，对于想磁盘解析操作也做了保护。而且发现一旦绕过他的保护自动重启或关机，主要针对急救箱对抗，因为其他杀软他都可以无视。重启方式包括但不限于IO重启，清空 SYSTEM EPROCESS结构，导致系统随机蓝屏，及调用HalReturnToFirmware强制关机等，而且急救箱一更新，他就更新驱动对抗。相当恶心，建议到WINPE下去查杀。没必要和他斗的天翻地覆了。
具体分析及运行方法请至 https://bbs.kafan.cn/thread-2138187-1-1.html 查看。
补充样本：https://wwx.lanzoui.com/iKbhpqq2tzi            https://pan.baidu.com/s/1yJvIH47oA5aVFYxOkdv5Mg
          https://share.weiyun.com/5lE2R5g       杀软测试此病毒链接：    https://bbs.kafan.cn/thread-2211328-1-1.html   
   
2.紫狐病毒

MD5：971bd6b087aa17dc582d08a5fe0904f7
中文名称：同上
英文名称：Trojan.Win32.PurpleFox
简介：  http://www.360.cn/n/10386.html（详细分析）   
样本：https://wwx.lanzoui.com/isUI0r05rnc

3.猫癣下载器

MD5：ed918b67662896536fe1583b4359539c
中文名称：同上
英文名称：Trojan-Downloader.Win32.Murlo.A（标准）
简介：“猫癣”病毒最明显的中毒症状，是电脑桌面上出现usp10.dll文件、迅雷无法启动及安全软件自动关闭，并且伴随网游帐号被盗。目标囊括魔兽世界、大话西游onlineII、剑侠世界、封神榜II、完美系列游戏、梦幻西游、魔域等主流游戏，对用户的虚拟财产影响巨大。
    无论是哪款变种的“猫癣”，都能利用IE7 0day漏洞、微软access漏洞、新浪uc漏洞、realplay漏洞等多种系统和第三方软件的安全漏洞进行网页挂马传播，如果用户系统存在以上漏洞，又刚好浏览到被挂马的网页，“猫癣”就会趁虚而入。
https://m.c114.com.cn/w501-381931.html（详细分析）
样本：https://wwx.lanzoui.com/imqRgwj1yta


4.FannyU盘病毒

MD5：c82eee84c051abef1c60d0954eb3fdc9
中文名称：同上
英文名称：Exploit.Lnk.CVE-2010-2568
简介：通过“ LNK 图标漏洞”传播的木马，大多包含多个“恶意快捷方式”，如日前发现的“双子”木马包含两个快捷方式，而这次发现的“ Fanny 木马”更是包含了 5 个快捷方式。这是因为恶意的快捷方式在调用病毒文件时，必须采用绝对路径。而木马作者无法准确得知用户插入 U 盘的盘符，因此往往要准备多套方案。从“ Fanny 木马”包含的 5 个快捷方式的名称上（如图 1 所示），我们也能看这些快捷方式分别是针对 U 盘盘符是 E 、 F 、 G 、 H 、 I 这五种情况而制作的。     虽然 Fanny 木马和双子木马一样，都是利用 LNK 图标漏洞进行传播，但显然攻击手段进行了升级。除了 Fanny 木马采用了更多快捷方式提高攻击命中率以外，还将病毒文件伪装成了图片格式（ .bmp ），更具伪装性。
样本：https://wwx.lanzoui.com/id6Vtwjhrej
