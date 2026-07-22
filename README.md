# 🏭 Saleem's AI Factory: AI Specialists Ready to Transform Your Workflow

> **A complete AI factory at your fingertips** — From frontend wizards to security auditors, from growth hackers to reality checkers. Each AI specialist is a finely-tuned expert with personality, processes, and proven deliverables.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)

---

## 🚀 What Is This?

**Saleem's AI Factory** is a growing collection of meticulously crafted AI specialist personalities. Each specialist is:

- **🎯 Specialized**: Deep expertise in their domain (not generic prompt templates)
- **🧠 Personality-Driven**: Unique voice, communication style, and approach
- **📋 Deliverable-Focused**: Real code, processes, and measurable outcomes
- **✅ Production-Ready**: Battle-tested workflows and success metrics

**Think of it as**: Assembling your dream team, except they're AI specialists who never sleep, never complain, and always deliver.

---

## ⚡ Quick Start

### Option 1: Install via Scripts

```bash
# First convert all agent files to your tool's format
./scripts/convert.sh

# Install interactively (auto-detects your installed tools)
./scripts/install.sh

# Or target a specific tool directly
./scripts/install.sh --tool claude-code
./scripts/install.sh --tool cursor
./scripts/install.sh --tool opencode
./scripts/install.sh --tool gemini-cli
./scripts/install.sh --tool copilot
```

### Option 2: Install Only What You Need

```bash
./scripts/install.sh                                    # interactive wizard: pick tools + teams
./scripts/install.sh --tool claude-code --division engineering,security
./scripts/install.sh --tool cursor --agent frontend-developer,ui-designer
./scripts/install.sh --list teams                       # see every team + agent count
./scripts/install.sh --tool opencode --division engineering --dry-run
```

### Option 3: Use as Reference

Each agent file contains:
- Identity & personality traits
- Core mission & workflows
- Technical deliverables with code examples
- Success metrics & communication style

Browse the specialists below and copy/adapt the ones you need!

> **OpenCode note:** OpenCode's runtime currently registers only ~119 agents and silently drops the rest ([upstream bug](https://github.com/anomalyco/opencode/issues/27988)). Installing a subset with `--division` keeps you under that limit. The installer warns you when a selection would exceed it.

---

## 🎨 The AI Factory Roster

### 💻 Engineering Division

Building the future, one commit at a time.

| Specialist | Specialty | When to Use |
|---|---|---|
| 🎨 [Frontend Developer](engineering/engineering-frontend-developer.md) | React/Vue/Angular, UI implementation, performance | Modern web apps, pixel-perfect UIs, Core Web Vitals optimization |
| 🏗️ [Backend Architect](engineering/engineering-backend-architect.md) | API design, database architecture, scalability | Server-side systems, microservices, cloud infrastructure |
| 📱 [Mobile App Builder](engineering/engineering-mobile-app-builder.md) | iOS/Android, React Native, Flutter | Native and cross-platform mobile applications |
| 🤖 [AI Engineer](engineering/engineering-ai-engineer.md) | ML models, deployment, AI integration | Machine learning features, data pipelines, AI-powered apps |
| 🚀 [DevOps Automator](engineering/engineering-devops-automator.md) | CI/CD, infrastructure automation, cloud ops | Pipeline development, deployment automation, monitoring |
| 🌐 [Network Engineer](engineering/engineering-network-engineer.md) | Cisco IOS/IOS-XE, Juniper Junos, Palo Alto PAN-OS | Router/switch/firewall configuration, BGP/OSPF, ACLs, show-output troubleshooting |
| ⚡ [Rapid Prototyper](engineering/engineering-rapid-prototyper.md) | Fast POC development, MVPs | Quick proof-of-concepts, hackathon projects, fast iteration |
| 💎 [Senior Developer](engineering/engineering-senior-developer.md) | Laravel/Livewire, advanced patterns | Complex implementations, architecture decisions |
| 🔧 [Filament Optimization Specialist](engineering/engineering-filament-optimization-specialist.md) | Filament PHP admin UX, structural form redesign, resource optimization | Restructuring Filament resources/forms/tables for faster, cleaner admin workflows |
| ⚡ [Autonomous Optimization Architect](engineering/engineering-autonomous-optimization-architect.md) | LLM routing, cost optimization, shadow testing | Autonomous systems needing intelligent API selection and cost guardrails |
| 🔩 [Embedded Firmware Engineer](engineering/engineering-embedded-firmware-engineer.md) | Bare-metal, RTOS, ESP32/STM32/Nordic firmware | Production-grade embedded systems and IoT devices |
| 🚨 [Incident Response Commander](engineering/engineering-incident-response-commander.md) | Incident management, post-mortems, on-call | Managing production incidents and building incident readiness |
| ⛓️ [Solidity Smart Contract Engineer](engineering/engineering-solidity-smart-contract-engineer.md) | EVM contracts, gas optimization, DeFi | Secure, gas-optimized smart contracts and DeFi protocols |
| 🧭 [Codebase Onboarding Engineer](engineering/engineering-codebase-onboarding-engineer.md) | Fast developer onboarding, read-only codebase exploration, factual explanation | Helping new developers understand unfamiliar repos quickly by reading the code, tracing code paths, and stating facts about structure and behavior |
| 📚 [Technical Writer](engineering/engineering-technical-writer.md) | Developer docs, API reference, tutorials | Clear, accurate technical documentation |
| 💬 [WeChat Mini Program Developer](engineering/engineering-wechat-mini-program-developer.md) | WeChat ecosystem, Mini Programs, payment integration | Building performant apps for the WeChat ecosystem |
| 👁️ [Code Reviewer](engineering/engineering-code-reviewer.md) | Constructive code review, security, maintainability | PR reviews, code quality gates, mentoring through review |
| 🗄️ [Database Optimizer](engineering/engineering-database-optimizer.md) | Schema design, query optimization, indexing strategies | PostgreSQL/MySQL tuning, slow query debugging, migration planning |
| 🌿 [Git Workflow Master](engineering/engineering-git-workflow-master.md) | Branching strategies, conventional commits, advanced Git | Git workflow design, history cleanup, CI-friendly branch management |
| 🏛️ [Software Architect](engineering/engineering-software-architect.md) | System design, DDD, architectural patterns, trade-off analysis | Architecture decisions, domain modeling, system evolution strategy |
| 🛡️ [SRE](engineering/engineering-sre.md) | SLOs, error budgets, observability, chaos engineering | Production reliability, toil reduction, capacity planning |
| 🧬 [AI Data Remediation Engineer](engineering/engineering-ai-data-remediation-engineer.md) | Self-healing pipelines, air-gapped SLMs, semantic clustering | Fixing broken data at scale with zero data loss |
| 🔧 [Data Engineer](engineering/engineering-data-engineer.md) | Data pipelines, lakehouse architecture, ETL/ELT | Building reliable data infrastructure and warehousing |
| 🔗 [Feishu Integration Developer](engineering/engineering-feishu-integration-developer.md) | Feishu/Lark Open Platform, bots, workflows | Building integrations for the Feishu ecosystem |
| 🧱 [CMS Developer](engineering/engineering-cms-developer.md) | WordPress & Drupal themes, plugins/modules, content architecture | Code-first CMS implementation and customization |
| 📧 [Email Intelligence Engineer](engineering/engineering-email-intelligence-engineer.md) | Email parsing, MIME extraction, structured data for AI agents | Turning raw email threads into reasoning-ready context |
| 🎙️ [Voice AI Integration Engineer](engineering/engineering-voice-ai-integration-engineer.md) | Speech-to-text pipelines, Whisper, ASR, speaker diarization | End-to-end transcription pipelines, audio preprocessing, structured transcript delivery |
| 🖧 [IT Service Manager](engineering/engineering-it-service-manager.md) | ITIL 4 service management | Incident/problem/change management, SLAs, CMDB |
| 🪡 [Minimal Change Engineer](engineering/engineering-minimal-change-engineer.md) | Minimum-viable diffs | Fixing only what's asked, no scope creep |
| 📜 [OrgScript Engineer](engineering/engineering-orgscript-engineer.md) | OrgScript grammar & AST validation | Designing/parsing OrgScript business-logic definitions |
| 🧬 [Prompt Engineer](engineering/engineering-prompt-engineer.md) | LLM prompt design & optimization | Turning vague instructions into reliable AI behaviors |
| 🕸️ [Multi-Agent Systems Architect](engineering/engineering-multi-agent-systems-architect.md) | Multi-agent pipeline design & governance | Topology, context, trust, failure recovery for agent systems |
| 🛒 [Drupal Shopping Cart Engineer](engineering/engineering-drupal-shopping-cart.md) | Drupal Commerce storefronts | Catalog, payments, checkout, orders on Drupal 10/11 |
| 🛍️ [WordPress Shopping Cart Engineer](engineering/engineering-wordpress-shopping-cart.md) | WooCommerce storefronts | Catalog, payments, checkout, conversion on WordPress |
| 💳 [Payments & Billing Engineer](engineering/engineering-payments-billing-engineer.md) | PSP integration, idempotent payment flows, subscription billing | Stripe/Adyen/Braintree integrations, webhook processing, dunning, reconciliation |
| 🌍 [Internationalization Engineer](engineering/engineering-i18n-engineer.md) | ICU MessageFormat, RTL/bidi layouts, CLDR formatting, pseudo-localization | Making apps translation-ready, locale-aware formatting, RTL support, i18n audits |
| ⚡ [Drupal Performance Engineer](engineering/engineering-drupal-performance.md) | Drupal performance & Core Web Vitals | Caching, DB/query tuning, render pipeline, profiling high-traffic Drupal |
| ⚡ [WordPress Performance Engineer](engineering/engineering-wordpress-performance.md) | WordPress performance & Core Web Vitals | Caching, query/asset optimization, plugin tuning, profiling high-traffic WP |
| ♿ [Section 508 Accessibility Specialist](engineering/engineering-section-508-specialist.md) | US federal 508 / WCAG accessibility | ARIA, screen-reader testing, VPAT/ACR authoring, remediation |
| 🏛️ [USWDS Developer](engineering/engineering-uswds-developer.md) | US Web Design System (federal) | Accessible gov UI components & design-system patterns |
| 🔎 [Search Relevance Engineer](engineering/engineering-search-relevance-engineer.md) | Search ranking & relevance | Query understanding, embeddings, ranking/eval, relevance tuning |
| 🔐 [Identity & Access Engineer](engineering/engineering-identity-access-engineer.md) | AuthN/AuthZ & IAM | OAuth/OIDC/SAML, SSO, RBAC/ABAC, token & session security |
| 🤝 [Realtime Collaboration Engineer](engineering/engineering-realtime-collaboration-engineer.md) | Realtime sync & presence | CRDTs/OT, conflict resolution, live cursors, offline sync |
| 💻 [Desktop App Engineer](engineering/engineering-desktop-app-engineer.md) | Cross-platform desktop apps | Electron/Tauri, native integration, packaging, auto-update |
| 🚀 [Mobile Release Engineer](engineering/engineering-mobile-release-engineer.md) | Mobile release & CI/CD | App Store/Play submission, signing, staged rollout, crash triage |
| 🎬 [Video Streaming Engineer](engineering/engineering-video-streaming-engineer.md) | Video streaming & transcoding | HLS/DASH, ABR, codecs, CDN delivery, low-latency streaming |
| 💰 [FinOps Engineer](engineering/engineering-finops-engineer.md) | Cloud cost engineering | Cost allocation, rightsizing, unit economics, budget & anomaly control |
| 🧩 [WebAssembly Engineer](engineering/engineering-webassembly-engineer.md) | WebAssembly & WASI | Rust/C++→WASM, sandboxing, host bindings, performance |
| 🔌 [API Platform Engineer](engineering/engineering-api-platform-engineer.md) | API gateways & platforms | Gateway design, versioning, rate limiting, developer portals |
| 🛟 [Database Reliability Engineer](engineering/engineering-database-reliability-engineer.md) | Database reliability (DBRE) | HA/replication, automated failover, PITR backups, zero-downtime ops |
| 🛠️ [Developer Tooling Engineer](engineering/engineering-developer-tooling-engineer.md) | CLI & developer tooling | Command-line tools, internal DX, build/dev workflows |
| 📡 [IoT Fleet Engineer](engineering/engineering-iot-fleet-engineer.md) | IoT & edge fleet | Device provisioning/identity, MQTT telemetry, OTA updates |
| 🔍 [RAG Pipeline Engineer](engineering/engineering-rag-pipeline-engineer.md) | Production RAG pipelines | Chunking, retrieval quality, hybrid search, re-ranking, eval-driven iteration |
| 🗄️ [GaussDB Expert Engineer](engineering/engineering-gaussdb-expert.md) | Huawei GaussDB OLTP | Enterprise OLTP performance, HA, and migration on Huawei's GaussDB |
| 🕵️ [Privacy Engineer](engineering/engineering-privacy-engineer.md) | PII discovery, data minimization, consent enforcement, DSAR/deletion pipelines | Implementing privacy in code, right-to-be-forgotten across services, retention automation |

### 🎨 Design Division

Making it beautiful, usable, and delightful.

| Specialist | Specialty | When to Use |
|---|---|---|
| 🎯 [UI Designer](design/design-ui-designer.md) | Visual design, component libraries, design systems | Interface creation, brand consistency, component design |
| 🔍 [UX Researcher](design/design-ux-researcher.md) | User testing, behavior analysis, research | Understanding users, usability testing, design insights |
| 🏛️ [UX Architect](design/design-ux-architect.md) | Technical architecture, CSS systems, implementation | Developer-friendly foundations, implementation guidance |
| 🎭 [Brand Guardian](design/design-brand-guardian.md) | Brand identity, consistency, positioning | Brand strategy, identity development, guidelines |
| 📖 [Visual Storyteller](design/design-visual-storyteller.md) | Visual narratives, multimedia content | Compelling visual stories, brand storytelling |
| ✨ [Whimsy Injector](design/design-whimsy-injector.md) | Personality, delight, playful interactions | Adding joy, micro-interactions, Easter eggs, brand personality |
| 📷 [Image Prompt Engineer](design/design-image-prompt-engineer.md) | AI image generation prompts, photography | Photography prompts for Midjourney, DALL-E, Stable Diffusion |
| 🌈 [Inclusive Visuals Specialist](design/design-inclusive-visuals-specialist.md) | Representation, bias mitigation, authentic imagery | Generating culturally accurate AI images and video |
| 🎭 [Persona Walkthrough Specialist](design/design-persona-walkthrough.md) | Persona-driven cognitive walkthroughs | Simulating user reactions and friction at each scroll position |

### 💰 Paid Media Division

Turning ad spend into measurable business outcomes.

| Specialist | Specialty | When to Use |
|---|---|---|
| 💰 [PPC Campaign Strategist](paid-media/paid-media-ppc-strategist.md) | Google/Microsoft/Amazon Ads, account architecture, bidding | Account buildouts, budget allocation, scaling, performance diagnosis |
| 🔍 [Search Query Analyst](paid-media/paid-media-search-query-analyst.md) | Search term analysis, negative keywords, intent mapping | Query audits, wasted spend elimination, keyword discovery |
| 📋 [Paid Media Auditor](paid-media/paid-media-auditor.md) | 200+ point account audits, competitive analysis | Account takeovers, quarterly reviews, competitive pitches |
| 📡 [Tracking & Measurement Specialist](paid-media/paid-media-tracking-specialist.md) | GTM, GA4, conversion tracking, CAPI | New implementations, tracking audits, platform migrations |
| ✍️ [Ad Creative Strategist](paid-media/paid-media-creative-strategist.md) | RSA copy, Meta creative, Performance Max assets | Creative launches, testing programs, ad fatigue refreshes |
| 📺 [Programmatic & Display Buyer](paid-media/paid-media-programmatic-buyer.md) | GDN, DSPs, partner media, ABM display | Display planning, partner outreach, ABM programs |
| 📱 [Paid Social Strategist](paid-media/paid-media-paid-social-strategist.md) | Meta, LinkedIn, TikTok, cross-platform social | Social ad programs, platform selection, audience strategy |

### 💼 Sales Division

Turning pipeline into revenue through craft, not CRM busywork.

| Specialist | Specialty | When to Use |
|---|---|---|
| 🎯 [Outbound Strategist](sales/sales-outbound-strategist.md) | Signal-based prospecting, multi-channel sequences, ICP targeting | Building pipeline through research-driven outreach, not volume |
| 🔍 [Discovery Coach](sales/sales-discovery-coach.md) | SPIN, Gap Selling, Sandler — question design and call structure | Preparing for discovery calls, qualifying opportunities, coaching reps |
| ♟️ [Deal Strategist](sales/sales-deal-strategist.md) | MEDDPICC qualification, competitive positioning, win planning | Scoring deals, exposing pipeline risk, building win strategies |
| 🛠️ [Sales Engineer](sales/sales-engineer.md) | Technical demos, POC scoping, competitive battlecards | Pre-sales technical wins, demo prep, competitive positioning |
| 🏹 [Proposal Strategist](sales/sales-proposal-strategist.md) | RFP response, win themes, narrative structure | Writing proposals that persuade, not just comply |
| 📊 [Pipeline Analyst](sales/sales-pipeline-analyst.md) | Forecasting, pipeline health, deal velocity, RevOps | Pipeline reviews, forecast accuracy, revenue operations |
| 🗺️ [Account Strategist](sales/sales-account-strategist.md) | Land-and-expand, QBRs, stakeholder mapping | Post-sale expansion, account planning, NRR growth |
| 🏋️ [Sales Coach](sales/sales-coach.md) | Rep development, call coaching, pipeline review facilitation | Making every rep and every deal better through structured coaching |
| 🧲 [Offer & Lead Gen Strategist](sales/sales-offer-lead-gen-strategist.md) | Offers & lead magnets | Top-of-funnel offer construction and lead gen |

### 📢 Marketing Division

Growing your audience, one authentic interaction at a time.

| Specialist | Specialty | When to Use |
|---|---|---|
| 🚀 [Growth Hacker](marketing/marketing-growth-hacker.md) | Rapid user acquisition, viral loops, experiments | Explosive growth, user acquisition, conversion optimization |
| 📝 [Content Creator](marketing/marketing-content-creator.md) | Multi-platform content, editorial calendars | Content strategy, copywriting, brand storytelling |
| 🐦 [Twitter Engager](marketing/marketing-twitter-engager.md) | Real-time engagement, thought leadership | Twitter strategy, LinkedIn campaigns, professional social |
| 🛰️ [X/Twitter Intelligence Analyst](marketing/marketing-x-twitter-intelligence-analyst.md) | Social listening, trend detection, account monitoring | Brand risk, competitor, and audience intelligence on X/Twitter |
| 📱 [TikTok Strategist](marketing/marketing-tiktok-strategist.md) | Viral content, algorithm optimization | TikTok growth, viral content, Gen Z/Millennial audience |
| 📸 [Instagram Curator](marketing/marketing-instagram-curator.md) | Visual storytelling, community building | Instagram strategy, aesthetic development, visual content |
| 🤝 [Reddit Community Builder](marketing/marketing-reddit-community-builder.md) | Authentic engagement, value-driven content | Reddit strategy, community trust, authentic marketing |
| 📱 [App Store Optimizer](marketing/marketing-app-store-optimizer.md) | ASO, conversion optimization, discoverability | App marketing, store optimization, app growth |
| 🌐 [Social Media Strategist](marketing/marketing-social-media-strategist.md) | Cross-platform strategy, campaigns | Overall social strategy, multi-platform campaigns |
| 📕 [Xiaohongshu Specialist](marketing/marketing-xiaohongshu-specialist.md) | Lifestyle content, trend-driven strategy | Xiaohongshu growth, aesthetic storytelling, Gen Z audience |
| 💬 [WeChat Official Account Manager](marketing/marketing-wechat-official-account.md) | Subscriber engagement, content marketing | WeChat OA strategy, community building, conversion optimization |
| 🧠 [Zhihu Strategist](marketing/marketing-zhihu-strategist.md) | Thought leadership, knowledge-driven engagement | Zhihu authority building, Q&A strategy, lead generation |
| 🇨🇳 [Baidu SEO Specialist](marketing/marketing-baidu-seo-specialist.md) | Baidu optimization, China SEO, ICP compliance | Ranking in Baidu and reaching China's search market |
| 🎬 [Bilibili Content Strategist](marketing/marketing-bilibili-content-strategist.md) | B站 algorithm, danmaku culture, UP主 growth | Building audiences on Bilibili with community-first content |
| 🎠 [Carousel Growth Engine](marketing/marketing-carousel-growth-engine.md) | TikTok/Instagram carousels, autonomous publishing | Generating and publishing viral carousel content |
| 💼 [LinkedIn Content Creator](marketing/marketing-linkedin-content-creator.md) | Personal branding, thought leadership, professional content | LinkedIn growth, professional audience building, B2B content |
| 🛒 [China E-Commerce Operator](marketing/marketing-china-ecommerce-operator.md) | Taobao, Tmall, Pinduoduo, live commerce | Running multi-platform e-commerce in China |
| 🎥 [Kuaishou Strategist](marketing/marketing-kuaishou-strategist.md) | Kuaishou, 老铁 community, grassroots growth | Building authentic audiences in lower-tier markets |
| 🔍 [SEO Specialist](marketing/marketing-seo-specialist.md) | Technical SEO, content strategy, link building | Driving sustainable organic search growth |
| 📘 [Book Co-Author](marketing/marketing-book-co-author.md) | Thought-leadership books, ghostwriting, publishing | Strategic book collaboration for founders and experts |
| 🌏 [Cross-Border E-Commerce Specialist](marketing/marketing-cross-border-ecommerce.md) | Amazon, Shopee, Lazada, cross-border fulfillment | Full-funnel cross-border e-commerce strategy |
| 🎵 [Douyin Strategist](marketing/marketing-douyin-strategist.md) | Douyin platform, short-video marketing, algorithm | Growing audiences on China's leading short-video platform |
| 🎙️ [Livestream Commerce Coach](marketing/marketing-livestream-commerce-coach.md) | Host training, live room optimization, conversion | Building high-performing livestream e-commerce operations |
| 🎧 [Podcast Strategist](marketing/marketing-podcast-strategist.md) | Podcast content strategy, platform optimization | Chinese podcast market strategy and operations |
| 🔒 [Private Domain Operator](marketing/marketing-private-domain-operator.md) | WeCom, private traffic, community operations | Building enterprise WeChat private domain ecosystems |
| 🎬 [Short-Video Editing Coach](marketing/marketing-short-video-editing-coach.md) | Post-production, editing workflows, platform specs | Hands-on short-video editing training and optimization |
| 🔥 [Weibo Strategist](marketing/marketing-weibo-strategist.md) | Sina Weibo, trending topics, fan engagement | Full-spectrum Weibo operations and growth |
| 🎙️ [Global Podcast Strategist](marketing/marketing-global-podcast-strategist.md) | Show positioning, audience growth, monetisation | Podcast launch, platform algorithms, sponsorship, community building |
| 🔮 [AI Citation Strategist](marketing/marketing-ai-citation-strategist.md) | AEO/GEO, AI recommendation visibility, citation auditing | Improving brand visibility across ChatGPT, Claude, Gemini, Perplexity |
| 🇨🇳 [China Market Localization Strategist](marketing/marketing-china-market-localization-strategist.md) | Full-stack China market localization, Douyin/Xiaohongshu/WeChat GTM | Turning trend signals into executable China go-to-market strategies |
| 🎬 [Video Optimization Specialist](marketing/marketing-video-optimization-specialist.md) | YouTube algorithm strategy, chaptering, thumbnail concepts | YouTube channel growth, video SEO, audience retention optimization |
| 🏗️ [AEO Foundations Architect](marketing/marketing-aeo-foundations.md) | AI Engine Optimization infrastructure | llms.txt, AI-aware robots.txt, agent discovery files |
| 🤖 [Agentic Search Optimizer](marketing/marketing-agentic-search-optimizer.md) | WebMCP & agentic task completion | Making sites usable by AI browsing agents |
| 📧 [Email Marketing Strategist](marketing/marketing-email-strategist.md) | Lifecycle email & deliverability | CRM campaigns, automation, segmentation |
| 📡 [Multi-Platform Publisher](marketing/marketing-multi-platform-publisher.md) | One-click Chinese multi-platform publishing | Routing one article to 知乎/小红书/CSDN/B站/公众号/掘金 |
| 📣 [PR & Communications Manager](marketing/marketing-pr-communications-manager.md) | PR, media relations & crisis comms | Press releases, thought leadership, reputation |

### 📊 Product Division

Building the right thing at the right time.

| Specialist | Specialty | When to Use |
|---|---|---|
| 🎯 [Sprint Prioritizer](product/product-sprint-prioritizer.md) | Agile planning, feature prioritization | Sprint planning, resource allocation, backlog management |
| 🔍 [Trend Researcher](product/product-trend-researcher.md) | Market intelligence, competitive analysis | Market research, opportunity assessment, trend identification |
| 💬 [Feedback Synthesizer](product/product-feedback-synthesizer.md) | User feedback analysis, insights extraction | Feedback analysis, user insights, product priorities |
| 🧠 [Behavioral Nudge Engine](product/product-behavioral-nudge-engine.md) | Behavioral psychology, nudge design, engagement | Maximizing user motivation through behavioral science |
| 🧭 [Product Manager](product/product-manager.md) | Full lifecycle product ownership | Discovery, PRDs, roadmap planning, GTM, outcome measurement |

### 🎬 Project Management Division

Keeping the trains running on time (and under budget).

| Specialist | Specialty | When to Use |
|---|---|---|
| 🎬 [Studio Producer](project-management/project-management-studio-producer.md) | High-level orchestration, portfolio management | Multi-project oversight, strategic alignment, resource allocation |
| 🐑 [Project Shepherd](project-management/project-management-project-shepherd.md) | Cross-functional coordination, timeline management | End-to-end project coordination, stakeholder management |
| ⚙️ [Studio Operations](project-management/project-management-studio-operations.md) | Day-to-day efficiency, process optimization | Operational excellence, team support, productivity |
| 🧪 [Experiment Tracker](project-management/project-management-experiment-tracker.md) | A/B tests, hypothesis validation | Experiment management, data-driven decisions, testing |
| 👔 [Senior Project Manager](project-management/project-manager-senior.md) | Realistic scoping, task conversion | Converting specs to tasks, scope management |
| 📋 [Jira Workflow Steward](project-management/project-management-jira-workflow-steward.md) | Git workflow, branch strategy, traceability | Enforcing Jira-linked Git discipline and delivery |
| 📋 [Meeting Notes Specialist](project-management/project-management-meeting-notes-specialist.md) | Structured meeting summaries | Extracting decisions, action items, open questions |

### 🧪 Testing Division

Breaking things so users don't have to.

| Specialist | Specialty | When to Use |
|---|---|---|
| 📸 [Evidence Collector](testing/testing-evidence-collector.md) | Screenshot-based QA, visual proof | UI testing, visual verification, bug documentation |
| 🔍 [Reality Checker](testing/testing-reality-checker.md) | Evidence-based certification, quality gates | Production readiness, quality approval, release certification |
| 📊 [Test Results Analyzer](testing/testing-test-results-analyzer.md) | Test evaluation, metrics analysis | Test output analysis, quality insights, coverage reporting |
| ⚡ [Performance Benchmarker](testing/testing-performance-benchmarker.md) | Performance testing, optimization | Speed testing, load testing, performance tuning |
| 🔌 [API Tester](testing/testing-api-tester.md) | API validation, integration testing | API testing, endpoint verification, integration QA |
| 🛠️ [Tool Evaluator](testing/testing-tool-evaluator.md) | Technology assessment, tool selection | Evaluating tools, software recommendations, tech decisions |
| 🔄 [Workflow Optimizer](testing/testing-workflow-optimizer.md) | Process analysis, workflow improvement | Process optimization, efficiency gains, automation opportunities |
| ♿ [Accessibility Auditor](testing/testing-accessibility-auditor.md) | WCAG auditing, assistive technology testing | Accessibility compliance, screen reader testing, inclusive design verification |
| 🎭 [Test Automation Engineer](testing/testing-test-automation-engineer.md) | Playwright/Cypress E2E, flake elimination, CI parallelization | Browser test suites, deterministic pipelines, trace-driven failure debugging |

### 🔒 Security Division

Defending the stack — from secure-by-design architecture to breach response.

| Specialist | Specialty | When to Use |
|---|---|---|
| 🛡️ [Security Architect](security/security-architect.md) | Threat modeling, secure-by-design, trust boundaries | System security models, architecture reviews, defense-in-depth |
| 🔐 [Application Security Engineer](security/security-appsec-engineer.md) | SDLC security, SAST/DAST, secure code review | Securing the dev lifecycle, code-level vulnerabilities |
| 🗡️ [Penetration Tester](security/security-penetration-tester.md) | Authorized pentests, red team ops, exploitation | Finding exploitable weaknesses before attackers do |
| ☁️ [Cloud Security Architect](security/security-cloud-security-architect.md) | Zero trust, cloud-native defense-in-depth | Securing cloud infrastructure and architectures |
| 🚨 [Incident Responder](security/security-incident-responder.md) | DFIR, breach investigation, threat containment | Active breaches, forensics, crisis response |
| 🔍 [Threat Intelligence Analyst](security/security-threat-intelligence-analyst.md) | Adversary tracking, campaign mapping, ATT&CK | Understanding who's attacking and how |
| 🎯 [Threat Detection Engineer](security/security-threat-detection-engineer.md) | SIEM rules, threat hunting, ATT&CK mapping | Building detection layers and threat hunting |
| 🛡️ [Senior SecOps Engineer](security/security-senior-secops.md) | Secrets scanning, secure-by-default submissions | Defensive code-level security on every change |
| 📋 [Compliance Auditor](security/security-compliance-auditor.md) | SOC 2, ISO 27001, HIPAA, PCI-DSS | Guiding organizations through compliance certification |
| 🛡️ [Blockchain Security Auditor](security/security-blockchain-security-auditor.md) | Smart contract audits, exploit analysis | Finding vulnerabilities in contracts before deployment |
| 🔎 [AI-Generated Code Security Auditor](security/security-ai-generated-code-auditor.md) | Security review of AI/vibe-coded apps | Hardcoded secrets, broken RLS, prompt-injection sinks |
| 🔑 [Secrets & Credential Hygiene Engineer](security/security-secrets-credential-engineer.md) | Secrets & credential lifecycle | Detection, vaulting, rotation, leak response |

### 🛟 Support Division

The backbone of the operation.

| Specialist | Specialty | When to Use |
|---|---|---|
| 💬 [Support Responder](support/support-support-responder.md) | Customer service, issue resolution | Customer support, user experience, support operations |
| 📊 [Analytics Reporter](support/support-analytics-reporter.md) | Data analysis, dashboards, insights | Business intelligence, KPI tracking, data visualization |
| 💰 [Finance Tracker](support/support-finance-tracker.md) | Financial planning, budget management | Financial analysis, cash flow, business performance |
| 🏗️ [Infrastructure Maintainer](support/support-infrastructure-maintainer.md) | System reliability, performance optimization | Infrastructure management, system operations, monitoring |
| ⚖️ [Legal Compliance Checker](support/support-legal-compliance-checker.md) | Compliance, regulations, legal review | Legal compliance, regulatory requirements, risk management |
| 📑 [Executive Summary Generator](support/support-executive-summary-generator.md) | C-suite communication, strategic summaries | Executive reporting, strategic communication, decision support |

### 🥽 Spatial Computing Division

Building the immersive future.

| Specialist | Specialty | When to Use |
|---|---|---|
| 🏗️ [XR Interface Architect](spatial-computing/xr-interface-architect.md) | Spatial interaction design, immersive UX | AR/VR/XR interface design, spatial computing UX |
| 💻 [macOS Spatial/Metal Engineer](spatial-computing/macos-spatial-metal-engineer.md) | Swift, Metal, high-performance 3D | macOS spatial computing, Vision Pro native apps |
| 🌐 [XR Immersive Developer](spatial-computing/xr-immersive-developer.md) | WebXR, browser-based AR/VR | Browser-based immersive experiences, WebXR apps |
| 🎮 [XR Cockpit Interaction Specialist](spatial-computing/xr-cockpit-interaction-specialist.md) | Cockpit-based controls, immersive systems | Cockpit control systems, immersive control interfaces |
| 🍎 [visionOS Spatial Engineer](spatial-computing/visionos-spatial-engineer.md) | Apple Vision Pro development | Vision Pro apps, spatial computing experiences |
| 🔌 [Terminal Integration Specialist](spatial-computing/terminal-integration-specialist.md) | Terminal integration, command-line tools | CLI tools, terminal workflows, developer tools |

### 🎯 Specialized Division

The unique specialists who don't fit in a box.

| Specialist | Specialty | When to Use |
|---|---|---|
| 🎭 [Agents Orchestrator](specialized/agents-orchestrator.md) | Multi-agent coordination, workflow management | Complex projects requiring multiple agent coordination |
| 🔍 [LSP/Index Engineer](specialized/lsp-index-engineer.md) | Language Server Protocol, code intelligence | Code intelligence systems, LSP implementation, semantic indexing |
| 📥 [Sales Data Extraction Agent](specialized/sales-data-extraction-agent.md) | Excel monitoring, sales metric extraction | Sales data ingestion, MTD/YTD/Year End metrics |
| 📈 [Data Consolidation Agent](specialized/data-consolidation-agent.md) | Sales data aggregation, dashboard reports | Territory summaries, rep performance, pipeline snapshots |
| 📬 [Report Distribution Agent](specialized/report-distribution-agent.md) | Automated report delivery | Territory-based report distribution, scheduled sends |
| 🔐 [Agentic Identity & Trust Architect](specialized/agentic-identity-trust.md) | Agent identity, authentication, trust verification | Multi-agent identity systems, agent authorization, audit trails |
| 🔗 [Identity Graph Operator](specialized/identity-graph-operator.md) | Shared identity resolution for multi-agent systems | Entity deduplication, merge proposals, cross-agent identity consistency |
| 💸 [Accounts Payable Agent](specialized/accounts-payable-agent.md) | Payment processing, vendor management, audit | Autonomous payment execution across crypto, fiat, stablecoins |
| 🌍 [Cultural Intelligence Strategist](specialized/specialized-cultural-intelligence-strategist.md) | Global UX, representation, cultural exclusion | Ensuring software resonates across cultures |
| 🗣️ [Developer Advocate](specialized/specialized-developer-advocate.md) | Community building, DX, developer content | Bridging product and developer community |
| 🔬 [Model QA Specialist](specialized/specialized-model-qa.md) | ML audits, feature analysis, interpretability | End-to-end QA for machine learning models |
| 🗃️ [ZK Steward](specialized/zk-steward.md) | Knowledge management, Zettelkasten, notes | Building connected, validated knowledge bases |
| 🔌 [MCP Builder](specialized/specialized-mcp-builder.md) | Model Context Protocol servers, AI agent tooling | Building MCP servers that extend AI agent capabilities |
| 📄 [Document Generator](specialized/specialized-document-generator.md) | PDF, PPTX, DOCX, XLSX generation from code | Professional document creation, reports, data visualization |
| ⚙️ [Automation Governance Architect](specialized/automation-governance-architect.md) | Automation governance, n8n, workflow auditing | Evaluating and governing business automations at scale |
| 📚 [Corporate Training Designer](specialized/corporate-training-designer.md) | Enterprise training, curriculum development | Designing training systems and learning programs |
| 🌱 [Personal Growth Mentor](specialized/personal-growth-mentor.md) | Goal clarity, habit systems, accountability, life strategy | Cross-domain personal development without motivational fluff |
| 🏛️ [Government Digital Presales Consultant](specialized/government-digital-presales-consultant.md) | China ToG presales, digital transformation | Government digital transformation proposals and bids |
| ⚕️ [Healthcare Marketing Compliance](specialized/healthcare-marketing-compliance.md) | China healthcare advertising compliance | Healthcare marketing regulatory compliance |
| 🎯 [Recruitment Specialist](specialized/recruitment-specialist.md) | Talent acquisition, recruiting operations | Recruitment strategy, sourcing, and hiring processes |
| 🎓 [Study Abroad Advisor](specialized/study-abroad-advisor.md) | International education, application planning | Study abroad planning across US, UK, Canada, Australia |
| 🔗 [Supply Chain Strategist](specialized/supply-chain-strategist.md) | Supply chain management, procurement strategy | Supply chain optimization and procurement planning |
| 🗺️ [Workflow Architect](specialized/specialized-workflow-architect.md) | Workflow discovery, mapping, and specification | Mapping every path through a system before code is written |
| ☁️ [Salesforce Architect](specialized/specialized-salesforce-architect.md) | Multi-cloud Salesforce design, governor limits, integrations | Enterprise Salesforce architecture, org strategy, deployment pipelines |
| 🇫🇷 [French Consulting Market Navigator](specialized/specialized-french-consulting-market.md) | ESN/SI ecosystem, portage salarial, rate positioning | Freelance consulting in the French IT market |
| 🇰🇷 [Korean Business Navigator](specialized/specialized-korean-business-navigator.md) | Korean business culture, 품의 process, relationship mechanics | Foreign professionals navigating Korean business relationships |
| 🏗️ [Civil Engineer](specialized/specialized-civil-engineer.md) | Structural analysis, geotechnical design, global building codes | Multi-standard structural engineering across Eurocode, ACI, AISC, and more |
| 🎧 [Customer Service](specialized/customer-service.md) | Omnichannel support, complaint handling, retention, escalation | Any industry customer support — retail, SaaS, hospitality, finance, logistics |
| 🏥 [Healthcare Customer Service](specialized/healthcare-customer-service.md) | HIPAA-aware patient support, billing, insurance, emergency routing | Healthcare organizations needing compliant, empathetic patient support |
| 🏨 [Hospitality Guest Services](specialized/hospitality-guest-services.md) | Reservations, concierge, complaint recovery, loyalty, events | Hotels, resorts, restaurants, and event venues |
| 🤝 [HR Onboarding](specialized/hr-onboarding.md) | Pre-boarding, compliance, benefits enrollment, 30-60-90 day plans | Any company onboarding new hires — from startups to enterprise |
| 🌐 [Language Translator](specialized/language-translator.md) | Spanish ↔ English translation, dialect awareness, cultural context | Travel, business, medical, and legal translation needs |
| ⏱️ [Legal Billing & Time Tracking](specialized/legal-billing-time-tracking.md) | Time capture, billing narratives, IOLTA compliance, collections | Law firms maximizing revenue recovery and billing accuracy |
| 📋 [Legal Client Intake](specialized/legal-client-intake.md) | Prospect qualification, conflict screening, consultation scheduling | Law firms converting inquiries into retained clients |
| ⚖️ [Legal Document Review](specialized/legal-document-review.md) | Contract review, risk flagging, version comparison, compliance | Attorney-ready first-pass review across any practice area |
| 🏦 [Loan Officer Assistant](specialized/loan-officer-assistant.md) | Borrower intake, TRID compliance, pipeline tracking, closing coordination | Mortgage and consumer lending teams |
| 🏠 [Real Estate Buyer & Seller](specialized/real-estate-buyer-seller.md) | Buyer/seller representation, offers, transaction coordination | Residential and investment real estate transactions |
| 🛒 [Retail Customer Returns](specialized/retail-customer-returns.md) | Return processing, fraud prevention, exchanges, vendor returns | Brick-and-mortar, e-commerce, and omnichannel retail |
| ♟️ [Business Strategist](specialized/business-strategist.md) | Management-consulting strategy | Competitive analysis, market entry, growth planning |
| 🔄 [Change Management Consultant](specialized/change-management-consultant.md) | ADKAR/Kotter/Prosci change | Guiding orgs through transformation & adoption |
| 🧭 [Chief of Staff](specialized/specialized-chief-of-staff.md) | Executive coordination | Filtering noise, owning processes, routing decisions |
| 🌟 [Customer Success Manager](specialized/customer-success-manager.md) | Onboarding, health & retention | QBRs, churn prevention, renewals & expansion |
| 📝 [Grant Writer](specialized/grant-writer.md) | Grant proposals & funding | LOIs, proposals, budgets for nonprofits/research |
| 🏥 [Medical Billing & Coding Specialist](specialized/medical-billing-coding-specialist.md) | ICD-10/CPT/HCPCS & revenue cycle | Claims, denial management, RCM optimization |
| 💰 [Pricing Analyst](specialized/specialized-pricing-analyst.md) | Pricing models & margin optimization | Competitor/cost analysis, value-based pricing |
| 💼 [Chief Financial Officer](specialized/chief-financial-officer.md) | Capital allocation & financial strategy | Treasury, FP&A, M&A finance, investor & board reporting |
| 🌱 [ESG & Sustainability Officer](specialized/esg-sustainability-officer.md) | ESG programs & disclosure | Sustainability strategy, decarbonization, reporting |
| 🔐 [Data Privacy Officer](specialized/data-privacy-officer.md) | GDPR/CCPA privacy compliance | Data mapping, DPIAs, consent, breach response |
| ⚙️ [Operations Manager](specialized/operations-manager.md) | Lean/Six Sigma operations | Process mapping, capacity planning, KPI governance |
| 🤝 [M&A Integration Manager](specialized/ma-integration-manager.md) | Post-merger integration | Day 1/100-day plans, synergy tracking, TSA management |
| 🧠 [Organizational Psychologist](specialized/organizational-psychologist.md) | Team dynamics & culture health | Psychological safety, burnout risk, high-performing teams |
| ⚔️ [Strategy Duel Agent](specialized/specialized-strategy-duel-agent.md) | Game theory & the 36 stratagems | Turn-based strategy duels, adversarial scenario simulation |
| 🛡️ [FedRAMP & RMF Compliance Engineer](specialized/specialized-fedramp-rmf-compliance.md) | Federal cloud authorization (ATO) | NIST 800-53, FedRAMP Rev5/20x, SSP/POA&M, ConMon, OSCAL |
| 🏺 [Codebase Archaeologist](specialized/specialized-codebase-archaeologist.md) | Multi-tool codebase drift audits | Detecting silent drift across Claude/Cursor/Copilot/Windsurf edits |
| 🧾 [Resume Tailor](specialized/resume-tailor.md) | Candidate-side resume optimization | JD mapping, ATS keyword alignment, experience-to-requirement matching |
| 🧡 [Aging Parent Care Companion](specialized/healthcare-aging-parent-care-companion.md) | Family caregiver decision-support | Appointment/medication coordination, care-team comms, caregiver wellbeing (HIPAA-aligned) |

### 💵 Finance Division

Accounting, financial analysis, tax strategy, and investment research specialists.

| Specialist | Specialty | When to Use |
|---|---|---|
| 📒 [Bookkeeper & Controller](finance/finance-bookkeeper-controller.md) | Month-end close, reconciliation, GAAP compliance, internal controls | Day-to-day accounting operations, audit readiness, financial record-keeping |
| 📊 [Financial Analyst](finance/finance-financial-analyst.md) | Financial modeling, forecasting, scenario analysis, decision support | Three-statement models, variance analysis, data-driven business intelligence |
| 📈 [FP&A Analyst](finance/finance-fpa-analyst.md) | Budgeting, rolling forecasts, variance analysis, business reviews | Annual operating plans, monthly business reviews, strategic resource allocation |
| 🔍 [Investment Researcher](finance/finance-investment-researcher.md) | Due diligence, portfolio analysis, asset valuation, equity research | Investment thesis development, risk assessment, market research |
| 🏛️ [Tax Strategist](finance/finance-tax-strategist.md) | Tax optimization, multi-jurisdictional compliance, transfer pricing | Entity structuring, ETR analysis, audit defense, strategic tax planning |

### 🎮 Game Development Division

Building worlds, systems, and experiences across every major engine.

#### Cross-Engine Specialists (Engine-Agnostic)

| Specialist | Specialty | When to Use |
|---|---|---|
| 🎯 [Game Designer](game-development/game-designer.md) | Systems design, GDD authorship, economy balancing, gameplay loops | Designing game mechanics, progression systems, writing design documents |
| 🗺️ [Level Designer](game-development/level-designer.md) | Layout theory, pacing, encounter design, environmental storytelling | Building levels, designing encounter flow, spatial narrative |
| 🎨 [Technical Artist](game-development/technical-artist.md) | Shaders, VFX, LOD pipeline, art-to-engine optimization | Bridging art and engineering, shader authoring, performance-safe asset pipelines |
| 🔊 [Game Audio Engineer](game-development/game-audio-engineer.md) | FMOD/Wwise, adaptive music, spatial audio, audio budgets | Interactive audio systems, dynamic music, audio performance |
| 📖 [Narrative Designer](game-development/narrative-designer.md) | Story systems, branching dialogue, lore architecture | Writing branching narratives, implementing dialogue systems, world lore |

#### Unity

| Specialist | Specialty | When to Use |
|---|---|---|
| 🏗️ [Unity Architect](game-development/unity/unity-architect.md) | ScriptableObjects, data-driven modularity, DOTS/ECS | Large-scale Unity projects, data-driven system design, ECS performance work |
| ✨ [Unity Shader Graph Artist](game-development/unity/unity-shader-graph-artist.md) | Shader Graph, HLSL, URP/HDRP, Renderer Features | Custom Unity materials, VFX shaders, post-processing passes |
| 🌐 [Unity Multiplayer Engineer](game-development/unity/unity-multiplayer-engineer.md) | Netcode for GameObjects, Unity Relay/Lobby, server authority, prediction | Online Unity games, client prediction, Unity Gaming Services integration |
| 🛠️ [Unity Editor Tool Developer](game-development/unity/unity-editor-tool-developer.md) | EditorWindows, AssetPostprocessors, PropertyDrawers, build validation | Custom Unity Editor tooling, pipeline automation, content validation |

#### Unreal Engine

| Specialist | Specialty | When to Use |
|---|---|---|
| ⚙️ [Unreal Systems Engineer](game-development/unreal-engine/unreal-systems-engineer.md) | C++/Blueprint hybrid, GAS, Nanite constraints, memory management | Complex Unreal gameplay systems, Gameplay Ability System, engine-level C++ |
| 🎨 [Unreal Technical Artist](game-development/unreal-engine/unreal-technical-artist.md) | Material Editor, Niagara, PCG, Substrate | Unreal materials, Niagara VFX, procedural content generation |
| 🌐 [Unreal Multiplayer Architect](game-development/unreal-engine/unreal-multiplayer-architect.md) | Replication, Steam/Matchmaking, dedicated servers, net debug | Unreal multiplayer games, replication, client prediction |
| 🏔️ [Unreal World Builder](game-development/unreal-engine/unreal-world-builder.md) | World Partition, HLOD, Landmass, PCG | Large open-world Unreal levels, procedural world generation |

#### Godot

| Specialist | Specialty | When to Use |
|---|---|---|
| 🎮 [Godot Gameplay Scripter](game-development/godot/godot-gameplay-scripter.md) | GDScript/C#, scene tree, signals | Godot games — mechanics, UI, player systems |
| 🌐 [Godot Multiplayer Engineer](game-development/godot/godot-multiplayer-engineer.md) | ENet/WebRTC, RPC, state sync | Godot multiplayer, dedicated servers, netcode |
| ✨ [Godot Shader Developer](game-development/godot/godot-shader-developer.md) | Godot Shader Language, VisualShaders, VFX | Custom Godot shaders, post-processing, GPU particles |

#### Roblox

| Specialist | Specialty | When to Use |
|---|---|---|
| 🏗️ [Roblox Experience Designer](game-development/roblox-studio/roblox-experience-designer.md) | Place design, game loops, monetization | Roblox game design, experience architecture |
| 🎨 [Roblox Avatar Creator](game-development/roblox-studio/roblox-avatar-creator.md) | Avatar, accessories, layered clothing | Roblox avatar customization, UGC, marketplace items |
| 💻 [Roblox Systems Scripter](game-development/roblox-studio/roblox-systems-scripter.md) | Luau, networked gameplay, DataStores | Roblox game logic, leaderboards, persistence |

#### Blender

| Specialist | Specialty | When to Use |
|---|---|---|
| 🔧 [Blender Add-on Engineer](game-development/blender/blender-addon-engineer.md) | Python, bpy, UI toolkit, addon packaging | Blender addons, procedural tools, pipeline automation |

### 🗺️ GIS Division

Mapping, spatial analysis, and location intelligence.

| Specialist | Specialty | When to Use |
|---|---|---|
| 🗺️ [GIS Analyst](gis/gis-analyst.md) | Spatial analysis, geoprocessing, map production | Day-to-day GIS analysis, cartography, data management |
| 📡 [GIS Spatial Data Engineer](gis/gis-spatial-data-engineer.md) | Data pipelines, ETL, database management | Geospatial data engineering, automation, large datasets |
| 🔬 [GIS Spatial Data Scientist](gis/gis-spatial-data-scientist.md) | Spatial statistics, ML, predictive modeling | Advanced spatial analysis, geostatistics, spatial ML |
| 🌐 [GIS Web GIS Developer](gis/gis-web-gis-developer.md) | Web maps, geospatial APIs, frontend | Web mapping applications, geospatial APIs |
| 🏗️ [GIS Solution Engineer](gis/gis-solution-engineer.md) | Enterprise GIS, architecture, implementation | End-to-end GIS solutions, technical architecture |
| 🌍 [GIS 3D Scene Developer](gis/gis-3d-scene-developer.md) | 3D scenes, digital twins, Cesium | 3D GIS, digital twin visualization, scene layers |
| 🏛️ [GIS BIM Specialist](gis/gis-bim-specialist.md) | BIM integration, IFC, infrastructure | GIS-BIM integration, infrastructure digital twins |
| 🎨 [GIS Cartography Designer](gis/gis-cartography-designer.md) | Map design, visual hierarchy, storytelling | Beautiful, publication-quality maps |
| 🚁 [GIS Drone Reality Mapping](gis/gis-drone-reality-mapping.md) | Drone imagery, orthomosaics, 3D mesh | Drone-based mapping, reality capture |
| 🤖 [GIS GeoAI ML Engineer](gis/gis-geoai-ml-engineer.md) | Deep learning for imagery, object detection | AI/ML for geospatial, feature extraction |
| ✅ [GIS QA Engineer](gis/gis-qa-engineer.md) | Data quality, validation, automation | GIS data quality assurance and testing |
| 💼 [GIS Technical Consultant](gis/gis-technical-consultant.md) | Client advisory, requirements, best practices | GIS consulting, requirements analysis, solutions advisory |

### 📚 Academic Division

Research, analysis, and scholarly rigor.

| Specialist | Specialty | When to Use |
|---|---|---|
| 🧠 [Academic Psychologist](academic/academic-psychologist.md) | Research methods, statistical analysis | Academic research design, data analysis |
| 📊 [Academic Statistician](academic/academic-statistician.md) | Statistical modeling, experimental design | Data analysis, hypothesis testing, research methodology |
| 🏛️ [Academic Historian](academic/academic-historian.md) | Historical research, archival methods | Historical analysis, archival research, scholarly writing |
| 🌍 [Academic Geographer](academic/academic-geographer.md) | Human/physical geography, spatial analysis | Geographic research, spatial humanities |
| 👥 [Academic Anthropologist](academic/academic-anthropologist.md) | Ethnography, cultural analysis | Field research, cultural analysis, ethnographic methods |
| 📖 [Academic Narratologist](academic/academic-narratologist.md) | Narrative theory, textual analysis | Literary analysis, narrative structure, storytelling theory |

### 🏥 Healthcare Division

Improving outcomes through AI-powered healthcare expertise.

| Specialist | Specialty | When to Use |
|---|---|---|
| 💊 [Healthcare Innovation Strategist](healthcare/healthcare-innovation-strategist.md) | Healthcare innovation, digital health strategy | Healthcare transformation, digital health initiatives |
| 🏛️ [Healthcare Sovereign Health Systems Agent](healthcare/healthcare-sovereign-health-systems-agent.md) | Health sovereignty, national health systems | Public health systems, health policy, sovereign capabilities |
| 🔬 [Healthcare Clinical Evidence Agent](healthcare/healthcare-clinical-evidence-agent.md) | Clinical evidence, literature review, evidence-based practice | Clinical research support, evidence synthesis |

---

## 🔧 Multi-Tool Integrations

Saleem's AI Factory supports all major AI coding tools. The `scripts/convert.sh` and `scripts/install.sh` scripts handle the conversion and installation for:

| Tool | Format | Scope |
|---|---|---|
| **Claude Code** | Identity (direct copy) | User & Project |
| **GitHub Copilot** | Identity (direct copy) | User & Project |
| **Antigravity** | SKILL.md | User & Project |
| **Gemini CLI** | Gemini Markdown | User & Project |
| **OpenCode** | OpenCode Markdown | User & Project |
| **OpenClaw** | Workspace format | User only |
| **Cursor** | .mdc rules | Project only |
| **Aider** | CONVENTIONS.md | Project only |
| **Windsurf** | .windsurfrules | Project only |
| **Qwen Code** | Qwen Markdown | User & Project |
| **ZCode** | ZCode Markdown | User & Project |
| **Kimi Code** | agent.yaml + system.md | User only |
| **Codex** | TOML format | User & Project |
| **Osaurus** | SKILL.md | User only |
| **Hermes** | Lazy-router plugin | User only |
| **Mistral Vibe** | TOML + Markdown | User & Project |

---

## 🤝 Contributing

Contributions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Creating new AI specialists
- Improving existing agents
- Adding new tool integrations
- Sharing success stories

---

## 📄 License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgments

This project is a rebranded and maintained fork of the excellent [agency-agents](https://github.com/msitarzewski/agency-agents) project by msitarzewski and the AgentLand community. The original work provided the foundation for this collection of AI specialists.

---

<div align="center">

**Saleem's AI Factory** — Built with ❤️

[Open an Issue](https://github.com/Saleem_Mo/saleems-ai-factory/issues) · [Submit a PR](https://github.com/Saleem_Mo/saleems-ai-factory/pulls)

</div>
