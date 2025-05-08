---
theme: apple-basic
title: Alpha is Now Powered by AI
info: |
  ## Alpha.isnow.ai Pitch Deck
  Vision, product pillars, and roadmap for the AI-driven trading platform.
drawings:
  persist: false
transition: slide-left
mdc: true
colorSchema: dark
layout: intro-image-right
image: 'https://images.unsplash.com/photo-1551288049-bebda4e38f71'
---
# Alpha is Now 

<br>

## [https://alpha.isnow.ai](https://alpha.isnow.ai)

<!--
This opening slide introduces the platform and its AI-driven focus. 
Welcome the audience and set the stage for how AI is powering Alpha's trading platform.
-->

---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---
# Table of Contents

This presentation outlines the vision, structure, and future roadmap of [alpha is now](https://alpha.isnow.ai) — a platform designed to democratize quantitative trading through content, tools, and intelligent insights.

You'll find an overview of the market problem, our solution architecture, the three core product pillars, and how we plan to scale both functionally and globally.

Whether you're a potential partner, investor, or user, this deck offers a clear look into where we are now and where we're headed next.

::right::

<Toc text-lg minDepth="1" maxDepth="2" />

<!--
Briefly walk through the agenda. Emphasize that we'll cover the problem space, our solution and product pillars, and our future plans (roadmap).
-->

---
layout: image-left
image: 'https://images.pexels.com/photos/7567429/pexels-photo-7567429.jpeg'
---
# Problem

- <div v-click>Retail investors face significant challenges in navigating international financial markets due to the lack of localized tutorials, comprehensive strategy frameworks, and native‑language trading resources.</div>
  
- <div v-click>Traders lack access to systematic trading benefits—missing out on data-driven discipline and backtested confidence in their investment decisions.</div>

- <div v-click>Unlike platforms that assume quant expertise, <a href="https://alpha.isnow.ai" target="_blank">Alpha is Now</a> builds trust through academic strategies and transparent backtests as educational entry points.</div>

<!--
Explain each pain point:
1. Lack of local-language guidance makes it hard for 3-speaking users to start.
2. Retail investors miss out on systematic trading benefits (discipline, data, confidence from backtesting).
3. Other platforms expect quant knowledge; instead, Alpha starts with real strategies and transparent backtests to educate and build trust.
-->

---
layout: image-right
image: 'https://images.pexels.com/photos/30268012/pexels-photo-30268012.jpeg'
---
# Market Opportunity

<div v-click>
- The global algorithmic trading market is projected to exceed $30B by 2028, driven by the rise of data access, retail participation, and AI-assisted strategy tools.
</div>

<div v-click>
- Despite this growth, most platforms remain fragmented or overly technical—leaving a gap for accessible, educational, end-to-end solutions.
</div>

<div v-click>
- <a href="https://alpha.isnow.ai" target="_blank">Alpha is Now</a> strategically targets Chinese-speaking markets first, while built from day one for global scalability.
</div>

<div v-click>
- This focused entry enables us to validate, refine, and expand internationally with proven traction and technical maturity.
</div>

<!--
Highlight the size and growth of the algorithmic trading market.
Note the unmet demand for user-friendly, educational platforms.
Explain that Alpha.isnow.ai targets Chinese-speaking users first but is built for global reach, which gives us a testing ground before expanding worldwide.
-->

---
layout: default
---
# Solution

- **Trading Strategy**: Provides backtested academic strategies and Python infrastructure—an educational gateway to systematic trading.

- **Marketing Insights**: Delivers AI-driven financial intelligence on earnings, patents, and executive behavior to inform high-conviction trading ideas.

- **Dashboard**: A personalized command center unifying strategy signals, alerts, and performance tracking in one intuitive interface.

These pillars support a global platform with initial focus on Chinese markets, leveraging regional channels while building international infrastructure.

<!--
Introduce the three solution pillars (Trading Strategy, Marketing Insights, Dashboard).
Explain briefly how each pillar functions.
Note that together they form a bilingual platform that starts in Chinese markets and is designed to scale internationally from day one.
-->

---
layout: default
level: 2
---
## Trading Strategy

- Leverages backtests of 40+ landmark academic papers to create shareable content across social media (articles, videos, explainers).

- Maintains a growing **Strategy Library** of 2,000+ strategies extracted via AI from over 5,000 open-access research papers (JEL:G14 category on EconPapers). This library offers structured insights into trading logic, signal design, and historical performance.

- Built on a modular Python-based strategy engine and unified market data source, the system is designed to support <span v-mark.red="3">**AI-assisted strategy generation and auto-backtesting**</span> in future iterations.
<!--
Trading Strategy pillar:
- We use academic research (40+ papers) to create content, making quant strategies accessible.
- We have an AI-curated library of 2,000+ strategies from 5,000+ papers, providing insights into how strategies work and perform.
- It's all built on a Python engine with unified data, laying groundwork for AI-driven strategy creation and automated backtesting in the future.
-->

---
layout: default
level: 2
---
## Marketing Insights

- Covers financial calendars, earnings call live streams, and SEC filings—enriched through **Deep Research** techniques that surface hidden signals in official disclosures and market timing.

- Enhances trading context by connecting strategy signal outputs with macroeconomic indicators, sector momentum, and market regime insights—turning raw alerts into actionable narratives.

- Tracks <span v-mark.red="3">**frontier developments**</span> across opinion leaders, emerging technologies, and patents using AI. It monitors key channels (podcasts, forums), patent filings, and executive moves to anticipate narrative shifts and market trends.

<!--
Marketing Insights pillar:
- We analyze standard market information (calendars, earnings, filings) with deep research methods to find less obvious signals.
- We add context by linking strategy signals to bigger-picture data (macro trends, sector momentum) to make alerts meaningful.
- We use AI to track cutting-edge news (thought leaders, tech trends, patent activity, executive changes) so we can spot shifts in market narrative early.
-->

---
layout: default
level: 2
---
## Dashboard

- Serves as a personalized investment command center, integrating strategy signals and marketing insights into one real-time performance view tailored to each user's portfolio and preferences.

- Offers customizable widgets, alert thresholds, and cross-strategy analytics—empowering advanced users to track multi-source intelligence in one seamless interface.

- Enables premium, high-margin features such as priority access to tailored reports, personalized market briefings, and strategy tuning based on user behavior or goals.

- Designed for future enterprise integrations and VIP-level services, where <span v-mark.red="3">**custom dashboards become a monetizable layer of insight**</span> for institutional or high-value retail clients.

<!--
Dashboard pillar:
- It's the user's personal hub, showing their strategy signals and insights in real time, customized to their portfolio.
- Users can customize the dashboard (widgets, alerts) to suit their needs and see all intelligence in one place.
- This dashboard unlocks premium offerings (exclusive reports, briefings, strategy fine-tuning for the user).
- In the future, this will integrate with enterprise systems and serve VIP clients, turning custom dashboards into a high-value product in itself.
-->

---
layout: default
---
# Product

- **Trading Strategy**: Comprehensive toolkit for algorithmic trading (our current focus), including:
  - An open-source Python library (available on [pypi](https://pypi.org/project/alpha-isnow/))
  - A backend strategy backtesting engine and [research reports](https://github.com/alpha-isnow-ai/alpha-isnow-strategy-reports)
  - Rich, multilingual [documentation](https://doc.alpha.isnow.ai) with built-in i18n and SEO-ready architecture for global reach

- **Marketing Insights**: An AI-driven intelligence engine that will connect financial events, macro signals, and emerging narratives into a cohesive, context-rich layer for next-generation traders *(coming soon)* .

- **Dashboard**: Will evolve into a high-value insight layer—merging real-time analytics, personalization, and premium services into a unified command center for serious traders and enterprise users.

<!--
Summarize the product components:
- Trading Strategy: We already offer a Python library, a backtesting engine with reports, and robust multilingual documentation.
- Marketing Insights: Coming next—an AI intelligence engine to tie together events, signals, and market narratives.
- Dashboard: The future integrated hub that combines analytics, personalization, and premium features for power users and enterprises.
-->

---
layout: two-cols
---
# Monetization Funnel

<div v-click>
- Freemium
  
  Entry-level users access backtested strategies and community-driven insights for free.
</div>

<div v-click>
- Premium
  
  Active users upgrade for personalized dashboards, curated signals, and AI-assisted strategy generation.
</div>

<div v-click>
- Enterprise
  
  Institutional and high-net-worth clients gain access to custom dashboards, sandbox testing, and VIP services.
</div>

::right::

# Conversion Strategy

<div v-click class="mb-18">
- Build user trust with transparent, research-backed content and tools.
</div>

<div v-click class="mb-18">
- Nurture deeper engagement through modular upgrades tied to user behavior.
</div>

<div v-click class="mb-18">
- Capture long-tail value by converting top users into premium and enterprise accounts.
</div>

<!--
Explain our revenue model:
Left (Funnel):
Freemium builds a user base; Premium offers advanced features for power users; Enterprise caters to big clients with custom needs.
Right (Conversion):
We earn trust via valuable free content/tools, encourage users to gradually upgrade as they find value, and focus on turning our most engaged users into paying premium or enterprise customers.
-->

---
layout: two-cols
---
# Roadmap

Our development strategy follows three phases:

- **Foundation**: Building core technology and data infrastructure.

- **Engagement**: Creating community and a content ecosystem.

- **Monetization**: Developing premium features and enterprise solutions.

Each phase builds on the previous one, expanding our market reach as we grow.

::right::

| **Completed**       | **In Progress**        | **Planned**            |
|:--------------------|:-----------------------|:-----------------------|
| Strategy Engine     | Content Creation       | Financial Calendar     |
| Backtest Reports    | Community Engagement   | Marketing Insights     |
| User Onboarding     | Signal Subscription    | AI Narrative Mining    |
|                     |                        | Personalized Dashboard |
|                     |                        | Enterprise Dashboard   |

<!--
Walk through the roadmap:
- Foundation: we've built the strategy engine, reports, onboarding.
- Engagement: currently focusing on content and community.
- Monetization: next up are features like financial calendars, advanced insights (AI narrative mining), personalized and enterprise dashboards.
The table shows what's done, in progress, and planned, giving a timeline of our growth.
-->

---
layout: center
class: text-center
transition: fade
---
# Learn More

<a href="https://alpha.isnow.ai" target="_blank">Documentation</a> · <a href="https://github.com/alpha-isnow-ai" target="_blank">GitHub</a> · <a href="https://pypi.org/project/alpha-isnow/" target="_blank">PyPI</a>

<!--
Closing slide. Encourage the audience to explore our documentation, check out the code on GitHub, or try our package on PyPI for more information.
Thank everyone for their time and attention.
-->
