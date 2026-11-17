# Awesome GPT-6.2

[English](README.md) · **简体中文**

**最近更新（Last Updated）· 2026-11-18** · AI Terrarium 整理

<a href="https://forest-walks-at-dusk.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/forest-walks/gallery-cover.webp" alt="Forest Walks：暮色中被夕阳照亮的林间小径" width="720"></a>

**Forest Walks · GPT-6.2 Astra。** 循着噼啪声去找篝火，再切换画风。同一片森林有三种样貌，切换时会保留你站的位置。[进入森林](https://forest-walks-at-dusk.openai.chatgpt.site/) · [Thomas Ricouard 的制作笔记](https://developers.openai.com/showcase/forest-walks)

**45 条 GPT-6.2 案例** · Astra 21 条 · Sol 22 条 · 混合流程 2 条 · 另附 6 条早期 GPT 对照。

[创意编程](#创意编程) · [可玩世界](#可玩世界) · [科学与工程](#科学与工程) · [公开源码](#公开源码) · [社区作品](COMMUNITY.zh-CN.md)

## 创意编程

| 作品 | 模型 | 可以看什么 |
| --- | --- | --- |
| 潮池木刻 | Astra · 官方 | 两份可编辑 SVG，同一主题分别直接生成、用参考图和设计技能生成。[直接生成](https://cdn.openai.com/devhub/docs/codex/svg-3d-design/tide-pool-without-skill.svg) · [参考图版本](https://cdn.openai.com/devhub/docs/codex/svg-3d-design/tide-pool-with-skill.svg) · [制作说明](https://learn.chatgpt.com/guides/svg-3d-design#creating-vector-illustrations-for-the-web) |
| 从风暴到日出 | Astra · 官方 | 用 JavaScript 改变风速和日光，让 SVG 里的浪高、白沫与色调一起变化。[动画和制作说明](https://learn.chatgpt.com/guides/svg-3d-design#animating-svg-curves-and-colors-with-code) |
| 飞蛾图鉴图标 | Astra · 官方 | 同一套 SVG 路径，换色后适配深浅主题，并在应用商店和小尺寸桌面图标上预览。[设计过程](https://learn.chatgpt.com/guides/svg-3d-design#designing-app-icons-for-light-and-dark-mode) |

想看更有趣的，社区还有月下像素小镇、骑 BMX 耍杂技的狮子和代码绘制的肖像。[社区插画、动画与设计](COMMUNITY.zh-CN.md#插画动画与设计)

## 公开源码

| 作品 | 看点 | 访问与来源 |
| --- | --- | --- |
| The Kite That Pulled the Sky | Canvas 画出风筝扯开乌云的过程，配乐由 Web Audio 合成。 | Astra，作者在发布前报告。可本地运行，未找到复用许可证。[源码](https://github.com/PankajKumardev/The-Kite-That-Pulled-the-Sky) · [作者原帖](https://x.com/pankajkumar_dev/status/2117948791496032542) |
| Ruby Kart | 同人卡丁车游戏，有多条赛道、多种模式和离线 HTML。 | Astra，作者称使用发布前的测试路由。原创代码按 MIT 授权，内嵌的第三方素材另计。作者说明在线版需要 GPT 账号。[仓库](https://github.com/vvvvvvvvvashhh/ruby-kart) · [试玩](https://ruby-kart-eight-circuits.vvvvvvvvvashhh.chatgpt.site/) |

## 可玩世界

下列八个项目的页面均明确写明使用 **GPT-6.2 Astra**，并提供制作过程。

| 作品 | 进去做什么 | 入口 |
| --- | --- | --- |
| Escapement · Eric Provencher | 看三颗弹珠触发一连串机械装置。 | [体验](https://escapement.openai.chatgpt.site/) · [制作笔记](https://developers.openai.com/showcase/escapement) |
| Forest Walks · Thomas Ricouard | 在三种画风里走同一条森林小径，循声找篝火。 | [体验](https://forest-walks-at-dusk.openai.chatgpt.site/) · [制作笔记](https://developers.openai.com/showcase/forest-walks) |
| Dot Rumble · Chaow Wu | 看参考图上的毛绒角色如何变成有骨骼和动作的格斗角色。 | [体验](https://dot-rumble-arcade.openai.chatgpt.site/) · [制作笔记](https://developers.openai.com/showcase/dot-rumble) |
| Light & Matter · Eric Provencher | 逛一座光影博物馆，近距离看材质、倒影和特效。 | [体验](https://light-and-matter.openai.chatgpt.site/) · [制作笔记](https://developers.openai.com/showcase/light-and-matter) |
| Paris Atlas · Thomas Ricouard | 在巴黎步行或开车。街道和建筑按地图数据流式加载，部分地标用了照片。 | [体验](https://paris-atlas-street-explorer.openai.chatgpt.site/) · [制作笔记](https://developers.openai.com/showcase/paris-atlas) |
| Notre Damn · Thomas Ricouard | 走进巴黎圣母院，逛小礼拜堂，切换光照时段。 | [体验](https://cathedral-walk.openai.chatgpt.site/) · [制作笔记](https://developers.openai.com/showcase/notre-damn) |
| Terrarium · Katia Gil Guzman | 在玻璃罐里摆放植物、苔藓和枝条，再调光看效果。 | [体验](https://terrarium-glasshouse-studio.openai.chatgpt.site/) · [制作笔记](https://developers.openai.com/showcase/terrarium-glasshouse-studio) |
| iMac G3 in Motion · Dominik Kundel | 滚动查看电脑如何装配，并切换外壳颜色。 | [体验](https://imac-g3-in-motion.openai.chatgpt.site/) · [制作笔记](https://developers.openai.com/showcase/imac-g3-in-motion) |

还有两个发布前归因的可玩作品。[雪国邮局和地毯赛车](COMMUNITY.zh-CN.md#可交互作品)

## 科学与工程

| 作品 | GPT-6.2 做了什么 | 来源 |
| --- | --- | --- |
| 山路底盘动力学 | Astra 建车模、编写轮胎与悬挂的 Python 求解器，再用 Blender 把结果做成动画。 | [官方视频和说明](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| 遥控越野车装配 | Astra 逐件建立装配模型，展示零部件如何装到一起。 | [官方展示](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| 直列六缸发动机 | Astra 按部件构建发动机模型。 | [官方展示](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| Marina City 纸灯 | Astra 把建筑参考照片变成 CAD 设计和纸灯制作网页，实体灯由人组装。 | [设计过程和工具入口](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |

科学编程的实际任务和模型成绩可查 [Terminal-Bench-Science 0.1](https://www.terminal-bench-science.ai/announcement) 与[各模型的评测结果](https://artificialanalysis.ai/evaluations/terminal-bench-science)。想比较同一个题目下的交互作品，可看 [AA-3D](https://artificialanalysis.ai/evaluations/aa-3d) 的弹球、黑洞和斗兽场等题目，打开前留意每个结果的模型标签。

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
- 数字统计的是目录中的条目。并列对照归入主要展示的 GPT-6.2 模型。同一作品由多个模型制作，或对照单模型和多模型两种制作流程，计入混合案例。每天复查，有内容变更才刷新更新日期。

## 投稿

欢迎用 Issue 或 PR 分享作品。请附上原帖或源码仓库、准确的模型版本，以及可用的试玩或录像链接。如果作者只是在猜测路由，也欢迎注明。能找到开源许可证或原始提示词的话，请一并附上。
