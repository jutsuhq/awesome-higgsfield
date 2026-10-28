# Awesome Higgsfield [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tools, SDKs, agent skills, apps and guides for Higgsfield, the AI video and image platform that runs Seedance, Kling, Wan and its own Soul and Genjutsu models.

Higgsfield gives one account access to dozens of video and image models through a web app, an API, a CLI and an MCP server. This list collects what people build on top of it.

This is an unofficial list. It is not affiliated with or endorsed by Higgsfield.

## Contents

- [Official](#official)
- [SDKs and Libraries](#sdks-and-libraries)
- [MCP Servers](#mcp-servers)
- [Agent Skills](#agent-skills)
- [Apps and Clients](#apps-and-clients)
- [Integrations](#integrations)
- [Open-Source Alternatives](#open-source-alternatives)
- [Guides](#guides)
- [Pricing](#pricing)
- [Showcase](#showcase)

## Official

- [Higgsfield](https://higgsfield.ai) - The web app: video, image, audio and character tools in one account.
- [API documentation](https://docs.higgsfield.ai/docs/quickstart) - REST API for every model, with polling, webhooks, idempotency and file uploads.
- [API console](https://cloud.higgsfield.ai) - API keys, usage and billing for the developer API.
- [Higgsfield MCP](https://higgsfield.ai/mcp) - Hosted MCP server for Claude, Cursor and other agents, signed in with a Higgsfield account instead of an API key.
- [Higgsfield CLI](https://github.com/higgsfield-ai/cli) - Generate, poll and download from the terminal, also used by the official agent skills.
- [Higgsfield Skills](https://github.com/higgsfield-ai/skills) - Official agent skills for image and video generation, Marketing Studio and brand systems.
- [Cursor plugin](https://github.com/higgsfield-ai/cursor-plugin) - Higgsfield MCP packaged as a Cursor Marketplace plugin.
- [App templates](https://github.com/higgsfield-ai/app-templates) - Next.js and shadcn studio template that calls the platform API, installed as a shadcn registry.
- [llms.txt](https://docs.higgsfield.ai/docs/llms.txt) - Machine-readable index of the API docs for coding agents.

## SDKs and Libraries

- [higgsfield-client](https://github.com/higgsfield-ai/higgsfield-client) - Official Python SDK.
- [higgsfield-js](https://github.com/higgsfield-ai/higgsfield-js) - Official SDK for Node.js and TypeScript.
- [Symfony AI Platform](https://github.com/symfony/ai-platform) - PHP abstraction over AI providers with a Higgsfield bridge.
- [higgsfield-gateway](https://github.com/jutsuhq/higgsfield-gateway) - Cloudflare Workers gateway for the API with spending caps and signed webhook verification.

## MCP Servers

- [Higgsfield MCP Unified](https://github.com/Hikhakk/higgsfield-mcp-unified) - Local MCP server for the API with typed image and video models.
- [hf-studio](https://github.com/Jjat00/hf-studio) - Self-hosted studio and MCP server on the Higgsfield and ElevenLabs APIs.

## Agent Skills

Skills and prompt packs for Claude Code, Codex, Cursor and other coding agents.

### Prompting

- [Higgsfield AI Prompt Skill](https://github.com/OSideMedia/higgsfield-ai-prompt-skill) - Cinematic prompt writing for Seedance 2.5 and other Higgsfield models, split into sub-skills.
- [Higgsfield Seedance Prompt Skill](https://github.com/jutsuhq/higgsfield-seedance-prompt-skill) - Seedance 2.5 prompts for image-to-video, motion transfer, multi-shot and character swap.
- [Higgsfield Seedance 2 Skills](https://github.com/beshuaxian/higgsfield-seedance2-jineng) - Seedance 2.0 prompt skills for cinematic, CGI, anime and e-commerce video (Chinese).
- [AI Video Generator for Claude](https://github.com/rediumvex/ai-video-generator-claude) - Seedance 2.0 prompt skills for hooks, ads and short-form video.

### Generation and Pipelines

- [Higgsfield API Skill](https://github.com/cth9191/higgsfield-api-skill) - On-demand API generation for coding agents with model-specific docs and resumable jobs.
- [Higgsfield Claude Skills](https://github.com/AKCodez/higgsfield-claude-skills) - Image generation, Seedance video and UGC ad pipeline skills for Claude Code.
- [Higgsfield Content Pipeline](https://github.com/cfongai/higgsfield-content-pipeline) - Claude Code and Higgsfield set up as an automated video production studio.
- [Higgsfield Supercomputer](https://github.com/kevinbadi/higgsfield-supercomputer) - Single-file generation dashboard bundled with Higgsfield agent skills.
- [Film Studio Skills](https://github.com/machina-exm/film-studio-skills) - Script-to-final-cut film production pipeline as installable skills.
- [Vision Art Creator](https://github.com/ilkaydemiralay/vision_art_creator) - Film production skills for Claude Code and Codex, from screenplay to final cut.
- [AI Film Pipeline](https://github.com/Gregory-Esman/ai-film-pipeline) - Four claude.ai skills for image prompts, video prompts and shot planning on Higgsfield.
- [Motion Design](https://github.com/cth9191/motion-design) - Turns source examples into finished motion design films through Higgsfield.
- [Vox](https://github.com/EricTechPro/vox) - One command from a topic to a narrated motion-graphics explainer, built on the CLI.

### Marketing and Ads

- [UGC Factory](https://github.com/charlesdove977/UGC-Factory) - UGC video ads with Higgsfield Elements and Seedance, with genre style skills.
- [Miko Video Ad Stack](https://github.com/mikoxai/miko-video-ad-stack) - Brand research, reference breakdown, ad planning and production on Higgsfield.
- [Claude Higgsfield Figma](https://github.com/mikefutia/claude-higgsfield-figma) - Text-free image plates from Higgsfield laid out into Meta ad variants in Figma.
- [Carousel Builder](https://github.com/charlesdove977/carousel-builder) - Branded Instagram carousels from Higgsfield images and Canva.
- [RE Walkthrough Pro](https://github.com/charlesdove977/re-walkthrough-pro) - Turns a real estate listing into a cinematic room-by-room walkthrough video.
- [AI Cartoon Studio](https://github.com/domco685/ai-cartoon-studio-skill) - One idea into a vertical cartoon episode and a social carousel.

### Websites

- [Higgsfield Website Skill](https://github.com/Arnie936/higgsfield-website-skill) - Cinematic video websites with Higgsfield MCP and Seedance.
- [Scroll Cinematic](https://github.com/zubair-trabzada/scroll-cinematic-claude) - 3D scroll websites with generated hero shots from one prompt.

## Apps and Clients

- [Jutsu Studio](https://github.com/jutsuhq/jutsu-studio) - Native Mac app for the API with a job queue, price before each run, daily spending cap and a local library.
- [Vireo](https://github.com/albertshiney/higgsfieldclone) - Hosted studio for every model the API exposes, with magic-link sign-in and Stripe credits.
- [UGC Dashboard](https://github.com/harshith-vaddiparthy/UGC-dashboard) - Visual workflow dashboard for AI UGC videos on Higgsfield and OpenAI.
- [CreatorOS Studio](https://github.com/thePloggy/CreatorOS-Studio) - Local creator studio that combines Higgsfield with ComfyUI.

## Integrations

- [ComfyUI Higgsfield Direct](https://github.com/jeremieLouvaert/ComfyUI-Higgsfield-Direct) - ComfyUI nodes for Higgsfield image and video models.
- [Higgsfield API ComfyUI Nodes](https://github.com/w0ver/Higgsfield-api-comfyui-nodes) - Minimal ComfyUI nodes for the API.

## Open-Source Alternatives

Self-hosted tools that cover parts of what Higgsfield does.

- [Open Higgsfield](https://github.com/wide-trace/open-higgsfield) - Image and video studio with one prompt bar for many hosted models.
- [HeliosGen](https://github.com/SegFault42/HeliosGen) - Self-hosted desktop app for visual image and video pipelines.
- [BeatDesign](https://github.com/BeatAPI/BeatDesign) - Local-first AI canvas and timeline that any MCP agent can drive.
- [OpenStudio](https://github.com/clawnify/OpenStudio) - Image generation studio with a gallery and node-based workflows.
- [OpenCanvas](https://github.com/opencanvasai/OpenCanvas) - Bring-your-own-key canvas for image and video models.
- [OpenJutsu](https://github.com/D3voz/openjutsu) - Local Genjutsu-style character swap on ComfyUI.
- [Swapjutsu](https://github.com/jutsuhq/swapjutsu-seedance-character-swap) - Mac app for Seedance 2.5 and Wan 2.2 Animate character swap.
- [Content Factory](https://github.com/jutsuhq/content-factory) - Open-source alternative to Higgsfield Content Factory: faceless What if videos made on a Mac.

## Guides

- [Higgsfield API guide](https://github.com/best-ai-humanizer/higgsfield-api) - Model catalogue, console, CLI, pricing and common gotchas.
- [Higgsfield API examples](https://github.com/aqua-voice-dev/higgsfield-api-examples) - CLI setup script, cost estimator and an agent prompt for Claude Code.
- [Higgsfield API, MCP or CLI](https://jutsustudio.com/blog/higgsfield-api-mcp-cli/) - Which access path fits which job, and what each one costs.
- [Higgsfield API in production](https://jutsustudio.com/blog/higgsfield-api-production/) - Webhook signatures, idempotency keys, concurrency limits and spending caps.

## Pricing

- [Pricing page](https://higgsfield.ai/pricing) - Official plans and credit packs.
- [Higgsfield credits explained](https://jutsustudio.com/blog/higgsfield-credits-explained/) - What credits cost on each plan, how they expire and when the API is cheaper.
- [Higgsfield price per second](https://jutsustudio.com/higgsfield-pricing/) - Every Higgsfield model priced per second of video on the API and on each plan.
- [video-api-prices](https://github.com/jutsuhq/video-api-prices) - Daily JSON of AI video prices per second at Higgsfield and 30+ other providers.

## Showcase

Open-source projects made with Higgsfield.

- [Omagotchi](https://github.com/higgsfield-ai/omagotchi) - 8-bit desktop avatar of you for Omarchy, made from one photo.
- [Arko landing](https://github.com/midudev/mcp-higgsfield-landing) - Restaurant landing page with a scroll-driven video tour generated through Higgsfield MCP.
- [A Long-Expected Party](https://github.com/MengTo/a-long-expected-party) - Procedural short film with a Higgsfield-generated score, sound and narration.
- [How I built Flight Website](https://github.com/Moh4696/How-I-built-Flight-Website) - Landing page hero turned into a seamless generated flight film with the CLI.
- [Higgsfield launch video in Remotion](https://github.com/naveen-annam/creativly.ai-higgsfield-video-remotion) - Frame-accurate recreation of the Higgsfield launch video in Remotion.

## Related Lists

- [awesome-seedance](https://github.com/ZeroLu/awesome-seedance) - Seedance prompts and resources.
- [awesome-seedance-2-prompts](https://github.com/YouMind-OpenLab/awesome-seedance-2-prompts) - Curated Seedance 2.0 prompts by style.
- [awesome-ai-video-models](https://github.com/Anil-matcha/awesome-ai-video-models) - AI video generation models.
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - MCP servers for every kind of tool.

## Contributing

Contributions welcome. Read the [contribution guidelines](contributing.md) first.
