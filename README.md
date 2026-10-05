# Awesome-Enterprise-Social-Network

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Internal Communications, Employee Engagement, Knowledge Sharing & Digital Workplace*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Social Networks**. These tools help organizations connect employees, streamline internal communications, share knowledge, and build digital workplace experiences that engage both desk-based and frontline workers.

**Examples** include Microsoft Viva Engage, Slack, Workplace from Meta (closing 2026), Workvivo, Jostle, MangoApps, Igloo Software, Staffbase, Simpplr, and LumApps (the category leaders).

**Open-source emphasis**: The open-source enterprise social network ecosystem is **mature and production-proven**. **HumHub** is the leading open-source enterprise social network with **6.7k+ stars**, GDPR-by-construction architecture, unlimited Spaces, and **~80 modules** including Wiki, Calendar, Polls, Tasks, and SSO . **eXo Platform** provides a full-featured digital workplace with activity streams, document management, and content publishing . **Zulip** offers unique topic-based threading for async-first distributed teams with **no message or user limits** . This section documents these production-grade solutions.

## 📖 Table of Contents

- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ SaaS/Hosted Platforms

> **📊 Market Context**: The global enterprise social network and digital workplace market is estimated at **~$10B in 2026**, growing toward **~$25B by 2032**. The sector is **moderately fragmented** — **Microsoft Viva Engage** (formerly Yammer) leverages Microsoft 365 distribution with **core features included in E1/E3/E5/F1/F3 and Business Premium at no additional cost**, while premium features require **Communities Premium at $2/user/month** or **Viva Suite at $12/user/month** . **Workplace from Meta is closing in 2026** — access terminated June 1, 2026, with **Workvivo by Zoom** as Meta's only preferred migration partner . **Chatter** is **turned off by default in all new Salesforce orgs beginning Summer '26** . **Staffbase** pricing runs **$8–$15 per employee annually** for mid-market, with minimum contracts of **$25,000–$40,000** . **Jostle** starts at **$990/year for 25 users** (Basic) . No single vendor holds a winner-take-all position; enterprises typically run multi-vendor stacks.

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Microsoft Viva Engage](https://www.microsoft.com/en-us/microsoft-viva/engage)** | **Microsoft's enterprise social network (formerly Yammer).** Communities, Storyline, Leadership Corner, and AI-powered Answers in Viva . | **Core included with Microsoft 365 E1/E3/E5/F1/F3/Business Premium** at no additional cost. **Communities Premium**: **$2/user/month**. **Viva Suite**: **$12/user/month** . | **Included with M365 E1/E3/E5/F1/F3/Business Premium**. **M365 F1 (kiosk) does NOT include Viva Engage Core** — requires F3 minimum . | **~$281B revenue (Microsoft FY2025)**  |
| **[Slack](https://slack.com/)** | **The category-defining team messaging platform.** Channels, direct messages, integrations with 2,600+ apps. | **Free**: $0; **Pro**: **$8.75/user/month** (annual); **Business+**: **$15/user/month**; **Enterprise Grid**: Custom. | **Free tier**: **90-day message history**, 10 app integrations, 1:1 huddles . | **Part of Salesforce (~$37.9B revenue)** |
| **[Workvivo](https://www.workvivo.com/)** | **Meta's only preferred migration partner for Workplace.** Employee experience platform combining intranet with social-style engagement . | **Custom enterprise pricing** — quote required. | **None** — enterprise demo required. | **Part of Zoom (~$4.5B revenue est.)** |
| **[Staffbase](https://staffbase.com/)** | **AI-native employee experience platform for all employees.** Mobile-first, strong for frontline workers . | **$8–$15 per employee annually** for mid-market. **Minimum contract**: **$25,000–$40,000** . | **None** — enterprise demo required. | **Private (~$500M+ valuation est.)** |
| **[Jostle](https://www.jostle.me/)** | **Intranet platform focused on employee connection.** People directory, news, and team collaboration. | **Basic**: **$990/year** (25 users). **Standard**: **$1,490/year**. **Pro**: **$2,990/year** . | **Free trial** available. | **Private (~$10M+ revenue est.)** |
| **[MangoApps](https://www.mangoapps.com/)** | **Unified employee experience platform.** Intranet, team collaboration, and frontline tools. | **$299/month** (25 users included) . | **Free trial** available. | **Private (~$50M+ revenue est.)** |
| **[Igloo Software](https://www.igloo software.com/)** | **Digital workplace platform.** Internal communications, collaboration, and knowledge management. | **Custom enterprise pricing** — quote required. | **None** — enterprise demo required. | **Private (~$100M+ revenue est.)** |
| **[Simpplr](https://www.simpplr.com/)** | **AI-powered employee experience platform.** Intranet, internal communications, and enterprise search. | **Custom enterprise pricing** — quote required. | **None** — enterprise demo required. | **Private (~$100M+ ARR est.)** |
| **[LumApps](https://www.lumapps.com/)** | **Digital workplace platform.** Aligns with brand guidelines and streamlines workflows. | **Custom enterprise pricing** — quote required. | **None** — enterprise demo required. | **Private (~$100M+ raised)** |
| **[Workplace from Meta](https://forwork.meta.com/meta-workplace/)** | **CLOSING IN 2026.** Enterprise social network. | **N/A** — **closing June 1, 2026**. Data export available until May 31, 2026 . | **N/A** — service terminating. | **Part of Meta (~$165B revenue)** |

## 🔓 Open-Source GitHub Projects

| Repo | Description | Stars |
|------|-------------|-------|
| **[HumHub](https://github.com/humhub/humhub)** — **The leading open-source enterprise social network.** **GDPR by construction** — German-made, self-hosted, member data never touches a third-party platform . **Four core concepts**: Users (rich profiles with follows), **Spaces** (rooms for departments/projects with per-Space permissions, notifications, email summaries), **Content** (posts, wiki pages, photos/video, events, tasks with threaded comments, versioning, moderation), and **Modules** (~80 install-and-activate extensions including Calendar, Wiki, Polls, Tasks, Gallery, News, Mail, OnlyOffice, Advanced LDAP, SAML/JWT SSO, RESTful API, mass user import, Translation Manager, Theme Builder) . **LAMP stack** (PHP 8.1+, MySQL/MariaDB) — one of the easiest platforms to operate long-term . **6.7k stars, 1.7k forks, actively maintained** . | [![Stars](https://img.shields.io/github/stars/humhub/humhub?style=social&color=white)](https://github.com/humhub/humhub/stargazers) | ~6,700 |
| **[eXo Platform](https://github.com/exoplatform/platform)** — **The leading open-source digital collaboration platform.** **20+ years of development**, 100s of enterprise deployments, US headquarters in San Francisco . **Enterprise-grade**: tested in production for defense agencies . **Features**: Collaboration spaces, document storage, project management, content management with publication lifecycles, **enterprise social network** (find/connect/interact with colleagues), **activity streams** (tailored feeds and notifications), **knowledge management** (wikis, forums, search), single access point for all business apps, and **mobile access** . **AGPL-3.0** . | [![Stars](https://img.shields.io/github/stars/exoplatform/platform?style=social&color=white)](https://github.com/exoplatform/platform/stargazers) | ~1,500 |
| **[Zulip](https://github.com/zulip/zulip)** — **Best for distributed, async-first teams.** **Unique topic-based threading** keeps conversations organized by subject rather than time — ideal for teams across time zones . **No message limits, no user limits**, well-documented self-hosting . **Tradeoff**: UX has a learning curve; mobile apps are functional but not the strongest . **Best for**: Distributed teams willing to invest a week to adapt to the topic model . | [![Stars](https://img.shields.io/github/stars/zulip/zulip?style=social&color=white)](https://github.com/zulip/zulip/stargazers) | ~24,000 |
| **[Mattermost](https://github.com/mattermost/mattermost)** — **Open-source Slack alternative with unlimited history.** **Team Edition**: Free, unlimited messages, capped at **250 activated users** . **Push notifications**: TPNS (Test Push Notification Service) is documented as **not recommended for production** with no production-grade SLA; paid deployments can use HPNS . **Best for**: Teams wanting open-source control, unlimited history, and no SSO requirement . | [![Stars](https://img.shields.io/github/stars/mattermost/mattermost?style=social&color=white)](https://github.com/mattermost/mattermost/stargazers) | ~35,000 |
| **[Rocket.Chat](https://github.com/RocketChat/Rocket.Chat)** — **Easiest free self-hosted Slack-like option for small teams.** **Starter**: Free for small teams under 50 users in 2026 . Push notifications route through provider-managed gateways . **Best for**: Small teams wanting the simplest free self-hosted Slack alternative . | [![Stars](https://img.shields.io/github/stars/RocketChat/Rocket.Chat?style=social&color=white)](https://github.com/RocketChat/Rocket.Chat/stargazers) | ~42,000 |
| **[NodeBB](https://github.com/NodeBB/NodeBB)** — **Modern forum platform with real-time discussions.** Built-in chat, SSO options, plugins, and flexible theming. Backed by Redis, MongoDB, or PostgreSQL. **GPL-3.0** . | [![Stars](https://img.shields.io/github/stars/NodeBB/NodeBB?style=social&color=white)](https://github.com/NodeBB/NodeBB/stargazers) | ~15,200 |
| **[Apache Answer](https://github.com/apache/answer)** — **Open-source Q&A platform for teams.** Build knowledge bases, forums, and help centers. **Apache-2.0**, 15.7k stars, actively maintained . | [![Stars](https://img.shields.io/github/stars/apache/answer?style=social&color=white)](https://github.com/apache/answer/stargazers) | ~15,700 |
| **[Loomio](https://github.com/loomio/loomio)** — **Collaborative decision-making tool.** Group discussions, proposals, and polls with transparent async decision records. **AGPL-3.0** . | [![Stars](https://img.shields.io/github/stars/loomio/loomio?style=social&color=white)](https://github.com/loomio/loomio/stargazers) | ~2,600 |
| **[Elgg](https://github.com/Elgg/Elgg)** — **Modular open-source social network platform.** Plugin-based extensions for building collaborative communities . | [![Stars](https://img.shields.io/github/stars/Elgg/Elgg?style=social&color=white)](https://github.com/Elgg/Elgg/stargazers) | ~1,700 |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[Movim](https://github.com/movim/movim)** — Open-source social network built on XMPP. Blog, chat, and community features . |
| **[diaspora*](https://github.com/diaspora/diaspora)** — Open-source, decentralized social network. Community-focused with privacy controls . |
| **[OpenPNE](https://github.com/openpne/OpenPNE3)** — Japanese open-source SNS with 30,000+ community deployments . |
| **[Campfire](https://github.com/basecamp/campfire)** — Self-hosted group chat with rooms, @mentions, and DMs. MIT licensed . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Enterprise social networks handle sensitive employee and organizational data; ensure compliance with GDPR, CCPA, and applicable data protection regulations.
- **Critical lifecycle notices**: **Workplace from Meta is closing in 2026** — access terminated **June 1, 2026**. Data export available until **May 31, 2026** . **Chatter is turned off by default in all new Salesforce orgs beginning Summer '26** . **Microsoft Viva Engage Core is included with M365 E1/E3/E5/F1/F3/Business Premium**, but **M365 F1 (kiosk) does NOT include it** — frontline workers need F3 minimum .
- **Open-source reality**: The open-source ecosystem for enterprise social networks is **mature and production-proven**. **HumHub** is the leading open-source enterprise social network with **GDPR-by-construction** architecture, unlimited Spaces, and **~80 modules** . **eXo Platform** provides a full-featured digital workplace with **20+ years of development** and defense-grade deployments . **Zulip** delivers unique topic-based threading for async-first teams with **no message or user limits** . However, **commercial platforms** (Microsoft Viva Engage, Slack, Staffbase) provide **polished mobile experiences, managed infrastructure, and native compliance integration** that open-source alternatives require additional configuration to match. The open-source path is **genuinely viable** for organizations seeking data sovereignty and cost control.
- **Important distinction**: **HumHub is NOT a Slack alternative** — it is a private social network and intranet platform, closer to an internal Facebook or employee community forum . For team messaging, **Mattermost**, **Rocket.Chat**, or **Zulip** are the appropriate open-source options .

---

**Made for internal communications teams, HR leaders, IT administrators, and digital workplace strategists.**
Let's make enterprise social networks more open, transparent, and engaging.
