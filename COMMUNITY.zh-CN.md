# 社区作品集

[← Awesome GPT-6.2](README.zh-CN.md) · [English](COMMUNITY.md) · **简体中文**

大多数作品在 OpenAI 11 月 17 日正式发布前就已经公开，第一节收录发布后的案例，目录保留作者对模型的说法。凡是作者根据线索推测实际模型的条目，都标明路由不确定。标为录屏的链接可以看作品效果，在线链接可以打开原作。作者称为模拟的作品，在此按视觉演示收录。

[发布后案例](#发布后案例) · [插画、动画与设计](#插画动画与设计) · [可交互作品](#可交互作品) · [3D 世界](#3d-世界与程序化场景) · [动态与模拟](#视觉模拟与动态效果) · [游戏与对比](#玩法与动画对照)

## 发布后案例

| 作品 | 模型 | 作者分享了什么 |
| --- | --- | --- |
| 恒星诞生 · u/GapNew4766 | Astra 6.2 单独制作，对照 Astra + Qwen 3.8 | 同一份简报做成两段单文件 HTML 短片，可以对照日食、恒星点火和行星轨道场景。[作者原帖](https://www.reddit.com/r/ChatGPTPro/comments/1xyty9y/gpt62_astra_built_the_same_3d_scene_for_162/) |
| Three.js Eval 作品集 · u/k1rd | Sol 6.2 High · 作者报告 | 与其他模型使用同一组固定提示词，可以逐个打开场景。作者称全部场景均可运行，其中一项经过修复；发帖时尚无盲评票数或排名。[作品集](https://threejseval.com/models/gpt-6.2-sol-high) · [作者的配置与结果](https://www.reddit.com/r/OpenAI/comments/1xz037w/gpt62_sol_results_on_a_standard_threejs_eval_16/) |
| Hearth 家庭事务面板 · Amanda Caswell | Astra 6.2 · 作者报告 | 将日历、餐单、购物清单和家务放在同一个面板。[11 月 18 日提示词与截图](https://www.tomsguide.com/ai/chatgpt/i-tested-chatgpts-new-gpt-6-2-astra-with-one-prompt-and-built-a-website-id-actually-use)。作者称改动可保存；文中未提供公开试玩或源码。 |
| 三项视觉编程对照 · u/Fresh-Resolution182 | Astra 6.2 · 作者报告 | 一帖对照了 Three.js 平台跳跃游戏、带油门滑块和实时读数的交互式喷气发动机课程，以及一段 3D 动态作品。作者报告三次运行费用分别为 $0.13、$0.14 和 $0.09；这是作者报告的单次运行成本，不是 API 标准单价。[作者原帖、视频、提示词与运行表](https://www.reddit.com/r/ArtificialInteligence/comments/1y16hqw/gpt62_astra_vs_claude_fable_52_on_3_real_creator/) |

<a href="https://www.tomsguide.com/ai/chatgpt/i-tested-chatgpts-new-gpt-6-2-astra-with-one-prompt-and-built-a-website-id-actually-use"><img src="https://cdn.mos.cms.futurecdn.net/uZ7a46fApaQChpifaFz9k7.jpg" alt="Amanda Caswell 实测中的 Hearth 家庭事务面板" width="480"></a>

## 插画、动画与设计

以下作品在正式发布前分享，模型标签和对照说明来自作者。

| 作品 | 模型 | 可以看什么 |
| --- | --- | --- |
| 月下像素小镇 · @SahilPanhotra | Sol | 樱花、灯火和水面倒影。作者称动画用代码绘制。[录屏](https://x.com/SahilPanhotra/status/2119461852426219747) |
| 骑 BMX 的狮子 · @SahilPanhotra | Sol | 狮子一边骑车一边抛接，背景走过四季。[录屏](https://x.com/SahilPanhotra/status/2119458278115835912) |
| 两幅代码肖像 · @marcthecreatorr | Sol | 作者称两幅肖像由 SVG 绘制，原帖提供提示词和成图。[原帖](https://x.com/marcthecreatorr/status/2119466616693850352) |
| 一笔一笔画肖像 · @Ananth7e | Sol | 看模型实时画出 Sam Altman 的肖像。[录屏](https://x.com/Ananth7e/status/2119482362614677566) |
| 单文件网页设计挑战 · @Stargridcompass | Sol 对比 Opus 5.5 | 同一提示词，让两个模型各做一张让人想截图分享的网页。[对照](https://x.com/Stargridcompass/status/2119743048364277820) |
| 模型发布动画 · @GulaGala001 | Astra | 作者制作的 GPT-6.2 Astra 发布概念动画。[录屏](https://x.com/GulaGala001/status/2116921245296132479) |
| 像素幻想小镇 · @notjazii | Astra 对比 GPT-6 Astra | 同一提示词分别在 Codex 和 Devin 运行，两个结果的工具环境也不同。[对照](https://x.com/notjazii/status/2117323835364245744) |

## 可交互作品

| 作品 | 可以体验什么 | 模型说明与链接 |
| --- | --- | --- |
| 雪中邮局 · @nelia | 探索雪中的车站、切换视角并打开一封信。 | Astra，模型路由不确定。作者表示，使用记录中没有显示新版本。[在线 HTML](https://yukino-snowletter-halt.atonelia.chatgpt.site/) · [创作者帖子与提示词](https://linux.do/t/topic/3117060#post_10) |
| 童年地毯赛车 · @noclipepe | 驾驶迷你赛车，在游戏地毯上驰骋。 | 混合使用。创作者称赛车逻辑和对手 AI 使用 Sol，画面、物理效果与集成使用 Fable 5.2。[在线体验](https://noclipepe.pages.dev/rug/) · [创作者帖子](https://x.com/noclipepe/status/2120107337650155798) |
| 逆潮电台 · Thweki | 中文像素横版游戏，设有修理铺和调频教程。 | 上传者称为 Astra 测试产物，未提供生成对话。[源码与移植说明](https://github.com/Thweki/undertow-fm) · [桌面浏览器预览](https://page.thweki.com:8443/undertow-fm/)。网页版含后续兼容性改动；上传者的检查未完成教程。未找到游戏自身代码或美术的复用许可。 |

<a href="https://github.com/Thweki/undertow-fm"><img src="https://raw.githubusercontent.com/Thweki/undertow-fm/main/docs/browser-review/gameplay-movement.png" alt="逆潮电台的修理铺与未完成的教程" width="480"></a>

## 3D 世界与程序化场景

3D 作品预览已放进首页，按 [Astra 6.2](README.zh-CN.md#3d--astra-62) 和 [Sol 6.2](README.zh-CN.md#3d--sol-62) 浏览。

## 视觉模拟与动态效果

| 作品 | 录屏展示内容 | 作者报告的模型与原帖 |
| --- | --- | --- |
| 动态测试 · @BreezeOg1 | 与节拍同步的转场、镜头运动和故障特效。工作流程使用了参考视频、角色素材和音频。 | [Sol](https://x.com/BreezeOg1/status/2119495488445497489) |
| 只有四种工作？· @yuchenz79260729 | 一段代码生成的短片，使用 Swift 渲染、Python 生成配乐，并在本地生成语音。 | [Sol，模型路由不确定](https://x.com/yuchenz79260729/status/2122391206386925698) |

## 玩法与动画对照

| 作品 | 录屏展示内容 | 作者报告的模型与原帖 |
| --- | --- | --- |
| 游戏地毯赛车效果对比 · @noclipepe | 使用相同地毯和提示词，比较赛车机制与画面效果。这是前期测试，对上方的混合模型游戏有所启发。 | [Sol 与 Fable 5.5，路由为作者报告](https://x.com/noclipepe/status/2119728047754547326) |
| 代码动画效果对比 · @vikktorrrre | 创作者对同一条提示词生成的两种结果进行比较。 | [Sol 与 Opus 5.5，路由为作者报告](https://x.com/vikktorrrre/status/2119473712751649201) |

## 其他资源

- [OpenAI 游戏展示](https://developers.openai.com/showcase/games) 和 [OpenAI 网站展示](https://developers.openai.com/showcase/websites) 收录了多个模型世代的作品。请在各项目页面查看具体使用的模型。
- SandBase 的 [Astra 列表](https://github.com/sandbase-lab/awesome-gpt-6-2-astra) 与 [Sol 列表](https://github.com/sandbase-lab/awesome-gpt-6-2-sol) 汇集了创作者录屏，其中许多视频录制自生成的 HTML 页面。
- @cheercheung 的 [Astra 示例](https://github.com/cheercheung/awesome-gpt-6-2-astra-guide-and-use-cases) 与 [Sol 示例](https://github.com/cheercheung/awesome-gpt-6-2-sol-use-cases) 便于追溯社交媒体帖子、录屏和任务说明。
- 这些发现列表中的模型标签有时与创作者帖子的说法不一致。例如，[Mallow Catch 的创作者](https://x.com/RenaRoze_doll/status/2118310499213312478) 将作品归功于 Opus 5.5，尽管同一帖子也提到了 GPT-6.2。帖子中提及某个模型，并不一定代表作品就是用它制作的。
