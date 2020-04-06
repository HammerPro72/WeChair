
<p align=center><font size=10><strong>WeChair</strong></font></p>
<p align=center><font size=10>软件需求规格说明书</font></p><br/>
<div align=center><img width="100" height="100" src="https://github.com/irvingming11/WeChair/raw/master/WeChair.jpg?raw=true" /></div><br/><br/>
<p align=center><font size=5>所属学院：<u>福州大学至诚学院</u></font></p>
<p align=center><font size=5>团队名称：<u>WeChair</u></font></p>
<p align=center><font size=5>指导老师：<u>张栋</u></font></p>

<h2 align="center">目录</h2>
<div>
<br><a style="font-size:18px" >第一章 引言</a>
<br><a style="font-size:16px" >  1.1 编写目的</a>
<br><a style="font-size:16px" >  1.2 预期读者</a>
<br><a style="font-size:16px" >  1.3 项目背景</a>
<br><a style="font-size:16px" >  1.4 参考资料</a>
<br><a style="font-size:18px" >第二章 系统说明</a>
<br><a style="font-size:16px" >  2.1 产品描述</a>
<br><a style="font-size:16px" >  2.2 产品功能</a>
<br><a style="font-size:14px" >    2.2.1 活动图</a>
<br><a style="font-size:14px" >    2.2.2 类图 </a>
<br><a style="font-size:14px" >    2.2.3 主要功能说明 </a>  
<br><a style="font-size:16px" >  2.3 用户特点</a>
<br><a style="font-size:14px" >    2.3.1 用户群体 </a>
<br><a style="font-size:14px" >    2.3.1 典型用户场景 </a>  
<br><a style="font-size:16px" >  2.4 一般约束</a>
<br><a style="font-size:16px" >  2.5 假设和依赖</a>
<br><a style="font-size:18px" >第三章 功能性需求</a>
<br><a style="font-size:16px" >  3.1 界面原型</a>     
<br><a style="font-size:16px" >  3.2 硬件接口</a>
<br><a style="font-size:16px" >  3.3 软件接口</a>
<br><a style="font-size:16px" >  3.4 通信接口</a>
<br><a style="font-size:18px" >第四章 非功能性需求</a>    
<br><a style="font-size:16px" >  4.1 性能需求</a> 
<br><a style="font-size:14px" >    4.1.1个人信息精度(学生)</a>
<br><a style="font-size:14px" >    4.1.2个人信息精度(管理员)</a>
<br><a style="font-size:14px" >    4.1.3座位信息精度(图书馆)</a>
<br><a style="font-size:14px" >    4.1.4分享信息精度</a>
<br><a style="font-size:14px" >    4.1.5学习时长及排行榜精度</a>
<br><a style="font-size:16px" >  4.2 软件属性</a> 
<br><a style="font-size:14px" >    4.2.1 可靠性</a>
<br><a style="font-size:14px" >    4.2.2 可用性</a>
<br><a style="font-size:14px" >    4.2.3 安全保密性</a>
<br><a style="font-size:14px" >    4.2.4 可维护性</a>
<br><a style="font-size:18px" >第五章 验收验证标准</a>
<br>
</div>

<p align=center><b><font size=7>第一章&emsp;引言</font></b></p>
<p><font size=6><b>1.1编写目的</b></font></p>
<p><font size=4>&emsp;&emsp;为准确描述软件定位，明确软件需求，减少开发工作以及便于软件升级和产品转移撰写本文档。本篇软件规格说明书详细描述了“WeChair”这一小程序的用户需求、软件规格等内容。方便用户深入了解该小程序。同时也是开发者进行开发、测试以及软件验收的主要依据。</font></p>
<p><span><font size=6><b>1.2预期读者</b></font></span></p>
<ul>
  <li><p><font size=4>项目经理：项目经理可以根据本文档了解产品的实现预期以及产品的诸多细节，便于进行项目管理。</font></p></li>
  <li><p><font size=4>设计员：根据软件的需求有 针对性地设计出各种框架，其中包括数据库设计、WeUI界面设计等等</font></p></li>
  <li><p><font size=4>程序员：程序员可以根据本文档详细阐述的软件功能进行小程序开发编码。</font></p></li>
  <li><p><font size=4>测试员：测试员可以通过本文档阐述功能描述进行功能测试、接口测试以及各种细节。</font></p></li>
  <li><p><font size=4>用户：用户可以根据本文档了解产品的出发点以及小程序的功能，有助于用户确定该小程序是否满足其需求以及是否达到预期效果。协助用户与开发着更好地协商讨论，</font></p></li>
</ul>
<p><font size=4>&emsp;&emsp;本文档用于指导小程序开发者与软件工程实践课程中开发小程序项目的过程。通过规范小程序项目承担团队开发过程达到提高小程序质量、降低维护成本的目的。在阅读本文档时，首先要了解产品的功能概貌，然后可以根据自身的需要对每一功能进行适当的了解。</font></p>
<p><span><font size=6><b>1.3项目背景</b></font></span></p>
<p>&emsp;&emsp;<font size=4>小程序名称：WeChair</font></p>
<p>&emsp;&emsp;<font size=4>开发者：福州大学至诚学院2017级综合实验班软件工程实践“WeChair小组”</font></p>
<p>&emsp;&emsp;<font size=4>本项目初期通过问卷对用户需求进行调查，详细了解了潜在用户的需求，从用户需求以及当前市场上产品存在的用户痛点出发，在小组内部分析和讨论之后，确定了小程序的定位和主要功能。WeChair面对的用户是经常出入学校图书馆的学生，结合软件即服务的思维，旨在通过WeChair给经常进出图书馆的学生提供图书馆的优质服务。用户能随时随地了解图书馆座位分布情况，实时预订图书馆座位享受方便快捷的服务，座位分配问题得到合理优化。用户还可通过WeChair分享自己与图书馆之间的故事，留下自己的故事给别人带来激励和慰藉，同时在图书馆的学习时间会根据用户需要进行排名，达到利用人性心理的竞争性引导大家积极学习的效果。</font></p>
<p><span><font size=6><b>1.4参考资料</b></font></span></p>
<p>&emsp;&emsp;<font size=4>[1]《GB9385-2008 计算机软件需求规格说明规范》</font></p>
<p>&emsp;&emsp;<font size=4>[2]《GB9385-2008 计算机软件测试文档编制规范》</font></p>
<p>&emsp;&emsp;<font size=4>[3]《构建之法》第三版 作者：邹欣</font></p><br/><br/><br/><br/>


<p align=center><b><font size=7>第二章&emsp;系统说明</font></b></p>
<p><font size=6><b>2.1产品描述</b></font></p>
<p>&emsp;&emsp;<font size=4>WeChair体现软件即服务的思想，通过WeChair小程序给用户提供服务。旨在让图书馆灵活化，用户使用图书馆座位的方式人性化，行走的图书馆--无论你身处何地何时，都能利用我们的WeChair小程序，了解到图书馆内的座位使用情况，座位跟用户之间有了交互。用户能实时获取每个座位使用信息并预约座位，每个座位能记录用户的学习时长，同时用户在WeChair小程序上还能聆听或分享属于自己跟图书馆的故事，在我们WeChair提供的服务下，希望能让用户更享受图书馆、更享受学习。
</font></p>
<p><font size=6><b>2.2产品功能</b></font></p>
<p>&emsp;&emsp;&emsp;&emsp;<font size=5><b>2.2.1活动图</b></font></p>
<div align=center><img width="600" height="700" src="https://github.com/yuwenjin-king/WeChair/raw/master/%E6%B4%BB%E5%8A%A8%E5%9B%BE.png?raw=true" /></div><br/><br/>
<p>&emsp;&emsp;&emsp;&emsp;<font size=5><b>2.2.2类图</b></font></p>
<div align=center><img width="600" height="700" src="https://github.com/yuwenjin-king/WeChair/raw/master/%E7%B1%BB%E5%9B%BE.jpg?raw=true" /></div><br/><br/>


<p>&emsp;&emsp;&emsp;&emsp;<font size=5><b>2.2.3主要功能说明</b></font></p>

序号|功能名称|功能需求标识|优先级|简要解释
:--:|:--:|:--:|:--:|:--:|
1|预约座位|L1|高|本产品的核心之一，用户可以在手机上预约座位
2|扫码上座|L2|高|本产品的核心之一，用户可以扫码上座
3|时间沙漏|L5|中|记录用户在图书馆每周每月学习曲线
4|故事分享|L7|低|用户可以分享有趣的故事
5|自动下座|L3|高|系统会根据手机定位判定用户是否离开座位
6|学习时长排行|L3|中|对用户学习时长进行每日每周排行

<p><font size=6><b>2.3用户特点</b></font></p>
<p>&emsp;&emsp;&emsp;&emsp;<font size=5><b>2.3.1用户群体</b></font></p>

- 自主学习能力
- 组队学习人群
- 爱好阅读人群
- 其他人群

<p><font size=5><b>2.3.2典型用户场景</b></font></p>

姓名|学生甲
:--:|:--|
性别|男
职业|大三
目的、动机|喜欢在空闲时间阅读各类书籍
困难|经常去图书馆没有找到座位
典型场景	|甲想要去图书馆阅读书籍，但是又怕图书馆没有座位白跑一趟
用户定位	|本产品的核心功能为提供座位管理服务，可以让你随时随地在手机上都能看到图书馆座位的使用情况并对空座位进行预约

姓名|学生乙
:--:|:--|
性别|女
职业|大二
目的、动机|喜欢在图书馆自习
困难|有时候中途有事离开一下，回来后位置被他人使用了
典型场景|乙在图书馆写作业的时候，辅导员临时找她有事情，于是离开了图书馆，回来的时候就发现座位被别人坐了
用户定位|本产品还提供用户定位服务，根据你的定位，当你离开图书馆50米超过20分钟后系统会给您发信息提示，30分钟后如果你还未回到座位，系统会将你自动下座

姓名|老师丙
:--:|:--|
性别|男
职业|教师
目的、动机|偶尔需要去图书馆查阅教学资料
困难|有时候在图书馆查找资料时，不知道哪里有空座位可以坐下来
典型场景	|丙在找到一本教学资料后，在图书馆中到处寻找空座位，这一过程浪费了很多时间
用户定位	|本产品提供查看座位功能，用户可以通过手机清晰看到图书馆各个地方的座位分布以及状态

<p><font size=6><b>2.4一般约束</b></font></p>


* <font size=4>项目开发经验约束:组员都是大三的在校生，缺乏项目开发实战经验，所以此次是一个边学边做的过程
* 管理约束:每个人都有不同的想法，在做项目的过程中，当组长分配好任务后，组员间需要经过一定时间的磨合，对于组员和组长都是考验，同时遇到难题时，组长需要及时进行决策，调整方案，在组员的相互配合下完成好项目
* 技术约束:在一些技术方面存在着欠缺，在开发过程中需要不断地去学习和加强
* 硬件约束:这次项目涉及到关于位置的查询，这可能十分消耗cpu和io，资金受限的情况下使用低端服务器可能会造成在高并发情况下使得用户体验感不佳
* 网络传输约束:项目产品为小程序，应用于在线服务，用户的网络传输速率会对用户体验造成一定影响
* 安全和保密考虑:对于用户信息的存储保护，对于数据库结构合理性和安全性需要严谨的考虑</font>

<p><font size=6><b>2.5假设和依赖</b></font></p>

+ <font size=4>用户配合:假设小程序开发过程中，投放的问卷等调查能得到大量目标潜在用户的积极响应，并且调查结果具有真实性、普遍性和可靠性
+ 人员配合:假设在小程序开发过程中，全体组员都能够按质按量、高效地完成好自己所负责的部分，在推广过程中能够得到图书馆负责人和全体师生的支持
+ 软件开发平台支持:假设在小程序开发过程中所涉及的开发工具和平台都能很好地支持开发
+ 资金限制:假设该项目有足够的启动资金
+ 时间限制:假设该项目完成的时间不会前移
+ 可操作性:假设大多数用户对于该小程序都能灵活操作
+ 可行性:假设图书馆会给予项目鼓励并大力支持</font>
<br/><br/><br/><br/>
<p align=center><b><font size=7>第三章&emsp;功能性需求</font></b></p>

<p><font size=6><b>3.1&emsp;界面原型</b></font></p><br/><br/><br/>
&emsp;&emsp;&emsp;&emsp;&emsp;<img width="200" height="400" src="https://github.com/irvingming11/WeChair/raw/master/prototype_1.jpg?raw=true" />
 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<img width="200" height="400" src="https://github.com/irvingming11/WeChair/raw/master/prototype_2.png?raw=true" />
<br/><br/><br/><br/><br/>
&emsp;&emsp;&emsp;&emsp;&emsp;<img width="200" height="400" src="https://github.com/irvingming11/WeChair/raw/master/prototype_3.jpg?raw=true" />
 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<img width="200" height="400" src="https://github.com/irvingming11/WeChair/raw/master/prototype_4.jpg?raw=true" /><br/><br/><br/><br/>
 
<p><font size=6><b>3.2&emsp;硬件接口</b></font></p>
<br/>

+ 客户端：
  + WeChat用户
  + GPS模块
  + 小程序API支持
  + 网络连接支持
+ 服务端:
  + CPU：2.0GHz以上
  + 内存：8G以上
  + 带宽：100Mbps
  + 存储：100G以上

<br/><br/>
<p><font size=6><b>3.3&emsp;软件接口</b></font></p>
<br/>

+ 客户端
 + WeChat版本7.0
 + 系统定位服务启用
+ 服务端
 + Java版本1.8以上
 + Springboot 2.0以上
 + 数据库：MySQL 8.0 以上
<br/><br/>
<p><font size=6><b>3.4&emsp;通信接口</b></font></p>
<br/>

+ 传输层用TCP
+ 应用层使用HTTP
<br/><br/><br/><br/>
<p align=center><b><font size=7>第四章&emsp;非功能性需求</font></b></p><br/>
<p><font size=6><b>4.1&emsp;性能需求（精度需求）</b></font></p>

&emsp;&emsp;包括五部分的数据精度，分别如下：

&emsp;&emsp;&emsp;1.个人信息精度（学生）：
>+ 用户名：9位数字（学号），不可为空。INT
>+ 用户密码：密码由6-12个字符组成。密码只能由数字、英文字符、下划线组成。不可为空。
>+ 用户昵称：长度不超过20个字符，不包含中文、大写英文、小写英文、数字、下划线及其组合以外的特殊字符。不可为空。
>+ 用户性别：单选框，只有“男”、“女”两种选择。不可为空。
>+ 用户手机号码：只允许11位的数字组成。可为空。
>+ 用户邮箱：符合邮箱的正则表达式。包含@字符。可为空。
>+ 经纬度：decimal(10, 7)，不可为空。
>+ 座位：参考座位信息精度。
>+ 预约时间：DATE类型。可为空。
>+ 学习时长及排名：参考学习时长及排行榜精度。

&emsp;&emsp;&emsp;2.个人信息精度（管理员）：
>+ 用户名：x位数字（工号），不可为空。
>+ 用户密码：密码由6-12个字符组成。密码只能由数字、英文字符、下划线组成。不可为空。
>+ 用户昵称：长度不超过20个字符，不包含中文、大写英文、小写英文、数字、下划线及其组合以外的特殊字符。不可为空。
>+ 用户手机号码：只允许11位的数字组成。可为空。
>+ 用户邮箱：符合邮箱的正则表达式。包含@字符。可为空。

&emsp;&emsp;&emsp;3.座位信息精度（图书馆）：
>+ 区域：单选框，只有“南楼”、“北楼”两种选择。不可为空。
>+ 楼层：单选框，只有“1楼”、“2楼”、“3楼”、“4楼”、“5楼”五种选择。不可为空。
>+ 服务项目：单选框，只有“图书馆阅览一室”、“图书馆阅览二室”、“图书馆阅览三室”、“报纸、期刊阅览室”、“ 自修室”五种选择。不可为空。
>+ 座位号：1号到n号（n：视服务项目而定），INT，不可为空。
>+ 座位标识：“0”代表未使用，“1”代表正在使用，“2”代表已预约。不可为空。
>+ 经纬度：decimal(10, 7)，不可为空。

&emsp;&emsp;&emsp;4.分享信息精度：
>+ 信息标题：不允许出现除小括号、中文、数字、英文以外的特殊字符。长度在1~140字之间。不可为空。
>+ 信息标号：整型，自动生成，不为负数。不可为空。
>+ 信息内容：长度不能超过10000个字，不小于10个字。
>+ 发表时间：DATE类型，自动生成。不可为空。
>+ 修改时间：DATE类型，自动生成。不可为空。

&emsp;&emsp;&emsp;5：学习时长及排行榜精度：
>+ 日期：DATE类型，自动生成。不可为空。
>+ 时长：TIME类型，自动生成。不可为空。
>+ 排行榜名次：整型，自动生成，正整数。不可为空。
>+ 用户昵称：根据个人信息（学生）生成。不可为空。
<br/>
<p><font size=6><b>4.2&emsp;软件属性</b></font></p>
<p>&emsp;&emsp;&emsp;&emsp;<font size=5><b>4.2.1&emsp;可靠性</b></font></p>
&emsp;&emsp;在规定的条件下和规定的时间区间完成规定功能的能力。规定的条件是指直接与软件运行相关的使用该软件的计算机系统的状态和软件的输入条件，或统称为软件运行时的外部输入条件；规定的时间区间是指软件的实际运行时间区间；规定功能是指为提供给定的服务，软件产品所必须具备的功能。软件可靠性不但与软件存在的缺陷和（或）差错有关，而且与系统输入和系统使用有关。
<p>&emsp;&emsp;&emsp;&emsp;<font size=5><b>4.2.2&emsp;可用性</b></font></p>
&emsp;&emsp;在一定的条件下，产品还能够正常提供服务，尽可能做到对用户来说有效、易学、高效、好记、少错和令人满意<br/>
<p>&emsp;&emsp;&emsp;&emsp;<font size=5><b>4.2.3&emsp;安全保密性</b></font></p>
&emsp;&emsp;信息安全保障体系：建立统一的身份认证体系、建立统一的信息安全管理体系、建立规范的信息安全保密体系、建立完善的网络边界防护体系；加密和解密技术：加密算法、数字证书、身份认证技术；安全协议：IPSec协议、SSL（Secure Socket Layer）协议、PGP（Pretty Good Privacy）协议<br/>
<p>&emsp;&emsp;&emsp;&emsp;<font size=5><b>4.2.4&emsp;可维护性</b></font></p>
&emsp;&emsp;维护人员为纠正软件的错误或缺陷以及满足新的需求而理解、修改和改进软件的难易程度。软件维护并不只是修改错误，为维护的最终目的，是满足用户对软件的性能与运行环境不断提高的需求，进而延长软件寿命。
<br/><br/><br/><br/>
<p align=center><b><font size=7>第五章&emsp;验收验证标准</font></b></p>
<br/><br/>
<table>
  <tr>
    <td>测试功能</td>
    <td>测试项</td>
    <td>输入/操作</td>
    <td>检验点</td>
    <td>预期结果</td>
    <td>验收情况</td>
  </tr>
  <tr>
    <td rowspan=6>主页面</td>
    <td>扫码上座</td>
    <td>点击下方导航栏中间绿色按钮</td>
    <td>获取摄像头权限并进行扫码</td>
    <td>使用扫码上座功能扫描桌子上的二维码显示座位信息并点击确认或取消返回主界面</td>
    <td></td>
  </tr>
  <tr>
    <td>预约座位</td>
    <td>点击首页的预约座位</td>
    <td>能在预约页面浏览到座位分布情况和空座情况同时进行相应预约</td>
    <td>点击成功后会看到座位的分布情况和空座情况也能实时进行空座预约</td>
    <td></td>
  </tr>
  <tr>
    <td>学习排行</td>
    <td>点击下方首页学习排行</td>
    <td>查看自己学习时间或进度排名</td>
    <td>按时间（日/周/月）对学习时长进行累加得到自己学习时间，并在全校所有用户中按由高到低的时长排名</td>
    <td></td>
  </tr>
  <tr>
    <td>书籍推荐</td>
    <td>点击首页书籍推荐模块</td>
    <td>定期推送优质书籍文章的推荐</td>
    <td>按日期呈现推荐的书籍名称、简介、推荐理由等</td>
    <td></td>
  </tr>
  <tr>
    <td>时间沙漏</td>
    <td>点击首页时间沙漏模块</td>
    <td>记录用户的学习曲线</td>
    <td>查看自己每周每月的学习曲线，实时定位自己的学习目标</td>
    <td></td>
  </tr>
  <tr>
    <td>故事分享</td>
    <td>点击首页故事分享模块</td>
    <td>分享跟图书馆之间的故事、经历和鸡汤</td>
    <td>利用用户投稿分享故事，或者选取优质的故事分享到WeChair平台上</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan=6>信息界面</td>
    <td>个人信息</td>
    <td>点击头像右边按钮</td>
    <td>查看或修改个人信息</td>
    <td>用户可以修改自己的性别、昵称、地址；显示用户的头像、ID、真实姓名、学校、学号、专业、手机号码（这些是手机绑定和学生认证所填写的信息）</td>
    <td></td>
  </tr>
  <tr>
    <td>学生认证</td>
    <td>点击信息界面学生认证</td>
    <td>认证学生个人信息</td>
    <td>用户填写自己的真实姓名、学号、学校（选择）、专业（选择），若填写信息与数据库匹配成功则认证成功</td>
    <td></td>
  </tr>
  <tr>
    <td>预约记录</td>
    <td>点击信息页面预约记录</td>
    <td>查看最近预约记录</td>
    <td>可以查看实时预约记录，也可以查看历史预约记录</td>
    <td></td>
  </tr>
  <tr>
    <td>扫码记录</td>
    <td>点击信息页面扫码记录</td>
    <td>查看最近扫码记录和扫码座位信息</td>
    <td>显示实时扫码记录也可查看历史扫码记录</td>
    <td></td>
  </tr>
  <tr>
    <td>意见反馈</td>
    <td>点击信息界面意见反馈</td>
    <td>用户可结合自身用户体验对WeChair提出意见反馈</td>
    <td>可以在文本栏目中填写对我们的意见并发送，发送至我们指定邮箱</td>
    <td></td>
  </tr>
  <tr>
    <td>授权登录</td>
    <td>点击信息界面授权登录</td>
    <td>弹出授权获取用户信息弹窗</td>
    <td>当用户点击允许授权时，小程序将获取用户信息，并在登录页的用户信息板块显示用户的微信头像、微信昵称。（用户也可以自己更改头像）</td>
    <td></td>
  </tr>
  
</table>
