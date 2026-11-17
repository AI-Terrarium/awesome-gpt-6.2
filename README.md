# Awesome GPT-6.2

**English** · [简体中文](README.zh-CN.md)

**Last Updated · 2026-11-18** · Curated by AI Terrarium

<a href="https://forest-walks-at-dusk.openai.chatgpt.site/"><img src="https://developers.openai.com/showcase/forest-walks/gallery-cover.webp" alt="Forest Walks: an illuminated pine trail at dusk" width="720"></a>

**Forest Walks · GPT-6.2 Astra.** Follow the sound of a campfire, then switch among three renderings of the same forest without losing your place. [Explore the forest](https://forest-walks-at-dusk.openai.chatgpt.site/) · [Thomas Ricouard’s build notes](https://developers.openai.com/showcase/forest-walks)

**45 GPT-6.2 entries** · 21 Astra · 22 Sol · 2 mixed workflows · 6 earlier GPT references listed below.

[Creative coding](#creative-coding) · [Playable worlds](#playable-and-interactive) · [Science and engineering](#science-and-engineering) · [Source code](#source-available) · [Community gallery](COMMUNITY.md)

## Creative coding

| Work | Model | What to open |
| --- | --- | --- |
| Tide Pool Woodcut | Astra · official | Compare two editable SVGs. One was generated with reference art and a design skill. [Direct generation](https://cdn.openai.com/devhub/docs/codex/svg-3d-design/tide-pool-without-skill.svg) · [Reference-led version](https://cdn.openai.com/devhub/docs/codex/svg-3d-design/tide-pool-with-skill.svg) · [Build notes](https://learn.chatgpt.com/guides/svg-3d-design#creating-vector-illustrations-for-the-web) |
| Storm to Sunrise | Astra · official | A 2D SVG seascape where wind changes the waves and daylight shifts the palette. [Recorded animation and build notes](https://learn.chatgpt.com/guides/svg-3d-design#animating-svg-curves-and-colors-with-code) |
| Moth Field Guide Icon | Astra · official | One SVG shape in light and dark palettes, shown at app-store and home-screen sizes. [Design walkthrough](https://learn.chatgpt.com/guides/svg-3d-design#designing-app-icons-for-light-and-dark-mode) |

The [community creative gallery](COMMUNITY.md#illustration-animation-and-design) includes a moonlit pixel-art town, a bicycle-riding lion that juggles through four seasons, and code-drawn portraits.

## Source available

| Work | What to explore | Access and provenance |
| --- | --- | --- |
| The Kite That Pulled the Sky | Interactive Canvas short film with animated storm clouds and a synthesized Web Audio score. | [Public source](https://github.com/PankajKumardev/The-Kite-That-Pulled-the-Sky) · [Creator post](https://x.com/pankajkumar_dev/status/2117948791496032542). Astra, creator-reported prelaunch. Source can be served locally. A reuse license was not located in the repository. |
| Ruby Kart | A fan-made browser kart racer with multiple courses, modes, and an offline HTML build. | [Repository](https://github.com/vvvvvvvvvashhh/ruby-kart) · [Live](https://ruby-kart-eight-circuits.vvvvvvvvvashhh.chatgpt.site/). Astra, creator-reported prelaunch test route. The repository documents MIT for original code and exclusions for embedded third-party material. The creator says the hosted build requires a GPT account. |

## Playable and interactive

These eight OpenAI showcase pages identify **GPT-6.2 Astra** and include build notes. The demo links go to the hosted works.

| Work | What to try | Links |
| --- | --- | --- |
| Escapement · Eric Provencher | Watch three marbles trigger a chain of mechanical mechanisms. | [Live](https://escapement.openai.chatgpt.site/) · [Build notes](https://developers.openai.com/showcase/escapement) |
| Forest Walks · Thomas Ricouard | Explore the same forest in three visual styles and find a campfire by sound. | [Live](https://forest-walks-at-dusk.openai.chatgpt.site/) · [Build notes](https://developers.openai.com/showcase/forest-walks) |
| Dot Rumble · Chaow Wu | See how a reference silhouette becomes a rigged plush fighter and joins an arcade roster. | [Live](https://dot-rumble-arcade.openai.chatgpt.site/) · [Build notes](https://developers.openai.com/showcase/dot-rumble) |
| Light & Matter · Eric Provencher | Walk through a museum of materials, reflections, lighting, and effects. | [Live](https://light-and-matter.openai.chatgpt.site/) · [Build notes](https://developers.openai.com/showcase/light-and-matter) |
| Paris Atlas · Thomas Ricouard | Walk or drive around Paris. The browser streams streets and buildings using geographic data. Some landmarks use photographs. | [Live](https://paris-atlas-street-explorer.openai.chatgpt.site/) · [Build notes](https://developers.openai.com/showcase/paris-atlas) |
| Notre Damn · Thomas Ricouard | Explore Notre-Dame, its chapels, and changing daylight in a 3D scene. | [Live](https://cathedral-walk.openai.chatgpt.site/) · [Build notes](https://developers.openai.com/showcase/notre-damn) |
| Terrarium · Katia Gil Guzman | Arrange plants, moss, and branches in a glass garden and adjust the lighting. | [Live](https://terrarium-glasshouse-studio.openai.chatgpt.site/) · [Build notes](https://developers.openai.com/showcase/terrarium-glasshouse-studio) |
| iMac G3 in Motion · Dominik Kundel | Scroll through the computer's assembly and switch among shell colors. | [Live](https://imac-g3-in-motion.openai.chatgpt.site/) · [Build notes](https://developers.openai.com/showcase/imac-g3-in-motion) |

Two more interactive works have prelaunch claims and are indexed with their provenance in the community gallery. [The Snow Post and Childhood Rug Racer](COMMUNITY.md#playable).

## Science and engineering

| Work | What GPT-6.2 did | Evidence |
| --- | --- | --- |
| Mountain-road chassis dynamics | Astra created a 3D car model, wrote a Python solver for tires and suspension, and animated the simulation in Blender. | [Official video and write-up](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| RC buggy assembly | Astra modeled the assembly part by part. | [Official showcase](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| Inline-six engine | A part-by-part model of a six-cylinder engine. | [Official showcase](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |
| Marina City paper lamp | Astra helped turn architectural reference photos into a CAD design and a lamp-builder site. A person assembled the physical lamp. | [Official design video and builder entry](https://openai.com/index/introducing-gpt-6-2-astra-sol/#computer-use-and-interactive-web-design) |

For scientific coding evaluation, see [Terminal-Bench-Science 0.1](https://www.terminal-bench-science.ai/announcement) and the [model-specific runs](https://artificialanalysis.ai/evaluations/terminal-bench-science).

[AA-3D](https://artificialanalysis.ai/evaluations/aa-3d) provides an independent benchmark and explorer for comparing generated Three.js experiences from shared briefs, including pinball, a black hole, and the Colosseum. Check the model shown for each run.

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
- The counts track entries in this catalog. A side-by-side comparison is attributed to the featured GPT-6.2 model. A mixed workflow uses multiple models to produce a result or compares that approach with a single-model run. We review new work daily and update the date when the catalog changes.

## Contribute

Open an issue or pull request with the creator's original post or repository, the exact model, and any live, source, or recording links. Say whether the author named the model, showed the model ID, or inferred a preview route. If the source has a license, note whether it covers code, art, and audio. When a comparison uses one prompt, link to it if the creator has shared it.
