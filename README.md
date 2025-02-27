# WechatMomentScreenshot

朋友圈转发截图生成工具

[去这里使用](https://transparentlc.github.io/WechatMomentScreenshot)

本工具仅可用于**个人应付各类强制要求转发朋友圈的情形**，请不要用于以下用途：

* 将生成的截图用于**造谣诽谤、微商宣传、灰色产业、数字藏品**等非法或令人反感的用途
* 使用各种方式大量批量生成截图
* 将源代码或生成的截图有偿售卖
* 以 **“关注○○，发送○○获取工具地址”** 等方式为自己的公众号**引流**，或将这个工具和源代码的链接通过“关注可见”、“登录可见”、“回复可见”等方式隐藏（想要推荐的话，在正文里留下地址或二维码之类的就没问题～）

不接受定制请求，~~有功能请求可以添加 Issue，如果建议合理的话我可能就会添加～~~我怎么能写出这么乱的代码……**因为自己改起来都费劲，所以不会再加新功能了。**

似乎是由于有广告机滥用 GitHub Pages 和 git.io 发广告，所有 git.io 短链接已获得微信的“绿色网站认证”。~~如果你需要在微信中使用，请使用完整链接 https://transparentlc.github.io/WechatMomentScreenshot~~ Yattaze！这个工具也已经荣获微信的“认证”啦！(　\^ω\^) 当然我更建议你抵制或尽量减少使用这类**正在制造“墙中墙”的 APP**。

如果你打开 GitHub Pages 比较困难，或者习惯于在微信等 APP 的“墙中墙”里享受局域网中冲浪的乐趣，可以选择下面的镜像站：

* 由 [@794TD](https://github.com/794TD) 提供：https://wl.shadiaoforever.xyz/
* 由 [@gaohan085](https://github.com/gaohan085) 提供：https://gaohan086.xyz/wechat/
* 由 [@drpasserby](https://github.com/drpasserby) 提供：https://my.wulvxinchen.cn/makewechat/
* 由 [@Allenorz](https://github.com/Allenorz) 提供：https://www.wanshiwutool.cn/
* 由 [@jinzi1007](https://github.com/jinzi1007) 提供：https://quziyuan.cn/zhuanti/zhuanfa/

目前使用的获取公众号文章的封面图和标题的 API 是我自己部署在 Cloudflare Worker 上的，你也可以自行部署 `get_article_info.php` 并修改网页上的相关前端代码来调用。

本工具是开源的，但是由于这个工具是我初学前端时写的，源代码非常混乱，所以即使开源了也没有多少学习的价值（暂时也没有重写的打算）。不过，你仍然可以下载源代码到自己的服务器上来部署一个镜像站，然后通过 Issue 提交镜像站地址～别忘了从这里获取最新的更新。

在自行部署时，请遵守以下规则：

* 请不要删除页脚的原作者相关信息以及右上角指向这个 repo 的链接。
    * 添加了一些加密后的代码对上面的删除行为进行检测，但是我也保留了原始的代码。虽然很容易就可以绕过，不过我并不希望你这么做。
    * 你可以在保留以上信息的基础上额外添加与自己的网站相关的文本和链接。
* 你可以添加自己的打赏相关信息、返利链接、收费服务广告、开通了流量主的公众号宣传等用于平衡域名、服务器等的开支（拿去喝快乐水什么的也不是不行），但是在这种情况下请保留原作者的打赏相关信息，并进行显著的区分。
    * 如果你不需要添加这类内容，则可以移除原作者的打赏相关信息。

### ⚠️ Hall of Shame ⚠️

以下网站二次部署时存在**抹去页脚的原作者相关信息、或移除右上角的指向这个 repo 的链接等违反了上面的使用规则的行为**，在此列出来批判一番。

这里不是为这些网站引流的地方，所以用 `(dot)` 替换了链接中的 `.`。

* h**ps://www(dot)41661(dot)com/ 移除原作者信息和源代码链接，目前以“本工具全新开发中”为理由关闭了截图生成功能，但实际上也并没有为本仓库提交过任何代码
* h**ps://dz(dot)luyashe(dot)top/ 移除原作者信息
* h**p://zan(dot)liflag(dot)cn/ “立 flag 网” 移除原作者信息和源代码链接
* h**ps://zxxgj(dot)net/tools/tuxiang/pyqjietu/ “在线小工具” 移除原作者信息和源代码链接
* h**ps://oss(dot)361s(dot)cn/tool/pyq/ “天乐博客” 移除原作者信息和源代码链接
* h**p://www(dot)chwl2015(dot)cn/ 移除原作者信息和源代码链接
* h**ps://www(dot)yeyulingfeng(dot)com/tools/zan/ “夜雨聆风” 移除原作者信息和源代码链接
* h**p://pyq(dot)cttuwen(dot)cn/ 移除源代码链接
* h**p://wxpyq(dot)ssltgm(dot)com/ “三石论坛” 移除原作者信息和源代码链接
* h**ps://www(dot)dkewl(dot)com/code/detail2196.html “刀客源码” 移除原作者信息和源代码链接
* h**ps://www(dot)chichisvip(dot)com/post/37497.html “痴痴资源网” 有偿售卖源代码
* h**ps://mirror(dot)xyz/z22222.eth/2DBLOfyd05xlHqOdBD0-ZI1pejXp009838kLvrVSDv0 “Free DAO” 在介绍中诱导将生成的截图有偿售卖和用于灰产，公众号和私域流量引流
* h**p://www(dot)jikexq(dot)cc/pyq/ “极客星球/宇宙领域科技” 移除原作者信息和源代码链接
* h**p://www(dot)jikexq(dot)cc/p/ “极客星球/宇宙领域科技” 同上，并对检测是否删除原作者相关信息的源代码进行恶意对抗
* h**p://xnw(dot)51tongxin(dot)cn/ 移除原作者信息和源代码链接
* h**p://h5(dot)05zh(dot)com/erji/pyqdzsc/ “库简盒 APP” 移除原作者信息
* h**ps://baitan(dot)lepinpin(dot)cn/dz/ “皇冠联盟数据工作室” 移除原作者信息
* h**p://lanmei(dot)freeee(dot)ml/pyq/ “蓝魅网络科技” 移除原作者信息和源代码链接
* h**p://pyq(dot)ggahh(dot)cn/ “郭郭爱花花” 移除原作者信息
* h**p://api(dot)xiaok1(dot)com/web/WechatLike/ 移除原作者信息和源代码链接
* h**ps://soujiz(dot)com/web/wechatimg/ “大雄搜集站” 移除原作者信息和源代码链接
* h**ps://soujiz(dot)com/10084.html “大雄搜集站” 有偿售卖整合本工具源代码的“全功能在线截图生成器工具网页版”，这一整套源码也极有可能并非该网站原创，原作者我暂时没有考证到，但在别的地方找到了时间更早且免费发布的[同一套源码](https://www.bilibili.com/read/cv22111444/)
* h**ps://lab(dot)adoi(dot)cn/html/pyq/ “多易 Web 实验室” 移除原作者信息和源代码链接
* h**p://vx(dot)alphag(dot)cn/ “小刀娱乐网” 移除原作者信息和源代码链接
* h**ps://api(dot)qiuliqi(dot)top/wx_pyq/ “小秋秋 API” 移除原作者信息
* h**ps://lijile(dot)github(dot)io/moment/ 移除原作者信息和源代码链接，将源代码链接替换为自己的 repo 后重新上传到 GitHub
* h**ps://latejust(dot)com/jizan/ “爱吃柑橘啊” 移除原作者信息和源代码链接
* h**ps://by(dot)mp4tu(dot)vip/wxjz/ 移除原作者信息和源代码链接
* h**p://tool(dot)mf2(dot)cn/gongju/pyq/index.html “魔方超级外链工具” 移除原作者信息
* h**ps://www(dot)php-asp(dot)net/product/view1047.html “好源码分享/爱源码” 有偿售卖源代码
* h**ps://wechat(dot)sxcto(dot)com/give_a_like.html 移除原作者信息和源代码链接
* h**ps://ourboy(dot)cn/dz/ 移除原作者信息和源代码链接
* h**p://app(dot)ippapp(dot)com/screenshot/ “小杯子 PYQ 截图生成工具” 移除原作者信息和源代码链接
* h**ps://www(dot)nbey(dot)net/ “Nbey WeChat Moments Build Tool” 移除原作者信息和源代码链接
* h**ps://icoolgo(dot)com/Tools/tuijian/pyq “花式玩客” 移除原作者信息和源代码链接
* h**p://pyq(dot)regqq(dot)com/ “宝尊网络” 移除原作者信息和源代码链接
* h**p://www(dot)99pan(dot)top/w/4/index.html 移除原作者信息和源代码链接
* h**ps://pyq(dot)soux2(dot)com/ “搜小二导航” 移除原作者信息和源代码链接
* h**p://www(dot)sxw818(dot)com/ymfb/pyqdz/ “四夕网” 移除原作者信息和源代码链接

---

### 这个小工具是什么？

一个因为不喜欢也不想往朋友圈发某些不得不发的废文而做出来的摸鱼产物。

### 为什么生成的截图和我在手机上截的不一样？能不能做出 iOS 的样式？

不同手机的界面总是有那么一点区别的，要和真正的截图完全一样……我也很难办啊！（摊手）

如果实在是很在意通知栏的样式的话，可以从自己的手机上截一个通知栏的图然后覆盖上去……

2023.5.8 更新：iOS 的样式已经添加了，不过因为我并没有 iOS 设备，所以只能参考网上找到的截图来写样式，**不一定能做到和实机一样**。

2023.6.14 更新：已经添加了使用自定义通知栏图片的选项。可以自行在手机上截图并裁剪出通知栏部分，然后使它出现在生成的截图上。

### 生成的截图中，文字部分能否出现表情符号？

微信中除 Emoji 之外的其它表情符号实际上是特定的文本，复制后粘贴到别处时就可以看到，在微信中则显示为表情符号。

比如<img src="https://ae01.alicdn.com/kf/HTB1kEKaXe3tHKVjSZSg7604QFXas.png" style="width:1em">这个表情，从简体中文版微信中发送的实际上是`[再见]`，繁体中文是`[再見]`，英文是`[Bye]`。即使不选择表情符号而是手动输入`[再见]`、`[再見]`或`[Bye]`（任选一个输入即可，和微信的语言设置无关），发送后它们都会显示为<img src="https://ae01.alicdn.com/kf/HTB1kEKaXe3tHKVjSZSg7604QFXas.png" style="width:1em">。

在这个小工具的“正文”处输入表情符号对应的文本，生成截图时也会被替换成对应的表情符号～

目前仅支持简体中文、繁体中文、英文版微信的表情文本。从使用其他语言的微信发送一条带有表情的消息然后复制到这里，生成的截图中不一定会出现对应的表情符号。

### 头像是从哪来的？

头像是我自己手动从<abbr title="新浪微博">肖浪微博</abbr>、<abbr title="知乎">故事乎/带货乎</abbr>、<abbr title="哔哩哔哩">睿站</abbr>等网络社区转存的。如果你在此工具中发现了你正在使用的头像则纯属巧合。

另外，头像并未按照不同类型出现的频率整理，也就是说某种类型的头像在截图中出现的概率可能会明显偏离实际 ( ﾟ∀。)

### 更新记录

<details>

<summary>点击展开</summary>

#### 2021.12.7

添加评论的时候可以使用随机的用户名和头像了。另外还加了一些功能以模拟转发视频号的效果。

#### 2021.10.6

可以将正文中以 # 开头的朋友圈话题和 URL 以蓝色显示了。

#### 2021.9.11

还是在那位打赏者的建议下，现在可以在评论开头加上“回复○○：”的字样了。

#### 2021.9.3

在一位打赏者的建议下，增加了将点赞的第一个头像固定为自己的选项。发完集赞朋友圈之后立即给自己点一个赞的人应该不少吧？(っ'ω')っ

#### 2020.6.20

生成截图的时候将会把一些设置使用 localStorage 保存，下次打开小工具的时候就不需要重新设置一遍了～

将会保存以下设置：

* 用户名
* 头像（但是不要选择文件大小很大的头像啊……）
* 正文
* 定位
* 转发出处
* 图片长度
* 使用 7.0 以上版本白色界面
* 显示 APP 图标
* 随机信号和电量

#### 2020.5.26

由于自己的服务器用了 Cloudflare 的免费 CDN，然而最近分配到的 IPv4 地址被墙了，所以后端（在墙内）不能用了……

于是试着用 Cloudflare Worker 写了个~~简单的代理~~（参见文件 `cfworker_proxy.js`）解决之(〃′▽`)~~

直接使用 [Images.weserv.nl](https://images.weserv.nl/) 的服务中转图片，就不需要部署后端了！

#### 2019.12.5

~~解决了一些已知问题。~~

支持选择生成 7.0 以上版本白色界面的截图。

#### 2019.6.8

还是根据 [Issue #4](https://github.com/TransparentLC/WechatMomentScreenshot/issues/4)，增加了在生成的截图中设定评论的功能～ฅ•̀∀•́ฅ

#### 2019.6.6

根据 [Issue #4](https://github.com/TransparentLC/WechatMomentScreenshot/issues/4) 修正了时间显示的问题。

* 截图日期和发表日期在同一天，时间显示为`**:**`。
* 截图日期在发表日期前一天，时间显示为`昨天 **:**`。
* 其他情况，时间显示为`****年**月**日 **:**`。

现在可以用短链接 [https://git.io/WMS](https://git.io/WMS) 打开本工具了～欢迎分享给有需要的人(`ヮ´ )

~~也欢迎请小透明喝肥宅快乐水(\*´∀`)~~

#### 2019.5.14

新功能：输入微信公众号文章链接，自动获取文章标题和封面。

* 相关后端代码参见文件 `get_article_info.php`。

#### 2019.3.1

新功能：生成发表纯文字或图片的截图。

</details>
