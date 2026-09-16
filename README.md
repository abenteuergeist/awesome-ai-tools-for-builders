# Awesome AI Tools for Builders

> 298 AI tools and startups that indie devs, app makers and SaaS builders actually use, grouped by job. Maintained as the open dataset behind [kinged.lol](https://kinged.lol), a directory where the #1 spot is bought by the hour and ranking is measured in minutes on top.

Updated 2026-09-16. Machine-readable: [tools.json](https://kinged.lol/api/tools.json) · [llms.txt](https://kinged.lol/llms.txt)

## Contents

- [Recommended stacks by job](#recommended-stacks-by-job)
- [AI Agent Tools](#ai-agent-tools) (22)
- [Development Tools](#development-tools) (21)
- [AI Video](#ai-video) (20)
- [Marketing](#marketing) (16)
- [Vibe Coding](#vibe-coding) (14)
- [Sales Tool](#sales-tool) (14)
- [Website Builder](#website-builder) (13)
- [AI Design](#ai-design) (12)
- [Design Inspiration](#design-inspiration) (10)
- [AI Development](#ai-development) (9)
- [UI Components](#ui-components) (8)
- [Productivity](#productivity) (8)
- [AI Marketing](#ai-marketing) (8)
- [Market Research](#market-research) (7)
- [App Analytics](#app-analytics) (6)
- [Design Tools](#design-tools) (6)
- [Payment](#payment) (6)
- [Startup Resources](#startup-resources) (5)
- [Resources](#resources) (5)
- [App Marketing](#app-marketing) (5)
- [CRM](#crm) (5)
- [Social Media](#social-media) (5)
- [AI Search](#ai-search) (4)
- [Video Editing](#video-editing) (4)
- [Community Platform](#community-platform) (4)
- [AI Research](#ai-research) (3)
- [AI Scraping](#ai-scraping) (3)
- [Forms](#forms) (3)
- [Link Management](#link-management) (3)
- [Email Marketing](#email-marketing) (3)
- [LinkedIn Tools](#linkedin-tools) (3)
- [AI Sales](#ai-sales) (3)
- [AI Education](#ai-education) (2)
- [AI Image](#ai-image) (2)
- [AI Prompts](#ai-prompts) (2)
- [Screen Recording](#screen-recording) (2)
- [Database](#database) (2)
- [AI Audio](#ai-audio) (2)
- [AI SEO](#ai-seo) (2)
- [AI Content](#ai-content) (2)
- [Marketing Agent](#marketing-agent) (2)
- [Social Media Automation](#social-media-automation) (2)
- [Monetization](#monetization) (2)
- [AI Hardware](#ai-hardware) (1)
- [AI Directory](#ai-directory) (1)
- [App Consulting](#app-consulting) (1)
- [Communication](#communication) (1)
- [AI Automation](#ai-automation) (1)
- [AI Tools](#ai-tools) (1)
- [AI Vision](#ai-vision) (1)
- [Voice AI](#voice-ai) (1)
- [Slides/Presentation](#slides-presentation) (1)
- [SEO](#seo) (1)
- [Email Verification](#email-verification) (1)
- [AI Worker](#ai-worker) (1)
- [LinkedIn Automation](#linkedin-automation) (1)
- [Email Outreach](#email-outreach) (1)
- [Instagram Automation](#instagram-automation) (1)
- [AI Image/Video](#ai-image-video) (1)
- [AI Phone Dialing](#ai-phone-dialing) (1)
- [Proposals](#proposals) (1)

## Recommended stacks by job

What we would use this month, updated 2026-09-03. Full version with links: [kinged.lol/stacks](https://kinged.lol/stacks).

### Build a mobile app

*Solo devs and small teams shipping iOS and Android apps*

| Role | Tool | Why |
| --- | --- | --- |
| Framework | [expo.dev](https://expo.dev) | React Native without the native setup. OTA updates, EAS builds, app store submission. |
| Code editor | [cursor.com](https://cursor.com) | The AI editor most indie devs actually use day to day. |
| Backend | [supabase.com](https://supabase.com) | Postgres, auth and storage in one, free tier survives a launch. |
| Payments | [revenuecat.com](https://revenuecat.com) | Subscriptions across both stores, paywalls without writing StoreKit. |
| Analytics | [posthog.com](https://posthog.com) | Events, funnels and session replay, generous free tier. |
| Errors | [sentry.io](https://sentry.io) | Crash reports with the stack trace that matters. |
| Attribution | [adjust.com](https://adjust.com) | Know which ad brought the install once you spend on ads. |

### Ship a SaaS

*Web products with a login and a monthly price*

| Role | Tool | Why |
| --- | --- | --- |
| Framework and hosting | [vercel.com](https://vercel.com) | Next.js on Vercel, deploys on push, edge functions when you need them. |
| Database | [convex.dev](https://convex.dev) | Realtime by default, TypeScript end to end. Supabase if you want plain Postgres. |
| Auth | [clerk.com](https://clerk.com) | Sign-in, orgs and user management done in an afternoon. |
| Payments | [stripe.com](https://stripe.com) | Checkout, subscriptions, webhooks. Polar or Lemon Squeezy if you want merchant of record. |
| UI | [ui.shadcn.com](https://ui.shadcn.com) | Components you own, styled with Tailwind. |
| Email | [react.email](https://react.email) | Transactional email written as React components. |
| Product analytics | [posthog.com](https://posthog.com) | Flags, experiments and replays without a second vendor. |

### Vibe-code a prototype

*Idea to something clickable in a weekend, no team*

| Role | Tool | Why |
| --- | --- | --- |
| Full app from a prompt | [lovable.dev](https://lovable.dev) | Fastest path from a paragraph to a deployed app with auth and a database. |
| Alternative | [bolt.new](https://bolt.new) | Same idea, more control over the code in the browser. |
| UI screens | [v0.dev](https://v0.dev) | Generate the screens, paste them into your own codebase. |
| Editor for the second week | [cursor.com](https://cursor.com) | When the prompt-only tools stop being enough. |
| Backend | [supabase.com](https://supabase.com) | Every vibe tool speaks Supabase. |
| Landing page | [framer.com](https://framer.com) | Design and publish the marketing site without code. |

### Build agents and automations

*Workflows that call models, scrape, and act*

| Role | Tool | Why |
| --- | --- | --- |
| Model routing | [openrouter.ai](https://openrouter.ai) | One key for every model, switch providers without a redeploy. |
| Workflow builder | [n8n.io](https://n8n.io) | Self-hostable automations with real branching, cheaper than Zapier at scale. |
| Web data | [firecrawl.dev](https://firecrawl.dev) | Turn any site into clean markdown for the model. |
| Search | [exa.ai](https://exa.ai) | Search built for agents, not for humans. |
| Tool integrations | [composio.dev](https://composio.dev) | Hundreds of app integrations as agent tools. |
| Voice | [vapi.ai](https://vapi.ai) | Phone and voice agents without building the telephony. |
| Speech | [elevenlabs.io](https://elevenlabs.io) | Voices that do not sound like a voicemail. |

### Make content and video

*Short video, thumbnails, and posts at volume*

| Role | Tool | Why |
| --- | --- | --- |
| Programmatic video | [remotion.dev](https://remotion.dev) | Videos as React code, renders in CI, perfect for data-driven clips. |
| AI video | [higgsfield.ai](https://higgsfield.ai) | Image-to-video with consistent characters. |
| Avatars | [heygen.com](https://heygen.com) | Talking-head videos from a script. |
| Images | [midjourney.com](https://midjourney.com) | Still the reference for stylized stills. |
| Editing | [capcut.com](https://capcut.com) | Captions and cuts on the phone, free. |
| Scheduling | [postiz.com](https://postiz.com) | Open source scheduler for every network. |
| Newsletter | [beehiiv.com](https://beehiiv.com) | Growth features built in, referral program included. |

### Launch and grow

*The first 1,000 users after the product exists*

| Role | Tool | Why |
| --- | --- | --- |
| Waitlist and forms | [typeform.com](https://typeform.com) | Forms people finish. |
| Outbound | [instantly.ai](https://instantly.ai) | Cold email at volume with warmup and rotation. |
| Lead data | [clay.com](https://clay.com) | Enrich a list from 50 sources in one sheet. |
| SEO | [ahrefs.com](https://ahrefs.com) | Know what people search before you write. |
| Link in bio | [beacons.ai](https://beacons.ai) | One link for every profile. |
| Community | [skool.com](https://skool.com) | Paid communities with courses, no plugins. |
| Be seen | [kinged.lol](https://kinged.lol) | The #1 spot for AI tools, $1 an hour. You are reading it. |

## AI Agent Tools

- **[Agentivehub](https://agentivehub.com)** — Platform for AI agent services. Best for Teams adopting AI agents. [[details](https://kinged.lol/t/agentivehub.com)]
- **[AgentMail](https://agentmail.to)** — Email infrastructure for AI agents. Best for AI agent developers. [[details](https://kinged.lol/t/agentmail.to)]
- **[Agentyug](https://agentyug.com)** — One click MCP integration for Claude. Best for Claude and MCP users. [[details](https://kinged.lol/t/agentyug.com)]
- **[Aurachat](https://aurachat.io)** — AI tool for generating UI designs. Best for Founders and designers. [[details](https://kinged.lol/t/aurachat.io)]
- **[Composio](https://composio.dev)** — Tool calling and app integrations for agents. Best for Developers building AI agents. [[details](https://kinged.lol/t/composio.dev)]
- **[Google Opal](https://opal.withgoogle.com)** — No code builder for AI mini apps. Best for no code AI makers. [[details](https://kinged.lol/t/opal.withgoogle.com)]
- **[Google Project Mariner](https://deepmind.google)** — Research prototype for AI browser agents. Best for Early agent researchers. [[details](https://kinged.lol/t/deepmind.google)]
- **[Gumloop](https://gumloop.com)** — No code automation with AI agents. Best for Operators automating workflows. [[details](https://kinged.lol/t/gumloop.com)]
- **[Hermes Agent](https://hermes-agent.nousresearch.com)** — Personal AI agent that learns over time. Best for Individuals wanting an assistant. [[details](https://kinged.lol/t/hermes-agent.nousresearch.com)]
- **[Make](https://make.com)** — Visual automation and workflow builder. Best for Operators automating workflows. [[details](https://kinged.lol/t/make.com)]
- **[MindStudio](https://mindstudio.ai)** — No code platform for building AI agents. Best for teams building no code AI agents. [[details](https://kinged.lol/t/mindstudio.ai)]
- **[n8n](https://n8n.io)** — Open source workflow automation platform. Best for developers wanting self hosted automation. [[details](https://kinged.lol/t/n8n.io)]
- **[OpenAI Operator](https://operator.chatgpt.com)** — AI agent that operates a web browser. Best for people automating browser tasks. [[details](https://kinged.lol/t/operator.chatgpt.com)]
- **[Paperclip](https://paperclip.ing)** — Open source orchestration for agent workflows. Best for builders automating agent pipelines. [[details](https://kinged.lol/t/paperclip.ing)]
- **[Pickaxe](https://pickaxe.com)** — No code platform to build and sell AI products. Best for creators selling AI products. [[details](https://kinged.lol/t/pickaxe.com)]
- **[Relay](https://relay.app)** — Visual builder for AI agents and app workflows. Best for teams automating work. [[details](https://kinged.lol/t/relay.app)]
- **[Relevance AI](https://relevanceai.com)** — AI agents for data automation and analytics. Best for teams automating data work. [[details](https://kinged.lol/t/relevanceai.com)]
- **[Respell](https://respell.ai)** — Build AI workflows with natural language. Best for teams building AI automations. [[details](https://kinged.lol/t/respell.ai)]
- **[Rube](https://rube.app)** — Universal MCP server for AI agents. Best for developers wiring up agents. [[details](https://kinged.lol/t/rube.app)]
- **[Shipable](https://shipable.ai)** — Platform for building AI agents. Best for teams building AI agents. [[details](https://kinged.lol/t/shipable.ai)]
- **[STRING](https://string.com)** — Agent platform for workflow automation. Best for teams automating operations. [[details](https://kinged.lol/t/string.com)]
- **[Zapier](https://zapier.com)** — No code automation across apps. Best for founders automating busywork. [[details](https://kinged.lol/t/zapier.com)]

## Development Tools

- **[Appwrite](https://appwrite.io)** — Open source backend for app development. Best for App developers wanting open source backend. [[details](https://kinged.lol/t/appwrite.io)]
- **[Clerk](https://clerk.com)** — Authentication and user management for apps. Best for Developers adding auth to apps. [[details](https://kinged.lol/t/clerk.com)]
- **[Code Wiki](https://codewiki.google)** — Centralized documentation for code. Best for Engineering teams documenting code. [[details](https://kinged.lol/t/codewiki.google)]
- **[Convex](https://convex.dev)** — Real time backend platform for apps. Best for Developers building reactive apps. [[details](https://kinged.lol/t/convex.dev)]
- **[Cursor](https://cursor.com)** — AI first code editor with pair programming. Best for Developers coding day to day. [[details](https://kinged.lol/t/cursor.com)]
- **[Docker Desktop](https://docker.com)** — Run containers and MCP agents locally. Best for Developers running local containers. [[details](https://kinged.lol/t/docker.com)]
- **[Expo](https://expo.dev)** — framework for shipping React Native apps. Best for React Native mobile developers. [[details](https://kinged.lol/t/expo.dev)]
- **[Expo MCP Server](https://docs.expo.dev)** — MCP server for Expo and EAS docs. Best for Expo developers using AI agents. [[details](https://kinged.lol/t/docs.expo.dev)]
- **[GitHub](https://github.com)** — code hosting and version control. Best for developers and software teams. [[details](https://kinged.lol/t/github.com)]
- **[InstantDB](https://instantdb.com)** — Real time database for apps. Best for Developers building reactive apps. [[details](https://kinged.lol/t/instantdb.com)]
- **[Launch (RN Boilerplate)](https://launchtoday.dev)** — React Native starter boilerplate. Best for Indie mobile developers. [[details](https://kinged.lol/t/launchtoday.dev)]
- **[Mux](https://mux.com)** — Video API for adding video to apps. Best for developers adding video features. [[details](https://kinged.lol/t/mux.com)]
- **[Nativewind](https://nativewind.dev)** — Tailwind CSS styling for React Native. Best for React Native developers using Tailwind. [[details](https://kinged.lol/t/nativewind.dev)]
- **[Play](https://createwithplay.com)** — Design and prototype iOS apps with SwiftUI. Best for iOS designers and developers. [[details](https://kinged.lol/t/createwithplay.com)]
- **[React Email](https://react.email)** — Build email templates with React components. Best for developers building transactional email. [[details](https://kinged.lol/t/react.email)]
- **[Revyl](https://revyl.com)** — AI mobile testing on real iOS and Android devices. Best for mobile QA and dev teams. [[details](https://kinged.lol/t/revyl.com)]
- **[Snyk](https://snyk.io)** — Developer security for code and dependencies. Best for engineering and security teams. [[details](https://kinged.lol/t/snyk.io)]
- **[TesterArmy](https://tester.army)** — AI testing to catch app bugs. Best for Developers testing apps. [[details](https://kinged.lol/t/tester.army)]
- **[Three.js](https://threejs.org)** — JavaScript library for 3D graphics. Best for Developers building 3D web. [[details](https://kinged.lol/t/threejs.org)]
- **[Vercel](https://vercel.com)** — deploy and host web apps. Best for web app hosting. [[details](https://kinged.lol/t/vercel.com)]
- **[XcodeBuildMCP](https://xcodebuildmcp.com)** — MCP server for Xcode builds. Best for iOS developers using AI agents. [[details](https://kinged.lol/t/xcodebuildmcp.com)]

## AI Video

- **[Airpost](https://airpost.ai)** — AI video ad creation. Best for Marketers running video ads. [[details](https://kinged.lol/t/airpost.ai)]
- **[Basedlabs AI](https://basedlabs.ai)** — Long form AI video generation. Best for AI video creators. [[details](https://kinged.lol/t/basedlabs.ai)]
- **[Fastlane AI](https://usefastlane.ai)** — AI short form content creation. Best for Short form content creators. [[details](https://kinged.lol/t/usefastlane.ai)]
- **[Google Flow](https://labs.google)** — AI filmmaking studio for long videos. Best for AI filmmakers and creators. [[details](https://kinged.lol/t/labs.google)]
- **[Hailuo AI](https://hailuoai.video)** — AI video generation from prompts. Best for creators and marketers. [[details](https://kinged.lol/t/hailuoai.video)]
- **[Hera](https://hera.video)** — AI motion design for animated video. Best for marketers and content creators. [[details](https://kinged.lol/t/hera.video)]
- **[HeyGen](https://heygen.com)** — AI avatar and UGC video creation. Best for marketers making video ads. [[details](https://kinged.lol/t/heygen.com)]
- **[Higgsfield AI](https://higgsfield.ai)** — AI video and image generation platform. Best for creators and ad makers. [[details](https://kinged.lol/t/higgsfield.ai)]
- **[JSON2Video](https://json2video.com)** — Video generation API driven by JSON. Best for Developers automating video output. [[details](https://kinged.lol/t/json2video.com)]
- **[Kling AI](https://klingai.com)** — AI video and image generation. Best for Creators and marketers. [[details](https://kinged.lol/t/klingai.com)]
- **[Lumen5](https://lumen5.com)** — AI video creation from text. Best for Content and marketing teams. [[details](https://kinged.lol/t/lumen5.com)]
- **[Overlap](https://overlap.ai)** — AI clipping of long videos into shorts. Best for Podcasters and video creators. [[details](https://kinged.lol/t/overlap.ai)]
- **[Pictory.ai](https://pictory.ai)** — Turn text and scripts into videos. Best for Content marketers. [[details](https://kinged.lol/t/pictory.ai)]
- **[Reeler AI](https://reelerai.com)** — AI video creation for reels and shorts. Best for social video creators. [[details](https://kinged.lol/t/reelerai.com)]
- **[Remotion](https://remotion.dev)** — Create videos programmatically with React. Best for developers automating video creation. [[details](https://kinged.lol/t/remotion.dev)]
- **[Runway ML](https://runwayml.com)** — AI video generation and editing. Best for filmmakers and video creators. [[details](https://kinged.lol/t/runwayml.com)]
- **[Sendspark](https://sendspark.com)** — Personalized video prospecting for sales. Best for sales and marketing teams. [[details](https://kinged.lol/t/sendspark.com)]
- **[Sora](https://sora.com)** — AI video generation from text. Best for creators and storytellers. [[details](https://kinged.lol/t/sora.com)]
- **[Tavus AI](https://tavus.ai)** — Personalized AI video for outreach. Best for sales teams doing video outreach. [[details](https://kinged.lol/t/tavus.ai)]
- **[Zebracat.ai](https://zebracat.ai)** — turn text prompts into videos. Best for indie marketers making short video. [[details](https://kinged.lol/t/zebracat.ai)]

## Marketing

- **[Arcads](https://arcads.ai)** — AI UGC video ads from scripts. Best for App and performance marketers. [[details](https://kinged.lol/t/arcads.ai)]
- **[Before](https://before.click)** — Pre launch landing page builder. Best for founders validating ideas. [[details](https://kinged.lol/t/before.click)]
- **[Copy Emojis](https://emojikopieren.de)** — Emoji collection for copy and paste. Best for Social media writers. [[details](https://kinged.lol/t/emojikopieren.de)]
- **[CopyAI](https://copy.ai)** — AI copywriting for marketing content. Best for Marketing and content teams. [[details](https://kinged.lol/t/copy.ai)]
- **[Foreplay](https://foreplay.co)** — Ad saving and organization workflow. Best for Performance marketing teams. [[details](https://kinged.lol/t/foreplay.co)]
- **[Fourthlane](https://fourthlane.com)** — Marketing workflow and automation tooling. Best for small marketing teams. [[details](https://kinged.lol/t/fourthlane.com)]
- **[Jasper](https://jasper.ai)** — AI content writing for marketing teams. Best for enterprise marketing teams. [[details](https://kinged.lol/t/jasper.ai)]
- **[LightReel](https://lightreel.ai)** — AI research for short form ad creative. Best for App marketers and growth teams. [[details](https://kinged.lol/t/lightreel.ai)]
- **[MakeUGC](https://makeugc.ai)** — AI generated UGC for campaigns. Best for App marketers running paid ads. [[details](https://kinged.lol/t/makeugc.ai)]
- **[Playkit](https://playkit.xyz)** — Tech UGC creation for consumer apps. Best for Consumer app marketers. [[details](https://kinged.lol/t/playkit.xyz)]
- **[SideShift](https://sideshift.app)** — UGC creator recruitment and campaign management. Best for brands running UGC programs. [[details](https://kinged.lol/t/sideshift.app)]
- **[The Viral App](https://theviralapp.com)** — UGC and influencer marketing for apps. Best for app founders growing with creators. [[details](https://kinged.lol/t/theviralapp.com)]
- **[TokComment](https://tokcomment.com)** — TikTok comment marketing and engagement. Best for marketers growing on TikTok. [[details](https://kinged.lol/t/tokcomment.com)]
- **[Trackr](https://ugctrackr.com)** — Tracking tool for UGC performance. Best for marketers running UGC campaigns. [[details](https://kinged.lol/t/ugctrackr.com)]
- **[Tryatria](https://tryatria.com)** — AI marketing for content and campaigns. Best for founders running their own marketing. [[details](https://kinged.lol/t/tryatria.com)]
- **[Uizard](https://uizard.io)** — turn sketches into UI designs. Best for founders prototyping app UI. [[details](https://kinged.lol/t/uizard.io)]

## Vibe Coding

- **[10X](https://10x.app)** — AI builder for native SwiftUI iOS apps. Best for Solo iOS app builders. [[details](https://kinged.lol/t/10x.app)]
- **[Bolt.new](https://bolt.new)** — AI powered full stack web app builder. Best for Solo founders prototyping web apps. [[details](https://kinged.lol/t/bolt.new)]
- **[Databutton](https://databutton.com)** — No code builder for SaaS apps. Best for Non technical SaaS founders. [[details](https://kinged.lol/t/databutton.com)]
- **[Lovable](https://lovable.dev)** — AI app and UI builder from prompts. Best for founders shipping web apps. [[details](https://kinged.lol/t/lovable.dev)]
- **[manus.ai](https://manus.ai)** — AI agent for code, design, and research. Best for builders delegating multi step work. [[details](https://kinged.lol/t/manus.ai)]
- **[Momen](https://momen.app)** — AI app builder for web apps. Best for founders building functional apps. [[details](https://kinged.lol/t/momen.app)]
- **[Polymet](https://polymet.ai)** — AI product design and UI generation. Best for product teams and founders. [[details](https://kinged.lol/t/polymet.ai)]
- **[Replit](https://replit.com)** — Browser based coding and app building. Best for developers and learners prototyping fast. [[details](https://kinged.lol/t/replit.com)]
- **[Rork](https://rork.app)** — Generate mobile apps from a prompt. Best for founders prototyping mobile apps. [[details](https://kinged.lol/t/rork.app)]
- **[Tempo.new](https://tempo.new)** — Productivity and focus workspace. Best for Founders managing focus. [[details](https://kinged.lol/t/tempo.new)]
- **[v0.dev](https://v0.dev)** — generate UI from prompts. Best for frontend prototyping. [[details](https://kinged.lol/t/v0.dev)]
- **[VibeCodePrompts](https://vibecodeprompts.cloud)** — prompt generator for vibe coding. Best for vibe coders. [[details](https://kinged.lol/t/vibecodeprompts.cloud)]
- **[VibeFlow](https://vibeflow.ai)** — full stack AI app builder. Best for full stack app builders. [[details](https://kinged.lol/t/vibeflow.ai)]
- **[Wrapifai](https://wrapifai.com)** — Build SEO lead generation tools. Best for Marketers building lead gen tools. [[details](https://kinged.lol/t/wrapifai.com)]

## Sales Tool

- **[Apollo.io](https://apollo.io)** — B2B contact database and sales outreach. Best for B2B sales and outbound teams. [[details](https://kinged.lol/t/apollo.io)]
- **[Cargo](https://cargo.io)** — Revenue orchestration for go to market teams. Best for Revenue operations teams. [[details](https://kinged.lol/t/cargo.io)]
- **[Clay](https://clay.com)** — Lead research and data enrichment. Best for Sales and growth teams. [[details](https://kinged.lol/t/clay.com)]
- **[ColdIQ](https://coldiq.com)** — Lead generation agency and AI sales tools. Best for B2B outbound teams. [[details](https://kinged.lol/t/coldiq.com)]
- **[Freckle](https://freckle.com)** — Lead research and enrichment for sales. Best for sales and growth teams. [[details](https://kinged.lol/t/freckle.com)]
- **[HeyReach](https://heyreach.io)** — LinkedIn outreach automation at scale. Best for agencies and sales teams. [[details](https://kinged.lol/t/heyreach.io)]
- **[Honeysales](https://honeysales.io)** — AI sales intelligence and prospecting. Best for sales and prospecting teams. [[details](https://kinged.lol/t/honeysales.io)]
- **[Lemlist](https://lemlist.com)** — Cold email and LinkedIn outreach. Best for Sales teams and founders. [[details](https://kinged.lol/t/lemlist.com)]
- **[Persana AI](https://persana.ai)** — AI sales prospecting and enrichment. Best for B2B sales teams. [[details](https://kinged.lol/t/persana.ai)]
- **[Reply.io](https://reply.io)** — Multichannel sales outreach and engagement. Best for outbound sales teams. [[details](https://kinged.lol/t/reply.io)]
- **[Tapistro](https://tapistro.com)** — AI account research and personalization. Best for sales and marketing teams. [[details](https://kinged.lol/t/tapistro.com)]
- **[Tome.app](https://tome.app)** — AI sales assistant for accounts. Best for sales reps researching accounts. [[details](https://kinged.lol/t/tome.app)]
- **[Trigify.io](https://trigify.io)** — Buying intent signal tracking. Best for outbound sales teams. [[details](https://kinged.lol/t/trigify.io)]
- **[Vanta](https://vanta.com)** — automated security compliance platform. Best for startups pursuing SOC 2. [[details](https://kinged.lol/t/vanta.com)]

## Website Builder

- **[AppView](https://appview.dev)** — Website template for iOS apps. Best for iOS app developers. [[details](https://kinged.lol/t/appview.dev)]
- **[Aura](https://aurajs.dev)** — Build websites and export to Lovable. Best for Website builders using Lovable. [[details](https://kinged.lol/t/aurajs.dev)]
- **[Builder.io](https://builder.io)** — Figma to code and visual web building. Best for Design and engineering teams. [[details](https://kinged.lol/t/builder.io)]
- **[Carrd](https://carrd.co)** — Simple one page landing site builder. Best for Makers needing a quick landing page. [[details](https://kinged.lol/t/carrd.co)]
- **[Dirstarter](https://dirstarter.com)** — Next.js template for directory sites. Best for Founders building directory sites. [[details](https://kinged.lol/t/dirstarter.com)]
- **[Duda](https://duda.co)** — website builder for agencies and SaaS. Best for agencies and SaaS providers. [[details](https://kinged.lol/t/duda.co)]
- **[Framer](https://framer.com)** — design focused website builder. Best for designers and founders. [[details](https://kinged.lol/t/framer.com)]
- **[Hostinger](https://hostinger.com)** — Web hosting and site builder. Best for Small businesses and founders. [[details](https://kinged.lol/t/hostinger.com)]
- **[Landingi](https://landingi.com)** — Landing page builder. Best for Marketers and founders. [[details](https://kinged.lol/t/landingi.com)]
- **[Leadpages](https://leadpages.com)** — Landing page builder for lead generation. Best for marketers and small businesses. [[details](https://kinged.lol/t/leadpages.com)]
- **[Unicorn Platform](https://unicornplatform.com)** — landing page and website builder. Best for startup landing pages. [[details](https://kinged.lol/t/unicornplatform.com)]
- **[Webflow](https://webflow.com)** — visual professional website builder. Best for designers and agencies. [[details](https://kinged.lol/t/webflow.com)]
- **[Wix](https://wix.com)** — Drag and drop website builder. Best for small businesses and creators. [[details](https://kinged.lol/t/wix.com)]

## AI Design

- **[Design Arena](https://designarena.ai)** — AI design comparison and evaluation. Best for Designers refining concepts. [[details](https://kinged.lol/t/designarena.ai)]
- **[Design Prompts](https://designprompts.dev)** — AI design style explorer. Best for Designers exploring styles. [[details](https://kinged.lol/t/designprompts.dev)]
- **[Designs AI](https://designs.ai)** — All in one AI design suite. Best for Marketers needing varied assets. [[details](https://kinged.lol/t/designs.ai)]
- **[Google Stitch](https://stitch.withgoogle.com)** — AI generation of website UI. Best for Founders drafting web UI. [[details](https://kinged.lol/t/stitch.withgoogle.com)]
- **[MagicPath.ai](https://magicpath.ai)** — AI design tool for user interfaces. Best for Founders prototyping interfaces. [[details](https://kinged.lol/t/magicpath.ai)]
- **[Masko](https://masko.ai)** — AI mascot generator for brands. Best for Founders building brand identity. [[details](https://kinged.lol/t/masko.ai)]
- **[Mixboard](https://labs.google.com)** — AI mood board and concept exploration. Best for Early visual ideation. [[details](https://kinged.lol/t/labs.google.com)]
- **[Napkin AI](https://napkin.ai)** — Text to visuals and infographics. Best for Visualizing written ideas. [[details](https://kinged.lol/t/napkin.ai)]
- **[Neuform](https://neuform.ai)** — AI generated HTML design templates. Best for Quick template starting points. [[details](https://kinged.lol/t/neuform.ai)]
- **[Paywall Experiments](https://paywallexperiments.com)** — Mobile paywall design gallery. Best for Mobile app monetization design. [[details](https://kinged.lol/t/paywallexperiments.com)]
- **[QuiverAI](https://quiver.ai)** — AI vector design generation. Best for AI vector asset creation. [[details](https://kinged.lol/t/quiver.ai)]
- **[Weavy](https://weavy.ai)** — AI design workflow for creative work. Best for Creative professionals and studios. [[details](https://kinged.lol/t/weavy.ai)]

## Design Inspiration

- **[60fps](https://60fps.design)** — Curated UI and UX animation inspiration. Best for Designers seeking motion ideas. [[details](https://kinged.lol/t/60fps.design)]
- **[Awwwards](https://awwwards.com)** — Award gallery for outstanding web design. Best for Web designers and agencies. [[details](https://kinged.lol/t/awwwards.com)]
- **[Dribbble](https://dribbble.com)** — Design community and inspiration platform. Best for Designers and creatives. [[details](https://kinged.lol/t/dribbble.com)]
- **[Landbook](https://land-book.com)** — Gallery of curated landing page designs. Best for Designers seeking web inspiration. [[details](https://kinged.lol/t/land-book.com)]
- **[Mobbin](https://mobbin.com)** — Mobile and web app design reference library. Best for Product and UX designers. [[details](https://kinged.lol/t/mobbin.com)]
- **[Refero](https://refero.design)** — UI and UX design inspiration library. Best for Designers and AI agents. [[details](https://kinged.lol/t/refero.design)]
- **[ScreensDesign](https://screensdesign.com)** — iOS app screen design library. Best for iOS design inspiration. [[details](https://kinged.lol/t/screensdesign.com)]
- **[scrnshts](https://scrnshts.club)** — Curated App Store screenshot gallery. Best for App Store listing design. [[details](https://kinged.lol/t/scrnshts.club)]
- **[SpottedInProd](https://spottedinprod.com)** — App design and UI search. Best for App design research. [[details](https://kinged.lol/t/spottedinprod.com)]
- **[Variant](https://variant.com)** — Endless design inspiration as you scroll. Best for Designers seeking inspiration. [[details](https://kinged.lol/t/variant.com)]

## AI Development

- **[Brave Search API](https://brave.com)** — Web search API for apps and AI agents. Best for Developers building AI search features. [[details](https://kinged.lol/t/brave.com)]
- **[Claude](https://claude.ai)** — AI assistant for writing and reasoning. Best for Founders planning products. [[details](https://kinged.lol/t/claude.ai)]
- **[Claude Code](https://claude.com)** — Agentic coding tool for the terminal. Best for Developers working in the terminal. [[details](https://kinged.lol/t/claude.com)]
- **[Context7](https://context7.com)** — Live documentation for AI code editors. Best for Developers using AI code editors. [[details](https://kinged.lol/t/context7.com)]
- **[Google AI Studio](https://aistudio.google.com)** — Build and test apps on Gemini. Best for developers building on Gemini. [[details](https://kinged.lol/t/aistudio.google.com)]
- **[Greptile](https://greptile.com)** — AI code review for pull requests. Best for Engineering teams. [[details](https://kinged.lol/t/greptile.com)]
- **[Jam AI](https://jam.dev)** — AI bug reporting with repro steps. Best for Product and engineering teams. [[details](https://kinged.lol/t/jam.dev)]
- **[OpenRouter](https://openrouter.ai)** — Unified API for many language models. Best for developers needing flexible model access. [[details](https://kinged.lol/t/openrouter.ai)]
- **[Woz](https://withwoz.com)** — Build software businesses with AI. Best for non technical founders. [[details](https://kinged.lol/t/withwoz.com)]

## UI Components

- **[21st.dev](https://21st.dev)** — Production ready UI components for Cursor. Best for developers building UIs. [[details](https://kinged.lol/t/21st.dev)]
- **[HeroUI](https://heroui.chat)** — React UI component library. Best for React frontend developers. [[details](https://kinged.lol/t/heroui.chat)]
- **[Magic UI](https://magicui.design)** — Animated React component library. Best for React developers building landing pages. [[details](https://kinged.lol/t/magicui.design)]
- **[Shadcn](https://ui.shadcn.com)** — React and Tailwind component building blocks. Best for React frontend developers. [[details](https://kinged.lol/t/ui.shadcn.com)]
- **[Supahero](https://supahero.io)** — Hero section components for websites. Best for Builders designing landing pages. [[details](https://kinged.lol/t/supahero.io)]
- **[Tailwind Plus](https://tailwindcss.com)** — Premium UI components for Tailwind CSS. Best for Tailwind web developers. [[details](https://kinged.lol/t/tailwindcss.com)]
- **[The Component Gallery](https://component.gallery)** — UI component design reference. Best for Component design reference. [[details](https://kinged.lol/t/component.gallery)]
- **[Tweakcn](https://tweakcn.com)** — Visual theme editor for shadcn components. Best for React and Tailwind developers. [[details](https://kinged.lol/t/tweakcn.com)]

## Productivity

- **[DartAI](https://dartai.com)** — AI native project management tool. Best for Teams managing projects. [[details](https://kinged.lol/t/dartai.com)]
- **[Google Workspace](https://workspace.google.com)** — Productivity suite for email and docs. Best for Teams and solo founders. [[details](https://kinged.lol/t/workspace.google.com)]
- **[Granola](https://granola.ai)** — AI note taking for meetings. Best for Founders in many meetings. [[details](https://kinged.lol/t/granola.ai)]
- **[Motion](https://usemotion.com)** — AI calendar and task planning. Best for busy professionals and small teams. [[details](https://kinged.lol/t/usemotion.com)]
- **[Notion](https://notion.so)** — All in one workspace for docs and projects. Best for individuals and teams organizing work. [[details](https://kinged.lol/t/notion.so)]
- **[Reclaim.ai](https://reclaim.ai)** — AI calendar for scheduling and time blocking. Best for busy professionals and teams. [[details](https://kinged.lol/t/reclaim.ai)]
- **[Tinyformat](https://tinyformat.com)** — lightweight admin panel builder. Best for indie internal tooling. [[details](https://kinged.lol/t/tinyformat.com)]
- **[Whimsical](https://whimsical.com)** — Visual workspace for flowcharts and docs. Best for product teams and planners. [[details](https://kinged.lol/t/whimsical.com)]

## AI Marketing

- **[Adcreative.ai](https://adcreative.ai)** — AI ad creative generation for marketing. Best for Performance marketers and ad teams. [[details](https://kinged.lol/t/adcreative.ai)]
- **[Aftermark](https://aftermark.ai)** — AI content marketing for SaaS. Best for SaaS founders and marketers. [[details](https://kinged.lol/t/aftermark.ai)]
- **[InstaAgent](https://instaagent.com)** — Run one campaign across many audiences. Best for performance marketers. [[details](https://kinged.lol/t/instaagent.com)]
- **[Kive AI](https://kive.ai)** — On brand AI visuals in one place. Best for Brand and marketing teams. [[details](https://kinged.lol/t/kive.ai)]
- **[Predis.ai](https://predis.ai)** — AI ad creatives and social posts. Best for Small business marketers. [[details](https://kinged.lol/t/predis.ai)]
- **[Stormy](https://stormy.ai)** — AI agent for influencer marketing. Best for brands running influencer campaigns. [[details](https://kinged.lol/t/stormy.ai)]
- **[Superscale.ai](https://superscale.ai)** — AI generation of viral social content. Best for social marketers and creators. [[details](https://kinged.lol/t/superscale.ai)]
- **[viral.app](https://viral.app)** — grow content across short video platforms. Best for creators chasing organic growth. [[details](https://kinged.lol/t/viral.app)]

## Market Research

- **[appgaps](https://findappgaps.com)** — Finding market gaps and app opportunities. Best for founders hunting app ideas. [[details](https://kinged.lol/t/findappgaps.com)]
- **[Explodingtopics](https://explodingtopics.com)** — Trend analysis for emerging topics. Best for founders and marketers. [[details](https://kinged.lol/t/explodingtopics.com)]
- **[Fomo.com](https://fomo.com)** — Social proof notifications for websites. Best for online businesses and stores. [[details](https://kinged.lol/t/fomo.com)]
- **[Glint](https://glint.trade)** — Real time prediction market intelligence. Best for Traders and market researchers. [[details](https://kinged.lol/t/glint.trade)]
- **[Particl](https://particl.com)** — Competitor intelligence and price tracking. Best for Commerce and product teams. [[details](https://kinged.lol/t/particl.com)]
- **[Proven SaaS](https://proven-saas.com)** — Profitable SaaS ideas that work. Best for SaaS founders seeking ideas. [[details](https://kinged.lol/t/proven-saas.com)]
- **[SpyTok](https://spytok.com)** — Viral TikTok analytics and research. Best for TikTok creators and marketers. [[details](https://kinged.lol/t/spytok.com)]

## App Analytics

- **[Adjust](https://adjust.com)** — Mobile attribution and analytics platform. Best for Mobile growth and UA teams. [[details](https://kinged.lol/t/adjust.com)]
- **[Appfigures](https://appfigures.com)** — App store optimization and mobile analytics. Best for Mobile developers and ASO teams. [[details](https://kinged.lol/t/appfigures.com)]
- **[appkittie](https://appkittie.com)** — App Store intelligence and research. Best for Indie app makers and ASO researchers. [[details](https://kinged.lol/t/appkittie.com)]
- **[AppStoreTracker](https://appstoretracker.com)** — Tracking fast growing App Store apps. Best for App builders watching market trends. [[details](https://kinged.lol/t/appstoretracker.com)]
- **[Sentry](https://sentry.io)** — Error monitoring and performance tracking. Best for Developers monitoring production apps. [[details](https://kinged.lol/t/sentry.io)]
- **[What's the App](https://whatsthe.app)** — Verified mobile app metrics database. Best for app founders and analysts. [[details](https://kinged.lol/t/whatsthe.app)]

## Design Tools

- **[Anymark](https://anymark.co)** — Handcrafted logos and brand kits. Best for Founders building a brand. [[details](https://kinged.lol/t/anymark.co)]
- **[Canva](https://canva.com)** — Drag and drop graphic design tool. Best for Marketers and non designers. [[details](https://kinged.lol/t/canva.com)]
- **[Excalidraw](https://excalidraw.com)** — Free hand drawn diagram and whiteboard tool. Best for Developers mapping out ideas. [[details](https://kinged.lol/t/excalidraw.com)]
- **[LottieFiles](https://lottiefiles.com)** — Create and ship lightweight animations. Best for Designers and developers adding motion. [[details](https://kinged.lol/t/lottiefiles.com)]
- **[Paper](https://paper.design)** — Interface design and sharing tool. Best for Interface design teams. [[details](https://kinged.lol/t/paper.design)]
- **[Polymorph](https://usepolymorph.com)** — Convert designs into UI code. Best for frontend designers and developers. [[details](https://kinged.lol/t/usepolymorph.com)]

## Payment

- **[GoCardless](https://gocardless.com)** — Recurring payments and bank debits. Best for Subscription and recurring billing. [[details](https://kinged.lol/t/gocardless.com)]
- **[Lemon Squeezy](https://lemonsqueezy.com)** — Payments and tax for digital products. Best for Indie digital product sellers. [[details](https://kinged.lol/t/lemonsqueezy.com)]
- **[Mollie](https://mollie.com)** — European online payment processing. Best for European online businesses. [[details](https://kinged.lol/t/mollie.com)]
- **[Polar](https://polar.sh)** — Payments and billing for software. Best for Developers monetizing software. [[details](https://kinged.lol/t/polar.sh)]
- **[RevenueCat](https://revenuecat.com)** — In app subscription infrastructure for mobile. Best for Mobile app subscription teams. [[details](https://kinged.lol/t/revenuecat.com)]
- **[Stripe](https://stripe.com)** — Online payments and subscription billing. Best for SaaS and online businesses. [[details](https://kinged.lol/t/stripe.com)]

## Startup Resources

- **[Braavo](https://getbraavo.com)** — Non dilutive funding for app makers. Best for Mobile app and game studios. [[details](https://kinged.lol/t/getbraavo.com)]
- **[Enty](https://enty.io)** — All in one platform to run a company. Best for Founders and small businesses. [[details](https://kinged.lol/t/enty.io)]
- **[Loot Drop](https://loot-drop.vercel.app)** — Archive of failed startup ideas. Best for Founders validating ideas. [[details](https://kinged.lol/t/loot-drop.vercel.app)]
- **[Startfleet](https://startfleet.io)** — US company formation for international founders. Best for international startup founders. [[details](https://kinged.lol/t/startfleet.io)]
- **[Startups.RIP](https://startups.rip)** — Database of failed YC startups and their ideas. Best for founders researching ideas. [[details](https://kinged.lol/t/startups.rip)]

## Resources

- **[BoilerplateList](https://boilerplatelist.com)** — Directory of starter boilerplates by stack. Best for Developers starting new projects. [[details](https://kinged.lol/t/boilerplatelist.com)]
- **[GrizzlySMS](https://grizzlysms.com)** — Virtual numbers for SMS verification. Best for account testing and signups. [[details](https://kinged.lol/t/grizzlysms.com)]
- **[Padlet AI Tools](https://padlet.com)** — Curated AI tools for academic work. Best for Students and researchers. [[details](https://kinged.lol/t/padlet.com)]
- **[Tech Twitter](https://techtwitter.com)** — Curated tech news from Twitter and X. Best for founders following tech trends. [[details](https://kinged.lol/t/techtwitter.com)]
- **[The Wonder Project](https://thewonderproject.com)** — Curated entertainment for faith audiences. Best for faith and values audiences. [[details](https://kinged.lol/t/thewonderproject.com)]

## App Marketing

- **[AppScreens](https://appscreens.com)** — App Store screenshot generator. Best for App developers building store listings. [[details](https://kinged.lol/t/appscreens.com)]
- **[AppSprint](https://appsprint.app)** — App ad campaigns optimized for paying users. Best for App marketers acquiring paying users. [[details](https://kinged.lol/t/appsprint.app)]
- **[Astro](https://tryastro.app)** — App Store optimization and ranking tool. Best for App developers and ASO teams. [[details](https://kinged.lol/t/tryastro.app)]
- **[Branch](https://branch.io)** — Mobile deep linking and attribution. Best for Mobile growth and marketing teams. [[details](https://kinged.lol/t/branch.io)]
- **[Ryplix Studio](https://ryplix.studio)** — App Store screenshot design and ASO. Best for Mobile app developers and marketers. [[details](https://kinged.lol/t/ryplix.studio)]

## CRM

- **[Attio](https://attio.com)** — Flexible CRM for modern teams. Best for Startups and revenue teams. [[details](https://kinged.lol/t/attio.com)]
- **[Bigin by Zoho](https://bigin.com)** — Simple CRM for small businesses. Best for Small businesses and solo founders. [[details](https://kinged.lol/t/bigin.com)]
- **[Capsule](https://capsulecrm.com)** — CRM for small businesses. Best for Small business owners. [[details](https://kinged.lol/t/capsulecrm.com)]
- **[Copper](https://copper.com)** — CRM with Google Workspace integration. Best for Google Workspace teams. [[details](https://kinged.lol/t/copper.com)]
- **[HubSpot](https://hubspot.com)** — All in one CRM and marketing suite. Best for growing sales and marketing teams. [[details](https://kinged.lol/t/hubspot.com)]

## Social Media

- **[Buffer](https://buffer.com)** — Social media scheduling and publishing. Best for Founders and social media managers. [[details](https://kinged.lol/t/buffer.com)]
- **[Ocoya](https://ocoya.com)** — AI social media content and scheduling. Best for Social media managers. [[details](https://kinged.lol/t/ocoya.com)]
- **[Postiz](https://postiz.com)** — AI social media scheduling and publishing. Best for Creators and social teams. [[details](https://kinged.lol/t/postiz.com)]
- **[Social Bee](https://socialbee.com)** — Social media scheduling and automation. Best for creators and small teams. [[details](https://kinged.lol/t/socialbee.com)]
- **[Vista Social](https://vistasocial.com)** — social media management dashboard. Best for agencies managing social accounts. [[details](https://kinged.lol/t/vistasocial.com)]

## AI Search

- **[Exa](https://exa.ai)** — web search API for AI apps. Best for AI app developers. [[details](https://kinged.lol/t/exa.ai)]
- **[Okara](https://okara.ai)** — AI search and summary across Reddit. Best for Founders researching audiences. [[details](https://kinged.lol/t/okara.ai)]
- **[Perplexity](https://perplexity.ai)** — AI search engine with cited answers. Best for Founders and researchers. [[details](https://kinged.lol/t/perplexity.ai)]
- **[TheHomebase AI](https://thehomebase.ai)** — AI curated newsletter for tools and trends. Best for builders tracking AI tools. [[details](https://kinged.lol/t/thehomebase.ai)]

## Video Editing

- **[CapCut](https://capcut.com)** — Video editing for social media content. Best for Social video creators. [[details](https://kinged.lol/t/capcut.com)]
- **[Descript](https://descript.com)** — Edit video and audio like a document. Best for Creators editing video and podcasts. [[details](https://kinged.lol/t/descript.com)]
- **[Shortkit](https://shortkit.dev)** — Simple video creation and editing. Best for short video creators. [[details](https://kinged.lol/t/shortkit.dev)]
- **[Veed.io](https://veed.io)** — online video editing in the browser. Best for creators editing social videos. [[details](https://kinged.lol/t/veed.io)]

## Community Platform

- **[Bettermode](https://bettermode.com)** — Community and knowledge base platform. Best for Product teams building communities. [[details](https://kinged.lol/t/bettermode.com)]
- **[Circle.so](https://circle.so)** — Community platform for membership areas. Best for Creators and membership brands. [[details](https://kinged.lol/t/circle.so)]
- **[Mighty](https://mighty.com)** — Community platform for courses and memberships. Best for Course and membership creators. [[details](https://kinged.lol/t/mighty.com)]
- **[Skool](https://skool.com)** — Community platform for courses and groups. Best for course creators and coaches. [[details](https://kinged.lol/t/skool.com)]

## AI Research

- **[Gemini](https://gemini.google.com)** — Google AI model for research and analysis. Best for Founders doing market research. [[details](https://kinged.lol/t/gemini.google.com)]
- **[Google NotebookLM](https://notebooklm.google.com)** — AI research assistant for your documents. Best for Researchers and writers. [[details](https://kinged.lol/t/notebooklm.google.com)]
- **[H Company](https://hcompany.ai)** — AI agent research lab. Best for AI researchers and builders. [[details](https://kinged.lol/t/hcompany.ai)]

## AI Scraping

- **[Apify](https://apify.com)** — Web scraping and developer APIs. Best for Developers needing web data. [[details](https://kinged.lol/t/apify.com)]
- **[Firecrawl](https://firecrawl.dev)** — web data API for AI apps. Best for AI developers and data teams. [[details](https://kinged.lol/t/firecrawl.dev)]
- **[Thunderbit](https://thunderbit.com)** — AI web scraper for data extraction. Best for Teams collecting web data. [[details](https://kinged.lol/t/thunderbit.com)]

## Forms

- **[Heyflow](https://heyflow.app)** — Interactive lead generation forms and funnels. Best for Marketers running lead funnels. [[details](https://kinged.lol/t/heyflow.app)]
- **[Typeform](https://typeform.com)** — Conversational forms and surveys. Best for Teams collecting feedback and leads. [[details](https://kinged.lol/t/typeform.com)]
- **[Youform](https://youform.com)** — Free form and survey builder. Best for Budget conscious form builders. [[details](https://kinged.lol/t/youform.com)]

## Link Management

- **[Beacons AI](https://beacons.ai)** — Link in bio page for creators. Best for Creators and solo founders. [[details](https://kinged.lol/t/beacons.ai)]
- **[Linktree](https://linktr.ee)** — Link in bio page for social profiles. Best for Creators and social media accounts. [[details](https://kinged.lol/t/linktr.ee)]
- **[Rebrandly](https://rebrandly.com)** — Branded URL shortening and link management. Best for Marketing and brand teams. [[details](https://kinged.lol/t/rebrandly.com)]

## Email Marketing

- **[Beehiiv](https://beehiiv.com)** — Newsletter publishing and growth platform. Best for Newsletter writers and creators. [[details](https://kinged.lol/t/beehiiv.com)]
- **[ConvertKit](https://convertkit.com)** — Email marketing for creators. Best for Creators and newsletter writers. [[details](https://kinged.lol/t/convertkit.com)]
- **[Mailchimp](https://mailchimp.com)** — Email marketing and automations. Best for Small businesses and creators. [[details](https://kinged.lol/t/mailchimp.com)]

## LinkedIn Tools

- **[Kondo](https://trykondo.com)** — LinkedIn inbox management and organization. Best for Sales and outreach on LinkedIn. [[details](https://kinged.lol/t/trykondo.com)]
- **[Mirror Profiles](https://mirrorprofiles.com)** — LinkedIn account rental for outreach. Best for Sales and outreach agencies. [[details](https://kinged.lol/t/mirrorprofiles.com)]
- **[Socialsonic](https://socialsonic.com)** — LinkedIn content creation and scheduling. Best for LinkedIn creators and founders. [[details](https://kinged.lol/t/socialsonic.com)]

## AI Sales

- **[Nomi](https://heynomi.com)** — Real time sales call copilot. Best for Sales reps on calls. [[details](https://kinged.lol/t/heynomi.com)]
- **[Pally](https://pally.com)** — Relationship tracking from online activity. Best for Founders and networkers. [[details](https://kinged.lol/t/pally.com)]
- **[Venta AI](https://getventa.ai)** — sales automation and lead generation. Best for founders scaling sales pipeline. [[details](https://kinged.lol/t/getventa.ai)]

## AI Education

- **[Anthropic Courses](https://anthropic.skilljar.com)** — Official courses for learning Claude and AI. Best for Developers learning Claude. [[details](https://kinged.lol/t/anthropic.skilljar.com)]
- **[OpenAI Academy](https://academy.openai.com)** — Learning resources and prompts from OpenAI. Best for Teams learning AI. [[details](https://kinged.lol/t/academy.openai.com)]

## AI Image

- **[Leonardo AI](https://leonardo.ai)** — AI image generation for creative assets. Best for Designers and creative teams. [[details](https://kinged.lol/t/leonardo.ai)]
- **[remove.bg](https://remove.bg)** — Automatic image background removal. Best for Fast background removal. [[details](https://kinged.lol/t/remove.bg)]

## AI Prompts

- **[God of Prompt](https://godofprompt.ai)** — ChatGPT prompt library for entrepreneurs. Best for entrepreneurs using ChatGPT. [[details](https://kinged.lol/t/godofprompt.ai)]
- **[YouMind](https://youmind.com)** — AI prompt packs and image generation. Best for marketers making UGC imagery. [[details](https://kinged.lol/t/youmind.com)]

## Screen Recording

- **[Loom](https://loom.com)** — Screen recording for Mac and PC. Best for Teams sharing async video. [[details](https://kinged.lol/t/loom.com)]
- **[Riverside](https://riverside.fm)** — Screen recording and podcast production. Best for podcasters and content creators. [[details](https://kinged.lol/t/riverside.fm)]

## Database

- **[Supabase](https://supabase.com)** — Postgres backend with auth and storage. Best for Developers needing a full backend. [[details](https://kinged.lol/t/supabase.com)]
- **[The 100k Database](https://the100kdatabase.com)** — Database of successful products and companies. Best for Founders doing market research. [[details](https://kinged.lol/t/the100kdatabase.com)]

## AI Audio

- **[ElevenLabs](https://elevenlabs.io)** — AI voice generation and audio. Best for Video and app audio. [[details](https://kinged.lol/t/elevenlabs.io)]
- **[Whisper](https://openai.com)** — Automatic speech to text model. Best for developers adding transcription. [[details](https://kinged.lol/t/openai.com)]

## AI SEO

- **[SEO Bot](https://seobot.ai)** — Automated SEO blog post generation. Best for Founders growing organic traffic. [[details](https://kinged.lol/t/seobot.ai)]
- **[Writesonic](https://writesonic.com)** — AI SEO content writing. Best for Content and marketing teams. [[details](https://kinged.lol/t/writesonic.com)]

## AI Content

- **[Blaze.ai](https://blaze.ai)** — AI content creation for brands. Best for Solo marketers and small teams. [[details](https://kinged.lol/t/blaze.ai)]
- **[Typetone.ai](https://typetone.ai)** — AI content creation with brand voice. Best for marketers keeping steady output. [[details](https://kinged.lol/t/typetone.ai)]

## Marketing Agent

- **[Kuli](https://kuli.one)** — AI agent for influencer marketing. Best for Brands running influencer marketing. [[details](https://kinged.lol/t/kuli.one)]
- **[Lindy](https://lindy.ai)** — AI agent for marketing workflows. Best for Small marketing teams. [[details](https://kinged.lol/t/lindy.ai)]

## Social Media Automation

- **[Phantombuster](https://phantombuster.com)** — Social media scraping and outreach automation. Best for Growth and sales teams. [[details](https://kinged.lol/t/phantombuster.com)]
- **[ReelFarm](https://reel.farm)** — Automated TikTok video creation and posting. Best for high volume TikTok marketers. [[details](https://kinged.lol/t/reel.farm)]

## Monetization

- **[Stan Store](https://stan.store)** — All in one creator store and monetization. Best for creators monetizing an audience. [[details](https://kinged.lol/t/stan.store)]
- **[Whop Content Rewards](https://whop.com)** — creator campaigns and content rewards. Best for founders running creator campaigns. [[details](https://kinged.lol/t/whop.com)]

## AI Hardware

- **[Bee](https://bee.computer)** — Wearable AI assistant that records and summarizes. Best for Hands free personal productivity. [[details](https://kinged.lol/t/bee.computer)]

## AI Directory

- **[The Rundown Supertools](https://rundown.ai)** — Directory of AI tools by category. Best for builders choosing AI tools. [[details](https://kinged.lol/t/rundown.ai)]

## App Consulting

- **[Roast My App](https://roastmyapp.co)** — Onboarding and monetization review for B2C apps. Best for B2C mobile app founders. [[details](https://kinged.lol/t/roastmyapp.co)]

## Communication

- **[Beeper](https://beeper.com)** — Unified inbox for all chat apps. Best for People with many messaging apps. [[details](https://kinged.lol/t/beeper.com)]

## AI Automation

- **[Ghost Team AI](https://ghostteam.ai)** — AI automation partner for businesses. Best for businesses adopting automation. [[details](https://kinged.lol/t/ghostteam.ai)]

## AI Tools

- **[Huxe AI](https://huxe.com)** — AI platform for automation and productivity. Best for Teams streamlining work. [[details](https://kinged.lol/t/huxe.com)]

## AI Vision

- **[Moondream](https://moondream.ai)** — Compact vision language model for images. Best for developers adding vision features. [[details](https://kinged.lol/t/moondream.ai)]

## Voice AI

- **[Vapi](https://vapi.ai)** — build voice AI agents. Best for voice assistant developers. [[details](https://kinged.lol/t/vapi.ai)]

## Slides/Presentation

- **[Gamma AI](https://gamma.app)** — AI presentation and deck generation. Best for Founders building pitch decks. [[details](https://kinged.lol/t/gamma.app)]

## SEO

- **[Ahrefs](https://ahrefs.com)** — SEO keyword research and backlink analysis. Best for SEO and content teams. [[details](https://kinged.lol/t/ahrefs.com)]

## Email Verification

- **[Zerobounce](https://zerobounce.net)** — Email verification for clean lists. Best for Email marketing and sales teams. [[details](https://kinged.lol/t/zerobounce.net)]

## AI Worker

- **[Artisan](https://artisan.co)** — AI sales agents for outbound. Best for Sales teams scaling outbound. [[details](https://kinged.lol/t/artisan.co)]

## LinkedIn Automation

- **[Dux Soup](https://dux-soup.com)** — LinkedIn outreach automation. Best for Sales reps and recruiters. [[details](https://kinged.lol/t/dux-soup.com)]

## Email Outreach

- **[Instantly.ai](https://instantly.ai)** — Cold email outreach with warmup. Best for outbound sales teams. [[details](https://kinged.lol/t/instantly.ai)]

## Instagram Automation

- **[Manychat](https://manychat.com)** — Chat marketing automation for social. Best for Brands automating social DMs. [[details](https://kinged.lol/t/manychat.com)]

## AI Image/Video

- **[Midjourney](https://midjourney.com)** — AI image generation from text prompts. Best for Designers and brand visuals. [[details](https://kinged.lol/t/midjourney.com)]

## AI Phone Dialing

- **[Nooks](https://nooks.ai)** — AI powered cold calling and dialing. Best for Outbound sales teams. [[details](https://kinged.lol/t/nooks.ai)]

## Proposals

- **[Qwill](https://qwilr.com)** — Proposal and quote creation for sales. Best for agencies and sales teams. [[details](https://kinged.lol/t/qwilr.com)]

## Contributing

Open a pull request adding your tool to `tools.json` with name, domain, one-line description, category and who it is for. No payment, no affiliate links, no ranking by donation. The paid part lives on [kinged.lol](https://kinged.lol) and is measured openly in minutes.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — use the list, credit kinged.lol.
