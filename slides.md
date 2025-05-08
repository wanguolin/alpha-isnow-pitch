---
# You can also start simply with 'default'
theme: apple-basic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Alpha is Now powered by AI
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
# class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# open graph
# seoMeta:
#  ogImage: https://cover.sli.dev
colorSchema: 'dark'

layout: intro-image-right
image: 'https://images.unsplash.com/photo-1551288049-bebda4e38f71'
---

# Alpha is Now Powered by AI

https://alpha.isnow.ai

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: two-cols
layoutClass: gap-16
---

# Table of Contents

This presentation outlines the vision, structure, and future roadmap of **alpha.isnow.ai**—a platform designed to democratize quantitative trading through content, tools, and intelligent insights.

You'll find an overview of the market problem, our solution architecture, the three core product pillars, and how we plan to scale both functionally and globally.

Whether you're a potential partner, investor, or user, this deck offers a clear look into where we are now and where we're headed next.

::right::

<Toc text-lg minDepth="1" maxDepth="2" />


---
layout: default
---

# Problem

- While Chinese-speaking users can technically access global trading tools, the lack of localized onboarding—such as structured tutorials, strategy walkthroughs, and native-language content—creates a steep entry barrier.
- Retail traders remain disconnected from systematic trading advantages like discipline, data-driven logic, and backtested confidence, widening the gap between casual investing and institutional-grade decision-making.
- Existing platforms often assume prior quant knowledge; in contrast, [Alpha is Now](https://alpha.isnow.ai) uses real academic trading strategies and verifiable backtests as an entry point—building both trust and understanding through reproducible results and educational content.

<!--
Here is another comment.
-->
---
layout: default
---

# Market Opportunity

- The global algorithmic trading market is projected to exceed $30B by 2028, driven by the rise of data access, retail participation, and AI-assisted strategy tools.
- Despite this growth, most platforms remain fragmented or overly technical—leaving a gap for accessible, educational, and end-to-end solutions.
- alpha.isnow.ai begins with content-led growth in Chinese-speaking communities, but is architected from day one for a multilingual, international audience.
- This early traction provides a practical springboard into broader markets, enabling us to test, refine, and scale globally with localized trust and technical maturity.


---
layout: default
---

# Solution

- **Trading Strategy**: Provides reproducible, backtested academic strategies and Python-based infrastructure—serving as a transparent, educational gateway into systematic trading.
- **Marketing Insights**: Surfaces AI-driven financial intelligence, such as earnings sentiment, patent activity, and executive behavior, to inform high-conviction trading ideas.
- **Dashboard**: A personalized command center combining strategies, alerts, and performance tracking—bridging the gap between fragmented tools and retail usability.

These three pillars support a bilingual platform that begins with content-driven growth in the Chinese-speaking market—leveraging WeChat, Bilibili, and X-based communities—and is built from the ground up for global expansion through multilingual websites, SEO, and scalable content delivery.


---
layout: default
level: 2
---

## Trading Strategy

- Leverages backtests of 40+ landmark academic papers to create shareable content across social media (e.g. articles, videos, explainers).
- Maintains a growing **Strategy Library** of 2,000+ strategies extracted via AI-assisted review from over 5,000 open-access JEL:G14 research papers (EconPapers), offering structured insights into trading logic, signal design, and historical performance.
- Built on a modular Python-based strategy engine and unified market data source, the system is designed to support <span v-mark.red="3">**AI-assisted strategy generation and auto-backtesting**</span> in future iterations.


---
layout: default
level: 2
---

## Marketing Insights

- Covers financial calendars, earnings call live streams, and SEC filings—enriched through **Deep Research** techniques that surface hidden signals across official disclosures and market timing.
- Enhances trading context by connecting signal outputs from strategies with macroeconomic indicators, sector momentum, and market regime insights—turning raw alerts into actionable narratives.
- Tracks <span v-mark.red="3">**frontier developments across opinion leaders, emerging technologies, and patents**</span> using AI: monitoring key channels, podcasts, discussion groups, patent filings, and executive moves (e.g. LinkedIn profiles, reddit, etc.) to anticipate narrative shifts and market relevance.


---
layout: default
level: 2
---

## Dashboard

- Serves as a personalized investment command center, integrating strategy signals and marketing insights into a unified, real-time performance view tailored to each user's portfolio and preferences.
- Offers customizable widgets, alert thresholds, and cross-strategy analytics—empowering advanced users to track multi-source intelligence in one seamless interface.

- Enables premium, high-margin features such as priority access to personalized reports, personalized market briefings, and strategy tuning based on user behavior or goals.
- Designed for future enterprise integrations and VIP-level services, where <span v-mark.red="4">**custom dashboards become a monetizable layer of insight delivery**</span> for institutional or high-value retail clients.


---
layout: default
---

# Product

- Trading Strategy: Comprehensive toolkit for algorithmic trading (current focus), including:
  - An open-source Python library (available on [PyPI](https://pypi.org/project/alpha-isnow/))
  - A backend strategy backtesting engine and [reports](https://github.com/alpha-isnow-ai/alpha-isnow-strategy-reports)
  - Rich, multilingual [documentation](https://doc.alpha.isnow.ai) with built-in i18n support and SEO-ready architecture for global content reach.
- Marketing Insights: (coming soon) will serve as an AI-driven intelligence engine—connecting financial events, macro signals, and emerging narratives into a cohesive, context-rich layer for next-generation traders.
- Dashboard will evolve into a high-value insight layer—merging real-time analytics, personalization, and premium services into a unified command center for serious traders and enterprise users.



---
layout: two-cols
---

# Monetization Funnel

- **Freemium**  
  Entry-level users access backtested strategies and community-driven insights for free.

- **Premium**  
  Active users upgrade for personalized dashboards, curated signals, and AI-assisted strategy generation.

- **Enterprise**  
  Institutional and high-net-worth clients gain access to custom dashboards, sandbox testing, and VIP services.

::right::

# Conversion Strategy

- Build user trust with transparent, research-backed content and tools.
- Nurture usage depth through modular upgrades tied to user behavior.
- Capture long-tail value by converting top users into premium and enterprise accounts.



<!--
Notes can also sync with clicks

[click] This will be highlighted after the first click

[click] Highlighted with `count = ref(0)`

[click:3] Last click (skip two clicks)
-->

---
layout: two-cols
---

# Roadmap

Our development strategy follows three phases:

- **Foundation**: Building core technology and data infrastructure
- **Engagement**: Creating community and content ecosystem
- **Monetization**: Developing premium features and enterprise solutions

Each phase builds on previous achievements while expanding our market reach.

::right::

| **Completed** | **In Progress** | **Planned** |
|:-------------|:--------------|:-----------|
| Strategy Engine | Content Creation | Financial Calendar |
| Backtest Reports | Community Engagement | Marketing Insights |
| User Onboarding | Signal Subscription | AI Narrative Mining |
| | | Personalized Dashboard |
| | | Enterprise Dashboard |


---
layout: center
class: text-center
---

# Learn More

[Documentation](https://alpha.isnow.ai) · [GitHub](https://github.com/alpha-isnow-ai) · [PyPI](https://pypi.org/project/alpha-isnow/)
