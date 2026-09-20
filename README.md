# Tools I Found Along the Way

A running list of open-source repos I came across while building my own systems. These are **links, not code** — nothing here is vendored, forked, or redistributed. Every project belongs to the person who wrote it, and the link goes to their repo so they get the star, the traffic, and the credit.

Curated by [Jon Jason](https://jonjason.com/?utm_source=awesome-repos&utm_medium=readme&utm_campaign=attribution) · [jonjason.com/skills](https://jonjason.com/skills?utm_source=awesome-repos&utm_medium=readme&utm_campaign=attribution)

> **On licenses:** the license column is a starting point, not legal advice. Check the repo before you use anything commercially — licenses change, and "no license file" means all rights reserved, not public domain.

---

## Agent safety and control

| Repo | What it does | License |
|---|---|---|
| [Dicklesworthstone/destructive_command_guard](https://github.com/Dicklesworthstone/destructive_command_guard) | Rust pre-execution hook that blocks destructive shell commands before an AI agent runs them. Has saved me more than once. | MIT |
| [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | Makes an agent build the lazy, simple version instead of over-engineering. | check repo |
| [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | Terse-prose mode for agents. Pairs well with the above. | check repo |

## Agent workflow and quality

| Repo | What it does | License |
|---|---|---|
| [robonuggets/gauntlet-loop](https://github.com/robonuggets/gauntlet-loop) | Turns a goal into one paste-ready prompt that runs a builder and a separate harsh critic against a real, named quality bar and loops until the work wins the blind comparison. The bar is the trick — a vague one gets you approval, not quality. Technique originally [Matt Shumer's](https://github.com/mshumer/Claude-of-Duty). | CC BY 4.0 |
| [robonuggets/doctor-plus](https://github.com/robonuggets/doctor-plus) | Runs `/doctor`, then audits your workspace against the six context-engineering shifts Anthropic published for the Claude 5 models. Reports first, fixes only on approval. | CC BY 4.0 |
| [mattpocock/skills](https://github.com/mattpocock/skills) | About twenty small, composable engineering skills — TDD, code review, diagnosing bugs, spec to tickets — that deliberately refuse to own your process the way BMAD or Spec-Kit do. `/wait-what`, in `skills/productivity`, makes the agent re-pitch a message that didn't land, in plain Simplified Technical English. | MIT |
| [dmmulroy/skills](https://github.com/dmmulroy/skills) | Home of `/bro` — six lines that make the agent drop the jargon and restate its last message like one human talking to another. Also carries Effect service design and Cloudflare composition-root skills. | MIT |

## Security

| Repo | What it does | License |
|---|---|---|
| [usestrix/strix](https://github.com/usestrix/strix) | Autonomous AI pentesting agents. Runs your app in a Docker sandbox, finds vulnerabilities and proves them with a working exploit instead of a static-analysis guess. | Apache-2.0 |

## Writing and anti-slop

| Repo | What it does | License |
|---|---|---|
| [blader/humanizer](https://github.com/blader/humanizer) | Strips the AI tells out of generated writing. | check repo |
| [petergyang/no-ai-slop](https://github.com/petergyang/no-ai-slop) | Another angle on the same problem. | check repo |
| [jcarterjohnson/vibecoded-design-tells](https://github.com/jcarterjohnson/vibecoded-design-tells) | The visual equivalent — how to spot a vibe-coded UI. | check repo |
| [NulightJens/humanizer-stack](https://github.com/NulightJens/humanizer-stack) | Humanizing as a pipeline rather than one pass. | check repo |
| [jenna-russell/storyscope](https://github.com/jenna-russell/storyscope) | Story structure analysis. | check repo |
| [guillaumemeyer/watermarks-remover](https://github.com/guillaumemeyer/watermarks-remover) | Strips the invisible layer — zero-width Unicode, C2PA provenance metadata, statistical fingerprints — out of PNG, JPEG, SVG, PDF, DOCX, HTML and Markdown. The tells you can't catch by reading. | MIT |

## Design and front-end

| Repo | What it does | License |
|---|---|---|
| [DavidHDev/canvas-ui](https://github.com/DavidHDev/canvas-ui) | 25 WebGL effects that run over live, still-interactive HTML. | MIT |
| [Jakubantalik/thinking-orbs](https://github.com/Jakubantalik/thinking-orbs) | Six animated "agent is thinking" states. Better than any spinner. | MIT |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | Front-end design taste, encoded. | check repo |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | Design judgment as a repeatable process. | check repo |
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | Broad UI/UX reference. | check repo |
| [emilkowalski/skills](https://github.com/emilkowalski/skills) | Animation and interaction craft from someone who genuinely has it. | check repo |
| [nhn/tui.image-editor](https://github.com/nhn/tui.image-editor) | Full browser image editor. | MIT |
| [scaleflex/filerobot-image-editor](https://github.com/scaleflex/filerobot-image-editor) | Same category, different trade-offs. | MIT |

## Research and knowledge

| Repo | What it does | License |
|---|---|---|
| [tobi/qmd](https://github.com/tobi/qmd) | Local search over a markdown corpus. Powers my second brain. | check repo |
| [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | What people actually said about a topic in the last 30 days. | check repo |
| [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | One CLI that gives an agent read access to Twitter, Reddit, YouTube, GitHub, LinkedIn, RSS and more - installs and routes the backends for you. | MIT |
| [microsoft/markitdown](https://github.com/microsoft/markitdown) | Converts anything (docx, pdf, xlsx, pptx) to markdown. | MIT |
| [robonuggets/markitdown-guide](https://github.com/robonuggets/markitdown-guide) | Practical guide to the above. | check repo |
| [garrytan/gbrain](https://github.com/garrytan/gbrain) | Personal knowledge system. | check repo |
| [garrytan/gstack](https://github.com/garrytan/gstack) | The stack around it. | check repo |
| [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) | Turns a folder into a force-directed graph. | check repo |

## Infrastructure and integrations

| Repo | What it does | License |
|---|---|---|
| [knadh/listmonk](https://github.com/knadh/listmonk) | Self-hosted newsletter and mailing list manager. Runs my email. | AGPL-3.0 |
| [mastanley13/GoHighLevel-MCP](https://github.com/mastanley13/GoHighLevel-MCP) | MCP server for GoHighLevel. | check repo |
| [leadgenjay/hyros-mcp](https://github.com/leadgenjay/hyros-mcp) | MCP server for Hyros attribution. | check repo |
| [fastapi/full-stack-fastapi-template](https://github.com/fastapi/full-stack-fastapi-template) | The FastAPI starter worth actually starting from. | MIT |
| [anthropics/anthropic-sdk-python](https://github.com/anthropics/anthropic-sdk-python) | Claude SDK. Also [TypeScript](https://github.com/anthropics/anthropic-sdk-typescript), [Go](https://github.com/anthropics/anthropic-sdk-go), [Ruby](https://github.com/anthropics/anthropic-sdk-ruby), [Java](https://github.com/anthropics/anthropic-sdk-java), [PHP](https://github.com/anthropics/anthropic-sdk-php), [C#](https://github.com/anthropics/anthropic-sdk-csharp). | MIT |
| [higgsfield-ai/higgsfield-client](https://github.com/higgsfield-ai/higgsfield-client) | Higgsfield API client. Also [JS](https://github.com/higgsfield-ai/higgsfield-js). | check repo |

## Media and video

| Repo | What it does | License |
|---|---|---|
| [browser-use/video-use](https://github.com/browser-use/video-use) | Drive a browser from video. | check repo |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | HTML/CSS/GSAP in, deterministic MP4 out. Agent-native motion graphics — the model writes a webpage and gets a video, no Remotion bundler dance. Runs fully local, no HeyGen account or key. | Apache-2.0 |
| [argmaxinc/WhisperKit](https://github.com/argmaxinc/WhisperKit) | On-device Whisper for Apple silicon. Fast. | MIT |
| [FluidInference/FluidAudio](https://github.com/FluidInference/FluidAudio) | Swift audio inference. | check repo |
| [YouMind-OpenLab/awesome-seedance-2-prompts](https://github.com/YouMind-OpenLab/awesome-seedance-2-prompts) | Prompt patterns for Seedance video. | check repo |
| [robonuggets/higgsfield-skill](https://github.com/robonuggets/higgsfield-skill) | One MCP, 30+ image and video models behind a single key. This is the lane most of my generation work actually runs on. | check repo |
| [robonuggets/gpt-image-2-skill](https://github.com/robonuggets/gpt-image-2-skill) | GPT Image 2 with both endpoints wired, text-to-image and edit. What I reach for when the picture *is* the typography — signs, packaging, UI mockups. | check repo |
| [robonuggets/seedance-skill](https://github.com/robonuggets/seedance-skill) | Seedance 2.0 for liquid-glass motion graphics. Screenshot an app, get a promo clip. | check repo |
| [robonuggets/fantastic-posters](https://github.com/robonuggets/fantastic-posters) | 31 poster styles on GPT Image 2 — it picks the right style from your brief instead of making you name one. | MIT |

## Odds and ends

| Repo | What it does | License |
|---|---|---|
| [teamchong/pxpipe](https://github.com/teamchong/pxpipe) | Renders long prompts as images to arbitrage token pricing. Genuinely clever. | check repo |
| [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) | Focus tooling that doesn't nag. | check repo |
| [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | Model routing. | check repo |
| [per-simmons/clone-app-pat-pro-public](https://github.com/per-simmons/clone-app-pat-pro-public) | App cloning workflow. | check repo |

---

## Why this list exists

I build a lot of internal tooling, and almost none of it is invented from nothing — it stands on work other people published for free. This is the paper trail. If something here is useful to you, go star the original repo, not this one.

If you maintain a project listed here and want the entry changed or removed, open an issue and I'll handle it same day.
