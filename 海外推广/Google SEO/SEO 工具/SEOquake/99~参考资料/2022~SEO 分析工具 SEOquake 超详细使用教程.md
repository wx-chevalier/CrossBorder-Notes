> [原文地址](https://zhuanlan.zhihu.com/p/492320951)

# SEO 分析工具 SEOquake 超详细使用教程

古语曰”工欲善其事，必先利其器“。今天来分享一款好用的 SEO 分析工具，它就是 SEOquake。

**【 什么是 SEOquake 】**

SEOquake 是一个免费的浏览器插件，兼容于 Google Chrome，Mozilla Firefox 以及 Opera 浏览器，每天有超过 300,000 人 在使用。

SEOquake 可以嵌入搜索引擎结果页面，让用户直接在 SERP 本身快速查看任何结果页面的实时 SEO 分析指标，包括 Google 索引、Alexa 排名、SEMrush 排名数据等，此外，SEOquake 还提供其他一些有用的工具，包括页面 SEO 诊断、关键词自然排名的竞争难度、关键词密度报告、内链/外链分析报告、自定义查询参数等。

另外，这里再提一句，SEOquake 是 Semrush （2020 年 12 月，SEMrush 已更名为 Semrush）提供的辅助工具之一，相信做 SEO 的朋友对 Semrush 不会陌生，这是一个强大的、多功能的多合一在线营销竞争情报工具套件，提供有网站流量数据查看，关键词调研，网站 SEO 策略分析，社交媒体营销情况研究等诸多功能。

![img](https://pic1.zhimg.com/80/v2-ab12256234d83c599f9cd3824d090514_1440w.webp)

**【 SEOquake 插件安装 】**

SEOquake 是一个免费的插件，这里以 Chrome 浏览器为例，直接在谷歌的 Chrome 网上应用商店搜索安装启用即可。

![img](https://pic4.zhimg.com/80/v2-cd49ef38357aed6bd3152be74651ca5f_1440w.webp)

**【 SEOquake 使用介绍 】**

SEOquake 主要由几个工具组成，分别是 SEObar，SERP overlay ，SEO Dashboard 以及 SEOquake reports，可以根据自己的实际需求自由搭配使用。

**SEObar：**这是一个附加工具栏，默认显示在浏览器页面顶部，能够提取您正在浏览的任何网页的即时 SEO 摘要，快速查看分析数据。SEObar 也可根据个人需求自由调整或完全关闭。

![img](https://pic3.zhimg.com/80/v2-8d9aa393d8fcea283e74ff976c3f74ea_1440w.webp)

**SERP overlay：**搜索结果页面覆盖，对 SERP 进行全面分析，在每个搜索结果下方显示一个条状图，提供与当前页面相关的参数数据，点击任意一个参数都可跳转查看该参数数据的详细来源页面。

![img](https://pic4.zhimg.com/80/v2-ed66db7dd7d20068a3d77cf380f22e2f_1440w.webp)

- AS：即 Authority Score（权威分数），AS 是 Semrush 用来衡量域名整体质量和 SEO 影响力的专有指标，这个分数是基于反向链接，引荐域名的数量，自然搜索流量和其他数据，得分值是 0~100；
- Visites：网站月访问流量（基于点击流数据）；
- Pages/Visit：一个会话期间内平均每个用户的页面访问数；
- Avg. Visit：平均访问时长；
- Bounce rate：网站预估跳出率；
- Google Index：指 Google 对当前网站的索引量，也就是当前网站被 Google 收录的页面数；
- L：即 Link，当前结果页面的反向链接（也即外链）数量；
- LD：即 Link Subdomain，当前网站子域（[http://www.xxx.com](https://link.zhihu.com/?target=http%3A//www.xxx.com)）的反向链接数量；
- LRD：即 Link Root Domain，当前网站根域（[http://xxx.com](https://link.zhihu.com/?target=http%3A//xxx.com)）的反向链接数量；
- Bing Index：上图 LRD 参数旁边的黄色小图标（Bing 在 2013~2016 使用的 Logo），指 Bing（微软旗下的互联网搜索引擎） 对当前网站的索引量；
- Rank：Alexa 网站排名；
- whois：查看域名 IP 及所有者等信息；
- </>source：查看当前页面的源代码；
- Rank：即 Semrush Rank，是 Semrush 基于每月从自然搜索中获得的预估流量对网站进行的专有排名，数据来自 Semrush 数据库的月度数据；
- Traffic：Semrush 预估的当前网站能获得的自然搜索流量/月（基于关键词定位）；

这里要注意的是，上面的 Visites，Pages/Visit，Avg. Visit，Bounce rate 这几个参数 Semrush 统计的是整个网站的数据，而不是指当前结果页面的数据，且是 Semrush 默认是统计的网站过去一个月美国这一国家的结果数据，

另外，Visites 跟 Traffic 这两个参数的流量数据是不同的，Visites 的流量数据来源是 Semrush 的 Traffic Analytics 报告里面的数据，Traffic 的流量数据来源是 Semrush 的 Domain Overview 报告里面的数据。

为什么 Traffic Analytics 跟 Domain Overview 报告里面的流量数据 Traffic 是不同的？这是因为它们收集的数据不同。

Traffic Analytics 报告中的 Traffic 是基于对所有流量来源的点击流数据的分析，而不仅仅是搜索流量数据，

![img](https://pic1.zhimg.com/80/v2-de17fb24539c40526fea250069c1e7ec_1440w.webp)

向下滚动 Traffic Analytics 报告，就可以看到网站流量来源细分，包括直接流量，引荐流量，搜索流量，付费流量，等等，

![img](https://pic3.zhimg.com/80/v2-ad02ec09ebf030176f24a70821366746_1440w.webp)

Traffic Analytics 这里的流量数据的最佳用途是将一个网站的总体流量与其他网站进行基准评估，对比分析竞争对手网站的各渠道流量来源情况。

Domain Overview 报告中的 Traffic 是基于关键词在自然搜索和付费搜索中的位置预估的对应所得流量（搜索量 \* 平均点击率），而且这里仅考虑搜索流量，并没有将社交、引荐或直接流量等其他渠道流量考虑在内，

![img](https://pic3.zhimg.com/80/v2-185cc48105b9f77bacfb085fb71720ea_1440w.webp)

Domain Overview 这里的流量数据的最佳用途是用来了解一个网站关键词在谷歌搜索结果页面上的排名位置对应的预计能带来多少潜在搜索流量。

另外，上面这两个数据在 SERP overlay 中显示的有可能是会跟 Semrush 显示的数据有点差异，可能这是 SEQquake 的一个小 Bug 吧~这种情况的话就还是参考 Semrush 后台实际提供的数据就好。

除了在每个搜索结果下面显示参数条状图外，SERP overlay 还在 Google 的搜索框下面显示了一个关键词难度参数，

![img](https://pic3.zhimg.com/80/v2-38fd17317f3aa143fa6d355d11c8a2e6_1440w.webp)

这里的关键词难度指的是关键词自然排名的竞争难度，关键词难度可以让用户预估在自然搜索中利用特定关键词抢占竞争对手的位置的难度(1-100%)。

最后，SERP overlay 在搜索结果页面还提供了一个侧边栏，主要包括这几个功能小部件，SEOquake enabled，Parameters，SERP report，Export CSV，Sort this page，Locate。其中，

SEOquake enabled：启用/禁用 SEOquake；

Parameters：设置要在 SERP overlay 显示的参数；

![img](https://pic4.zhimg.com/80/v2-53a665e8dabdc29a99021f1facde94af_1440w.webp)

所谓的 Parameter 参数是指 SEOquake 提供的指标，这些指标实际来源于不同的数据提供商，例如 Ageddomain、SEMrush、Pinterest、Alexa、Facebook、Google 等。SEOquake 参数可以分为两类：值和链接。值是一个经过计算生成的具体数值，链接则只是简单地显示为一个链接，而不是实际值。例如，上面的 Google Index 就是一个值参数，而 </>source 则是一个链接参数。

点击 Parameters，便可看到 SEOquake 提供的所有参数列表，在这里您可以自由勾选要在 SERP overlay 显示哪些参数。

SERP report：当前 SERP 排名前 10 的页面的详细报告；

![img](https://pic4.zhimg.com/80/v2-b5c6b451bc50d067745013cd84fcd78b_1440w.webp)

Export CSV：导出上面的结果报告数据；

Sort this page：按特定的条件选择升序/降序重新排列当前搜索结果页面数据，这里每个搜索结果链接旁边的数字指的是它原来在 SERP 的位置排名，并不是排序后的位置排名；

![img](https://pic2.zhimg.com/80/v2-2d9c6f1321836be88e7867b7dcd143c5_1440w.webp)

Locate：设置特定的国家和语言来进行模拟搜索。

![img](https://pic4.zhimg.com/80/v2-7f6b0010c43716faefec93e01cfc000b_1440w.webp)

**SEO Dashboard：**SEOquake 后台面板，在浏览器右上角工具栏中单击该插件图标后的弹出窗口，显示当前正在查看页面的相关信息，分为 4 个模块，分别是 Parameters，Backlinks，Display Advertising，Traffic Analytics。其中，

Parameters：当前查看页面的所有 Semrush 参数详细数据，Parameters 标签选项卡下方这个位置会显示 6 个主要参数：

- Alexa Rank：Alexa 网站排名，
- Google Index：Google 索引的页面数，
- Bing Index：Bing 索引的页面数，
- Semrush Rank：Semrush 对网站的自然搜索排名，
- Semrush Backlinks：当前页面的反向链接（外链）数量，
- Semrush Root Domain Backlinks：网站根域的反向链接（外链）数量，

这里的 6 个参数是我自定义设置显示的，点击具体的数字可跳转至参数数据来源的详细页面，具体要显示哪些参数可点击旁边的倒三角下拉框根据自己的实际需求选择，最后下面这里显示的是当前页面 Semrush 提供的所有参数的具体数据。

![img](https://pic2.zhimg.com/80/v2-54e4083322672fe10886073bd3688179_1440w.webp)

Backlinks：反向链接（外链）详细数据，可按子域，根域等进一步细分查看，

![img](https://pic1.zhimg.com/80/v2-a7995e118506459c4e930c246c15a50c_1440w.webp)

点击 View full report 可跳转至 Semruch 查看详细数据报告，

![img](https://pic3.zhimg.com/80/v2-1f7e45fb3fb565b8e86d29eeaba233e6_1440w.webp)

Display Advertising：展示广告数据，调用的是 Semrush 的数据，

![img](https://pic4.zhimg.com/80/v2-79d2ed6aa83ac11fa5414d6cefd59afb_1440w.webp)

但目前 Semrush 的展示广告工具套件已不再可用，所以这部分的数据查看不了，

![img](https://pic1.zhimg.com/80/v2-8062a05e72e88552b960271ec2cdbc7c_1440w.webp)

同时，Semrush 提供有一个专为日益复杂的展示广告而设计的全新的展示广告工具 --- AdClarity，据 Semrush 介绍，AdClarity 是一种具有竞争力的商业智能广告跟踪解决方案，它收集、分析和汇总数以亿计的实时广告事件，能够跟踪竞争对手的数字营销活动并发现表现最佳的广告投放平台，广告创意和着陆页；查看竞争对手的展示广告数据，例如市场份额，广告支出和展示次数等；对竞争对手的在线广告策略进行基准测试；挖掘新的流量来源和广告平台，使广告策略效益最大化；等等。

直接输入竞争对手网站便可查看结果数据，

![img](https://pic2.zhimg.com/80/v2-1096cf6dd6f01965d207cd1d83450dcd_1440w.webp)

![img](https://pic4.zhimg.com/80/v2-e57bc91b7fdbd474795ad149c598cb9f_1440w.webp)

![img](https://pic1.zhimg.com/80/v2-7746e746b022320dda79078fbf9d63e8_1440w.webp)

AdClarity 是一个付费工具，但目前 Semrush 提供有 7 天免费试用，感兴趣的可以自己去了解下。

另外，上面的 Backlinks 和 Traffic Analytics 这两部分数据是需要登录 Semrush 账号后才能查看的，没登录是看不到的，

![img](https://pic1.zhimg.com/80/v2-62108bb95497ca64e7d390a6deea9268_1440w.webp)

免费 Semrush 账号就可以了，而且，注册一个免费的 Semrush 账号每天有 10 次的搜索查询机会，可以藉此利用 Semrush 查看一定的网站分析数据，还是比较实用的。

**SEOquake reports：**点击浏览器右上角的 SEOquake 的插件图标的弹出窗口顶部位置，提供有 6 大数据报告，分别是：Page Info，Diagnosis，Internal，External，Density，Compare URLs/Domains。

点击具体的报告标签选项卡能够跳转至该报告的完整分析页面，其中，

![img](https://pic3.zhimg.com/80/v2-0839e287a0500b8aed9685f34b6e5e2a_1440w.webp)

Page Info：页面信息报告，首先可以看到当前查看页面的一些基本信息，例如，

![img](https://pic2.zhimg.com/80/v2-7b8baf039e1d5712e283e4834ffbe37d_1440w.webp)

- Title：页面标题，
- Meta Keywords：元关键字，
- Meta Description：元描述，
- Internal Links：当前页面找到的所有内部链接数量，
- External Links：当前页面找到的指向其他网站的所有外部链接数量，
- Server：网站的托管服务器，

接下来是当前查看页面的所有 SEOquake 参数的具体数据，同样的，点击任意一个可跳转查看参数数据来源的详细页面。

比如说，点击 Google Index 图标，便会跳转至 Google 搜索页面，通过 site: 高级搜索指令，查看具体的 Google 索引页面数，

![img](https://pic2.zhimg.com/80/v2-b26294c8a29b033b3534b930a31dabe1_1440w.webp)

再例如，点击 Alexa Rank 图标，便会跳转至 Alexa 的详细网站分析页面，上面显示了当前网站的 Alexa 具体排名，

![img](https://pic1.zhimg.com/80/v2-3222e822d6f19a545434e1a348890ce8_1440w.webp)

最后是关键词密度，向下滚动当前页面，还进一步查看当前页面细分的关键词数据，例如 2 字关键字、3 字关键字等。

![img](https://pic2.zhimg.com/80/v2-e3d0da1f8ccf020e72a01a171eb97b19_1440w.webp)

Diagnosis：即 PAGE SEO AUDIT ，页面 SEO 诊断报告，实时检测当前查看的页面，识别并告诉 SEOquake 发现的任何技术问题及给出相应的优化建议，可帮助修复和改善页面 SEO 和网站优化。结果数据分为三大部分，分别是 Page Analysis，Mobile Compliance，Site Compliance。其中，

Page Analysis：页面分析，分析当前查看页面的源代码，包括 URL 标题、页面标题，元描述和元关键字的字数统计和格式是否正确；6 种 H 标签的使用情况统计；当前页面是否有使用权威链接标签 rel =“Canonical”；页面图片是否有添加添加 ALT 文本；当前页面是否有使用框架 Frames 及矢量图和 web 动画 Flash；页面上的文本与页面 HTML 代码数量的比例 Text/HTML Ratio 是否低于 15%；

点击每个分析指标右边的 Tips 可查看 SEOquake 给出的最佳优化建议，例如 SEOquake 建议页面标题长度最好控制在 10-70 个字符内（包括空格）；元描述长度最好控制在 160-300 个字符内（描述应该带有页面关键词）；等等。

![img](https://pic2.zhimg.com/80/v2-fce379ac4f86223b298563527a1778ad_1440w.webp)

Mobile Compliance：移动合规性，检查当前页面与移动设备的兼容性，分为两大部分内容，分别是 AMP 和 Meta Viewport。其中，

![img](https://pic1.zhimg.com/80/v2-db3f836dc6a06b455d416ff0bf69d7fc_1440w.webp)

- AMP ：检测 AMP 版本页面的可用性， AMP（加速移动页面）是一种让页面在移动设备上快速加载的解决方案。据 Google 的研究分析表明，在使用移动设备访问网站时，如果页面加载时间需要 3 秒以上，那么大多数的访问者会选择离开，所以为了让自己从竞争中脱颖而出，优化着陆页的加载速度体验至关重要。
- Meta Viewport：检测当前页面是否有使用 Viewport 元标签，Viewport 视窗是网页中用户的可见区域，视窗因设备而异，例如移动设备的视窗就比电脑屏幕上的视窗要小。Viewport 元标签能够控制网页如何在移动设备上显示。如果没有 Viewport，移动设备将以典型的桌面屏幕宽度呈现页面，并缩放以适应屏幕，而通过使用 Viewport 元标签，可以在不同的设备上控制页面的宽度和缩放，即所谓的响应式网页设计，内容布局会根据设备的尺寸和功能而变化，自适应用户所使用设备的需求。

Site Compliance：网站合规性检测，这里指的是网站整体性的检查，而不仅仅是一个特定的网页，内容包括查看当前网站是否有 Robots.txt 文件，站点地图 XML sitemap，Favicon 网站图标，网站语言声明，Unicode 字符集编码格式，文档类型规范，等等。

![img](https://pic2.zhimg.com/80/v2-be344657484d079c985470e940fd96b9_1440w.webp)

Internal：内部链接报告，显示 SEOquake 就正在分析的页面找到的所有内部链接列表，每个链接下面都会标注有与该链接的链接类型，锚文本（如果有的话），链接重复次数（如果链接在这个页面中重复出现的话）；还可按照页面顶部的链接类型例如，Follow，No follow，Images，Text 等来进一步筛选查找，最后，可点击下面的 Save as CSV 的按钮来导出结果列表数据。

![img](https://pic3.zhimg.com/80/v2-ae49afa4f3e23ad2fa013f20207faf3e_1440w.webp)

External：外部链接报告，显示 SEOquake 就正在分析的页面找到的所有外部链接列表，报告内容跟上面的内部链接报告是类似的，这里就不再重复说了。

![img](https://pic3.zhimg.com/80/v2-56c624c6ed51e3fef7e3f0313ee794ca_1440w.webp)

Density：即 KEYWORD DENSITY 关键词密度报告，获取 SEOquake 就当前页面找到的所有关键词的详细和结构化报告，能够为理解当前网站或页面的语义和主要主题提供参考建议。报告列表默认是按照关键词出现的次数（重复度）降序排列，也可点击报告顶部位置的 2 字关键词，3 字关键词等进一步筛选结果。

![img](https://pic1.zhimg.com/80/v2-26c917620db32426769386008456e020_1440w.webp)

报告右边几个指标的解释如下：

- Found in：关键词在页面中出现的位置（页面标题/元描述/H 标签，等）；
- Repeats：关键词出现的次数；
- Density：关键词密度；
- Prominence：关键词对当前页面的重要性；

另外，在报告页面右侧边栏还有几个功能小部件，例如 Page info 看查看当当前页面的页面标题，元关键字和元描述。使用 Filter 过滤器可以进一步筛选特定的结果数据。最后，还有一个 Keywords cloud，里面的关键词的字体越大，就表示在页面出现的次数越多，点击可查看该关键词的详情数据。

![img](https://pic1.zhimg.com/80/v2-3e778893ae0e0197b511d22ac3f9f2a8_1440w.webp)

Compare URLs/Domains：能够将多个域和 URL 放在一起比较，通过查看 SEOquake 参数找到表现最优的结果，一次最多可输入处理 1000 个 URL。

![img](https://pic2.zhimg.com/80/v2-3e1054c1c9d90dabae299304c2a99159_1440w.webp)

如有需要，也可点击 Save as CSV 按钮导出结果数据。

![img](https://pic3.zhimg.com/80/v2-932fb69dc2bddf8080a860ddd750758a_1440w.webp)

**【 SEOquake 设置 】**

根据自己的实际需要正确设置 SEOquake，例如自定义指定首选项参数等，能够更加灵活地使用这个工具，仅接收所需的信息，提高工作效率。

SEOquake 设置可分为 Quick Options 快速设置和 Preferences 首选项设置。其中，

**Quick Options：**快速设置，这是在 SEOquake 后台面板中单击右上角齿轮设置图标后出现的下拉菜单，

![img](https://pic4.zhimg.com/80/v2-cf416fe3b0833e785cc7480f49602b6b_1440w.webp)

以下是各设置选项的含义：

- Enable SEOquake：在当前浏览器启用/禁用 SEOquake；
- Show SEObar：勾选即启用 SEObar；
- Highlight no-follow：用删除线标记来突出显示网页上出现的 “no-follow” 链接；

![img](https://pic3.zhimg.com/80/v2-76112c7497d9860320228a7a2ab2d326_1440w.webp)

- Show SERP Overlay：勾选希望在哪些搜索引擎中启用 SERP overlay；
- Preferences：导航到一个新页面，显示关于 SEOquake 的所有首选项设置；
- About SEOquake：点击会跳转至 SEOquake 官网，详细介绍什么是 SEOquake 及其功能。

**Preferences：**首选项设置，主要分为 4 大部分，分别是 General，SERP Overlay，SEObar，Parameters。其中，

General：SEOquake 一般性选项设置，

![img](https://pic3.zhimg.com/80/v2-7172d40d0b9f68036ec2421adfc56bce_1440w.webp)

以下是各选项的含义：

SEOquake is Enabled：在当前浏览器启用/禁用 SEOquake；

Enable Parameters Caching: SEOquake 的缓存设置，如果启用，SEOquake 将在系统内部缓存所有的参数值，直到浏览器重启。这个选项可以帮助避免被某些参数服务提供商(例如 Google)禁止，建议保持默认的启用即可；

Clear cache：快速清理系统内部的参数缓存（如果有启用了上面的缓存设置的话）；

Parameters Request Delay：参数请求延迟，设置接收首选项中设置的参数的速度，但要注意如果这里设置请求延迟速度过快可能会导致谷歌的禁止，来到谷歌验证页面 Captcha Page，

![img](https://pic1.zhimg.com/80/v2-45ae030f6b81fef2807f7f2faa610ea8_1440w.webp)

发生这种情况的原因就是这里设置的参数抓取速度过快，如果 Google 接收数据请求的速度过快，那么谷歌就会认为这是一种垃圾信息接收方式，同时因为 SEQquake 参数过多，试图一次获取如此多的参数数据，Google 会将其视为一种快速收集大量数据的自动化机器程序尝试，从而禁止请求。

避免出现这种情况的方法就是像上面所说的启用参数缓存设置，同时设置参数请求延迟不低于 500ms，低于此值就可能导致被 Google 禁止。

Load Parameters：设置参数加载方式，On Show 可理解为自动加载参数数据，By Request 可理解为手动点击加载参数数据，SEOquake 建议是选择 By Request 手动加载参数数据，从而避免出现上面所说的因为大量而快速的参数数据请求而被 Google 禁止的情况。

Show Tips：勾选后每天都会在 SEOquake 后台面板底部位置出现一个使用技巧的介绍。

SERP Overlay：SERP Overlay 首选项设置，以下是各选项的含义：

Show Numbers：显示各个搜索结果在 SERP 中的位置排名；

Show Keyword Difficulty：设置是否在 Google 搜索框下面显示关键词难度；

Show in Search Engine: 设置选择在哪些搜索引擎中启用 SERP Overlay；

Load Parameters：设置在 SERP 的每个搜索结果的 SERP Overlay 中，自动加载或通过请求接收（需要自己手动一个个去点击）参数数据；

![img](https://pic4.zhimg.com/80/v2-15dfb3c43b0c9d62e7ec197592cd456f_1440w.webp)

Active Parameters in SERP Overlay：设置希望在 SERP Overlay 中显示的参数；

![img](https://pic1.zhimg.com/80/v2-d8282bfeb4ccdc25df2bca2a0ef64a58_1440w.webp)

Highlight Domains：突出显示域，设置想要在搜索结果页面中突出显示的网站，直接在输入框中输入想要突出显示的网站即可，下面是设置高亮显示的颜色；

![img](https://pic2.zhimg.com/80/v2-c61443d3e2183ad8f5eadf1dc901158d_1440w.webp)

设置后如果搜索结果页面有上面列表中设置的网站，就会高亮显示；

![img](https://pic1.zhimg.com/80/v2-492a1e55de0760473282981e7ac3bc5c_1440w.webp)

SEObar：SEObar 首选项设置，以下是一些主要选项的含义：

SEObar Enabled: 设置是否允许在所有页面启用 SEObar；

Show on HTTPS：使得 SEObar 能够出现在 https 页面上；

Load Parameter: 设置自动加载或手动加载参数；

Position：设置 SEObar 在浏览器窗口中显示的位置 ，默认是页面顶部；

Colour style：选择用于 SEObar 显示的颜色风格；

![img](https://pic3.zhimg.com/80/v2-d617fe765faafaa5dd898dec855bded2_1440w.webp)

Parameters：选择想要显示在 SEObar 的特定参数；

Special Parameters：其他的一些参数选项，可以勾选显示在 SEObar 中；

URL Filters：URL 过滤器，排除某些域名或 URL，在这些排除页面不显示 SEObar；

Whitelisted Domains：设置可以显示 SEObar 的域名白名单。

![img](https://pic2.zhimg.com/80/v2-efce1d8defe32bbf1329dd15ca5bb8a9_1440w.webp)

Parameters：SEOquake 所有参数设置，可自由调整选择仅需显示的参数。通过勾选相应的复选框便可设置希望看到的参数以及在哪些工具/搜索引擎中启用这些参数，行属性表示 SEOquake 提供的所有参数，列属性表示希望给定参数出现在哪个工具/报告/搜索引擎中。

![img](https://pic1.zhimg.com/80/v2-bfa076f7b828db06efd75ec979577e8c_1440w.webp)

其中，列属性的选项含义如下：

- All：在 SEOquake 的每一个 report, tool and search engine 中启用所有参数；
- SEObar：在 SEObar 中启用指定的参数；
- Google：在 Google SERP 中启用指定的参数；
- Yahoo：在 Yahoo SERP 中启用指定的参数；
- Bing：在 Bing SERP 中启用指定的参数；
- Yandex：在 Yandex SERP 中启用指定的参数；
- SEMrush：在 SEMrush 结果中启用指定的参数；
- Linkinfo：在 Page Info 报告中启用指定的参数；
- Internal：在 Internal Links 报告中启用指定的参数 ；
- External：在 External Links 报告中启用指定的参数；

除了上面这些 SEOquake 目前支持的参数外，您也可以通过点击左上角的 “new Parameter” 按钮来自定义添加一个新的参数。但如果要自定义新参数，首先需要理解 SEOquake 参数的工作原理，另外，还需要一定的代码技术，例如如何通过代码定义网页的网址以及如何从那里获取此参数等。

如果对自定义创建新参数有兴趣的话，也可以点击 [SEOquake](https://link.zhihu.com/?target=https%3A//www.seoquake.com/guide/parameters/create.html) 的这篇文章查看。

好了，以上便是 SEOquake 这款 SEO 工具的详细使用介绍。
