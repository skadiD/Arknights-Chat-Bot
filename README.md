# Arknight-Chat-Bot-明日方舟群聊机器人
  An amazing robot to break the ice for game **Arknights** 
  一个能活跃气氛的智(沙)能(雕)先蒂牌机器人
  
## Show-说明
### How Can I Do-我能做什么
  1.高仿真模拟`干员寻访` `公开招募`的结果 (支持[标准池] [联合招募池] [限定池] [新手池] **[整活运动池]** **[桃子池]**)

  2.查询干员相关资料信息

  3.寻找最受欢迎的某关作业

  4.半人工智(障)能对话
  
  5.群新人欢迎信息
  
  6.试图模拟`基建` `每日/周任务`以完善经济体制
  
  7.群成员文字回合PVP
  
  8.~~氪金~~为爱发电快速获取[合成玉] 可用于 `干员寻访`
### Information-信息
  项目主体分为Web端以及机器人插件,目前提供`[契约框架 酷Q框架 QQLight框架]`的插件源码(请注意,您可能需要额外购买机器人框架的高级版本以实现全部的功能)并提供完整的接口文档.

  Web端基于ThinkPHP6 + MDUI开发,提供群聊接口的同时提供了(算是美观的)前端页面.群成员使用机器人所产生的所有数据均可以在Web端查询分享.
### Usage-用法
  1.本地部署
  
   1.首先您得有支持PHP环境的服务器/虚拟主机/SAE等,推荐与机器人程序处于同一内网环境降低延迟(推荐使用Windows Server 或Linux + Docker)
    
   2.修改Web端根目录`.env`中的Mysql信息,并将根目录下的`Bot.sql`导入进数据库(如果您的服务器支持Redis建议使用Redis存储缓存数据)
    
   3.解析`www` `api` `user` `admin`的二级域名到您的服务器,完成Web端的部署
   
   4.修改机器人插件源码中的接口地址等信息,编译生成Dll文件完成打包放入机器人框架中
   
   5.开始使用
   
  2.白嫖版(SaaS)
  
   1.访问网站注册~~白嫖专属账号~~或添加QQ群[1062708250] 获取专属Token
   
   2.选择一只指定的蒂蒂[先帝 or 温蒂]作为你的群聊机器人
### 数据素材来源及鸣谢感谢
  #### 在制作过程中使用了部分数据以及借鉴了算法思路,在此一并表示感谢
  
  - [Kengxxiao/ArknightsGameData](https://github.com/Kengxxiao/ArknightsGameData)（数据）
  - [罗德岛人事中心](https://amiya.xyz/)(干员头像)
  - [Tsuk1ko/arknights-toolbox](https://github.com/Tsuk1ko/arknights-toolbox)(干员信息二次整理思路借鉴)
  - [ark-nights.com](https://github.com/Houdou/arkgraph)（材料图片）
  - [企鹅物流数据统计](https://penguin-stats.io/)（掉落数据）
  - [素材获取最优策略规划](https://bbs.nga.cn/read.php?tid=17507710)（思路）
  - [作业信息](https://www.bigfun.cn/post/14680)(作业信息)
## Contents-目录
* 中文版：
	* [环境配置](#环境配置-中文)  
	* [基础设定](#基础设定-中文)
	* [二次开发](#二次开发-中文)
	* [附录](#附录-中文)
	* [备注](#备注-中文)

