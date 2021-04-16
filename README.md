# NiNiTechnology
## 温馨提示：
ff14国际服版本5.5及后续版本的尼尼科技Triggernometry触发器将分为普通版和专业版两种不同版本。专业版触发器需使用尼尼科技专业版增强触发插件Triggernometry-pro导入（ https://github.com/pipirapira/triggernometry-pro ）

专业版触发器包含更多强大的实验性功能和更好的版本兼容性，我们今后的开发将逐步转向全面支持专业版触发器。

## 伊甸再生篇
一套包含了大多数简单机制的Triggernometry TTS已上传。
## 伊甸共鸣篇
一套包含了大多数简单机制的Triggernometry TTS已上传。因为ACT解析插件的局限性，我们在这一试行版本中暂无法实现其它更复杂的功能。
## 绝亚历山大
#### 时间轴
更新至P3狂暴
#### P4全套豪华轮椅（目前支持：EN/JP/CN客户端）
##### 内容包括：<br>
##### 简单机制TTS：
3连死刑：在boss读条白光之鞭的时候播报“死刑”。<br>
易伤死刑：在boss读条易伤死刑的时候播报“换T”。<br>
行动命令：在boss读条行动命令的时候播报“动动动”。<br>
静止命令：在boss读条静止命令的时候播报“停停停”。<br>
制导分摊：在boss读条制导分摊的时候播报“前后分摊”。<br>
制导散开：在boss读条制导散开的时候播报“散开散开”。<br>
##### 确定判决：
接触保护(Contact Regulation)：播报“大黄大黄，出去4D”。<br>
逃亡监察(Escape Detection)：播报“大黑大黑，站在2B”。<br>
其它：播报“小黑小黄，2点集合”。<br>
##### 未来观测α：
大圈点名：播报“大圈大圈，快出去”。<br>
闪电点名：播报“闪电闪电，人群右侧”。<br>
其它：播报“分摊分摊，人群左侧”。<br>
行动静止：在看到幻影动画时播报“行动“”静止”，在生效前3秒再次播报“动动动”或“停停停”。<br>
安全点：播报“左左左”（指C点左侧）或“右右右”（指C点右侧）。<br>
##### 未来观测β：
接触保护：播报“大黄大黄，快去A点”。<br>
逃亡监察：播报“大黑大黑，B点不动”。<br>
逃亡禁止：播报“小黑小黑，B点向左”。<br>
蓝线+逃亡禁止：播报“蓝线小黑，B点向南”。<br>
红绿线+逃亡禁止：播报“红绿小黑，B点向北”。<br>
其它人：播报“小黄小黄，留在人群”。<br>
分散或分摊：在看到动画时播报一次“双分摊/散开”，在判定前6秒再次播报。如果是双分摊，你是黄点，会加上指示“北北北”，是黑点，会加上指示“南南南”。<br>
月环观测：在月环动画出现的时候播报位置，“2B2B”、“3C3C”或者“4D4D”。在月环判定前6秒再次播报。<br>
##### 地火：
2穿1倒计时：在第一个地火判定前播报“3,2,1,冲鸭”。

#### P4自动标点工具（实验性功能，慎重使用）
使用前，请您安装国际服最新版本的Paisley Park，设置Port为2005，并点击Start开启端口。<br>
P4开局标点：标记东南西北最外侧点ABCD。标记B点内侧集合点为2点。<br>
未来观测α：标记北侧安全点为1，南侧安全点为2。<br>
未来观测β：在B点的上下附近标1,2作为蓝线和红线小黑的起跑点。<br>
地火3点法（默认关闭，可修改）：总是在场地下方的左中右3个位置寻找安全点。标记起始点为2，结束（分摊）点为1。有3分之1的概率需要全员2穿1。适合网络好、重视输出的团队。<br>
地火4点法（默认开启，可修改）：总是在场地右下方的4个位置寻找安全点。一定是3穿1，标记起始点为2，结束（分摊）点为1。缺点是起跑点可能会出现在场地右边较远处，需要跑路。适合重视稳定的团队。<br>

#### 基础TTS模块
提供播报小队职业的功能，如果不导入，其它模块可能不播报TTS。<br>
#### 反毒配对
在终审开庭后，播报应该去传毒/接毒的人的名字。并把他的职业简称（如：SMN）显示在屏幕上。<br>
#### 计数圈点名
计数圈点名两个队员，播放他们的职业。如“龙忍”<br>
#### 麻将提示（含P3）
P2转场麻将圈圈计数器工作后显示如下：<br>
![image](https://github.com/pipirapira/NiNiTechnology/blob/master/resources/hawk2.gif)<br>
P2打法：按1256,3478散开。动态图如下：<br>
![image](https://github.com/pipirapira/NiNiTechnology/blob/master/resources/hawk1.gif)<br>
P3二运麻将默认按云玩家式播报，可切换至1A式。画面上将显示精确到0.1秒的计时器，提醒你接下来需要处理的个人机制。<br>
云玩家打法见网上视频攻略<br>
1A式基本规则如下：<br>
以亚力山大为12点。奇左偶右。<br>
12号：灵泉3进。3号：6点待机，4号12点超跳。 56号：灵泉1进。78号：灵泉2进。<br>
#### 水雷倒计时
在水属性压缩/雷属性压缩剩余5秒时开始倒计时5,4,3,2,1。<br>
#### 苏帕酱噗
在残暴正义号读条超级跳时播放“苏帕-酱噗！”，在残暴正义号读条双重火箭飞拳时播放“大波洛克托——胖奇！”<br>
#### 开发中
绝亚历山大的Triggernometry触发器已经基本完善，感谢在此过程中提供数据和测试案例的团队和玩家。如有问题可继续联系作者。
#### 疑难解答
##### Q：我需要将xxx改成自己的ID吗：<br>
A：不需要。尼尼科技的所有触发器都是开袋即食的。如有不能使用的情况，请检查插件版本、tts语音设置等<br>
##### Q：为什么未来观测轮椅没报：<br>
A：请自己观测，并将观测结果反馈给作者。<br>
##### Q：为什么未来观测轮椅报了很多，而且全是错的：<br>
A: 可能是您的act插件没有检测到玩家名字，请下载并安装最新版本的FFXIV_ACT_Plugin和Triggernometry。<br>
##### Q：为什么月环报了B，却跳了C：<br>
A: 笨比队友跑错了。<br>
##### Q：地火怎么标了2穿1：<br>
A: 请下载最新版本，选择开启“地火4点法”标点。<br>

另：根据用户反馈，腾讯加速器会对您的战斗日志做出不可预测的修改，尼尼科技的某些触发器在腾讯加速器的情况下可能出现播报错误，请谨慎使用。<br>
如果工作错误可将FFXIV_ACT_Plugin的解析模式设置为WinpCap Network。<br>

## ff14时间轴和触发器
  
时间轴使用ACT.Timeline.dll和FZTimeline.dll插件导入。(所有时间轴已支持EN/CN/JP语言客户端）<br>
  
触发器使用Triggernometry.dll插件导入。(Triggernometry TTS已支持所有语言客户端）<br>
  
## CardcaptorAST
5.0占星用卡牌优化系统，使用Triggernometry.dll插件导入。<br>
  
## 尼尼科技指挥插件

功能：本插件为高难度副本中的各种复杂机制提供解决方案。<br>
包括但不仅限于：石牢科技，一运安全点，绝巴哈P2俯冲标点，连击拘束器提示，连击大地摇动标记分配，群龙跑法提示，踩塔分配，百京核爆方向提示等。<br>
 
本插件不播报热风点名玩家，请结合其它TTS插件使用。<br>
本插件不播报 死亡宣告点名，凶鸟台词，旋风。请整合其它TTS插件使用。<br>
如果插件不正常工作，请检查FFXIV_Plugin是否启动，能否读出数据，插件日志中的小队列表与游戏中是否一致，然后重启本插件。<br>
  
播报规则：<br>
#### 《伊甸》

4层：蓝标点名播报职业。<br>
  
#### 《欧米茄幻境9-12层》
  
11层：<br>
●6人踩塔：按顺序报出3组踩塔人员的职业，如：战骑，龙召，忍机<br>
●3-4人易伤光束炮：按顺序播报出所有被点名人员的名字。<br>
  
12层：<br>
●易伤死刑：播报被点名人员的职业，如“战”。<br>
●转向浮游炮：以场地12点为基准，播放上下左右。如“左下左下”，那么请往左下安全区域移动。<br>
●全存档：以boss面向为基准，播放“左左左”或“右右右”。注意，插件先播报，boss后转向，请等待boss转向后再进行移动。<br>
●冰火雷分摊+分散：播报分散人员的职业。被点名的职业请按团队散位安排远离中央。<br>
  
#### 《究极神兵绝境战》
  
●场地标点方式：<br>

　　Ａ<br>
  <br>
Ｄ　　　Ｂ<br>
  <br>
　　Ｃ<br>

●一杆进洞：	以泰坦为12点。报安全点位置。如果是左边安全，就报“左左左”，右边安全，就报“右右右”。<br>
●石牢顺位：	连续播报从前到后3个人的职业。如“战忍学”。顺位按如下规则：<br>
  
		前←MT ST D1 D2 D3 D4 H2 H1 →后
		其中 MT←暗战枪骑→ST    H2←学星白→H1  D1←龙武侍忍诗机舞赤召黑→D4
●石牢自动标记：请把宏放在F5-F12上。勾选“自动标记”，将按上述顺序进行标记。<br>

●泰坦落地点预告：警告，由于读取内存方式的不成熟，目前只能在落地前2秒判断出位置，无法作为提前移动的依据，请自己看清泰坦的转向。插件的播报方式：“AAAA，BBBB，CCCC，DDDD”。如果插件错误，会报“自己看”。<br>
  
●追击安全点：	播报格式：A点偏B，A点偏B，（原地危险，疾跑穿十字火。）<br>
  追击的安全点有8个，都在8个连续小字图案的中心，也就是第4个字的位置。如插件报A点偏B，请先向A点移动，然后向B方向寻找8个连续小字，并站在第四个字的位置。如果插件报“原地危险”，则起始位置并非最终安全点，需要在火神冲结束后迅速移动到同侧的另外8个小字安全点区域。<br>
如果团队采用减伤盾硬吃火神冲的方式，可直接向第二安全点移动。此时的移动位置请独立判断。<br>
  
#### 《巴哈姆特绝境战》
  
●雷左右：左←HDT→右<br>
●拘束器：1人无提示，2人，3人无序报职业。<br>
●龙神的加护读条时：按顺序播报俯冲三个标点的位置。如”2点，6点，10点"。<br>
●俯冲点名：报职业。报方位（可选）<br>
●进军3振翅：报除了奶妈以外，被振翅点名的职业。<br>
●连击4振翅：将根据玩家位置分配最优站位，第一次在场地6点散开，从左到右播报。（现在也可以进行玩家标记）。<br>
●连击拘束器：按如下形式，其中H1，D1和MT为1号补位，H2，D2和ST为2号补位，D3和D4为自由人。<br>
站位中D1D2为近战职业，按D1←龙武侍忍→D2的顺序分配，D3D4为远程职业，按D3←诗机赤召黑→D4的顺序分配。<br>
H1H2为奶妈职业，按H1←白占学→H2的顺序分配。MT，ST为T职业，按MT←暗战骑→ST的顺序分配。<br>
基本规则：见https://ffxivbahamut.netlify.com/p3.html <br>
  
●群龙：面向巴哈，按语音提示行动。<br>
  
1.巴哈位置，如“巴哈5点”，请将视角转到5点。<br>
2.行动位置，如“左下左下”，表示面向巴哈，朝左下移动为安全区。<br>
3.凶鸟情况，“凶鸟在前”，表示马拉松前方有凶鸟。“凶鸟在后”表示后方有凶鸟。<br>
4.马拉松方向，“顺时针”或“逆时针”<br>
5.小龙情况，如提示“前方有龙”，表示走到巴哈位置需要暂停等待第一条龙俯冲过后再走。<br>
6.双塔引导，会报双塔点名职业和双塔位置，请及时去引导双塔俯冲。<br>
注意：如果群龙发生减员，则无法预测双塔点名职业。它将是随机点名，请所有人尽可能去场边引导。<br>
  
●群龙4塔：以双塔脚下为顺时针1塔，报各职业踩塔顺位。顺位为"近战&gt;远程&gt;奶妈&gt;T"<br>
  
例如1龙2召3学4暗，表示顺时针1塔由龙骑踩，以此类推。<br>
双塔俯冲不踩塔，如果俯冲无分摊标，则由点名分摊的T和奶负责补位踩顺4位的塔。此时会报”T奶补位“<br>
  
●黄金巴哈：以12点为正北方向播报Exaflare的出现位置。<br>
  
