# Hi, I'm Jordi Cor

My first code ran on a ZX Spectrum 128K. My father bought programming books but never found time to learn from them. I did. I was eight or nine, copying BASIC line by line:

```basic
10 INPUT "Como te llamas? "; n$
20 PRINT "Hola "; n$
30 INPUT "Continuar? (s/n) "; r$
40 IF r$ = "s" THEN GOTO 10
50 STOP
```

One afternoon I copied five full pages of BASIC from a printed book without understanding a single line. It rendered a fan graphic that opened up on screen. That moment hooked me. Before the Spectrum there was an Atari 2600. After it, my father got an IBM 286 where I learned MS-DOS commands, watched him use Lotus 1-2-3 and dBASE III Plus, tinkered with WordPerfect 5.1, and kept writing small BASIC programs. That thread runs unbroken to today.

For the full personal story: [jordicor.com](https://jordicor.com)

## What I'm building now

I'm the solo founder and developer behind [OjoCentauri](https://github.com/jordicor), the AI division of Acerting Art Inc. (Florida). All code is mine, built from scratch.

- **[GranSabio LLM](https://github.com/jordicor/GranSabio)** (open-source, MIT): Multi-layer QA orchestration engine for AI-generated content. Pipeline: preflight validation, content generation, parallel multi-model evaluation, consensus engine, deal-breaker detection, and final "Gran Sabio" arbitration (premium reasoning model as judge). 950+ automated tests, 200+ models benchmarked, JSON Schema structured outputs, lexical diversity scoring (MTLD, HD-D, Yule's K), confabulation detection. 96K+ lines of Python.

- **[Aurvek](https://github.com/jordicor/Aurvek)** (open-source, MIT): Production AI SaaS platform. Four business modes (aggregator, enterprise, white-label, freelancer marketplace). Six AI providers (OpenAI, Anthropic, Google, xAI, OpenRouter, ElevenLabs). Dual watchdog supervision: pre-response blocking plus post-response monitoring with 4-level escalation. Stripe Connect marketplace. Real-time voice calls via ElevenLabs and Twilio. 135K+ lines.

- **Axiotheon**: Proprietary narrative coherence engine.

- **KatariShoji**: Biographical interview system. Multiple AI interviewer personas, emotional safety protocols, ElevenLabs voice synthesis (33M credits grant). Multi-session, adaptive.

- **[ai-json-cleanroom](https://github.com/jordicor/ai-json-cleanroom)** (open-source, MIT): Zero-dependency JSON extraction and repair for malformed AI outputs. Truncation detection, JSON Schema validation. Python + PHP editions.

Total across all projects: 537K+ lines of code across 1,046 source files. 19 public repositories.

## The long road here

**Late 1980s–90s: First computers**

ZX Spectrum 128K. Sinclair BASIC loaded from cassette tapes (`LOAD ""`). Atari 2600 before that. Then the IBM 286: MS-DOS, WordPerfect 5.1, Lotus 1-2-3, dBASE III Plus. Programming meant copying from books and tinkering until something worked. No internet. No Stack Overflow. Just books and a blinking cursor.

**1998–2002: DOS games and first real code**

This is when it got serious. At 17 I was rendering 3D scenes in POV-Ray on an IBM 486DX2 with 4MB of RAM. The most ambitious scene: 13,000+ objects, 290 hours of continuous rendering. I built DOS games: [neo-atlantis](https://github.com/jordicor/neo-atlantis) (an RPG with 200+ 3D models, 8-directional movement, NPC AI), [mystery-in-the-pyramid](https://github.com/jordicor/mystery-in-the-pyramid) (C + Allegro library, resource encryption, multi-resolution support), and [HITS](https://github.com/jordicor/HITS) (a fighting game with digitized video characters). I wrote 15,000+ lines of IRC scripts ([CwT-ScripT](https://github.com/jordicor/CwT-ScripT)) with Blowfish encryption and channel protection bots. Studied COBOL formally ([cobol-studies-2000](https://github.com/jordicor/cobol-studies-2000)). Built accounting software for a courier company in QuickBASIC with a custom binary file format ([mega-contable-2000](https://github.com/jordicor/mega-contable-2000)). Published raytraced 3D renders in PCMania magazine ([4PCMANIA](https://github.com/jordicor/4PCMANIA)).

**2004–2006: Security research and enterprise IT**

Published two CVEs ([CVE-2004-2045, CVE-2006-0489](https://github.com/jordicor/security-research-archive)) and received recognition from the Microsoft Security Response Center (MSRC Case #6516) for an XSS vulnerability in Microsoft SMS 2003. Wrote C exploit code. Responsible disclosure, years before bug bounties existed. In parallel, I automated enterprise IT for 1,200+ workstations at a Barcelona automotive HQ ([enterprise-it-automation](https://github.com/jordicor/enterprise-it-automation)): mass patching during the Blaster/Sasser worm emergency, Windows migrations, VBScript + PsExec + Active Directory automation. All before PowerShell existed.

**2011–2015: Startups and web platforms**

Built [QRPager](https://github.com/jordicor/QRPager): a full iOS app (Objective-C, manual memory management) with PHP backend and Apple Push Notifications, published on the App Store. Built [MoonMetrics](https://github.com/jordicor/MoonMetrics): the first YouTube backlink analysis platform, started at StartupBus Europe 2013 (a 72-hour hackathon rolling from Barcelona to Vienna). PHP/Symfony 2.4, Doctrine ORM, Redis caching and queuing, indexing millions of YouTube channels.

**2015–present: Content tech**

YouTube Data API tooling, Flask, multi-language video metadata automation, computer vision pipelines (InsightFace face detection, DBSCAN clustering, Whisper STT), multi-provider AI image generation. This stack powers Acerting Art's content operations and is still actively developed. Repos: [YouTube-Video-Metadata-Translator](https://github.com/jordicor/YouTube-Video-Metadata-Translator), [youtube_thumbnail_generator_with_AIs](https://github.com/jordicor/youtube_thumbnail_generator_with_AIs).

In 2019 I commissioned a custom VR relaxation experience: [Acerting Art VR Relaxation Space Room](https://jordicor.itch.io/acerting-art-vr-relaxation-space-room). A sci-fi space hotel room orbiting planets with real-time solar system travel (14-day route), embedded YouTube player for Acerting Art content, music player, PDF reader, and Alexa voice control. Built in Unity, cross-platform VR (Oculus Rift, HTC Vive, WMR via SteamVR). Total investment around 5,500 EUR including 3D design and Unity assets. I connected with the developer through Blair Renaud (creator of the cyberpunk VR game LOW-FI) after backing his Kickstarter. I'm considering open-sourcing the Unity code.

**2024–present: AI systems**

FastAPI, WebSocket/SSE streaming, multi-provider LLM orchestration, Stripe Connect marketplace economics, ElevenLabs voice synthesis, Twilio telephony, NIST-validated cryptography. [santa-claus-is-calling](https://github.com/jordicor/santa-claus-is-calling): real-time AI phone calls where Santa calls children (Twilio + Deepgram + LLM + ElevenLabs, 4-service audio orchestration). [webcam-trng](https://github.com/jordicor/webcam-trng): true random number generator inspired by Cloudflare's LavaRand, validated with NIST SP800-90B (0.8487 bits/bit minimum entropy).

## The other half

Code is only half the picture. Acerting Art Inc. is my audiovisual wellness content company: 433K+ YouTube subscribers, 52.4M+ views, 318M+ streaming plays across Apple Music, Spotify, Amazon Music and 20+ platforms, distributed in 190+ countries. Professional field recordings in Switzerland, Japan, the UK, Tunisia, and Florida.

Technology was always the enabler. During my YouTube consulting years (2013–2019, advising 30+ channels), the work was deeply technical: SEO analysis, positioning, analytics, content optimization. The content creation itself is technical. The AI systems serve both sides. Art and technology have always been the same thread for me.

For the full story: [acerting.com](https://acerting.com)

## Tech stack

| Category | Technologies |
|---|---|
| **Languages** | Python, PHP, JavaScript, C, Objective-C, VBScript, COBOL, QuickBASIC, POV-Ray SDL, DIV, Sinclair BASIC, C# (Unity) |
| **AI/ML** | OpenAI, Anthropic, Google Gemini, xAI, OpenRouter, ElevenLabs, Deepgram, InsightFace, Whisper, DBSCAN |
| **Backend** | FastAPI, Flask, Symfony, Nginx, Redis, SQLite, MySQL, Neo4j |
| **Security** | CVE publication, MSRC recognition, ethical hacking, AES/PBKDF2, Cloudflare WAF, JWT |
| **Infrastructure** | Docker, Synology RAID 6 (192TB), Cloudflare CDN, Stripe Connect, Twilio, WebSocket/SSE |

## Connecting the dots

- [CwT-ScripT](https://github.com/jordicor/CwT-ScripT) (IRC chat scripting, 2001) → [Aurvek](https://github.com/jordicor/Aurvek) (AI chat platform, 2024): 23 years of real-time messaging systems.
- [security-research-archive](https://github.com/jordicor/security-research-archive) (CVE researcher, 2004) → Aurvek's dual watchdog (AI safety system, 2024): adversarial thinking, different targets.
- [HITS](https://github.com/jordicor/HITS) (DOS fighting game, 2000) → sponsoring professional Tekken players (2022): the loop closes after 22 years.

Each era built on the previous one. Nothing was wasted.

---

[acerting.com](https://acerting.com) · [jordicor.com](https://jordicor.com) · [@jordicor](https://twitter.com/jordicor)
