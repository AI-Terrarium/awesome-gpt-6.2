# Awesome GPT-6.2

<sub>English · <a href="README.zh-CN.md">简体中文</a> · Last Updated 2026-11-26</sub>

[**Terrarium on GitHub**](https://github.com/AI-Terrarium/terrarium) · [Browse the gallery](https://terraium.ai/) · [Source archive](https://huggingface.co/datasets/AI-Terrarium/terrarium-open-works)

Explore 3D work built with GPT-6.2, compare models on the same brief, and find code you can inspect. Terrarium collects work from more models, along with the code and prompts their creators share.

[**Play Forest Walks**](https://forest-walks-at-dusk.openai.chatgpt.site/) · [**Watch Sol demos**](#3d--sol-62) · [**Compare models**](https://artificialanalysis.ai/3d/explorer) · [**Find code**](#source-available)

<a href="https://github.com/AI-Terrarium/terrarium"><img src="https://raw.githubusercontent.com/AI-Terrarium/terrarium/main/assets/banner.webp" alt="Terrarium catalog of 3D games and interactive worlds" width="768"></a>

64 GPT-6.2 entries (34 Astra · 25 Sol · 5 mixed) · [All Astra 3D](#3d--astra-62) · [Creative coding](#creative-coding) · [Science and engineering](#science-and-engineering) · [Community gallery](COMMUNITY.md)

## Model performance

| Measure | Astra 6.2 | Sol 6.2 |
| --- | --- | --- |
| AA-3D Elo (Max) | **1,318 ± 31** | **1,259 ± 28** |
| API input / output | **$8 / $40** | **$2 / $10** |

AA-3D Elo comes from blind comparisons on the same brief (95% confidence intervals). Standard API rates are from OpenAI's November 17, 2026 launch, per million tokens; evaluation cost per task is linked separately below.

[Try the same tasks](https://artificialanalysis.ai/3d/explorer) · [Leaderboard](https://artificialanalysis.ai/evaluations/aa-3d#aa-3d-leaderboard) · [Cost per task](https://artificialanalysis.ai/evaluations/aa-3d#cost) · [API pricing](https://openai.com/index/introducing-gpt-6-2-astra-sol/#pricing-and-availability)

## 3D · Astra 6.2

Start with Forest Walks. Eight official projects have playable builds and notes. Community additions include a prelaunch RPG recording and a post-launch pinball test.

<table>
<tr>
<td width="50%" valign="top"><a href="https://forest-walks-at-dusk.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/forest-walks/gallery-cover.webp" alt="Forest Walks · Thomas Ricouard" width="228"></a><br><b>Forest Walks</b><br><sub>Thomas Ricouard</sub><br>Explore the same forest in three visual styles and find a campfire by sound.<br><a href="https://forest-walks-at-dusk.openai.chatgpt.site/">Live</a> · <a href="https://developers.openai.com/showcase/forest-walks">Build notes</a></td>
<td width="50%" valign="top"><a href="https://escapement.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/escapement/gallery-cover.webp" alt="Escapement · Eric Provencher" width="228"></a><br><b>Escapement</b><br><sub>Eric Provencher</sub><br>Watch three marbles trigger a chain of mechanical mechanisms.<br><a href="https://escapement.openai.chatgpt.site/">Live</a> · <a href="https://developers.openai.com/showcase/escapement">Build notes</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://dot-rumble-arcade.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/dot-rumble/gallery-cover.webp" alt="Dot Rumble · Chaow Wu" width="228"></a><br><b>Dot Rumble</b><br><sub>Chaow Wu</sub><br>See how a reference silhouette becomes a rigged plush fighter and joins an arcade roster.<br><a href="https://dot-rumble-arcade.openai.chatgpt.site/">Live</a> · <a href="https://developers.openai.com/showcase/dot-rumble">Build notes</a></td>
<td width="50%" valign="top"><a href="https://light-and-matter.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/light-and-matter/gallery-cover.webp" alt="Light &amp; Matter · Eric Provencher" width="228"></a><br><b>Light &amp; Matter</b><br><sub>Eric Provencher</sub><br>Walk through a museum of materials, reflections, lighting, and effects.<br><a href="https://light-and-matter.openai.chatgpt.site/">Live</a> · <a href="https://developers.openai.com/showcase/light-and-matter">Build notes</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://paris-atlas-street-explorer.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/paris-atlas/gallery-cover.webp" alt="Paris Atlas · Thomas Ricouard" width="228"></a><br><b>Paris Atlas</b><br><sub>Thomas Ricouard</sub><br>Walk or drive around Paris. The browser streams streets and buildings using geographic data. Some landmarks use photographs.<br><a href="https://paris-atlas-street-explorer.openai.chatgpt.site/">Live</a> · <a href="https://developers.openai.com/showcase/paris-atlas">Build notes</a></td>
<td width="50%" valign="top"><a href="https://cathedral-walk.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/notre-damn/gallery-cover.webp" alt="Notre Damn · Thomas Ricouard" width="228"></a><br><b>Notre Damn</b><br><sub>Thomas Ricouard</sub><br>Explore Notre-Dame, its chapels, and changing daylight in a 3D scene.<br><a href="https://cathedral-walk.openai.chatgpt.site/">Live</a> · <a href="https://developers.openai.com/showcase/notre-damn">Build notes</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://terrarium-glasshouse-studio.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/terrarium-glasshouse-studio/gallery-cover.webp" alt="Terrarium Glasshouse Studio · Katia Gil Guzman" width="228"></a><br><b>Terrarium Glasshouse Studio</b><br><sub>Katia Gil Guzman</sub><br>Arrange plants, moss, and branches in a glass garden and adjust the lighting.<br><a href="https://terrarium-glasshouse-studio.openai.chatgpt.site/">Live</a> · <a href="https://developers.openai.com/showcase/terrarium-glasshouse-studio">Build notes</a></td>
<td width="50%" valign="top"><a href="https://imac-g3-in-motion.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/imac-g3-in-motion/gallery-cover.webp" alt="iMac G3 in Motion · Dominik Kundel" width="228"></a><br><b>iMac G3 in Motion</b><br><sub>Dominik Kundel</sub><br>Scroll through the computer&#x27;s assembly and switch among shell colors.<br><a href="https://imac-g3-in-motion.openai.chatgpt.site/">Live</a> · <a href="https://developers.openai.com/showcase/imac-g3-in-motion">Build notes</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/karanC_12/status/2116895719248536032"><img src="https://pbs.twimg.com/amplify_video_thumb/2116861535880667136/img/MDtD5GVn0iU5sbs4.jpg" alt="Semi-open 3D RPG · @karanC_12" width="228"></a><br><b>Semi-open 3D RPG</b><br><sub>@karanC_12</sub><br>Gameplay footage of a prototype attributed to one prompt.<br>Prelaunch Astra claim<br><a href="https://x.com/karanC_12/status/2116895719248536032">Creator recording</a></td>
<td width="50%" valign="top"><a href="https://rutinelabo.com/gpt-6-2-astra/"><img src="https://rutinelabo.com/blog/wp-content/uploads/2026/11/gpt-6-2-astra-images6.webp" alt="NIGHT PORT pinball table · RutineLabo" width="228"></a><br><b>NIGHT PORT</b><br><sub>RutineLabo · Astra xhigh, creator-reported</sub><br>A spaceport pinball table from a November 18 same-brief test. The author reports a remaining flipper-speed issue; the models used different clients.<br><a href="https://rutinelabo.com/gpt-6-2-astra/">Recording, preview, and test notes</a></td>
</tr>
</table>

## 3D · Sol 6.2

Creators shared these 13 recordings before the public release. Model labels come from the original posts.

<table>
<tr>
<td width="50%" valign="top"><a href="https://x.com/Mr_Salio/status/2119437812604838342"><img src="https://pbs.twimg.com/amplify_video_thumb/2119437684120707072/img/hWdo-zoXb1i1TRWG.jpg" alt="Temple and planet · @Mr_Salio" width="228"></a><br><b>Temple and planet</b><br><sub>@Mr_Salio</sub><br>A temple, clouds, and a great planet overhead. Creator reports no external assets.<br><a href="https://x.com/Mr_Salio/status/2119437812604838342">Creator recording</a></td>
<td width="50%" valign="top"><a href="https://x.com/TokenGremlin/status/2119409785900552548"><img src="https://pbs.twimg.com/amplify_video_thumb/2119409755286384640/img/FUyYzAl2XbSN0HDB.jpg" alt="Village from day to night · @TokenGremlin" width="228"></a><br><b>Village from day to night</b><br><sub>@TokenGremlin</sub><br>A river and cherry blossoms as lighting changes in one Three.js HTML file.<br><a href="https://x.com/TokenGremlin/status/2119409785900552548">Creator recording</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/teddyaisi/status/2119503047646908664"><img src="https://pbs.twimg.com/amplify_video_thumb/2119501790601416704/img/i9BaBVQpTiUsxyhD.jpg" alt="City in one HTML file · @teddyaisi" width="228"></a><br><b>City in one HTML file</b><br><sub>@teddyaisi</sub><br>A Three.js city the author reports is interactive and runs offline.<br><a href="https://x.com/teddyaisi/status/2119503047646908664">Creator recording</a></td>
<td width="50%" valign="top"><a href="https://x.com/Khazix0918/status/2119507514459144677"><img src="https://pbs.twimg.com/amplify_video_thumb/2119507467990413312/img/dCMmCV5ohy_PaqTY.jpg" alt="The End of Time · @Khazix0918" width="228"></a><br><b>The End of Time</b><br><sub>@Khazix0918</sub><br>A Three.js environment with mouse interaction. The creator shares the brief.<br>Sol, routing reported<br><a href="https://x.com/Khazix0918/status/2119507514459144677">Creator recording</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/AnikaCodes/status/2119858362318033315"><img src="https://pbs.twimg.com/amplify_video_thumb/2119849730087833600/img/ieJLfQURTiMhfGWt.jpg" alt="Summer to winter · @AnikaCodes" width="228"></a><br><b>Summer to winter</b><br><sub>@AnikaCodes</sub><br>A miniature glass-cased world whose lake freezes and trees turn white.<br><a href="https://x.com/AnikaCodes/status/2119858362318033315">Creator recording</a></td>
<td width="50%" valign="top"><a href="https://x.com/marcthecreatorr/status/2119437126194335764"><img src="https://pbs.twimg.com/amplify_video_thumb/2119436763835854848/img/KsFMXlW6f3Tq1QSc.jpg" alt="Sailing ship · @marcthecreatorr" width="228"></a><br><b>Sailing ship</b><br><sub>@marcthecreatorr</sub><br>Ship interiors, reflected light, and a day/night cycle. The author reports a single Three.js HTML file with no external 3D assets.<br><a href="https://x.com/marcthecreatorr/status/2119437126194335764">Creator recording</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/mirochill/status/2119886504751194537"><img src="https://pbs.twimg.com/amplify_video_thumb/2119886262043639809/img/-KGR-EqmRFBBH_OC.jpg" alt="Kitchen scene · @mirochill" width="228"></a><br><b>Kitchen scene</b><br><sub>@mirochill</sub><br>The creator relaxed the layout constraints to see how the model would arrange a kitchen.<br><a href="https://x.com/mirochill/status/2119886504751194537">Creator recording</a></td>
<td width="50%" valign="top"><a href="https://x.com/Huoimo/status/2119721282170425584"><img src="https://pbs.twimg.com/amplify_video_thumb/2119719941834162176/img/Smse4dp4h5m_TgG3.jpg" alt="Mathematical lion · @Huoimo" width="228"></a><br><b>Mathematical lion</b><br><sub>@Huoimo</sub><br>Signed distance fields for the body and hair strands for the mane, per the author.<br><a href="https://x.com/Huoimo/status/2119721282170425584">Creator recording</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/dragono64v/status/2120545025893474415"><img src="https://pbs.twimg.com/amplify_video_thumb/2120544954028273664/img/MW3Rlkiste-jkTTx.jpg" alt="Mechanical butterfly · @dragono64v" width="228"></a><br><b>Mechanical butterfly</b><br><sub>@dragono64v</sub><br>Gears drive the butterfly’s hinged wings.<br><a href="https://x.com/dragono64v/status/2120545025893474415">Creator recording</a></td>
<td width="50%" valign="top"><a href="https://x.com/Cayden970207/status/2119464819229344113"><img src="https://pbs.twimg.com/amplify_video_thumb/2119464225299152896/img/ZysGDL457Z-2Myr9.jpg" alt="Tornado · @Cayden970207" width="228"></a><br><b>Tornado</b><br><sub>@Cayden970207</sub><br>An interactive Three.js tornado. The creator shares the brief and describes a single run.<br>Sol Max, routing reported<br><a href="https://x.com/Cayden970207/status/2119464819229344113">Creator recording</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/pankajkumar_dev/status/2119469657291997366"><img src="https://pbs.twimg.com/amplify_video_thumb/2119468024617160704/img/cCAWrs6LweOR2fYT.jpg" alt="Black-hole lensing · @pankajkumar_dev" width="228"></a><br><b>Black-hole lensing</b><br><sub>@pankajkumar_dev</sub><br>A glowing accretion disk and a visual treatment of gravitational lensing.<br><a href="https://x.com/pankajkumar_dev/status/2119469657291997366">Creator recording</a></td>
<td width="50%" valign="top"><a href="https://x.com/pankajkumar_dev/status/2119465155109196254"><img src="https://pbs.twimg.com/amplify_video_thumb/2119464782411780096/img/6Oce_2WAtZ9DVeIg.jpg" alt="Supernova · @pankajkumar_dev" width="228"></a><br><b>Supernova</b><br><sub>@pankajkumar_dev</sub><br>A collapsing star and expanding shock waves rendered from code.<br><a href="https://x.com/pankajkumar_dev/status/2119465155109196254">Creator recording</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://x.com/Thomas_jorgen/status/2119673965576655211"><img src="https://pbs.twimg.com/amplify_video_thumb/2119673512298487808/img/QIzbsMnZoa3KfSZh.jpg" alt="Space Pirate · @Thomas_jorgen" width="228"></a><br><b>Space Pirate</b><br><sub>@Thomas_jorgen</sub><br>A browser game prototype with a seamless universe, crews, trade, and resource management.<br>Sol via TesanaAI<br><a href="https://x.com/Thomas_jorgen/status/2119673965576655211">Creator recording</a></td>
</tr>
</table>

Two more playable works have prelaunch claims, one attributed to Astra and one combining Sol and Fable. [The Snow Post and Childhood Rug Racer](COMMUNITY.md#playable)

## Creative coding

<a href="https://learn.chatgpt.com/guides/svg-3d-design#creating-vector-illustrations-for-the-web"><img src="https://learn.chatgpt.com/images/codex/svg-3d-design/tide-pool.webp" alt="Two GPT-6.2 Astra SVG tide-pool woodcuts" width="330"></a>
<a href="https://x.com/SahilPanhotra/status/2119461852426219747"><img src="https://pbs.twimg.com/tweet_video_thumb/HWnXS5UasAA-ZuN.jpg" alt="GPT-6.2 Sol moonlit pixel-art town" width="234"></a>

[Tide Pool Woodcut · Astra 6.2](https://learn.chatgpt.com/guides/svg-3d-design#creating-vector-illustrations-for-the-web) · [Moonlit Pixel-Art Town · Sol 6.2, creator-reported](https://x.com/SahilPanhotra/status/2119461852426219747)

| Work | Model | What to open |
| --- | --- | --- |
| Tide Pool Woodcut | Astra · official | Compare two editable SVGs. One was generated with reference art and a design skill. [Direct generation](https://cdn.openai.com/devhub/docs/codex/svg-3d-design/tide-pool-without-skill.svg) · [Reference-led version](https://cdn.openai.com/devhub/docs/codex/svg-3d-design/tide-pool-with-skill.svg) · [Build notes](https://learn.chatgpt.com/guides/svg-3d-design#creating-vector-illustrations-for-the-web) |
| Storm to Sunrise | Astra · official | A 2D SVG seascape where wind changes the waves and daylight shifts the palette. [Recorded animation and build notes](https://learn.chatgpt.com/guides/svg-3d-design#animating-svg-curves-and-colors-with-code) |
| Moth Field Guide Icon | Astra · official | One SVG shape in light and dark palettes, shown at app-store and home-screen sizes. [Design walkthrough](https://learn.chatgpt.com/guides/svg-3d-design#designing-app-icons-for-light-and-dark-mode) |
| Vanitas, Rendered · Ajiang | Astra · creator-reported prelaunch | A procedural still life rendered with a custom path tracer. [Prompt and revision images](https://ajiang.me/en/toolbox/video-426-astra/#vanitas) |
| Conchae Pelagicae · Ajiang | Astra · creator-reported prelaunch | Invented shells modeled in 3D and converted into copperplate-style linework. [Prompt and revision images](https://ajiang.me/en/toolbox/video-426-astra/#planche) |
| The Night Train · Ajiang | Astra · creator-reported prelaunch | A code-rendered paper lightbox with layered silhouettes and soft shadows. [Prompt and revision images](https://ajiang.me/en/toolbox/video-426-astra/#train) |
| City, day and night · AI/ML API | Astra · creator-reported | An animated 2D city with traffic and a day/night switch. The article includes a preview and HTML download; the Fable comparison used a different client. [Creator's comparison](https://aimlapi.com/blog/gpt-6-2-astra-vs-claude-fable-5-2) |
| The Mossbound Giant · Deathdadev | Astra Max · creator-reported | A 42-second anime short drawn in code, with chapter seeking and synthesized sound. The creator shares an Arena trace and notes later font and video repairs. [Live](https://Deathdadev.github.io/mossbound-giant/) · [Source and provenance](https://github.com/Deathdadev/mossbound-giant). No project reuse license was found. |

Ajiang dates the three renders November 11–12, before launch, and reports that no image model was used. These are the creator's output images:

<a href="https://ajiang.me/en/toolbox/video-426-astra/#vanitas"><img src="https://ajiang.me/_astro/vanitas.BeYicIc0.webp" alt="Vanitas, Rendered: glass, lemon, oyster and pocket watch" width="160"></a>
<a href="https://ajiang.me/en/toolbox/video-426-astra/#planche"><img src="https://ajiang.me/_astro/planche-xiv.6IrQU_mf.webp" alt="Conchae Pelagicae: three invented shells in copperplate style" width="160"></a>
<a href="https://ajiang.me/en/toolbox/video-426-astra/#train"><img src="https://ajiang.me/_astro/night-train.BIf-HctJ.webp" alt="The Night Train: a rendered layered paper lightbox" width="240"></a>
<a href="https://aimlapi.com/blog/gpt-6-2-astra-vs-claude-fable-5-2"><img src="https://cdn.prod.website-files.com/65b8f36fa600366bc7cf9a67/6afcd933ccd11fb0245e2a85_gpt62-astra-city-test-1200.webp" alt="Astra's animated 2D city with illuminated windows and traffic" width="240"></a>

<a href="https://Deathdadev.github.io/mossbound-giant/"><img src="https://raw.githubusercontent.com/Deathdadev/mossbound-giant/main/verification/lighting.jpg" alt="Code-drawn forest and moss-covered giant" width="330"></a>

For a juggling lion on a bicycle and portraits drawn in code, see the [community art gallery](COMMUNITY.md#illustration-animation-and-design).

## Source available

| Work | What to explore | Access and provenance |
| --- | --- | --- |
| The Kite That Pulled the Sky | Interactive Canvas short film with animated storm clouds and a synthesized Web Audio score. | [Public source](https://github.com/PankajKumardev/The-Kite-That-Pulled-the-Sky) · [Creator post](https://x.com/pankajkumar_dev/status/2117948791496032542). Astra, creator-reported prelaunch. Source can be served locally. A reuse license was not located in the repository. |
| Ruby Kart | A fan-made browser kart racer with multiple courses, modes, and an offline HTML build. | [Repository](https://github.com/vvvvvvvvvashhh/ruby-kart) · [Live](https://ruby-kart-eight-circuits.vvvvvvvvvashhh.chatgpt.site/). Astra, creator-reported prelaunch test route. The repository documents MIT for original code and exclusions for embedded third-party material. The creator says the hosted build requires a GPT account. |
| Jelly Lab · Yari | A rainbow jelly toy with controls for poking, stretching, cutting, pinning, and heating. | Sol xhigh, creator-reported. [Public source](https://github.com/Yari-tuber/gpt62-vs-opus55-tests/tree/main/02_彩虹果冻/gpt-6.2-sol) · [Shared prompt, other model builds, and method](https://github.com/Yari-tuber/gpt62-vs-opus55-tests). MIT. The author used subscriptions and estimated API-equivalent costs; those figures are not paid API receipts. |

## Science and engineering

| Work | What GPT-6.2 did | Evidence |
| --- | --- | --- |
| Mountain-road chassis dynamics | Astra created a 3D car model, wrote a Python solver for tires and suspension, and animated the simulation in Blender. | [Official video and write-up](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| RC buggy assembly | Astra modeled the assembly part by part. | [Official showcase](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| Inline-six engine | A part-by-part model of a six-cylinder engine. | [Official showcase](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| Marina City paper lamp | Astra helped turn architectural reference photos into a CAD design and a lamp-builder site. A person assembled the physical lamp. | [Official design video and builder entry](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| PELAGOS wind-farm console · Ajiang | A 3D operations demo with weather replay, turbine alerts, and maintenance work orders. | Astra, creator-reported prelaunch. [Build notes](https://ajiang.me/en/toolbox/video-426-astra/#wind) · [Live](https://ajiang.me/demos/pelagos/gpt-6-2-astra/) · [Same-prompt model builds](https://ajiang.me/en/toolbox/pelagos/) |
| Verdant garden simulator · Ramanpal Singh | Sol 6.2 on Ultra with image-generated textures and illustrations, creator-reported mixed workflow. Plant, water, and prune a garden with light competition, pollination, and SVG ecology charts. | [November 19 recording, prompt, and tests](https://promptslove.com/blog/gpt-6-2-sol-review/). The author reports a plant cap and a preplanted starting layout; time-lapse export was not verified in their test browser. |
| Eksen Earth simulator · Avenox | Rotate a globe and explore seasons, sunlight, and three emissions scenarios through 2100. The climate calculations are a simplified educational model. | Sol 6.2 Medium, Ultra Fast · creator-reported November 18 test. [Prompt, screenshot, and notes](https://github.com/avenoxai/astra-notlari/tree/main/testler/04-sol-ultrafast) · [Single-file HTML source](https://github.com/avenoxai/astra-notlari/blob/main/testler/04-sol-ultrafast/sonuc/eksen-dunya-simulasyonu.html). |

<a href="https://github.com/avenoxai/astra-notlari/tree/main/testler/04-sol-ultrafast"><img src="https://raw.githubusercontent.com/avenoxai/astra-notlari/main/testler/04-sol-ultrafast/sonuc/dunya-simulasyonu-klip-son.jpg" alt="Eksen globe, sunlight controls, and educational climate scenarios" width="480"></a>

For scientific coding evaluation, see [Terminal-Bench-Science 0.1](https://www.terminal-bench-science.ai/announcement) and the [model-specific runs](https://artificialanalysis.ai/evaluations/terminal-bench-science).

## Related GPT work

| Work | Model | Links |
| --- | --- | --- |
| Void Explorer · procedural space exploration | GPT-6 Astra | [Live](https://void-explorer.openai.chatgpt.site/) · [Build notes](https://developers.openai.com/showcase/void-explorer) |
| Tidegarden · animated island and reef | GPT-6 Astra | [Live](https://tidegarden.openai.chatgpt.site/) · [Build notes](https://developers.openai.com/showcase/tidegarden) |
| Clockwork Observatory · transforming WebGL machinery | GPT-6 Astra | [Live](https://kinetic-architecture-astra-20260901.openai.chatgpt.site/) · [Build notes](https://developers.openai.com/showcase/impossible-kinetic-architecture) |
| Sunwake · sailing and lighthouse exploration | GPT-6 Astra | [Live](https://sunwake-the-last-light.openai.chatgpt.site/) · [Build notes](https://developers.openai.com/showcase/sunwake) |
| Felt Dot · same reference image used across two live characters | GPT-6.1 Sol vs. Claude Opus 5.5 | [Public source, prompt, and comparison](https://github.com/okonio/felt-dot-gpt-vs-opus) |
| Excavator controller and prototype | GPT-6.1 Sol Max selected by its creator | [Original discussion and recording](https://www.reddit.com/r/threejs/comments/1xru46w/gpt62_sol_seems_to_have_made_a_huge_leap_in_3d/) |

For a model-neutral catalog of procedural geometry, materials, terrain, and animation, see [Awesome Code-Native 3D](https://github.com/jiachengliu12345/awesome-code-native-3d).

## How entries are checked

- **Live** opens the hosted work. **Public source** points to code you can inspect. A recording is labeled as such. Reuse permissions are stated where a license can be found.
- **Official** attribution comes from the publisher. **Creator-reported** attribution comes from the maker. **Routing uncertain** marks an inferred model checkpoint. Prelaunch dates are relative to [OpenAI's November 17, 2026 announcement](https://community.openai.com/t/gpt-6-2-astra-and-sol-are-now-available/1417531).
- The counts cover unique GPT-6.2 entries shown as gallery cards or table rows here and in the community gallery. Preview images and repeated links do not add entries; a collection listed in one row counts once. A side-by-side comparison is attributed to the featured GPT-6.2 model. A mixed workflow uses multiple models to produce a result or compares that approach with a single-model run. We review new work daily and update the date when the catalog changes.

## Contribute

Open an issue or pull request with the creator's original post or repository, the exact model, and any live, source, or recording links. Say whether the author named the model, showed the model ID, or inferred a preview route. If the source has a license, note whether it covers code, art, and audio. When a comparison uses one prompt, link to it if the creator has shared it.
