[![Contributors](https://img.shields.io/github/contributors/bgzo-sandbox/make-vxna-great-again.svg?style=for-the-badge)](https://github.com/bgzo-sandbox/make-vxna-great-again/graphs/contributors)
[![Forks](https://img.shields.io/github/forks/bgzo-sandbox/make-vxna-great-again.svg?style=for-the-badge)](https://github.com/bgzo-sandbox/make-vxna-great-again/network/members)
[![Stargazers](https://img.shields.io/github/stars/bgzo-sandbox/make-vxna-great-again.svg?style=for-the-badge)](https://github.com/bgzo-sandbox/make-vxna-great-again/stargazers)
[![Issues](https://img.shields.io/github/issues/bgzo-sandbox/make-vxna-great-again.svg?style=for-the-badge)](https://github.com/bgzo-sandbox/make-vxna-great-again/issues)
[![Licence](https://img.shields.io/github/license/bgzo-sandbox/make-vxna-great-again.svg?style=for-the-badge)](https://github.com/bgzo-sandbox/make-vxna-great-again/blob/template/LICENCE)
[![Telegram](https://img.shields.io/badge/-telegram-black.svg?style=for-the-badge&logo=telegram&colorB=555)](https://t.me/imbGZo)


# VXNA Alternatives

This is a replacement for https://www.v2ex.com/xna, for the following reasons:

1. No censor, or small censor;
2. More open, more transparent;

The latest blog collected by v2ex is https://www.v2ex.com/xna/s/543, yet the public index (https://www.v2ex.com/xna) only shows `472` entries. The 71 missing blogs — removed for unknown reasons — are exactly why this project exists.

Latest source pull status: see [docs/status/latest-fetch-status.md](docs/status/latest-fetch-status.md).
This page is overwritten on each fetch run and only keeps the latest execution result.

Blocked sources are configured in [config/block.yaml](config/block.yaml).
Use `blocked_root_domains` with website root domains such as `example.com`.
Blocked domains are skipped during fetch and excluded from README and status output.


## Last Week Blog

| Date | Title | Summary |
| --- | --- | --- |
| 2026-09-26 | [是琐碎的小事让我活着](https://www.geedea.pro/article/little-things/) | 这几天试了试不同的搜索引擎，其实也没有厌倦 Kagi，只是他们似乎在往邮件、新闻这些业务上拓展了，让我有点担心某天会发病，所以在物色替代品。搜索关键词很自负地搜了自己博客的名字，结果发现两三个镜像站聚合了我的 RSS，然后用语言模型生成了非常诡异的总结，还改了我的标题，机翻了我的英文文章。罢了，不去… |
| 2026-09-26 | [Node.js、浏览器和 Cloudflare Workers 的wasm引入问题](https://blog.est.im/2026/stdout-36) | 最近在鼓捣 WebAssembly，这玩意没啥神秘的，可以看出一坨二进制的 .js 库文件 它本身的export和调用方式是统一的，但如今天我才知道，在不同 JavaScript 运行环境加载 .wasm 方式并不完全一样。 例如 Cloudflare Workers 可以直接： import wa… |
| 2026-09-26 | [出海赚美金:博客域名忘记续费了](https://dsx2016.com/going-global-to-earn-dollars-forgot-to-renew-the-blog-domain/) | 域名过期 前些天感冒，一个星期没好，所有业务都没有时间处理 就在这个敏感时间点，我的博客域名过期了，域名已经被... 出海赚美金:博客域名忘记续费了 最先出现在 大师兄2016 。 |
| 2026-09-26 | [Coffee Break Clojure, Vol.3](https://www.geedea.pro/article/clj3/) | 上一篇 我们讨论了不同类型的形式，了解了函数、Lambda、宏和特殊形式的皮毛，也学会了用一些基本的运算符、 let 和 if 等等。今天的文章要讨论集合数据类型。不过在此之前，我们还是先看看普通的数据类型有哪些。 今天的文章有点长，所以读的时候，呃…… 准备一杯大号的咖啡？ 你已经知道和你可能不知… |
| 2026-09-26 | [弥月佳期-中秋修水行记](https://yovey.me/%e5%bc%a5%e6%9c%88%e4%bd%b3%e6%9c%9f-%e4%b8%ad%e7%a7%8b%e4%bf%ae%e6%b0%b4%e8%a1%8c%e8%ae%b0/) | 清早出发，出城前先在Manner打好咖啡，一路西行。 行至三分之一，过路口的时候低速避让，路肩不平，点不到地， … Continue reading "弥月佳期-中秋修水行记" |
| 2026-09-26 | [开发了一个云剪贴板服务 Cloud Clipboard](https://hellodk.cn/post/1231) | 跨设备复制粘贴，文本 / 图片 / 文件，一个链接搞定。在电脑 A 上创建一条剪贴板，得到一个形如 https://paste.940304.xyz/a7 的短链接；在手机或另一台电脑上打开这个... |
| 2026-09-26 | [第一次拜月娘](https://www.hecaitou.com/2026/09/worshipping-moon-goddess-first-time.html) | 我经历过五十多个中秋，今年第一次在中秋夜拜月娘。 如果严格按照潮汕的拜月娘风俗，我最多只能帮着搬一下供桌和拜垫，上香这种事情根本轮不到我，因为在潮汕传统上拜月娘是女性的专属。月亮属阴，象征女性，自己人拜自己人很合理。 但我人在北京，一起赏月的一群人都不是本地人，而是一代移民。说起来，我们各自都是各家… |
| 2026-09-26 | [Coffee Break Clojure, Vol.2](https://www.geedea.pro/article/clj2/) | 上一篇 我们配置好了 REPL，可以随时开始编写 Clojure 代码并执行。 第零篇 提到，被求值（Eval）的列表叫作形式（form），形式的第一个元素是操作符，剩余的是参数。根据操作符的不同，形式被分为函数形式、Lambda 形式、宏形式和特殊形式。今天的文章就来介绍这几种形式。 函数形式 不… |
| 2026-09-26 | [2004，没有暑假的夏天](https://www.tortorse.com/archives/2004-summer-without-vacation/) | 招聘会上，人们在展位间看招聘信息 |
| 2026-09-26 | [Python 潮流周刊#169：AI 用 11 天证完费马大定理、Python 拟加 export 关键字、一个 Key 调 3000 个工具](https://pythoncat.top/posts/2026-09-26-weekly/) | 分享了 12 篇文章，12 个开源项目 |
| 2026-09-25 | [13.8 万星的 free-for-dev：57 类免费额度，替掉我一半的付费订阅](https://gugegt.com/free-for-dev-free-tier-guide.html) | 上周整理订阅列表，发现有 9 个服务在按月扣钱。一个数据库，一个对象存储，一个监控，一个错误追踪，两个只在周末跑一次定时任务的小机器，还有几个我自己都想不起什么时候开通的。 加起来一个月 60 多美元，折人民币四百多。 这些活儿有一个共同点：全都不需要付费。我把账单截图丢进 free-for-dev… |
| 2026-09-25 | [中秋快乐](https://blog.solazy.me/20260925/) | 中秋节过得越来越平静了 |
| 2026-09-25 | [这种效果搭配秒控板，不要太爽啊！我想要这](https://versun.me/blog/tweet-2103436216138121265) | Zsolt Kacso I wanted infinite canvas for my desktop. So I built it with Omarchy and Opus. I'm calling it Phantomat. Grab here: https://github.com/kaol… |
| 2026-09-25 | [Pensieve: 2609](https://xiaket.github.io/2026/pensieve-2609.html) | 所读所观所玩 |
| 2026-09-25 | [怯犬](https://www.geedea.pro/fiction/doggy/) | 一 今晚没有月亮，窗户外面其他人家的灯火也灭了，屋子里很黑，杉松迷迷糊糊地醒了。耳塞不能阻断嗅觉，好几个晚上，他都被香水、汗液和石楠花的味道弄醒，醒来时，他还紧紧地抱着一只玩偶，脸埋在沙发的靠背上。他感到背后有风，一阵远远的响动，随后皮革的气味取代了那些扰人心智的东西。他翻了个身，刚好碰到男友的手臂… |
| 2026-09-25 | [《火焰纹章 封印之剑》游戏感想](https://blog.yuanji.dev/posts/fire-emblem-fuuin-no-tsurugi-review/) | 接连写了两篇博客分别介绍了最近购买的复古游戏掌机（见：复古掌机初体验：ANBERNIC RG 34XX）和围绕 […] |
| 2026-09-25 | [终日网上翻垃圾](https://www.hecaitou.com/2026/09/dumpster-diving-on-the-modern-web.html) | 今天是中秋节，我想聊一点轻松的话题。 这几天我在选电脑显示器，目前我正使用的一台华硕显示器和苹果系统八字越来越冲，会频繁自动黑屏，然后又自动点亮。你想象一下，一个人站在空荡荡的房间里面对一套电脑，然后它毫无征兆地熄灭，等一会儿又自顾自地亮起来。你就说这时候是不是想上网买几道符回来给它贴满？ 再后来即… |
| 2026-09-25 | [简单让 AI 对比了下 4款 Agent](https://versun.me/blog/tweet-2103297487486513598) | 简单让 AI 对比了下 4款 Agent 网关工具， 分别是：magpie · cc-switch · CLIProxyAPI · AstrLink 供参考：https://agent-gateway-compare.versun.me |
| 2026-09-25 | [开水](https://mobius.blog/25780.html) | 这个标题来自于坐在我旁边的陌生人，正起身去咖啡厅吧台要求工作人员，往自己的茶杯里接了一杯开水。 她想让工作人员 […] —— 感谢订阅 莫比乌斯 ，如你有任何疑问、观点交流，请前往 创作者频道 ，或 私信 联系。 |
| 2026-09-25 | [这是吹起 ai 网关的风吗，这2天已经看](https://versun.me/blog/tweet-2103279669412065313) | yetone One more thing https://usemagpie.ai/ 这是吹起 ai 网关的风吗，这2天已经看到3个大佬在做同样的东西了 |
| 2026-09-25 | [opus 5.5 上下文在 256k 左](https://versun.me/blog/tweet-2103279251948707998) | opus 5.5 上下文在 256k 左右就会出现失忆，我已经遇到2次了，pi agent (max 1M) |
| 2026-09-25 | [Raft 开源了！ 但以一种很有意思的方](https://versun.me/blog/tweet-2103274356134830482) | stdrc https://x.com/i/article/2103157543891853312 Raft 开源了！ 但以一种很有意思的方式开源，建议看看 |
| 2026-09-24 | [一个值得关注的事： Cloudflare](https://versun.me/blog/tweet-2103266492137840882) | 一个值得关注的事： Cloudflare 的 Python Workers 正式 GA， 原生支持 FastAPI 与 Django，可玩性大大提升了 https://blog.cloudflare.com/python-workers-ga/ |
| 2026-09-24 | [上学路](https://honmaple.me/posts/2026/09/my-way-to-school/) | 我没有上过幼儿园，我是四岁时上了一年的学前班，接着就开始上一年级。我的妈妈经常说本来老师是不准备接收我的，因为当时我还太小，初入学前班时甚至还不到四岁，可是我哭得太厉害，死活要去上学，最后没办法他们只能和当时的校长也就是我们学前班的老师求情，最终老师还是接收了我。 我是在村委会所在地上的一二年级，离… |
| 2026-09-24 | [CLM-8B，比jev还要块还要准的模型](https://versun.me/blog/tweet-2103242309995569321) | Jacky Kwok Introducing Contrastive Language Model (CLM): an ultra-fast System One Model trained with a contrastive learning objective that connects st… |
| 2026-09-24 | [博客三周年，依旧是一些记录](https://blog.mfwt.top/index.php/archives/1633/) | 9/24，明天就中秋了，也是博客正式开始运行的三周年日子，特此纪念。同时，基本上也是决定停止Google AdSense投放的日子。 |
| 2026-09-24 | [博客时光机 2.0：在一台 Macintosh 里看见时间](https://liudon.com/posts/hugo-ipfs-time-machine-v2/) | 前言 9月21日，博客时光机 V1 版本上线。 当时满心欢喜，自己觉得还挺好玩。 但上线后，现实给我泼了一盆冷水。 虽然也在 V2EX 上发帖做了推广，上线到现在，一共才有68次浏览。 |
| 2026-09-24 | [他说的不一定对](https://blog.solazy.me/202609/) | 今天浅谈个生活中的小事儿引发的思考 |
| 2026-09-24 | [读《中国历代政治得失》](https://depp.wang/2026/china-dvnastic-political-systems/) | 我最开始是在一位同事那里了解到这本书的。 最开始也看了一点，感觉写得比较干，讲的都是制度、官职和税收，就没继续读下去。后来因为看了《万历十五年》，我又想到了这本书。那时我正想了解明代的历史，于是先看了明朝和清朝，之后又把前面的汉朝、唐朝、宋朝都看完了。 这本书还是有很多观点，是我以前从没有想到过的。… |
| 2026-09-24 | [天展钓Tenkara和在Folkestone挖化石](https://anotherdayu.com/tenkara-folkestone/) | 天展钓 Tenkara 在英国试了试天展钓。 它原本是日本山地溪流里的一种钓法。没有线轮，也不需要复杂的饵和线组。 主体就是一根竿，一根线，一只毛钩。 Less is more，钓鱼这件事变得更依赖人本身。要观察鱼在哪里，看水从石头哪一边流过，哪里形成回水，哪里有树荫，哪里水深突然变化。固定长度的线… |
| 2026-09-24 | [如何优雅地更新 MACOS 系统上的软件](http://yi.gs/post/duo_updater) | 上一次更新正好是一年前，所以更新一下。 既然是为了更新而更新，就来写写如何更新吧 ；） TL;DR：直接看 「更优雅地更新软件」 小节。 关于 macOS 上的软件安装 与 iOS 正常情况下只能通过 App Store 安装 APP 不同，macOS 有类似 Windows 的自由度来安装和使用第… |
| 2026-09-24 | [高鲁棒性 API 设计之 Idempotency Key：并发请求与执行一致性](https://blog.yasking.org/a/idempotency-key-concurrency-control) | 高鲁棒性 API 设计系列 1 Idempotency Key 幂等键 2 并发请求与执行一致性 上一篇介绍幂等键留下一些问题，幂等键有了，如果两个请 … |
| 2026-09-24 | [青甘行 序曲](https://hux.ink/posts/qinggan-trip-01/) | 「中秋」说每年带娃出去旅行一趟，今年继续执行。 今年选择的目的地是青海—甘肃大环线自驾游。她原本的计划是国庆期间去海南环岛游，问我要不要去当司机。我说与其去海南，不如再请三天假，与中秋节连休，组个超长假去新疆或走一趟青甘环线。 一拍即合，选定了青甘行。一个多月前，我提前报备请假获批，「中秋」同学便正… |
| 2026-09-24 | [专业的网络延迟波动检测工具 irtt](https://blog.frytea.com/archives/32470) | irtt 专门测长期延迟稳定性和抖动，按固定间隔发包（如每 10ms 一个），统计 RTT、单向延迟、IPDV […] |
| 2026-09-24 | [鹈鹕骑自行车的html页面生成测试202609（GPT-6 Astra，Gemini 3.8 flash，DeepSeek 4.1 flash）](https://blog.rustfisher.com/ai/pelican-bike-demo202609-gpt6astra-gemini3-8flash-deepseek4-1flash/) | 鹈鹕骑车测试，用同样的提示词，让不同的AI生成一只鹈鹕骑自行车的HTML页面。GPT-6 Astra，Gemini 3.8 flash，DeepSeek 4.1 flash |
| 2026-09-24 | [一次内存引起的网络丢包问题排查](https://www.kawabangga.com/posts/7422) | 记录一下最近排查的一个问题：某台机器一上线就有丢包，同 Rack 同规格的其他机器都没有问题，由于负载都是一样 […] Continue reading... |
| 2026-09-24 | [说个题外话，还有人在用 RSS 订阅资讯](https://versun.me/blog/tweet-2102996864631189645) | 说个题外话，还有人在用 RSS 订阅资讯吗？ 我在考虑要不要把 RSSBox 项目归档了。。。 https://rssbox.app https://github.com/versun/rssbox |
| 2026-09-24 | [用AI【做出来】更容易时，怎么做才能赚钱呢？](https://wenfeixiang.com/2026/09/how-to-get-the-value-in-the-ai-era/) | 最近有个搞笑的梗图：随着 AI 能力的增强，开发者越来越多、用户却越来越少，当用户都不够用了、你还指望这些 A […] |
| 2026-09-24 | [保持不好意思之心](https://www.hecaitou.com/2026/09/holding-onto-that-little-unease.html) | 以前写博客那会儿，文章里但凡加了广告，读者雪崩一般的抱怨就会汹涌而至：你变了！你堕落了！你不纯粹了！好像其中的某一个，就是约翰·列侬人生里听到的最后一句话，接下来就是轰鸣声了。可见大家当初关系之紧张。 现在则是完全反了过来，文章里但凡介绍什么吃的用的，写成一篇纯散文，读者雷鸣一般的怒吼就会扑面而来：… |
| 2026-09-24 | [记录下 claude pro 额度 5小](https://versun.me/blog/tweet-2102971446951870844) | Versun 哎，我可真贱，为了 opus 5.5，还是上了 达里奥 的贼床 看看这次能持久几天🥲 记录下 claude pro 额度 5小时用了10%，周用了5%，花费 25M token 预计一周500M，一个月2000M token，也就是20亿token，还可以 |
| 2026-09-24 | [噩耗，本站的微软 OneDrive E3 MSDN 存储被停止了，大量下载链接急需更新](https://www.cheshirex.com/11179.html) | 今早打开OneDrive 上传资源发现账号已经被停止了，文件还未被删除。 感觉天塌了，上面资源太多了，要一个一 […] |
| 2026-09-24 | [Plants vs. Zombies updated](https://macsourceports.com/game/pvz) | The build of PvZ Portable for Plants vs. Zombies has been updated to version 0.2.4 of the project |
| 2026-09-24 | [LXC 热载入设备文件](https://blog.frytea.com/archives/32467) | 下面以向运行中的 LXC 容器注入 `/dev/vhost-net` 为例讲解。 有两种思路:临时注入 […] |
| 2026-09-24 | [哎，我可真贱，为了 opus 5.5，还](https://versun.me/blog/tweet-2102945482633056415) | 哎，我可真贱，为了 opus 5.5，还是上了 达里奥 的贼床 看看这次能持久几天🥲 |
| 2026-09-24 | [回国终于安顿下来了，先热个身](https://koukyo.site/posts/startup-warmup-three-carrier-pivots/) | 安顿下来后想热热身，做了个找 YouTuber 邮箱的小工具。同一个后端换了三种壳，从 33 次点击 0 次使用，到有人把 100 次免费额度全部用完。 |
| 2026-09-24 | [书店消费区](https://mobius.blog/25771.html) | 在书店逛了逛，最后不得不在书店的消费区买了杯茶，落座在几乎没人的昏暗角落。不是因为逛书店逛累了，而是因为书店里 […] —— 感谢订阅 莫比乌斯 ，如你有任何疑问、观点交流，请前往 创作者频道 ，或 私信 联系。 |
| 2026-09-23 | [VictoriaLogs 集群 Helm 部署笔记（测试环境）](https://199604.com/3722) | VictoriaLogs 集群 Helm 部署笔记（测试环境） 记录时间：2026-09-22 环境：测试集群 […] |
| 2026-09-23 | [老鹰主机十年用户第一次买老鹰VPS，7个机房速度实测](https://gugegt.com/20260924-vps-datacenter-network-test.html) | 老鹰主机用了十年，这次第一次买它家的 VPS，卡在最后一栏：机房。 配置选完，系统选完，下面一长串城市名。洛杉矶、达拉斯、纽约、伦敦、香港、新加坡、多伦多。地图摊开一看，答案明摆着，香港最近，新加坡也不远。 下单前我把七个机房的测试 IP 挨个跑了一轮，每个四次。结果跟地图的顺序完全不搭。 数据摆在… |
| 2026-09-23 | [Zuma updated](https://macsourceports.com/game/zuma) | The build of Zuma Portable for Zuma has been updated to version 0.9 of the project |
| 2026-09-23 | [我如何看待充值这件事儿](https://blog.solazy.me/20260923/) | 今天聊聊充值这件事 |
| 2026-09-23 | [Register Token以及对变形金刚AI的四大批判](https://blog.est.im/2026/stdin-19) | 前几天 Yann LeCun 对 变形金刚(transformers) AI 进行了深刻的 批判 First, the reasoning abilities of current AI systems are based non-auto-regressive search (which is w… |
| 2026-09-23 | [聪明 Agent 四套路 和 人肉学习](https://blog.est.im/2026/stdin-18) | nVIDIA 联合 NTU，MIT 联合研究了一项关于 Agent harness 自我提升的 研究 ，项目叫 SoL-Pi ， Scaling Auto-Research Loops for Efficient Agent Harnesses 让 Research Agent 自动发现 Harne… |
| 2026-09-23 | [脑袋空空](https://blog.oospace.com/posts/2026-09-23/) | 与其每天被各种废料信息填满，不如放空大脑 |
| 2026-09-23 | [野人编年史](http://imlane.zhanglintc.co/ye-ren-bian-nian-shi) | 野人编年史 野人创始人 徐队 ，群昵称Shogun。姓徐，称徐队，真野人队长，野人 抖音官号 持有者。 张队 ，群昵称张小不。江湖人称竹节虫，简称虫队。 熊队 ，群昵称熊嘎婆，称熊队。 野人CLUB游泳事业部 群主。 亮队 ，群昵称亮什么，称亮队，野人 小红书官号 持有者。 野人声明 从 泳往直前… |
| 2026-09-23 | [解决宝塔安装 PG 失败的问题](https://blog.frytea.com/archives/32464) | 在宝塔面板安装 PostgreSQL 时遇到 `pgsql_install.sh: 83: Syntax er […] |
| 2026-09-23 | [Muse AI 注册教程：借助 Google Gemini Spark 完成注册](https://liudon.com/posts/muse-ai-registration-with-gemini-spark/) | Muse 是 Meta 于 2026 年 9 月 8 日推出的全球首款面向普通消费者的个人 AI 智能体（AI Agent）应用。 现在仅面向美国和加拿大地区的 18 岁以上用户开放。 在 V2ex 上看到可以通过 Gemini Spark 进行注册，绕过 IP 检测，本文记录整个操作过程。 |
| 2026-09-23 | [2026.9.22](https://www.justzht.com/2026-9-22/) | 最近都干了啥？ 周六和阳哥吃了四川菜。虽然都一直在湾区，但估计有三四年没见着面，然后见我他说我胖了，我 |
| 2026-09-23 | [古早石榴味](https://www.hecaitou.com/2026/09/old-taste-pomegranates.html) | 在我很小的时候，认为最好吃的石榴来自东川外婆家。昆明的石榴不好吃，不如东川石榴大，也不如东川石榴甜。今天的东川虽然只是昆明的一个区，相距 150 公里，但在当年坐车过去要一整天，夏季的时候还有泥石流中断公路的危险。因此，当舅舅他们请托公车司机带一份石榴来我家时，算得上是一次小型节日，连带着石榴也似乎… |
| 2026-09-23 | [还真能赚到钱，感谢 Tutti](https://versun.me/blog/tweet-2102597377601462724) | YC (Yucheng) 经常有人问 Tutti 是什么意思，正好用 Pexo 做了条片，顺便讲一下。 tutti 是乐谱上的记号，意大利语「全体」。前面小提琴首席 solo 一段，谱上标 tutti，整个乐队重新进来一起奏。 @tuttihq 干的就是这个：一个创作者发是 solo，很多创作者一起… |
| 2026-09-23 | [分享下出海Playbook，都是干货](https://versun.me/blog/tweet-2102591014636765429) | 出海去孵化器 经历了不知道多少次的反复挣扎，我们决定把过去三年积累的 48 场内部主题分享、10 节推特增长课和 13 节出海实战课，累计 68 小时 14 分钟， 做成一份完全免费的 Playbook 分享给想做出海产品的大家！ 累计消耗 16.19 亿 Token，历时 31 天， 梳理出 15… |
| 2026-09-23 | [Memos: 风云不语，只是一个劲儿的赠送重置卡](https://blog.yasking.org/a/1790127856) | 2026 年 9 月 22 日 Anthropic 发布 Claude Opus 5.5，同时赠送了一张重置卡（引入用户自主点击重置卡）。 同一天，OpenAI 发布 GPT-6 Sol 和 GPT-6 Luna 模型，也赠送 … |
| 2026-09-23 | [给 Twikoo 接入 Jev，用 AI 判断博客评论是不是广告](https://liudon.com/posts/twikoo-jev-spam-detection/) | 前言 最近 Jev 火了，时间线上全是讨论这个新模型的内容。 Jev 是 TypeSafe AI 发布的首个 System One 模型，主要面向软件中的快速、结构化决策。 和 ChatGPT、Claude 这类偏文本生成的大模型不太一样，它更偏向于“做判断”：输入一组状态和问题，直接返回结构化的判… |
| 2026-09-23 | [爹而不自知 III](https://mobius.blog/25768.html) | 这个系列发布后，我又收到常来博客互动的朋友的私信，他的观点正好引出了今天要继续讨论的内容： 如果一个人表现出居 […] —— 感谢订阅 莫比乌斯 ，如你有任何疑问、观点交流，请前往 创作者频道 ，或 私信 联系。 |
| 2026-09-23 | [汇总下目前 opus 5.5 的3D评测](https://versun.me/blog/tweet-2102550362435760339) | Stefan 3D AI First Opus 5.5 vs GPT-6 Astra test is 3D. One prompt, Blender only, all procedural. Render the 10-second shot, and record your own build… |
| 2026-09-22 | [OpenAI 这波完败啊，老家都被掀了](https://versun.me/blog/tweet-2102547956507595242) | OpenAI 这波完败啊，老家都被掀了 人家 Opus 5.5 这次目标是 GPT 6 Astra， 而 OpenAI 傻傻的还在挤牙膏，发布中小杯的 sol 和 luna 这不得赶紧掏个 GPT 7 出来，否则没得玩 |
| 2026-09-22 | [「折腾」水水的不想月报](https://www.wdssmq.com/post/20140225001.html) | 周期性的熬夜和心流 上星期也是达成了 git 满勤（9.13 ~ 9.19）。。 ；之前一次是 1.4 ~ 1.10。。 这篇文章主要也是想水一下这段时期的成果。。 AI 额度就不够了…… 这里是一条广告：[ShortSth:硅基流动][/ShortSth] 今天 9.23，这一周期的集中代码时间差… |
| 2026-09-22 | [Chris Sawyer's Locomotion updated](https://macsourceports.com/game/locomotion) | The build of OpenLoco for Chris Sawyer's Locomotion has been updated to version 26.09 of the project |
| 2026-09-22 | [PIVOT Vol.21](https://anotherdayu.com/pivot-vol21/) | 不定期更新的 Newsletter。 Mak5er/AirCard 可以在不越狱的情况下修改 Apple Wallet 卡面和锁屏界面，最近还增加了 iOS 版： Mak5er/AirCard-iOS 。 tamaNOTchi 网页版电子宠物，能贴到自己的博客上当挂件。支持静态博客等多种网站格式！… |
| 2026-09-22 | [普洱采茶：杀青烫手，和我那杯叫不响的永川秀芽](https://macin.org/2026/09/22/pu-er-cai-cha/) | 阅读全文 → 上一篇在普洱的山里采了三筐菌子， 敢下锅的没几样 ；这一篇，还是普洱，蹲进茶垄里，炒了一锅自己都怕的 烈茶 。 |
| 2026-09-22 | [Java 服务 CPU 打满排查笔记](https://199604.com/3720) | Java 服务 CPU 打满排查笔记 记录时间：2026-09-19 环境：Linux 服务器 / Java […] |
| 2026-09-22 | [M03车机如何使用网易云音乐「神光模式」？保姆级教程分享【效率工具指南】](https://penghh.fun/2026/09/22/2026-9-22-m03music/) | <script src=" |
| 2026-09-22 | [入蜀记 day484 桂香入肺](https://z.arlmy.me/posts/BBBPandINSW/INSW-ko/INSW_484/) | 「桂香入肺。」 |
| 2026-09-22 | [入蜀记 day483 真的能复现吗？](https://z.arlmy.me/posts/BBBPandINSW/INSW-ko/INSW_483/) | 「真的能复现吗？」 |
| 2026-09-22 | [入蜀记 day482 听友聚会](https://z.arlmy.me/posts/BBBPandINSW/INSW-ko/INSW_482/) | 「听友聚会。」 |
| 2026-09-22 | [为啥你们的成品质量都好好啊，这是烧了多少](https://versun.me/blog/tweet-2102349099161026675) | Ding https://x.com/i/article/2102306610626662400 为啥你们的成品质量都好好啊，这是烧了多少积分，费了多少时间做的，太牛了 |
| 2026-09-22 | [景行行止，一座公共历史人物纪念档案，域名是huainian.org](https://gugegt.com/20260922-huainian-org.html) | 前几天，我的一个新项目上线了：景行行止，网址 huainian.org 。 名字取自《诗经》里的"高山仰止，景行行止"。高山让人仰望，大道让人追随。网站的副标题是，怀念每一个值得记住的人。顺便坦白一句，这个名字我到现在还觉得有点别扭，可能还会改，先这么叫着。 打开首页，顶部四个大字加一个搜索框，往下… |
| 2026-09-22 | [深呼吸](https://www.gtdstudy.com/posts/2026-09-21-deep-breath/) | 朋友，上周我又做了不少事情，而且收获良多，忍不住跟你分享！ Awesome-Jev 星标超过 1000 个了！ 自上周 Jev 发布之后，我跟进了一个 Awesome-Jev 的 Github 仓库，很受欢迎。这大概是我历史上增速最快的 Github 仓库，仅仅一周就获得了破千的星标，每天都有十多个… |
| 2026-09-22 | [动起来，否则你就要费劲思考了](https://www.gtdstudy.com/posts/2026-09-15-pascal/) | 一段时间没写信了，你还好吗？再次提起笔来，真是让人开心，每一次写信都是你我的一次重逢，为了这份不断的缘分，我也要提笔写下去。 X 的关注量突破 5000 最近，我在 X 上的粉丝突破了 5000 人，不算多，也不算少。但现在 X 上的内容更新，基本上是我指挥 Agent 来处理的，我每天除了对着一张… |
| 2026-09-22 | [NeuroFlex: Lossless Element-Level ANN-SNN Co-Execution for Efficient Sparse Inference](https://mer.dev/posts/neuroflexlossless-element-level-ann-snn-co-execution-for-efficient-sparse-inference/) | 好像是 MICRO2026，ANN-SNN 混合稀疏加速器，Fig.1 的观察和统一 INT8 存储的设计还不错，但这里的 SNN core 更像一个 unary 编码的累加单元？ |
| 2026-09-22 | [NeuroFlex: Lossless Element-Level ANN-SNN Co-Execution for Efficient Sparse Inference](https://mer.run/posts/neuroflexlossless-element-level-ann-snn-co-execution-for-efficient-sparse-inference/) | 好像是 MICRO2026，ANN-SNN 混合稀疏加速器，Fig.1 的观察和统一 INT8 存储的设计还不错，但这里的 SNN core 更像一个 unary 编码的累加单元？ |
| 2026-09-22 | [我也玩了下 @Pexoai_offica](https://versun.me/blog/tweet-2102307878107586652) | 我也玩了下 @Pexoai_offical 我是想做一个绘本动画，我儿子很喜欢《小蛇散步》这个绘本，天天讲个不停，所以想搞个动画给他， 整体效果挺好的，会自动分角色分镜，然后才出视频，就是积分消耗太快了，最后没搞完🥲 |
| 2026-09-22 | [AI 写得越来越快，我却越来越看不完了](https://www.tortorse.com/archives/ai-writes-faster-than-i-can-read/) | 深夜里，一个人面对 AI 生成的大量文档和图片 |
| 2026-09-22 | [为什么我不再写技术文章](https://blog.oospace.com/posts/2026-09-22-c/) | 不是因为AI，很多年前也一直在写，后来发现大多都是copy别人的，而不是原创的有价值的 |
| 2026-09-22 | [不想好就开口的是什么人](https://kaix.in/2026/0922/) | 我对语音输入一事毫无研究，而且一直费解，真的会有人偏爱使用语音输入的方式来记录文章吗？文学史上倒是不乏先例，一些作家出于身体原因由助手转录口述来完成写作，但结果往往是行文变得冗长、繁复，句式枝蔓丛生。 作家尚且如此，而我们……恰好看到腾讯又出了一款集成了 AI 能力的语音输入法，口号竟然是「不必想好… |
| 2026-09-22 | [搭便车理论](https://blog.oospace.com/posts/2026-09-22-b/) | 世界科技的发展，国家经济的发展，个人的发展是息息相关的，中国搭美国便车，个人能否搭上时代的列车 |
| 2026-09-22 | [今年抱怨的人要比去年更多一些](https://www.hecaitou.com/2026/09/More-Complaints-This-Year-Than-Last.html) | 在后台我每天都会收到很多留言，就我个人的感觉，今年抱怨的人要比去年更多一些，而去年抱怨的人又要比前年更多一些。 大多内容是抱怨伴侣，或者抱怨孩子，刚好都落在我的经验盲区。我知道，对方并不需要我出主意，只是想找个地方倾诉。但是看得多了，我开始担忧自己，担忧自己因此形成了关于婚恋和家庭教育的错误认知，觉… |
| 2026-09-22 | [注意力机制与限制](https://blog.oospace.com/posts/2026-09-22-a/) | 人类的注意力有限，A(G)I的注意力领先吗 |
| 2026-09-22 | [AI泡沫破灭后可能造成的一些影响](https://blog.oospace.com/posts/2026-09-22/) | 准确的说是AGI泡沫破灭后可能造成的影响，准备面对海啸吧 |
| 2026-09-22 | [爹而不自知 II](https://mobius.blog/25763.html) | 继续昨天的话题。 当爹的核心并不是为了当别人爹，而是为了满足自己的心理需求，或是某种身份标签的存在性。具体来说 […] —— 感谢订阅 莫比乌斯 ，如你有任何疑问、观点交流，请前往 创作者频道 ，或 私信 联系。 |
| 2026-09-22 | [Memos: 看着一点也危险](https://blog.yasking.org/a/1790039812) | 早上骑车路过一个施工现场，远远就看到有个人站在渣土车上 ‘观察’，直直的站着，两脚就踩着车斗的两个边框上（比图中更 … |
| 2026-09-22 | [入蜀记 day481 同一个老板](https://z.arlmy.me/posts/BBBPandINSW/INSW-ko/INSW_481/) | 「同一个老板。」 |
| 2026-09-22 | [入蜀记 day480 卧底厨神](https://z.arlmy.me/posts/BBBPandINSW/INSW-ko/INSW_480/) | 「卧底厨神。」 |
| 2026-09-22 | [入蜀记 day479 but read](https://z.arlmy.me/posts/BBBPandINSW/INSW-ko/INSW_479/) | 「but read.」 |
| 2026-09-22 | [刚看了下这个jev wechat项目，模](https://versun.me/blog/tweet-2102201927178371280) | 李韭二 卧槽！ Jev WeChat 微信群聊！已开源！👇 再也不用担心不懂人情事故！ 微信客服！微信群助手！ 再也不用codex哄女朋友了！ https://x.com/Melinda58883532/status/2102008893350277215/video/2?s=46 刚看了下这个je… |
| 2026-09-22 | [入蜀记 day478 刷剧](https://z.arlmy.me/posts/BBBPandINSW/INSW-ko/INSW_478/) | 「刷剧。」 |
| 2026-09-21 | [Twikoo 2.x 升级踩坑：Netlify CORS 报错与解决方案](https://liudon.com/posts/twikoo-2-netlify-cors/) | 前言 刚更新完上一篇 《我给博客做了一个时光机》 ，顺手打开文章看看效果，结果发现评论区挂了。 浏览器控制台报错： Access to XMLHttpRequest at 'https://comment.example.com/' from origin 'https://blog.example… |
| 2026-09-21 | [R#120 沉迷](https://blog.sakanano.moe/journals/random_120) | 2026.9.15 ~ 2026.9.21 |
| 2026-09-21 | [恒星的结构和演化](https://physnya.top/compact-object/lesson-2-star-structure-and-evolution/) | 建立恒星的方程，我们通常考虑质量守恒、静力学平衡、能量守恒和反应几个角度. 质量守恒： d M d r = 4 π r 2 ρ ( r ) \frac{\mathrm{d}M}{\mathrm{d}r}=4\pi r^2\rho(r) d r d M ​ = 4 π r 2 ρ ( r ) |
| 2026-09-21 | [我给博客做了一个时光机](https://liudon.com/posts/hugo-ipfs-time-machine/) | 前言 博客早在23年的时候就接入了 IPFS 服务，通过 GitHub Actions 实现了 Cloudflare Pages 和 IPFS 两套服务托管。 整个流程大概是下面这样的，具体实现可以参考 Hugo 接入 IPFS 服务 这篇内容。 Hugo Build │ ├── 正常部署 → Cl… |
| 2026-09-21 | [读书有感](https://blog.oospace.com/posts/2026-09-21/) | 读书有感而记录 |
| 2026-09-21 | [复古游戏圈入门指南](https://blog.yuanji.dev/posts/retro-game-intro/) | 写完上一篇复古掌机初体验：ANBERNIC RG 34XX，转眼又过去了一周多。上个月初还不了解「复古游戏」「 […] |
| 2026-09-21 | [pi agent这几天更新后，很奇怪啊，](https://versun.me/blog/tweet-2101942460390031399) | pi agent这几天更新后，很奇怪啊，经常把自己思考死了，模型没变，你们有遇到过吗 |
| 2026-09-21 | [写在两份工作的 Gap 之时](https://blog.solazy.me/20260921/) | 今天想停下来聊聊我过去的这半年的所失所得 |
| 2026-09-21 | [在网上膨胀](https://www.hecaitou.com/2026/09/Inflating-Online.html) | 上网令人自我膨胀，关于这一点我有充分的经验。当我刚开始上网冲浪，很快就获得了认可，在网上拥有了另一种多姿多彩的生活，似乎世界上最有趣的人都在那里，而且都在等着我上线。 与此同时，在现实生活中我只是个刚刚开始工作的生瓜蛋子，转正前月薪 600 块，转正之后 800，当时一台汉显传呼机都要 1200，一… |
| 2026-09-21 | [最近惦念 20260906](https://z.arlmy.me/posts/TILs/thoughts/20260906_Recently/) | 「就像你说的。」 |
| 2026-09-21 | [Toots 437 2026 Sep.13 - Sep.19](https://z.arlmy.me/posts/MastodonArchives/2026/MastodonTootsArchives_20260919/) | 「鲸鱼可以那么平静地呼吸。」 |
| 2026-09-21 | [emacs-为重复任务添加自定义工作日判定](https://blog.prayhand13013.top/20260921T102942--emacs-为重复任务添加自定义工作日判定__blog.html) |  |
| 2026-09-21 | [爹而不自知 I](https://mobius.blog/25758.html) | 我是一个时不时需要“当爹”的人，因为大部分时间都在处理没办法得到及时回应的事情，例如写小说、剧本、制作短剧分镜 […] —— 感谢订阅 莫比乌斯 ，如你有任何疑问、观点交流，请前往 创作者频道 ，或 私信 联系。 |
| 2026-09-21 | [Jev 的边界](https://www.bmpi.dev/dev/jev-boundary/) | 把 Jev 放进 Free4Chat 的 Room App 和 Live View 做了一轮实验后，我没有找到一个必须接入它的产品场景，却更清楚地看到了确定性代码、Decision Model 和 Generative Model 之间的边界。 |
| 2026-09-20 | [大脑充血 Vol.99](https://www.geedea.pro/weekly/99/) | 最近一直在小步缓行，不急不忙地把事情做好。一方面是上班之后的确没有大块且高精力的时间来做自己想做的事情了，只能把事情拆得很碎，一点一点来做。这几天在读波拉尼奥的短篇集《地球上最后的夜晚》，每篇真的很短，大概十几二十页，可以每天上班前没有压力地读上一两篇。我很喜欢他的文风，平静却具有冲击力，不做作，就… |
| 2026-09-20 | [Harbor容器僵尸进程数告警——docker-compose.override.yml加init参数修复](https://199604.com/3718) | Harbor容器僵尸进程数告警——docker-compose.override.yml加init参数修复 记 […] |
| 2026-09-20 | [这几天爆火的 jev 和 laya 模型](https://versun.me/blog/tweet-2101808620426149961) | Versun 虽然不懂金融，看的有点懵逼， 但我觉得未来各个行业都会有自己的专用模型， 而目前通用模型应该会拿来做统筹，说不定统筹都会有专用模型😎 https://twitter.com/sodawhite_dev/status/2096262979042046435 这几天爆火的 jev 和 la… |
| 2026-09-20 | [有用 hermes agent 的，每次](https://versun.me/blog/tweet-2101807584831570411) | 有用 hermes agent 的，每次会话结束前，记得 /review 下，效果很不错，每次都有惊喜 |
| 2026-09-20 | [或许没人关心的细节](https://blog.solazy.me/20260920/) | 今天继续聊个日常所见而引发的思考 |
| 2026-09-20 | [No More Blind Dates; Dating Is Fine, Marriage Is Not](https://tianheg.co/posts/no-more-blind-dates-en/) | If she hadn't sent me a text today, I wouldn't have written this piece, because I want to forget that stretch of my life, even though it did teach me… |
| 2026-09-20 | [我再也不想相亲了；恋爱还是要谈，结婚就算了](https://tianheg.co/posts/no-more-blind-dates/) | 如果不是她今天给我发短信，我也不会写这篇文章，因为我想忘掉那段经历，尽管它的确教会了我一些东西。她说要电话聊一下，我不觉得有什么好聊的，她打电话的时候我在睡觉。醒来看到她的未接来电，为了避免她再次打来，我把她的号码拉黑了。 |
| 2026-09-20 | [苹果 iPhone 安全神话被打破：币圈应用FomoPeek沙盒逃逸读取了其他APP私钥](https://blog.renfei.net/posts/1626402130325676145) | 2026 年 9 月 19 日，慢雾联合 OKX 安全团队披露：iOS 应用 FomoPeek 1.1、1.2 版本内置一套 iOS 内核攻击框架，可突破沙盒读取并解密系统 Keychain，导致私钥、助记词、登录凭证泄露。受影响 iOS 版本为 12.0～18.7 与 26.0～26.1。 |
| 2026-09-20 | [沙蔥炒牛肉](https://taxodium.ink/recipe-sha-cong-chao-niu-rou.html) | 沙蔥炒牛肉 沙蔥有一股獨特的香味，之前買過沙蔥涼拌牛肉，很好吃，但沙蔥炒牛肉好吃嗎？試試唄。 食材 牛腿肉 (或其他類似部位) 約 200g 沙蔥約 200g 沙薑 2 顆 (喂！怎麼還有沙薑啊？別問俺，俺也是看視頻裡有，就買了) 大蒜 1 顆 (是一顆，不是一瓣哦) 小米辣几根 (能吃辣就多來點，… |
| 2026-09-20 | [问AI的问题备份 20260920](https://z.arlmy.me/posts/ZArlmyMe/QuestionsWithGemini_20260920/) | 「时间戳。」 |
| 2026-09-20 | [博客接入 Google AdSense：初体验并不好](https://blog.mfwt.top/index.php/archives/1617/) | 正如上一篇博文以及广告政策页面提到，本站在前两天的时候实验性地接入了Google AdSense（以下简称GGAD），打算先实验一个月，想看看这对于站点的开销是否有缓解作用。然而，如果光看这接入... |
| 2026-09-20 | [Zine#59 - 和手機的關係、謠言、已讀不回](https://taxodium.ink/59.html) | Zine#59 和手機的關係、謠言、已讀不回 目錄 News &#124; Article Cool Bit Tutorial &#124; Resource Code Related AI Related Tool &#124; Library Emacs 一些话 &#124; 摘抄 多媒体 開頭的音樂分享會有人期待嗎？不管如何，如果你… |
| 2026-09-20 | [A Long Run of Eight Kilometers](https://tianheg.co/posts/sport-run-8km-en/) | After a long gap, I went for a run again today. I ran it according to the half-marathon plan in Zepp, 8 kilometers, and it felt okay, I guess. Only to… |
| 2026-09-20 | [【运动记】长跑八千米](https://tianheg.co/posts/sport-run-8km/) | 时隔很久，今天又跑了一次步。是按照 Zepp 的半马计划跑的，跑了 8 公里，感觉还好吧。只是跑到最后，右腹部有点不适。那是因为很久没有跑了。 |
| 2026-09-20 | [滴答清单也加上了 AI 助手，还不错，我](https://versun.me/blog/tweet-2101638960120561692) | 滴答清单也加上了 AI 助手，还不错，我之前都是让 hermes 来管理清单任务的，这几天用用看怎么样 |
| 2026-09-20 | [空间的体积度量衡——行列式（Determinant）](https://www.less-bug.com/posts/volume-measurement-of-space-determinant/) | 在平面上，取两个向量： $$ \mathbf{a} = \begin{pmatrix} 3 \\ 0 \end{pmatrix}, \quad \mathbf{b} = \begin{pmatrix} 0 \\ 2 \end{pmatrix} $$ 这两个向量从原点出发，张成一个矩形。这个矩形的面积… |
| 2026-09-20 | [NixOS Is Not for Me Right Now](https://tianheg.co/posts/nixos-not-for-me-right-now-en/) | Over the past few days I tried NixOS, and yesterday I realized it's not for me. What first drew me in was one thing about NixOS: complete control over… |
| 2026-09-20 | [Vol.119 智能越便宜越需要外置标准：把判断留在模型之外的尺子地图](https://liduos.com/weekly/the-weekly-gradient-119) | 本期内容从可托付的智能出发，梳理把判断留在模型之外的尺子：实时语音与低成本架构、编译器与类型约束、Graph Engineering 与 Harness、安全默认拒绝，以及前沿模型治理、经验闭环与组织重构。 |
| 2026-09-20 | [短暂尝试 NixOS，它不适合我](https://tianheg.co/posts/nixos-not-for-me-right-now/) | 一开始想尝试，是因为 NixOS 有一点很吸引我：能完全掌控系统的内内外外，只要配置在，就能在一台全新设备上还原出一模一样的环境。这真的很棒，因为使用 Linux 系统要掌握很多内容，总有不熟悉的地方，而把系统搞崩溃后如何回退，往往是个很头疼的问题。NixOS 的设计恰好完美地解决了这个问题。 |
| 2026-09-20 | [SmailrX：我用Agent把Chrome插件做成了安卓App](https://www.evan.xin/5106/) | SmailrX Smailr 邮件助手 Android 应用。由同是我用AI写的功能的相同的 Chrome 扩 […] |
| 2026-09-20 | [让我头大的两个问题](https://www.hecaitou.com/2026/09/two-questions-that-give-me-a-headache.html) | 自从开始写作，我就掉头发。总结起来，应该有一半以上的头发是因为两个常见问题而掉落： ---当我介绍某种美食，留言区里一定会有人问：孕妇能不能吃？ ---当我介绍某部电影，留言区里一定会有人问：X 岁的孩子能看吗？ 我当然可以把这些问题简单理解为个人好奇，或者个人询问，并不必然意味着征询我的意见。但是… |
| 2026-09-20 | [呵护你](https://hux.ink/posts/care-of-you/) | 一直拖着没给群晖配上 UPS，借口之一是一年到头家里异常断电的次数可能也就一两回，抱着侥幸心理，觉得应该不会出什么问题，硬盘总不至于这么脆弱吧？借口之二则是 UPS 电源确实有点贵。就这样，买 UPS 的计划一拖再拖，直到上周二。 上周二，在公司发现 Synology Drive 同步文件时断时续，… |
| 2026-09-20 | [RSSHub 抓取 V2EX 报 403 Forbidden](https://blog.hoopan.net/853.html) | RSSHub 抓取 V2EX 路由返回 503，日志显示上游 403 Forbidden。本文记录排查过程与根因（Cloudflare WAF 拦截 RSSHub 项目标识 UA），以及通过注入浏览器 UA 修复的方法。 |
| 2026-09-20 | [如何理解直和分解与不变子空间？](https://www.less-bug.com/posts/how-to-understand-direct-sum-decomposition-and-invariant-subspace/) | 我不喜欢上来先上定义，然后再给性质、定理、例子的学习结构，和人认识世界的方式完全相悖，而且学起来一点也不爽！ 所以让我们从一个例子出发。 $\mathbb{R}^3$ 中任意向量都可记作： $$ \mathbf{v} = \begin{pmatrix} x \\ y \\ z \end{pmatri… |
| 2026-09-20 | [幸福者退让论其实是内耗的始作俑者？](https://mobius.blog/25748.html) | 果然，我对“周刊”已经没有了兴趣，既然是订阅性质的内容，那就聊一些比较实操的“方法论”。在开始之前，也先回顾一 […] —— 感谢订阅 莫比乌斯 ，如你有任何疑问、观点交流，请前往 创作者频道 ，或 私信 联系。 |
| 2026-09-20 | [Vespa: Distributors and Buckets](https://inhzus.io/posts/2026-09-20-vespa-distributor-and-buckets/) | In the Vespa comparison , I briefly mentioned that Vespa manages document distribution through buckets. This post expands on that part: how a document… |
| 2026-09-20 | [Vespa: HNSW Index Implementation](https://inhzus.io/posts/2026-09-20-vespa-hnsw-index/) | The previous index implementation post covered attributes and inverted indexes, but left out tensors. This post continues with the data structures beh… |
| 2026-09-20 | [Vespa: Thread Safety in the Storage Engine](https://inhzus.io/posts/2026-09-20-vespa-storage-engine-thread-safety/) | The earlier posts covered index data structures and matching . One question remains: while a query is using those structures, how can another thread u… |
| 2026-09-20 | [iPhone Duo 的 Vertical Bar](https://bluepika.life/blog/iphone-duo-vertical-bar) | 我将上周称为同时关注任天堂和苹果的人最快乐的一周，任天堂开了新一场直面会，苹果也如预期一样发布了折叠屏手机 iPhone Duo。 |
| 2026-09-19 | [用 jev 或者 llm 炒股的区别只有](https://versun.me/blog/tweet-2101448767757279473) | 用 jev 或者 llm 炒股的区别只有一个，亏钱的速度，jev更快😂 |
| 2026-09-19 | [FreeSpace 2 updated](https://macsourceports.com/game/freespace2) | The build of FreeSpace 2 Source Code Project for FreeSpace 2 has been updated to version 26.0.1 of the project |
| 2026-09-19 | [Wolfenstein: Enemy Territory updated](https://macsourceports.com/game/wolfet) | The build of ET: Legacy for Wolfenstein: Enemy Territory has been updated to version 2.86.0 of the project |
| 2026-09-19 | [Quetoo updated](https://macsourceports.com/game/quetoo) | The build of Quetoo has been updated to version v1.0.105 of the project |
| 2026-09-19 | [SFC 游戏：兔宝宝大冒险（Tiny Toon Adventures）](https://springwood.me/sfc-tiny-toon-adventures/) | （摘要）SFC 版不仅画面更加漂亮，而且玩法也更加多样化了。 |
| 2026-09-19 | [周末流水账 0919](https://blog.solazy.me/20260919/) | 里后的第一天，也是个周末 |
| 2026-09-19 | [软件工程亡了](https://blog.mzh.ren/zh/posts/2026/09/the-end-of-software-engineering/) | 朋友发给我一张图片，乍看之下是奥莱利的动物书的封面，还以为他是想给我分享一本好书. 结果一看名字是The End of Software Engineering, 软件工程的终点，然后配合底”编程/技术/人工智能“标签，然后中间那个动物呢，是一头趴在地上有些生无可恋的野猪（希望它还没有死）。 |
| 2026-09-19 | [最近折腾的U卡和TenPayGo](https://blog.thetbw.xyz/archives/usdt-card-and-tenpaygo) | 最近比特币的价格也是上来了，之前亏的钱回来了很多，早在之前刷到了一些油管博主的视频，申请了 safepal 的 visa 卡，还是挺好用的，作为虚拟币出金的一个渠道。 不知道是不是国人一窝蜂的涌入，就跟之前的 giffgaff 一样，safepal 背后的卡组织 fiat24 宣布维护，期间暂停虚拟… |
| 2026-09-19 | [万寿宫&景德镇](https://yovey.me/wanshougong-jingdezhen/) | 这大半月发生了不少事情。 1）延续对风水的兴趣，实则是周末短途摩旅的借口，跑了一趟西山万寿宫。 八月初一是许真 … Continue reading "万寿宫&景德镇" |
| 2026-09-19 | ["明天穿什么衣服"微信小程序，适合出差、旅行和选衣搭配困难症](https://gugegt.com/wear-tomorrow-miniprogram.html) | 每天早上出门前，最让人卡壳的就是这一句：今天穿什么。 天气 App 老老实实报个 27℃。可 27℃ 到底穿短袖还是加件薄外套，它不接这话。去搜「25 度穿什么」，跳出来的不是卖衣服的就是「适当增减衣物」这种车轱辘话。 我干脆自己做了个小程序，叫「明天穿什么衣服」。定位你的城市，看今天或者明天的体感… |
| 2026-09-19 | [vcfclick：ClickHouse + DuckDB 协作范例](https://luweiqing.com/gossip/vcfclick-ClickHouse-DuckDB.html) | vcfclick：让 VCF 回到可查询、可解释、可带走的地方如果你做过基因组分析，大概见过这样的夜晚：磁盘里躺着 VCF，终端里流着管道，脚本一层层加，最后只有作者知道哪一步在筛选。你可能是那... |
| 2026-09-19 | [网友网络老](https://www.hecaitou.com/2026/09/blog-post.html) | 昨晚，27 年前我刚上网时认识的老友突然联系我，说是授权一批照片给我，我大可以随便使用，全都是他的手笔（参见：《 来自 老友的照片 》）。 以后这种开头我看还是要少写，都在追求活人感，而我这种写法则是写出了「化石感」，好吓人。 当年我们在家乡的论坛里天天拍砖，玩得不亦乐乎。然后就是线下见面，都很年轻… |
| 2026-09-19 | [来自老友的照片](https://www.hecaitou.com/2026/09/photos-of-an-old-friend.html) | 昨晚 ， 一位我在 1999 年刚上网时结识的老友突然联系我，说是要把一批他拍摄的昆明照片授权给我，随我高兴我去发布。 我问他为什么不在自己公众号里发？他说他社恐，看到评论内心会不安定。但是，他又不希望这些照片一直放在硬盘上，毕竟他花费了很多心思。 所以，现在我把这些照片发布在这里。原因除了摄影者是… |
| 2026-09-19 | [2004，一切都像是安排好了](https://www.tortorse.com/archives/everything-seemed-arranged-2004/) | 黄昏里，一个年轻人站在已经关门的电脑培训中心门前 |
| 2026-09-19 | [做测试集是真不容易呀，除了收集完善题目外](https://versun.me/blog/tweet-2101103663112687698) | Versun 正在做一份本地模型的实用能力排行榜，测试集是从各种公开 benchmark中挑选微调，覆盖任务拆解、代码开发、长链路执行、上下文、指令遵循、记忆抽取、逻辑与常识 7 个维度 目前针对本地模型的评测很少，不知道有人感兴趣不，关注人多的话，我尽快测完放出来 做测试集是真不容易呀，除了收集完… |
| 2026-09-19 | [用了一周多的 gemini 3.8 fl](https://versun.me/blog/tweet-2101099541546361260) | 用了一周多的 gemini 3.8 flash，说说感受 智商在线，代码能力和 k3 差不多，速度快，说人话 但不适合做 review，唯命是从，不够独立，不够自信 |
| 2026-09-19 | [Python 潮流周刊#168：AI 智能体少写一半代码、Numba 提速 750 倍、PyPI 故障查了两周](https://pythoncat.top/posts/2026-09-19-weekly/) | 分享了 12 篇文章，12 个开源项目 |

## Vibe Coding

### GitHub copilot

Make sure to keep `.github/instructions` folder clean and simplest, or it may make context understanding and code generation worse, such as, `agent`, `instructions` and `prompts` should not conflict each other.

The **priority** of them should be like this:

Personal Instructions > Repository Instructions > Agent > Prompts > Your messages.

And get the template for GitHub Copilot from https://github.com/doggy8088/github-copilot-configs/tree/main/.github


## Common Steps:

- Read the documentation in `docs/memories` to understand the project structure, design and tech stack.
- Check the features in `docs/implementation-plans` to see if there are any questions or clarifications needed.
- Plan the simplest implementation steps in `docs/implementation-plans`, then list it append to the existing plans, and make every step clear enough for anyone to pick up and execute, and also make sure to include the verification steps for each implementation step.
- Then start implementation based on the plan step by step, and you should make sure keep these things:
  - Only when the verification steps are passed, you can move on to the next step, otherwise you should fix the problems until the verification steps are passed.
  - Link the related files, functions, or types in the codebase as much as possible, and also link the related plans if there are any. 
  - Make sure to record progress and what you have done in every step in the plan and things in other files.
  - Update the documents in `docs/memories` if there are any design changes or tech stack changes during the implementation.


## Roadmap

I use obdisian to manage roadmap of this project, and I will update it here when I have a clear plan for the next steps.

- [x] Add basic structure and files[^template-inspired].
- [x] Add Vibe coding support [^vibe-coding-inspired].

[^template-inspired]: Template inspired by https://github.com/kelseyhightower/nocode, https://github.com/othneildrew/Best-README-Template

[^vibe-coding-inspired]: https://github.com/tukuaiai/vibe-coding-cn

See the [open issues](https://github.com/bgzo-sandbox/make-vxna-great-again/issues) for a full list of proposed features (and known issues).
-->

## Contributing

Any contributions made are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'feat(module):add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Top contributors:

<a href="https://github.com/bgzo-sandbox/make-vxna-great-again/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=bgzo-sandbox/make-vxna-great-again" alt="contrib.rocks image" />
</a>

## License

All code is licensed under the AGPL-3.0 license. See `LICENSE` for more information.
