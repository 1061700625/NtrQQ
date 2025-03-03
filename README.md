
# NtrQQ

`NtrQQ`是一款为`QQ PC版`打造的一款集显IP、去广告、功能增强等功能于一体的辅助插件，使用`NtrQQ`可以让你的`PCQQ`更实用、更好用。
- 本软件是作者业余时间制作，由于作者平时较长时间都是在学校度过，很少上网，如果更新速度变慢，请大家不用着急。
- ~欢迎进入[社区(bbs.ntrqq.net)](https://bbs.ntrqq.net/)，或添加交流群(`①135807262`、`②2915042`)，与其他志同道合的朋友交流使用心得~。(社区已禁止注册)

# License

- 下述 **本软件** 为 **NtrQQ** 插件的略称
- 本软件的开发、制作和分享仅为了学习和研究QQPC版软件内含的设计思想和原理，因兴趣而开发，您需要保证您的使用是为了学习和交流、且不会用于商业用途。
- 本软件是免费软件，使用软件过程中出现的问题欢迎咨询，但因使用本软件产生的一切后果由您自行承担，作者不会对本软件承担任何责任。
- 本软件内的IP数据来源全部由网络提供，不会采集您的个人信息，其中高级探测功能为本软件论坛会员专用功能，不对外开放。
- 由于本软件的特殊性质，某些杀毒软件会干扰程序的正常运作，如您相信本软件的安全性并希望使用，请放行。
- 本软件作者对上述条约享有最终解释权，请您遵守。本软件并非强制您安装使用，也没有垄断行为，若您不同意上述条款，请勿使用、并立刻删除本软件的相关文件。

# Setup

### 安装说明
1、先运行“补丁.exe”。
2、再请将QQ原版`Bin(目录)`下的`HummerEngine.dll`**改名**为`HummerEngineBase.dll`再将本插件的下述文件**放入**。
3、然后将“NtrQQ”文件夹和几个“dll”文件，复制到QQ`Bin(目录)`下。
4、正常运行QQ即可。（最新测试可用QQ9.6.3版本）

### 文件介绍
下列文件是本插件的相关文件及说明：
- QQ/bin/HummerEngine.dll（**必须**，程序载入点）
- QQ/bin/NtrQQ/
    - NtrQQ/NtrQQ.dll（**必须**，本插件主程序）
    - NtrQQ/NtrQQ.ini（**必须**，本插件主配置文件）
    - NtrQQ/Plugin.ini（**必须**，QQ插件管理配置文件）
    - NtrQQ/Version.ini（**必须**，QQ版本号数据配置文件）
    - NtrQQ/Verify.ini（可选，本插件高级功能验证配置文件）
    - NtrQQ/ShowIP.exe（可选，纯真IP数据库管理器）
    - NtrQQ/qqwry.dat（可选，纯真IP数据库文件）
    - NtrQQ/location.loc（可选，LoCi格式IP数据库文件）

### ~高级功能开启方法~ (社区已禁止注册，无法使用高级功能)
1. 用记事本打开`NtrQQ/Verify.ini`配置文件
2. 在`[NTRQQ]`节的`UID=`后，输入您的论坛ID（数字）
3. 打开网页 https://bbs.ntrqq.net/md5.html
4. 输入您的论坛登陆密码，点击计算
5. 在`[NTRQQ]`节的`PWD=`后，复制刚才计算出的MD5值
6. 重启QQ后随意打开一个好友的聊天窗口，在窗口边框处右击即可看到高级功能的菜单

# New Features

### NtrQQ 5.0.2
- 修复 兼容 QQ9.0.5
- 修复 高级探测功能
- 优化 默认高精度IP查询点显示运营商信息
- 优化 被部分杀软误报的问题
- 更新 QQ版本号数据库至 2018-08-18

### NtrQQ 5.0.1
- 修复 兼容 QQ9.0.4
- 修复 好友关系分析
- 优化 重构近半数代码
- 优化 高级探测功能提交及查询模块
- 优化 默认在线IP库查询点设置为IPIP高精度查询
- 优化 自定义IP查询点支持HTTPS安全协议
- 优化 自定义IP查询点支持POST方式
- 优化 自定义IP查询点改为正则匹配方式
- 新增 批量好友关系分析功能
- 更新 QQ版本号数据库至 2018-06-24

### NtrQQ 5.0.0
- 修复 兼容 QQ9.0.0
- 优化 主程序代码结构
- 更新 QQ版本号数据库至 2018-01-24

# Release Info

>[Lance.Moe](https://www.lance.moe/)  
>2018-08-18 (_Beijing time_ zone)  
>In Xuzhou, Jiangsu, China  
  
[BBS.NTRQQ.NET](https://bbs.ntrqq.net/)
