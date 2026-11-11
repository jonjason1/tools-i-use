# Tools I Found Along the Way

A running list of repositories, tools, and design references I came across while building my own systems. These are **links, not code** — nothing here is vendored, forked, or redistributed. Each project belongs to its creator; links go to the original source.

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
| [morluto/rea](https://github.com/morluto/rea) | Reverse Engineer Anything — one MCP that drives Ghidra, JADX, Frida and friends so an agent can explain how an app or binary works, down to the native code. Bring your own engines; for software you own or are authorized to examine. | MIT |

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

## More tools and references

Additional projects and services to explore. A listing does not imply an endorsement or verified cost savings.

### Design reference sites and services

| Link | What it is |
|---|---|
| [Spline](https://spline.design/) | Interactive 3D design tool. |
| [Spline MCP endpoint](https://mcp.spline.design/mcp) | Connector endpoint; see Spline's setup guide. |
| [Refero Styles](https://styles.refero.design/) | Website design systems and DESIGN.md references. |
| [Mobbin](https://mobbin.com/) | Shipped app and website screen references. |
| [ArtCraft](https://getartcraft.com/) | Open-source creative apps and ArtCraft Studio. |
| [Open Higgsfield AI](https://www.openhiggsfield.ai/) | Project website. |
| [Zapier MCP](https://mcp.zapier.com/) | Official hosted MCP integration service. |

### Link to identify

| Link | Note |
|---|---|
| [Reverse Engineer Prompt](https://bit.ly/4i0wNCh) | Supplied short link; destination could not be verified. |

### Agent skills and workflows

| Repo | What it does | License |
|---|---|---|
| [vercel-labs/skills](https://github.com/vercel-labs/skills) | The open agent skills tool - npx skills | MIT |
| [Jakeschincariol/arena-skill](https://github.com/Jakeschincariol/arena-skill) | When Claude keeps giving you bad answers, make 100 versions of it fight to the death. Same task, 100 different strategies, a bracket, one answer left. Free Claude Code skill. | MIT |
| [chaseai-yt/claudex-loop](https://github.com/chaseai-yt/claudex-loop) | Claude Code skill: four-phase plan hardening (recon, interrogate, Codex adversarial review, cross-model build & inspection) — two AI models harden your plan before a line of code exists, then swap ... | check repo |
| [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) | DeepSeek Harness: Everything is a Plugin. | MIT |
| [google/elephant-goldfish-model](https://github.com/google/elephant-goldfish-model) | Open-source skills for designing and reviewing software with AI agents | Apache-2.0 |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | Production-grade engineering skills for AI coding agents. | MIT |
| [expo/skills](https://github.com/expo/skills) | A collection of AI agent skills for working with Expo projects and Expo Application Services | MIT |
| [supabase/agent-skills](https://github.com/supabase/agent-skills) | Agent Skills to help developers using AI agents with Supabase | MIT |
| [stripe/ai](https://github.com/stripe/ai) | One-stop shop for building AI-powered products and businesses with Stripe. | MIT |
| [daveebbelaar/bama](https://github.com/daveebbelaar/bama) | BAMA: Build Any Mac App. Agent skills to research, clone, design, build, optimize, and test native macOS apps with Swift and SwiftUI. | MIT |
| [stablyai/orca](https://github.com/stablyai/orca) | Orca is the place for working with a fleet of agents (e.g. Grok Bot, Claude Code). Run any coding agent with your own subscription. Available on desktop, mobile and remote runtime. | MIT |

### Design, UI, and creative software

| Repo | What it does | License |
|---|---|---|
| [shader-effects-inc/shaders](https://github.com/shader-effects-inc/shaders) | WebGPU components for React, Vue, Svelte, Solid, JS & Framer | MIT |
| [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, Qoder, and Pi. 45 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop. | MIT |
| [nateherkai/scroll-craft](https://github.com/nateherkai/scroll-craft) | An agent skill for building premium, immersive, scroll-driven websites. Works with Codex, Claude Code, and other coding agents. Also available as a Claude Code plugin. | MIT |
| [tt-a1i/archify](https://github.com/tt-a1i/archify) | Turn any idea, plan, or codebase into a beautiful interactive diagram. An agent skill for Claude Code, Codex, and more. | Apache-2.0 |
| [thesysdev/openui](https://github.com/thesysdev/openui) | The Open Standard for Generative UI | MIT |
| [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | Anti-AI-slop design skill for Claude Code, Cursor, and Codex. | MIT |
| [Motionsites-AI/claude-skill](https://github.com/Motionsites-AI/claude-skill) | Free Claude skill: make Claude build award-level, cinematic landing pages. By MotionSites. | check repo |
| [robbietilton/Compositor](https://github.com/robbietilton/Compositor) | The Photoshop alternative for Mac | MIT |
| [storytold/photocraft](https://github.com/storytold/photocraft) | PhotoCraft: An open-source, photo editor written by scratch in pure Rust | Apache-2.0 |

### Media and audio

| Repo | What it does | License |
|---|---|---|
| [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio) | VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design, video dubbing, dictation, transcription & audiobook creation in 646 languages. | AGPL-3.0 |
| [Autom8AI/Open-Higgsfield-AI](https://github.com/Autom8AI/Open-Higgsfield-AI) | Open-source alternative to Higgsfield AI — Free AI image generation & cinema studio with 20+ models (Flux, SDXL, Midjourney, Ideogram). Self-hosted, customizable, MIT licensed. | check repo |
| [OpenWhispr/openwhispr](https://github.com/OpenWhispr/openwhispr) | Voice-to-text dictation app with local (Nvidia Parakeet/Whisper) and cloud models (BYOK). Privacy-first and available cross-platform. | MIT |

### Research, security, and quality

| Repo | What it does | License |
|---|---|---|
| [NandhaKishorM/laya](https://github.com/NandhaKishorM/laya) | Non-autoregressive System 1 decision engine. Typed choice, score and yes/no decisions over any text in a single forward pass, in 100+ languages, with a router that picks the right checkpoint per re... | Apache-2.0 |
| [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings | MIT |
| [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) | Security scanner for AI agent skills. Detect vulnerabilities, malicious patterns, security risks, prompt injection, data exfiltration, and supply-chain risks in Claude Code, Codex, and MCP skills b... | Apache-2.0 |
| [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | Official, Anthropic-managed directory of high quality Claude Code Plugins. | Apache-2.0 |
| [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) | A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe. | check repo |
| [ItsssssJack/SlopMonster](https://github.com/ItsssssJack/SlopMonster) | Turn AI-written copy into copy a human would ship. Lint for AI tells, cleanse with a rival model, lint again. | MIT |
| [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor) | DeepTutor: Lifelong Personalized Tutoring. https://deeptutor.info/. | Apache-2.0 |

### Integrations and developer tools

| Repo | What it does | License |
|---|---|---|
| [googleworkspace/cli](https://github.com/googleworkspace/cli) | Google Workspace CLI — one command-line tool for Drive, Gmail, Calendar, Sheets, Docs, Chat, Admin, and more. Dynamically built from Google Discovery Service. Includes AI agent skills. | Apache-2.0 |
| [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) | The Apify MCP server enables your AI agents to extract data from social media, search engines, maps, e-commerce sites, or any other website using thousands of ready-made scrapers, crawlers, and aut... | MIT |
| [microsoft/playwright-cli](https://github.com/microsoft/playwright-cli) | CLI for common Playwright actions. Record and generate Playwright code, inspect selectors and take screenshots. | Apache-2.0 |
| [rehan-remade/universal-modder](https://github.com/rehan-remade/universal-modder) | Point Claude at any game. Skills, tools and the fal MCP that let Claude Code mod almost any PC game you own: recon, reverse engineering, fal-generated art/3D/audio, in-game testing, showcase videos. | MIT |
| [sebastienrousseau/bankstatementparser](https://github.com/sebastienrousseau/bankstatementparser) | Parse bank statements (CAMT, PAIN.001, MT940, MT942, OFX/QFX, BAI2, CSV, and PDF) into unified Transactions. Treasury analytics, 2-way reconciliation, PDF forensics, Parquet & Ledger exports (hledg... | check repo |

### Business and publishing

| Repo | What it does | License |
|---|---|---|
| [every-app/open-seo](https://github.com/every-app/open-seo) | Open source alternative to Semrush and Ahrefs | MIT |
| [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) | Universal SEO skill for Claude Code. 26 sub-skills + 19 sub-agents covering technical SEO, E-E-A-T, schema, GEO/AEO, agent readiness (Lighthouse Agentic Browsing, WebMCP, llms.txt), backlinks, loca... | MIT |
| [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | Open-source LLM knowledge platform: turn raw documents into a queryable RAG, an autonomous reasoning agent, and a self-maintaining Wiki. | check repo |
| [opf/openproject](https://github.com/opf/openproject) | OpenProject is the leading open source project management software for product, project and portfolio management. A powerful Jira alternative with agile planning, issue tracking, roadmaps, Gantt ch... | GPL-3.0 |
| [calcom/cal.diy](https://github.com/calcom/cal.diy) | Scheduling infrastructure for absolutely everyone. | MIT |
| [chatwoot/chatwoot](https://github.com/chatwoot/chatwoot) | Open-source live-chat, email support, omni-channel desk. An alternative to Intercom, Zendesk, Salesforce Service Cloud etc. 🔥💬 | check repo |
| [CapSoftware/Cap](https://github.com/CapSoftware/Cap) | Open source Loom alternative. Beautiful, shareable screen recordings. | check repo |
| [gitroomhq/postiz-app](https://github.com/gitroomhq/postiz-app) | 📨 The ultimate agentic social media scheduling tool 🤖 | AGPL-3.0 |
| [ai-job-search-dev/ai-job-search](https://github.com/ai-job-search-dev/ai-job-search) | The job search that runs on your machine. AI job application framework built on Claude Code: evaluate postings, tailor CVs, write cover letters, prep interviews. Fork it and own it. | MIT |

---

## Why this list exists

I build a lot of internal tooling, and almost none of it is invented from nothing — it stands on work other people published for free. This is the paper trail. If a repository here is useful to you, go star the original project.

If you maintain a project listed here and want the entry changed or removed, open an issue and I'll handle it same day.


## GitHub links from Vic's Airtable tools list

Source: [Vic's tools list](https://airtable.com/app8t3Je3tzNvbumq/shrXb5PjoVey26Aar/tblnB1kW5ZwYv5Y4d). Projects already listed above are omitted.

- [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server)
- [yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [dgtlmoon/changedetection.io](https://github.com/dgtlmoon/changedetection.io)
- [kevinwatt/yt-dlp-mcp](https://github.com/kevinwatt/yt-dlp-mcp)
- [apify/actors-mcp-server](https://github.com/apify/actors-mcp-server)
- [stanford-oval/storm](https://github.com/stanford-oval/storm)
- [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)
- [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp)
- [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills)
- [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut)
- [souzatharsis/podcastfy](https://github.com/souzatharsis/podcastfy)
- [m-bain/whisperX](https://github.com/m-bain/whisperX)
- [comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI)
- [michalparkola/tapestry-skills](https://github.com/michalparkola/tapestry-skills)
- [danielgatis/rembg](https://github.com/danielgatis/rembg)
- [ggml-org/whisper.cpp](https://github.com/ggml-org/whisper.cpp)
- [resemble-ai/chatterbox](https://github.com/resemble-ai/chatterbox)
- [KlingAIResearch/LivePortrait](https://github.com/KlingAIResearch/LivePortrait)
- [WyattBlue/auto-editor](https://github.com/WyattBlue/auto-editor)
- [ComposioHQ/awesome-claude-skills/tree/master/content-research-writer](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/content-research-writer)
- [mifi/lossless-cut](https://github.com/mifi/lossless-cut)
- [duixcom/Duix-Avatar](https://github.com/duixcom/Duix-Avatar)
- [heygen-com/skills](https://github.com/heygen-com/skills)
- [smixs/visual-skills](https://github.com/smixs/visual-skills)
- [linyqh/NarratoAI](https://github.com/linyqh/NarratoAI)
- [remotion-dev/remotion](https://github.com/remotion-dev/remotion)
- [upscayl/upscayl](https://github.com/upscayl/upscayl)
- [ComposioHQ/awesome-claude-skills/tree/master/twitter-algorithm-optimizer](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/twitter-algorithm-optimizer)
- [anthropics/skills/tree/main/skills/canvas-design](https://github.com/anthropics/skills/tree/main/skills/canvas-design)
- [anthropics/skills/tree/main/skills/theme-factory](https://github.com/anthropics/skills/tree/main/skills/theme-factory)
- [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server)
- [egbertbouman/youtube-comment-downloader](https://github.com/egbertbouman/youtube-comment-downloader)
- [Lightricks/LTX-2](https://github.com/Lightricks/LTX-2)
- [jamiepine/voicebox](https://github.com/jamiepine/voicebox)
- [nexu-io/open-design](https://github.com/nexu-io/open-design)
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server)
- [Anil-matcha/Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI)
- [CristianOlivera1/openvid](https://github.com/CristianOlivera1/openvid)
- [nocodb/nocodb](https://github.com/nocodb/nocodb)
- [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code)
- [twentyhq/twenty](https://github.com/twentyhq/twenty)
- [SegFault42/HeliosGen](https://github.com/SegFault42/HeliosGen)
- [ShawnPana/phone-harness](https://github.com/ShawnPana/phone-harness)
- [danilo-znamerovszkij/draw-your-font](https://github.com/danilo-znamerovszkij/draw-your-font)
- [hoainho/img2threejs](https://github.com/hoainho/img2threejs)
- [hugohe3/ppt-master](https://github.com/hugohe3/ppt-master)
- [SECHAK-AG/capptivo](https://github.com/SECHAK-AG/capptivo)
- [jd-opensource/JoyAI-Video-Edit](https://github.com/jd-opensource/JoyAI-Video-Edit)
- [plausible/analytics](https://github.com/plausible/analytics)
- [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2)
- [invoiceninja/invoiceninja](https://github.com/invoiceninja/invoiceninja)
- [makeplane/plane](https://github.com/makeplane/plane)
- [formbricks/formbricks](https://github.com/formbricks/formbricks)
- [AppFlowy-IO/AppFlowy](https://github.com/AppFlowy-IO/AppFlowy)
- [n8n-io/n8n](https://github.com/n8n-io/n8n)
- [documenso/documenso](https://github.com/documenso/documenso)
- [anomalyco/opencode](https://github.com/anomalyco/opencode)
- [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp)
- [dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden)
- [hostinger/api-mcp-server](https://github.com/hostinger/api-mcp-server)
- [umami-software/umami](https://github.com/umami-software/umami)
- [nextcloud/server](https://github.com/nextcloud/server)
- [openai/codex](https://github.com/openai/codex)
