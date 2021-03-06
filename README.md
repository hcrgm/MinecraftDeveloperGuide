#Java与Minecraft开发学习指南

##前言
有很多人问我怎么学Java，想成为Minecraft大神（大佬or大牛），所以就萌生了一个编写学习指南的想法，来引导想学习Java进行Minecraft相关开发的新人，经过一段时间的策划，本指南诞生了。  
本人从事Minecraft相关开发两年，经验不够丰富，还希望各位多多指教，互相交流经验，促进开发圈的良好发展。

##新手的疑问
初学者都有很多疑问，在这里对这些疑问进行一一解答。

- 我英语不好，可以学习编程吗？  
对于初学者来说，英语不是主要的障碍，国内有着充足的中文教程。但在接下来的学习过程中，需要阅读大量的英文文档，所以还是需要有一些英语基础和理解学习能力，配合翻译工具（如百度翻译）进行理解。

- 我数学不好，可以学习编程吗？  
对于初学者来说，有必要掌握数学逻辑思维和解决问题的思路，这些能力都在数学学习中得到锻炼，想必学习编程的人数学成绩肯定不错。初学者不需要多高的数学知识水平，但在未来的学习过程中需要更高级的数学知识，应随时做好接受学习新知识的准备。

- 我想学习编程，大佬可以教教我吗？  
一般我是拒绝的，我认为学习是互相促进的过程，而不是单方面的输出，并且我也有很多事情要做。不仅是我，绝大多数人都会拒绝。

- 学习编程是使用IDE好还是Notepad好？  
最近看到有人在争论这个问题，对于Java这门面向对象，语法糖较少的语言来说，使用IDE是一种极佳的选择。

- 好吧，我自学编程，有问题可以问大佬吗？  
可以，但是我拒绝回答书中的基础问题和可以通过搜索引擎解决的问题。

- 学习编程是看书好还是看视频好？  
萝卜青菜，各有所爱，关键是看哪种方式能让你更好理解和学习。我个人是喜爱书本，可以随时查阅资料，非常方便。

- 我学习了很久，但没有成效，我是不是没有天赋？    我个人觉得对于入门的学习来说，天赋对于学习的影响微乎其微，如果你的学习效率低下，考虑是不是以下原因：
  - 单纯的努力不足，三天打鱼两天晒网。如果不能改正，不如考虑干点别的。
  - 数学逻辑思维和解决问题的能力不足。这个可以学习一些简单易懂的教程，看看视频等，慢慢锻炼，没有任何捷径。
  - 学习方法不对，主要是练得少。只翻书和看视频是没有用的，必须配合大量的练习。个人推荐的方法是：
    - 看完书以后把书上给出的例题再敲一遍，不是照着书上写。
    - 把课后习题都给做了。
    - 做几个自己感兴趣的项目。
    - 对于自己不懂的问题，先看看书，再百度谷歌，最后才询问他人。

##提问的智慧
必读，教你如何获得答案
[外部链接](https://lug.ustc.edu.cn/wiki/doc/smart-questions)

##自学的方法
- 每当学习到新知识的时候应该及时的练习和实践
- 多看看开发文档，每次你都能获得新的收获
- 多看看别人的源代码，很多问题都能得到解决
- 搜索引擎是一个好东西
- 写学习笔记和博客是记录知识的好方式，但不是死记知识点
- 好的提问方式才能获得正确答案
- 合理的规划学习时间，而不是三天打鱼两天晒网

##Java基础教程

###《Java从入门到精通》
我的Java入门书，虽然内容有些老旧，但也是非常适合Java入门的。

###《Java8编程入门(参考)官方教程》
本书分两本，一本是 《Java8编程入门官方教程》，一本是 《Java8编程参考官方教程》。入门版本内容较少，由于我没看过不做评价，参考版本内容很多，可以当字典用。  

###《Java核心技术》
非常不错的一套书，共2本，解决了我的很多疑问，也可以当做字典来查阅。
  
###《Java编程思想》
由于我没看过不做评价，但别人都说不错。 
 
###《Effective Java》
相当好的一本关于Java的一些开发规范介绍书籍，帮助你写出更好，更健全，更规范的代码，强烈推荐阅读。    

###JAVA语言规范
http://docs.oracle.com/javase/specs/

###Java中文在线教程
http://www.runoob.com/java/  
（我绝对不是打广告）

###官方教程
http://docs.oracle.com/javase/tutorial/

##Forge模组开发

###1.8.9Forge教程
非常全面的Forge开发教程，强烈推荐。  
https://fmltutor.ustc-zzzz.net/

###国内优秀Mod开发者博客
一些比较高端的教程，建议有一定水平后阅读。  
- http://blog.hakugyokurou.net/?page_id=126
- http://www.windworkshop.cn/?page_id=525

###Forge中文文档
详细介绍了Forge添加的非常有用的功能。  
http://mcforge-cn.readthedocs.io/zh/latest/

###国外模组开发教程
由于没有详细的阅读过，不做评论，但大都全面，非常推荐英语水平好的同学前去阅读。    
- http://bedrockminer.jimdo.com/
- http://minecraftjp.info/modding/index.php/Minecraft_Modding_Wiki
- http://forgetutorials.weebly.com/
- http://jabelarminecraft.blogspot.com/
- http://greyminecraftcoder.blogspot.com/
- http://modwiki.temporal-reality.com/mw/index.php/Main_Page
- http://www.pahimar.com/tutorials/lets-mod/

###国外mod开发讨论
很多问题都能在这里解决
- Forge官方论坛Mod开发讨论版块    
http://www.minecraftforge.net/forum/index.php?board=73.0
- Forge官方论坛Mod开发教程版块    
http://www.minecraftforge.net/forum/index.php?board=120.0 
- 国外Minecraft论坛Mod开发讨论版块    
http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/modification-development

##Bukkit/Spigot插件开发

###810587921的插件教程
我的入门教程     
http://www.mcbbs.net/thread-283190-1-1.html

###其他国内优秀教程
由于没看过不做评价，但是内容都很全面
- Day's Bukkit插件开发教程索引    
http://www.mcbbs.net/thread-439856-1-1.html
- wyt的Bukkit插件开发教程    
http://www.mcbbs.net/thread-614388-1-1.html

###官方教程
- 新版本(现Spigot)    
https://www.spigotmc.org/wiki/spigot/
- 旧版本(原Bukkit)    
http://wiki.bukkit.org/Plugin_Tutorial

###Bukkit API开发者文档
- 中文文档    
https://docs.windit.net/Chinese_BukkitAPI/
- 英文文档    
https://hub.spigotmc.org/javadocs/spigot/

###Spigot官方论坛插件开发讨论版块
很多问题都能在这里解决。    
https://www.spigotmc.org/forums/spigot-plugin-development.52/

###其他插件开发高级教程
- ProtocolLib教程    
http://www.mcbbs.net/thread-568714-1-1.html
- Ebean数据库    
http://www.mcbbs.net/thread-628118-1-1.html      
http://www.mcbbs.net/thread-636860-1-1.html

##其他

###Github
世界上最大的~~同性交友~~源代码开放网站，可以在这里查看许多模组和插件的源代码。    
https://github.com/

###MCBBS开发讨论板块
有很多有用的东西哦。  
http://www.mcbbs.net/forum.php?mod=forumdisplay&fid=479

###MCBBS开发教程索引贴
http://www.mcbbs.net/thread-54579-1-1.html

###Javadoc
- 官方英文
http://docs.oracle.com/javase/8/docs/api/
- 中文文档(Java 6)
http://tool.oschina.net/apidocs/apidoc?api=jdk-zh

###搜索引擎
- https://www.baidu.com
- https://www.google.com

###国内开发讨论QQ群
- 国内最大的MC开发讨论群：284633248
- 插件开发交流群： 313498121
- 我的没什么dalao的开发讨论群： 345538010

###MC开发中文百科
https://www.mcdev-wiki.org/

###Stack Overflow
国外的一个关于开发的求助网站    
http://stackoverflow.com/

##后记
花了2天时间收集各种资料，写得不是很好的开发指南，希望大家能够多多支持。有什么建议可以通过Issue，电邮，站内信，在下方直接回复都可以。

##版权声明

本作品作者为耗子

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">知识共享署名-相同方式共享 4.0 国际许可协议</a>进行许可。

转载请附上本作品链接： https://github.com/mousesrc/MinecraftDeveloperGuide
