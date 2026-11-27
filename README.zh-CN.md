# Awesome GPT-6.2

<sub><a href="README.md">English</a> · 简体中文 · Last Updated 2026-11-27</sub>

[**Terrarium 作品库**](https://github.com/AI-Terrarium/terrarium) · [在线作品](https://terraium.ai/) · [源码档案](https://huggingface.co/datasets/AI-Terrarium/terrarium-open-works)

GPT-6.2 的 3D 作品、同题评测和公开源码。Terrarium 收录更多模型做的作品，也整理创作者公开的提示词与代码。

[**试玩 Forest Walks**](https://forest-walks-at-dusk.openai.chatgpt.site/) · [**看 Sol 录屏**](#3d--sol-62) · [**同题对照**](https://artificialanalysis.ai/3d/explorer) · [**找源码**](#公开源码)

<a href="https://github.com/AI-Terrarium/terrarium"><img src="https://raw.githubusercontent.com/AI-Terrarium/terrarium/main/assets/banner.webp" alt="Terrarium 作品库中的 3D 游戏与交互世界" width="768"></a>

66 条 GPT-6.2 案例（Astra 34 · Sol 25 · 混合 7） · [全部 Astra 3D](#3d--astra-62) · [创意编程](#创意编程) · [科学与工程](#科学与工程) · [社区作品](COMMUNITY.zh-CN.md)

## 模型表现

| 指标 | Astra 6.2 | Sol 6.2 |
| --- | --- | --- |
| AA-3D Elo（Max） | **1,318 ± 31** | **1,259 ± 28** |
| API 输入／输出 | **$8 / $40** | **$2 / $10** |

AA-3D Elo 来自同题作品的盲测偏好（95% 置信区间）。标准 API 单价来自 OpenAI 2026 年 11 月 17 日的发布公告，按每百万 token 计费；评测中的每题成本另见下方链接。

[同题试玩](https://artificialanalysis.ai/3d/explorer) · [排名](https://artificialanalysis.ai/evaluations/aa-3d#aa-3d-leaderboard) · [每题成本](https://artificialanalysis.ai/evaluations/aa-3d#cost) · [API 定价](https://openai.com/index/introducing-gpt-6-2-astra-sol/#pricing-and-availability)

## 3D · Astra 6.2

先从 Forest Walks 试玩。八款官方作品可直接体验并查看制作笔记，另有发布前的 RPG 录屏和发布后的弹珠台测试。

<table>
<tr>
<td width="50%" valign="top"><a href="https://forest-walks-at-dusk.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/forest-walks/gallery-cover.webp" alt="Forest Walks · Thomas Ricouard" width="228"></a><br><b>Forest Walks</b><br><sub>Thomas Ricouard</sub><br>在三种画风里走同一条森林小径，循声找篝火。<br><a href="https://forest-walks-at-dusk.openai.chatgpt.site/">体验</a> · <a href="https://developers.openai.com/showcase/forest-walks">制作笔记</a></td>
<td width="50%" valign="top"><a href="https://escapement.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/escapement/gallery-cover.webp" alt="Escapement · Eric Provencher" width="228"></a><br><b>Escapement</b><br><sub>Eric Provencher</sub><br>看三颗弹珠触发一连串机械装置。<br><a href="https://escapement.openai.chatgpt.site/">体验</a> · <a href="https://developers.openai.com/showcase/escapement">制作笔记</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://dot-rumble-arcade.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/dot-rumble/gallery-cover.webp" alt="Dot Rumble · Chaow Wu" width="228"></a><br><b>Dot Rumble</b><br><sub>Chaow Wu</sub><br>看参考图上的毛绒角色如何变成有骨骼和动作的格斗角色。<br><a href="https://dot-rumble-arcade.openai.chatgpt.site/">体验</a> · <a href="https://developers.openai.com/showcase/dot-rumble">制作笔记</a></td>
<td width="50%" valign="top"><a href="https://light-and-matter.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/light-and-matter/gallery-cover.webp" alt="Light &amp; Matter · Eric Provencher" width="228"></a><br><b>Light &amp; Matter</b><br><sub>Eric Provencher</sub><br>逛一座光影博物馆，近距离看材质、倒影和特效。<br><a href="https://light-and-matter.openai.chatgpt.site/">体验</a> · <a href="https://developers.openai.com/showcase/light-and-matter">制作笔记</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://paris-atlas-street-explorer.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/paris-atlas/gallery-cover.webp" alt="Paris Atlas · Thomas Ricouard" width="228"></a><br><b>Paris Atlas</b><br><sub>Thomas Ricouard</sub><br>在巴黎步行或开车。街道和建筑按地图数据流式加载，部分地标用了照片。<br><a href="https://paris-atlas-street-explorer.openai.chatgpt.site/">体验</a> · <a href="https://developers.openai.com/showcase/paris-atlas">制作笔记</a></td>
<td width="50%" valign="top"><a href="https://cathedral-walk.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/notre-damn/gallery-cover.webp" alt="Notre Damn · Thomas Ricouard" width="228"></a><br><b>Notre Damn</b><br><sub>Thomas Ricouard</sub><br>走进巴黎圣母院，逛小礼拜堂，切换光照时段。<br><a href="https://cathedral-walk.openai.chatgpt.site/">体验</a> · <a href="https://developers.openai.com/showcase/notre-damn">制作笔记</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://terrarium-glasshouse-studio.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/terrarium-glasshouse-studio/gallery-cover.webp" alt="Terrarium Glasshouse Studio · Katia Gil Guzman" width="228"></a><br><b>Terrarium Glasshouse Studio</b><br><sub>Katia Gil Guzman</sub><br>在玻璃罐里摆放植物、苔藓和枝条，再调光看效果。<br><a href="https://terrarium-glasshouse-studio.openai.chatgpt.site/">体验</a> · <a href="https://developers.openai.com/showcase/terrarium-glasshouse-studio">制作笔记</a></td>
<td width="50%" valign="top"><a href="https://imac-g3-in-motion.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/imac-g3-in-motion/gallery-cover.webp" alt="iMac G3 in Motion · Dominik Kundel" width="228"></a><br><b>iMac G3 in Motion</b><br><sub>Dominik Kundel</sub><br>滚动查看电脑如何装配，并切换外壳颜色。<br><a href="https://imac-g3-in-motion.openai.chatgpt.site/">体验</a> · <a href="https://developers.openai.com/showcase/imac-g3-in-motion">制作笔记</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/karanC_12/status/2116895719248536032"><img src="https://pbs.twimg.com/amplify_video_thumb/2116861535880667136/img/MDtD5GVn0iU5sbs4.jpg" alt="半开放式 3D RPG · @karanC_12" width="228"></a><br><b>半开放式 3D RPG</b><br><sub>@karanC_12</sub><br>据称由单条提示词生成的原型游戏实录。<br>作者称发布前使用 Astra<br><a href="https://x.com/karanC_12/status/2116895719248536032">录屏原帖</a></td>
<td width="50%" valign="top"><a href="https://rutinelabo.com/gpt-6-2-astra/"><img src="https://rutinelabo.com/blog/wp-content/uploads/2026/11/gpt-6-2-astra-images6.webp" alt="NIGHT PORT 太空港弹珠台 · RutineLabo" width="228"></a><br><b>NIGHT PORT</b><br><sub>RutineLabo · 作者称使用 Astra xhigh</sub><br>11 月 18 日同题测试中的太空港弹珠台。作者指出挡板速度仍有问题；各模型使用的客户端不同。<br><a href="https://rutinelabo.com/gpt-6-2-astra/">录屏、预览与测试记录</a></td>
</tr>
</table>

## 3D · Sol 6.2

这 13 段录屏由创作者在正式发布前分享，模型标签来自原帖。

<table>
<tr>
<td width="50%" valign="top"><a href="https://x.com/Mr_Salio/status/2119437812604838342"><img src="https://pbs.twimg.com/amplify_video_thumb/2119437684120707072/img/hWdo-zoXb1i1TRWG.jpg" alt="神殿与行星 · @Mr_Salio" width="228"></a><br><b>神殿与行星</b><br><sub>@Mr_Salio</sub><br>神殿、云层与高悬空中的巨型行星。创作者称未使用外部素材。<br><a href="https://x.com/Mr_Salio/status/2119437812604838342">录屏原帖</a></td>
<td width="50%" valign="top"><a href="https://x.com/TokenGremlin/status/2119409785900552548"><img src="https://pbs.twimg.com/amplify_video_thumb/2119409755286384640/img/FUyYzAl2XbSN0HDB.jpg" alt="从白昼到夜晚的村庄 · @TokenGremlin" width="228"></a><br><b>从白昼到夜晚的村庄</b><br><sub>@TokenGremlin</sub><br>单个 Three.js HTML 文件中的河流与樱花，光线随时间变化。<br><a href="https://x.com/TokenGremlin/status/2119409785900552548">录屏原帖</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/teddyaisi/status/2119503047646908664"><img src="https://pbs.twimg.com/amplify_video_thumb/2119501790601416704/img/i9BaBVQpTiUsxyhD.jpg" alt="单个 HTML 文件打造的城市 · @teddyaisi" width="228"></a><br><b>单个 HTML 文件打造的城市</b><br><sub>@teddyaisi</sub><br>Three.js 城市。作者称场景可交互且能离线运行。<br><a href="https://x.com/teddyaisi/status/2119503047646908664">录屏原帖</a></td>
<td width="50%" valign="top"><a href="https://x.com/Khazix0918/status/2119507514459144677"><img src="https://pbs.twimg.com/amplify_video_thumb/2119507467990413312/img/dCMmCV5ohy_PaqTY.jpg" alt="时间尽头 · @Khazix0918" width="228"></a><br><b>时间尽头</b><br><sub>@Khazix0918</sub><br>可用鼠标交互的 Three.js 环境。创作者分享了任务说明。<br>Sol，作者称经路由使用<br><a href="https://x.com/Khazix0918/status/2119507514459144677">录屏原帖</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/AnikaCodes/status/2119858362318033315"><img src="https://pbs.twimg.com/amplify_video_thumb/2119849730087833600/img/ieJLfQURTiMhfGWt.jpg" alt="从夏入冬 · @AnikaCodes" width="228"></a><br><b>从夏入冬</b><br><sub>@AnikaCodes</sub><br>玻璃罩中的微缩世界：湖面结冰，树木覆白。<br><a href="https://x.com/AnikaCodes/status/2119858362318033315">录屏原帖</a></td>
<td width="50%" valign="top"><a href="https://x.com/marcthecreatorr/status/2119437126194335764"><img src="https://pbs.twimg.com/amplify_video_thumb/2119436763835854848/img/KsFMXlW6f3Tq1QSc.jpg" alt="帆船 · @marcthecreatorr" width="228"></a><br><b>帆船</b><br><sub>@marcthecreatorr</sub><br>船舱内部、反射光线与昼夜循环。作者称作品为单个 Three.js HTML 文件，未使用外部 3D 素材。<br><a href="https://x.com/marcthecreatorr/status/2119437126194335764">录屏原帖</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/mirochill/status/2119886504751194537"><img src="https://pbs.twimg.com/amplify_video_thumb/2119886262043639809/img/-KGR-EqmRFBBH_OC.jpg" alt="厨房场景 · @mirochill" width="228"></a><br><b>厨房场景</b><br><sub>@mirochill</sub><br>作者放宽布局要求，观察模型如何安排厨房。<br><a href="https://x.com/mirochill/status/2119886504751194537">录屏原帖</a></td>
<td width="50%" valign="top"><a href="https://x.com/Huoimo/status/2119721282170425584"><img src="https://pbs.twimg.com/amplify_video_thumb/2119719941834162176/img/Smse4dp4h5m_TgG3.jpg" alt="数学狮子 · @Huoimo" width="228"></a><br><b>数学狮子</b><br><sub>@Huoimo</sub><br>作者称狮身由有符号距离场构建，鬃毛则由发丝组成。<br><a href="https://x.com/Huoimo/status/2119721282170425584">录屏原帖</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/dragono64v/status/2120545025893474415"><img src="https://pbs.twimg.com/amplify_video_thumb/2120544954028273664/img/MW3Rlkiste-jkTTx.jpg" alt="机械蝴蝶 · @dragono64v" width="228"></a><br><b>机械蝴蝶</b><br><sub>@dragono64v</sub><br>齿轮带动铰接的翅膀张合。<br><a href="https://x.com/dragono64v/status/2120545025893474415">录屏原帖</a></td>
<td width="50%" valign="top"><a href="https://x.com/Cayden970207/status/2119464819229344113"><img src="https://pbs.twimg.com/amplify_video_thumb/2119464225299152896/img/ZysGDL457Z-2Myr9.jpg" alt="龙卷风 · @Cayden970207" width="228"></a><br><b>龙卷风</b><br><sub>@Cayden970207</sub><br>可交互龙卷风。原帖附提示词，作者称单次生成。<br>Sol Max，作者称经路由使用<br><a href="https://x.com/Cayden970207/status/2119464819229344113">录屏原帖</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/pankajkumar_dev/status/2119469657291997366"><img src="https://pbs.twimg.com/amplify_video_thumb/2119468024617160704/img/cCAWrs6LweOR2fYT.jpg" alt="黑洞引力透镜 · @pankajkumar_dev" width="228"></a><br><b>黑洞引力透镜</b><br><sub>@pankajkumar_dev</sub><br>发光吸积盘，以及对引力透镜效应的视觉呈现。<br><a href="https://x.com/pankajkumar_dev/status/2119469657291997366">录屏原帖</a></td>
<td width="50%" valign="top"><a href="https://x.com/pankajkumar_dev/status/2119465155109196254"><img src="https://pbs.twimg.com/amplify_video_thumb/2119464782411780096/img/6Oce_2WAtZ9DVeIg.jpg" alt="超新星 · @pankajkumar_dev" width="228"></a><br><b>超新星</b><br><sub>@pankajkumar_dev</sub><br>通过代码呈现恒星坍缩与向外扩张的冲击波。<br><a href="https://x.com/pankajkumar_dev/status/2119465155109196254">录屏原帖</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/Thomas_jorgen/status/2119673965576655211"><img src="https://pbs.twimg.com/amplify_video_thumb/2119673512298487808/img/QIzbsMnZoa3KfSZh.jpg" alt="太空海盗 · @Thomas_jorgen" width="228"></a><br><b>太空海盗</b><br><sub>@Thomas_jorgen</sub><br>在连续的太空场景里招募船员、交易和管理资源。<br>通过 TesanaAI 使用 Sol<br><a href="https://x.com/Thomas_jorgen/status/2119673965576655211">录屏原帖</a></td>
</tr>
</table>

还有两款可交互作品，一款来自 Astra 的发布前测试，另一款由 Sol 和 Fable 共同制作。[雪国邮局和地毯赛车](COMMUNITY.zh-CN.md#可交互作品)

## 创意编程

<a href="https://learn.chatgpt.com/guides/svg-3d-design#creating-vector-illustrations-for-the-web"><img src="https://learn.chatgpt.com/images/codex/svg-3d-design/tide-pool.webp" alt="GPT-6.2 Astra 创作的潮池木刻 SVG 对照" width="330"></a>
<a href="https://x.com/SahilPanhotra/status/2119461852426219747"><img src="https://pbs.twimg.com/tweet_video_thumb/HWnXS5UasAA-ZuN.jpg" alt="GPT-6.2 Sol 月下像素小镇" width="234"></a>

[潮池木刻 · Astra 6.2](https://learn.chatgpt.com/guides/svg-3d-design#creating-vector-illustrations-for-the-web) · [月下像素小镇 · Sol 6.2，作者自述](https://x.com/SahilPanhotra/status/2119461852426219747)

| 作品 | 模型 | 可以看什么 |
| --- | --- | --- |
| 潮池木刻 | Astra · 官方 | 同一题目做了两份可编辑 SVG，其中一份使用参考图和设计技能。[直接生成](https://cdn.openai.com/devhub/docs/codex/svg-3d-design/tide-pool-without-skill.svg) · [参考图版本](https://cdn.openai.com/devhub/docs/codex/svg-3d-design/tide-pool-with-skill.svg) · [制作说明](https://learn.chatgpt.com/guides/svg-3d-design#creating-vector-illustrations-for-the-web) |
| 从风暴到日出 | Astra · 官方 | 用 JavaScript 改变风速和日光，让 SVG 里的浪高、白沫与色调一起变化。[动画和制作说明](https://learn.chatgpt.com/guides/svg-3d-design#animating-svg-curves-and-colors-with-code) |
| 飞蛾图鉴图标 | Astra · 官方 | 同一套 SVG 路径，换色后适配深浅主题，并在应用商店和小尺寸桌面图标上预览。[设计过程](https://learn.chatgpt.com/guides/svg-3d-design#designing-app-icons-for-light-and-dark-mode) |
| Vanitas, Rendered · 阿江 | Astra · 作者报告，发布前作品 | 用自行编写的路径追踪器渲染静物。[提示词和迭代图](https://ajiang.me/en/toolbox/video-426-astra/#vanitas) |
| Conchae Pelagicae · 阿江 | Astra · 作者报告，发布前作品 | 先为虚构贝壳建立 3D 模型，再转换成铜版画风格的线条。[提示词和迭代图](https://ajiang.me/en/toolbox/video-426-astra/#planche) |
| 夜车纸雕灯箱 · 阿江 | Astra · 作者报告，发布前作品 | 用代码渲染分层剪影与柔和阴影，呈现纸雕灯箱。[提示词和迭代图](https://ajiang.me/en/toolbox/video-426-astra/#train) |
| 昼夜城市 · AI/ML API | Astra · 作者报告 | 带车流和昼夜切换的 2D 动画城市。文章提供预览与 HTML 下载；Fable 对照使用了不同客户端。[作者对照文章](https://aimlapi.com/blog/gpt-6-2-astra-vs-claude-fable-5-2) |
| The Mossbound Giant · Deathdadev | Astra Max · 作者自述 | 用代码绘制的 42 秒动画短片，可按章节跳转，配有合成音轨。作者公开了 Arena 记录，并注明后续修复了字体和视频资源。[观看](https://Deathdadev.github.io/mossbound-giant/) · [源码与来源说明](https://github.com/Deathdadev/mossbound-giant)。未找到项目自身的复用许可。 |

阿江将前三件作品的制作日期记为 11 月 11–12 日，早于正式发布，并称未调用图像模型。以下图片来自创作者的实际输出：

<a href="https://ajiang.me/en/toolbox/video-426-astra/#vanitas"><img src="https://ajiang.me/_astro/vanitas.BeYicIc0.webp" alt="Vanitas, Rendered：酒杯、柠檬、牡蛎与怀表" width="160"></a>
<a href="https://ajiang.me/en/toolbox/video-426-astra/#planche"><img src="https://ajiang.me/_astro/planche-xiv.6IrQU_mf.webp" alt="Conchae Pelagicae：铜版画风格的三枚虚构贝壳" width="160"></a>
<a href="https://ajiang.me/en/toolbox/video-426-astra/#train"><img src="https://ajiang.me/_astro/night-train.BIf-HctJ.webp" alt="夜车：用代码渲染的分层纸雕灯箱" width="240"></a>
<a href="https://aimlapi.com/blog/gpt-6-2-astra-vs-claude-fable-5-2"><img src="https://cdn.prod.website-files.com/65b8f36fa600366bc7cf9a67/6afcd933ccd11fb0245e2a85_gpt62-astra-city-test-1200.webp" alt="Astra 的 2D 动画城市，窗户亮灯、车辆通行" width="240"></a>

<a href="https://Deathdadev.github.io/mossbound-giant/"><img src="https://raw.githubusercontent.com/Deathdadev/mossbound-giant/main/verification/lighting.jpg" alt="代码绘制的森林与苔藓巨人" width="330"></a>

还可以看骑 BMX 的杂技狮子和用 SVG 绘制的肖像。[社区插画、动画与设计](COMMUNITY.zh-CN.md#插画动画与设计)

## 公开源码

| 作品 | 看点 | 访问与来源 |
| --- | --- | --- |
| The Kite That Pulled the Sky | Canvas 画出风筝扯开乌云的过程，配乐由 Web Audio 合成。 | 发布前作品，作者标注 Astra。可本地运行，未找到复用许可证。[源码](https://github.com/PankajKumardev/The-Kite-That-Pulled-the-Sky) · [作者原帖](https://x.com/pankajkumar_dev/status/2117948791496032542) |
| Ruby Kart | 同人卡丁车游戏，有多条赛道、多种模式和离线 HTML。 | Astra，作者称使用发布前的测试路由。原创代码按 MIT 授权，内嵌的第三方素材另计。作者说明在线版需要 GPT 账号。[仓库](https://github.com/vvvvvvvvvashhh/ruby-kart) · [试玩](https://ruby-kart-eight-circuits.vvvvvvvvvashhh.chatgpt.site/) |
| 果冻实验室 · 亚里 | 彩虹果冻玩具，提供戳、拉扯、切开、扎钉子和加热的操作。 | 作者称使用 Sol xhigh。[公开源码](https://github.com/Yari-tuber/gpt62-vs-opus55-tests/tree/main/02_彩虹果冻/gpt-6.2-sol) · [共同提示词、其他模型版本与方法](https://github.com/Yari-tuber/gpt62-vs-opus55-tests)。MIT 许可。作者使用订阅，按 API 单价折算成本，所列金额并非实际 API 账单。 |
| 飞龙飞行模拟 · zhzh2001 | 一款可玩的 C++20 飞行与战斗游戏。项目混合使用 Claude、Codex 和 Hunyuan 3D；有日期的项目记录具体说明 Astra 6.2 在 Codex 中参与了生物骨架绑定与修复。 | 作者记录的混合流程。[项目与渲染片段](https://github.com/zhzh2001/dragon) · [Astra 模型生成记录](https://github.com/zhzh2001/dragon/blob/main/docs/MODEL_GENERATION.md)。仓库说明飞龙模型由 Hunyuan 3D 生成；Astra 负责部分骨架绑定和修复，并非整款游戏。 |

<a href="https://github.com/zhzh2001/dragon"><img src="https://raw.githubusercontent.com/zhzh2001/dragon/main/docs/media/roster.jpg" alt="飞行模拟项目中的六种飞龙" width="640"></a>

## 科学与工程

| 作品 | GPT-6.2 做了什么 | 来源 |
| --- | --- | --- |
| 山路底盘动力学 | Astra 建车模、编写轮胎与悬挂的 Python 求解器，再用 Blender 把结果做成动画。 | [官方视频和说明](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| 遥控越野车装配 | Astra 逐件建立装配模型，展示零部件如何装到一起。 | [官方展示](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| 直列六缸发动机 | Astra 按部件构建发动机模型。 | [官方展示](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| Marina City 纸灯 | Astra 把建筑参考照片变成 CAD 设计和纸灯制作网页，实体灯由人组装。 | [设计过程和工具入口](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| PELAGOS 风电控制台 · 阿江 | 展示天气回放、风机告警和维护工单的 3D 运维演示。 | Astra，作者报告的发布前作品。[制作记录](https://ajiang.me/en/toolbox/video-426-astra/#wind) · [在线体验](https://ajiang.me/demos/pelagos/gpt-6-2-astra/) · [各模型同题作品](https://ajiang.me/en/toolbox/pelagos/) |
| Verdant 花园模拟器 · Ramanpal Singh | 作者称使用 Sol 6.2 Ultra 编程，并用图像生成工具制作纹理与插画，计为混合流程。可种植、浇水和修剪，观察光照竞争、授粉及 SVG 生态图表。 | [11 月 19 日录屏、提示词与测试](https://promptslove.com/blog/gpt-6-2-sol-review/)。作者指出植物数量有上限，每次都从预设树木开始；测试浏览器中未能验证延时录像导出。 |
| Eksen 地球模拟器 · Avenox | 旋转地球，探索季节、日照和延伸至 2100 年的三种排放情景。气候计算采用简化的教学模型。 | Sol 6.2 Medium，Ultra Fast · 作者报告的 11 月 18 日测试。[提示词、截图与说明](https://github.com/avenoxai/astra-notlari/tree/main/testler/04-sol-ultrafast) · [单文件 HTML 源码](https://github.com/avenoxai/astra-notlari/blob/main/testler/04-sol-ultrafast/sonuc/eksen-dunya-simulasyonu.html)。 |

<a href="https://github.com/avenoxai/astra-notlari/tree/main/testler/04-sol-ultrafast"><img src="https://raw.githubusercontent.com/avenoxai/astra-notlari/main/testler/04-sol-ultrafast/sonuc/dunya-simulasyonu-klip-son.jpg" alt="Eksen 地球、日照控制与教学气候情景" width="480"></a>

想看模型如何完成完整的科研任务，可以查 [Terminal-Bench-Science 0.1](https://www.terminal-bench-science.ai/announcement) 和[各模型的评测结果](https://artificialanalysis.ai/evaluations/terminal-bench-science)。

## 早期 GPT 作品对照

| 作品 | 模型 | 入口 |
| --- | --- | --- |
| Void Explorer · 程序生成的太空探索 | GPT-6 Astra | [体验](https://void-explorer.openai.chatgpt.site/) · [制作笔记](https://developers.openai.com/showcase/void-explorer) |
| Tidegarden · 有潮汐与珊瑚礁的岛屿 | GPT-6 Astra | [体验](https://tidegarden.openai.chatgpt.site/) · [制作笔记](https://developers.openai.com/showcase/tidegarden) |
| Clockwork Observatory · 会变形的 WebGL 机械 | GPT-6 Astra | [体验](https://kinetic-architecture-astra-20260901.openai.chatgpt.site/) · [制作笔记](https://developers.openai.com/showcase/impossible-kinetic-architecture) |
| Sunwake · 驾帆船去找灯塔 | GPT-6 Astra | [体验](https://sunwake-the-last-light.openai.chatgpt.site/) · [制作笔记](https://developers.openai.com/showcase/sunwake) |
| Felt Dot · 用同一张参考图做两款 3D 角色 | GPT-6.1 Sol 对比 Claude Opus 5.5 | [源码、提示词和对照](https://github.com/okonio/felt-dot-gpt-vs-opus) |
| 挖掘机控制与游戏原型 | 作者在 Codex 里选的是 GPT-6.1 Sol Max | [原帖和录屏](https://www.reddit.com/r/threejs/comments/1xru46w/gpt62_sol_seems_to_have_made_a_huge_leap_in_3d/) |

想找适用于多个模型的程序化几何、材质、地形和动画素材，可以看 [Awesome Code-Native 3D](https://github.com/jiachengliu12345/awesome-code-native-3d)。

## 收录说明

- **体验**指可访问的在线作品。**公开源码**指能查看实现，是否可以复用要看各项目的许可证。录像和图片会标明。
- **官方**指发布方明确标注模型。社区作品按作者说法记录，推测路由的案例会单独注明。[OpenAI 正式发布于 2026 年 11 月 17 日](https://community.openai.com/t/gpt-6-2-astra-and-sol-are-now-available/1417531)。
- 数字按本页和社区作品集中的独立 GPT-6.2 卡片、表格条目统计；预览图和重复链接不另计，一行列出的作品集计一条。并列对照归入主要展示的 GPT-6.2 模型。同一作品由多个模型制作，或对照单模型和多模型两种制作流程，计入混合案例。每天复查，有内容变更才刷新更新日期。

## 投稿

欢迎用 Issue 或 PR 分享作品。请附上原帖或源码仓库、准确的模型版本，以及可用的试玩或录像链接。如果作者只是在猜测路由，也欢迎注明。能找到开源许可证或原始提示词的话，请一并附上。
