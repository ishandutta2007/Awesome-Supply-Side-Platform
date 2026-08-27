# Awesome-Supply-Side-Platform

Edit
Top Supply-Side Platform (SSP) Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Publisher Monetization, Programmatic Advertising, Header Bidding, RTB & Yield Optimization
Last updated: August 2026

This repository tracks notable SaaS/hosted platforms and open-source projects for Supply-Side Platforms (SSPs). These platforms help publishers and media owners monetize digital inventory across web, mobile apps, CTV/OTT, video, audio, native advertising, and other programmatic channels.

SSPs typically provide capabilities such as real-time bidding (RTB), header bidding, yield optimization, programmatic direct deals, private marketplaces (PMPs), identity/addressability, audience segmentation, fraud prevention, inventory management, analytics, and demand-partner connectivity.

Examples include Magnite, PubMatic, OpenX, Index Exchange, Equativ, TripleLift, Sharethrough, Xandr Monetize, Google Ad Manager, and Sovrn — among the major commercial platforms used by publishers and media companies.

Open-source emphasis: The open-source SSP ecosystem is considerably smaller than the commercial SSP market. Therefore, this list emphasizes projects that can actually provide pieces of an SSP stack — including open-source RTB auction infrastructure, header bidding, ad servers, OpenRTB implementations, SSP experiments, and publisher monetization infrastructure. Prebid Server, for example, is explicitly an open-source real-time advertising auction platform, while Revive Adserver provides a mature open-source ad-serving foundation.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or canonical GitHub repositories.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

Open-Source Building Blocks

How to Contribute

Disclaimer

## SaaS/Hosted Platforms

| Platform | Description | Pricing (Starting Tier / Model) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **Google Ad Manager** | Google's publisher ad platform combining ad serving, programmatic demand, direct campaigns, inventory management, and yield optimization. | Free standard tier; GAM 360 starts with custom contracted rates (~$1,500–$3,000/month minimum or ~$100k/year enterprise agreement). | **Free forever** up to 90M non-video impressions/month (US/CA/ANZ/Europe) or 200M non-video impressions/month (other regions); 800k video impressions/month. |
| **AdGlare** | Cloud-based ad server for publishers and advertisers supporting display advertising, campaign management, targeting, and analytics. | **Lite tier starts at $99/month** (up to 2M requests); Professional at $349/month (up to 10M requests); Enterprise at $649/month. | **14-day free trial** with all features unlocked and up to 10,000,000 ad requests. |
| **AdButler** | Hosted ad-serving platform providing direct-sold campaign management, programmatic integrations, custom pacing, and reporting. | **Essentials tier starts at $179/month** (up to 1M requests); Standard at $399/month; Advanced at $699/month. | **14-day free trial** with full platform feature access and 30 days of free onboarding support. |
| **Broadstreet** | Publisher-focused advertising platform designed for direct-sold advertising, hyper-local publishers, newsletters, and rich media campaigns. | **Manual tier starts at $299/month**; Automatic tier starts at $399/month; Enterprise custom pricing. | **Live sandbox demo** on request + free permanent access to "Daybreak" publisher lead-generation tools. |
| **Kevel** | API-first ad infrastructure platform enabling publishers and retailers to build custom ad servers, sponsored listings, and retail media networks. | **Starting tier at $3,000/month** (base API tier with standard request volume); custom scaling for enterprise deployments. | **Interactive developer sandbox & API test environment** during guided sales onboarding (no self-serve free tier). |
| **StackAdapt** | Multi-channel programmatic platform with extensive publisher and supply connectivity across display, video, CTV, native, and audio. | **$0 monthly platform software fee** (self-serve tier; recommended starting ad spend of $1,000–$2,000/month; managed service from $5,000/month). | **Free platform account registration** with full UI access and free enrollment in Programmatic Masterclass certification. |
| **Amazon Publisher Services (APS)** | Publisher monetization suite providing transparent server-to-server header bidding (TAM), marketplace demand (UAM), and shopping insights. | **10% publisher transaction fee** deducted from buyer bids before entering auction (Transparent Ad Marketplace / TAM). | **Free publisher registration & SDK integration** with zero recurring monthly subscription or maintenance fees. |
| **Sovrn** | Publisher technology platform providing programmatic advertising, commerce monetization, site performance analytics, and consent tools. | **Flat CPM platform fee** (0% rev-share take rate when bundling Ad Management + Exchange) or standard ~15%–20% exchange rev-share. | **Free publisher signup and onboarding** with no upfront setup fees (requires minimum 10,000 monthly pageviews). |
| **Magnite** | Independent sell-side advertising platform supporting omnichannel programmatic monetization across CTV, video, display, and mobile. | **Dynamic take rate starting at ~10%–15%** revenue share on cleared CTV and programmatic ad revenue. | **Free partner onboarding and contract evaluation**; live test-traffic auction analysis during publisher integration. |
| **PubMatic** | Cloud infrastructure platform for publishers and app developers, delivering header bidding (OpenWrap), programmatic auctions, and yield tools. | **Dynamic take rate starting at ~10%–13%** revenue share on publisher impression volume. | **Free publisher registration & OpenWrap wrapper integration** with no recurring software license fees. |
| **OpenX** | Programmatic advertising exchange and publisher monetization platform connecting inventory with global demand across web, mobile, and CTV. | **Programmatic revenue share starting at ~10%–15%** take rate on auction clearing prices. | **Free publisher onboarding & OpenRTB tag integration** with access to OpenX Community tools (traffic volume thresholds apply). |
| **Index Exchange** | Independent ad exchange providing transparent programmatic marketplaces, client audit logs, and unified auction decisioning. | **Transparent dynamic take rate starting at ~10%–12%** per-impression transaction fee. | **Free publisher integration and Client Audit Log access** with zero upfront setup or licensing fees. |
| **Equativ** | Independent ad tech company offering end-to-end programmatic supply infrastructure, curation, native formats, and video/CTV monetization. | **Programmatic take rate starting at ~10%–15%** margin / CPM-based targeting fee on auction transactions. | **Free publisher evaluation & SDK integration sandbox** during partner onboarding. |
| **TripleLift** | Programmatic platform specializing in native advertising, branded content, custom video, CTV, and retail media monetization. | **Programmatic take rate starting at ~15%–20%** revenue share on native and premium ad placements. | **Free tag/adapter implementation & creative rendering sandbox** testing prior to live monetization. |
| **Sharethrough** | Native and programmatic supply platform focused on dynamic ad enhancements, user-centric experiences, and publisher yield. | **Programmatic take rate starting at ~12%–15%** on dynamic native, display, and video placements. | **Free publisher placement setup & SmartSuite enhancement testing** with no upfront integration cost. |
| **Xandr Monetize** | Enterprise sell-side monetization technology (Microsoft Advertising) connecting publishers to demand through auctions and private marketplaces. | **Seller Auction Service Charge (SASC) starting at ~10%–15%** take rate or ~$0.01–$0.03 tech fee CPM. | **Free API sandbox testing & developer documentation access** during contractual partner onboarding. |
| **Yahoo SSP** | Omnichannel publisher monetization platform offering programmatic demand, identity resolution (Yahoo ConnectID), and header bidding. | **Programmatic take rate starting at ~10%–15%** on publisher inventory transactions. | **Free publisher onboarding, ConnectID integration, and yield test period** with no upfront fees. |
| **Nexxen** | Sell-side and video advertising platform combining CTV monetization, discovery data, identity, and exchange infrastructure. | **Programmatic take rate starting at ~12%–18%** on video, CTV, and omnichannel media spend. | **Free platform demo walkthrough and trial pilot evaluation** for verified publisher inventory. |
| **Adform** | Integrated programmatic advertising platform providing ad serving, media buying, identity (ID Fusion), and publisher monetization. | **Platform tech fee starting at ~$0.05–$0.15 CPM** or custom annual licensing for enterprise stack. | **Guided proof-of-concept / paid pilot period** with demo sandbox environment access. |
| **Yieldmo** | Ad exchange and optimization platform specializing in mobile and web inventory, contextual AI targeting, and micro-moment ad formats. | **Programmatic take rate starting at ~15%–20%** on proprietary high-engagement mobile ad units. | **Free tag integration & A/B yield test period** with zero upfront onboarding fees. |
| **Onetag** | Programmatic ad exchange and yield optimization engine utilizing AI to eliminate non-performing bid requests and streamline demand routing. | **Auction-based take rate starting at ~10%–15%** on direct programmatic demand routing. | **Free publisher header-bidding adapter setup & test-auction traffic analysis**. |
| **Bidtellect** | Programmatic technology provider focused on native advertising, contextual targeting, brand safety, and publisher yield. | **Programmatic revenue share starting at ~15%–20%** on native and contextual campaign delivery. | **Free publisher tag onboarding & initial campaign performance test period**. |

Open-Source GitHub Projects
Open-Source SSP / RTB Infrastructure

Prebid Server
Open-source server-side header-bidding and real-time advertising auction platform. It integrates with Prebid.js and Prebid Mobile and supports OpenRTB-based auctions, bid adapters, analytics modules, floors, privacy controls, and supply-chain functionality.

Prebid.js
Open-source client-side header-bidding framework that enables publishers to run auctions among multiple demand partners before or alongside their primary ad server.

Prebid Mobile
Open-source header-bidding SDK for mobile applications, bringing Prebid's auction infrastructure to iOS and Android environments.

OpenSSP
Open-source supply-side platform designed for general use, supporting RTB and multiple impression types. The project describes itself as a multi-channel SSP and includes OpenRTB support.

ZenAd
Apache-2.0 open-source advertising monetization platform combining SSP, ad-server, and DMP-style capabilities. It includes an OpenRTB adapter and federated auction architecture.

Ad Nano
Open-source experimental ad-tech platform containing publisher, SSP, DSP, ad exchange, and ad-view components. It supports OpenRTB auctions and provides an end-to-end environment for experimenting with programmatic advertising infrastructure.

Open-Source Ad Servers

Revive Adserver
Mature GPL-licensed open-source ad-serving system. It supports publisher inventory, campaign management, targeting, frequency capping, geo-targeting, impressions, clicks, conversions, and reporting.

OpenX Source / Revive Adserver lineage
Revive Adserver originated from the open-source OpenX lineage and remains one of the most established open-source options for self-hosted ad serving.

OIOpublisher
Community/open-source ad-management software historically used for direct advertising, inventory management, and publisher-side campaign delivery. Check current maintenance and licensing before production use.

OpenRTB / Programmatic Advertising Infrastructure

OpenRTB specification
IAB Tech Lab's OpenRTB specifications provide the common protocol foundation for communication between SSPs, exchanges, DSPs, and other programmatic advertising systems.

Prebid Server Go
Server-side OpenRTB auction infrastructure implemented in Go, suitable for publishers or technology providers building their own auction layer.

Prebid.js
Browser-side auction and bidder-adapter ecosystem providing the core client-side header-bidding layer used by publishers.

Prebid Universal Creative
Open-source creative-rendering infrastructure used within Prebid-based advertising workflows.

Additional Strong Open-Source Options

Revive Adserver — Mature self-hosted ad server.

Prebid Server — Server-side real-time auction infrastructure.

Prebid.js — Client-side header bidding.

Prebid Mobile — Mobile header bidding.

OpenSSP — Purpose-built open-source SSP project.

ZenAd — Modern open-source SSP/ad-server/DMP-style project.

Ad Nano — End-to-end experimental SSP/DSP/exchange stack.

OpenRTB — Core protocol specification for RTB systems.

Mediation / auction engines — Useful foundation for custom publisher auctions and yield experimentation.

Open-source analytics — Can be combined with ad infrastructure for publisher analytics.

Open-source observability — Useful for monitoring auction latency, fill rate, bid density, CPM, timeout rates, and infrastructure health.

Best open-source starting points:

Closest purpose-built SSP: OpenSSP

Best modern auction infrastructure: Prebid Server

Best client-side header bidding: Prebid.js

Best mature self-hosted ad server: Revive Adserver

Best experimental full ad-tech stack: ZenAd / Ad Nano

Best protocol foundation: OpenRTB

Best mobile auction layer: Prebid Mobile

Best customizable architecture: Prebid Server + Revive Adserver + OpenRTB

Best publisher-owned stack: Prebid.js + Prebid Server + Revive Adserver + custom analytics

Open-Source Building Blocks
Layer	Open-Source Options	Purpose
SSP / Auction	Prebid Server, OpenSSP, ZenAd	Real-time auctions and supply-side decisioning
Header Bidding	Prebid.js	Client-side multi-demand auctions
Mobile Bidding	Prebid Mobile	iOS/Android monetization
Ad Server	Revive Adserver	Inventory, campaigns, targeting and delivery
RTB Protocol	OpenRTB	SSP/DSP/exchange communication
Bid Adapters	Prebid Server / Prebid.js adapters	Connect demand partners
Yield Optimization	Prebid Floors / custom auction modules	Dynamic floors and auction optimization
Supply Chain	Prebid Server schain support	Supply-path transparency
Consent	Prebid privacy modules	GDPR/US privacy signaling and controls
Identity	Prebid identity modules	Addressability and identity integrations
Analytics	Matomo	Publisher and website analytics
Dashboards	Grafana	Auction and revenue monitoring
Metrics	Prometheus	Infrastructure and auction metrics
Data Processing	Apache Kafka	High-volume bid/event streaming
Analytics Warehouse	ClickHouse	High-volume impression/bid analytics
Cache	Redis	Low-latency auction and configuration caching
Database	PostgreSQL	Publisher, inventory, deal and configuration data
Object Storage	MinIO	Self-hosted event/creative/log storage
Search	OpenSearch	Search and log analysis
Workflow	Apache Airflow	ETL and advertising-data pipelines
Containers	Docker / Kubernetes	Deployment and horizontal scaling
API Gateway	Kong	API management for SSP services
Observability	OpenTelemetry	Distributed auction tracing
Typical Open-Source SSP Architecture

A publisher seeking to build a self-hosted alternative to a commercial SSP can combine:

Publisher Website/App — advertising inventory and ad slots.

Prebid.js / Prebid Mobile — client-side or mobile demand orchestration.

Prebid Server — server-side auction and OpenRTB processing.

OpenRTB — standardized SSP/DSP communication.

Revive Adserver — direct campaigns, fallback inventory and campaign management.

OpenSSP / custom auction engine — additional SSP-specific decisioning.

Redis — low-latency configuration, frequency and auction state.

Kafka — impression, bid, win, loss and event streaming.

ClickHouse — high-volume bid-stream and revenue analytics.

Grafana + Prometheus — operational and auction monitoring.

PostgreSQL — publishers, placements, deals and configuration.

MinIO — self-hosted creative and event storage.

This architecture can provide publishers with substantially more control over inventory, auction logic, bidder relationships, first-party data, infrastructure, and monetization economics than a fully outsourced SSP.

Key SSP Capabilities to Evaluate

When comparing commercial and open-source SSP solutions, evaluate:

Real-time bidding (RTB)

OpenRTB 2.x / 3.x support

Header bidding

Server-side header bidding

Client-side auctions

Mobile app monetization

CTV/OTT

Video advertising

Native advertising

Audio advertising

PMP/private deals

Programmatic guaranteed

Preferred deals

Dynamic floor pricing

Yield optimization

Bid shading / auction optimization

First-price auctions

Identity resolution

Privacy / consent management

GDPR / US privacy support

ads.txt

app-ads.txt

sellers.json

SupplyChain Object (schain)

Fraud detection

Brand safety

Viewability

Demand-partner management

Bidder adapters

Inventory management

Deal management

Frequency capping

Audience targeting

Contextual targeting

Real-time analytics

Revenue reporting

Latency monitoring

Auction transparency

Publisher APIs

Self-hosting

Kubernetes scalability

Data ownership

Commercial SSP vs Open-Source Stack
Capability	Commercial SSP	Open-Source Stack
Auction engine	Managed	Build/manage
Demand partners	Usually built-in	Configure adapters/partners
Infrastructure	Vendor-managed	Publisher-managed
Data ownership	Vendor-dependent	Publisher-controlled
Custom auction logic	Usually limited	Fully customizable
Header bidding	Included	Prebid
OpenRTB	Included	Prebid Server / OpenRTB
Direct campaigns	Usually available	Revive Adserver
Reporting	Built-in	Build/customize
Scaling	Vendor-managed	Kubernetes/cloud infrastructure
Privacy controls	Vendor-provided	Publisher-managed
Revenue share	Often applicable	No SSP platform fee, but infrastructure costs remain
Maintenance	Vendor	Publisher/team
Development effort	Low	High
Customization	Moderate	Very high
Transparency	Vendor-dependent	Code-level transparency
How to Contribute

Fork the repo.

Add/edit entries in README.md following the existing format.

Include: name, link, 1–2 sentence description, and whether it is SaaS, hosted, open-source, open-core, or source-available.

For GitHub projects, prefer the canonical upstream repository.

Clearly distinguish actual SSPs from ad servers, header-bidding frameworks, DSPs, RTB protocols, and supporting infrastructure.

Verify the current license and repository activity before labeling a project as open source.

Mention supported formats such as display, mobile, video, CTV, audio, native, and DOOH where applicable.

Mention important standards such as OpenRTB, ads.txt, sellers.json, and SupplyChain Object where applicable.

Submit a PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Commercial SSPs frequently change ownership, product names, positioning, and product capabilities.

SSP, ad server, ad exchange, header-bidding platform, DSP, and retail-media platform are distinct categories, although modern advertising companies may operate across several of them.

The open-source ecosystem is substantially smaller than the commercial SSP ecosystem.

Some projects listed in the open-source section are supporting infrastructure rather than complete production-grade SSPs.

OpenSSP, ZenAd, and Ad Nano should be evaluated carefully for production maturity, maintenance activity, scalability, security, and demand-partner availability before being used for significant advertising traffic.

Open source, source-available, free software, and hosted free tiers are different concepts. Always verify the current license.

A self-hosted SSP requires substantial operational work around latency, security, privacy, fraud, identity, consent, billing, demand integrations, uptime, monitoring, and regulatory compliance.

Advertising systems process potentially sensitive user and publisher data. Proper consent, privacy, security, data-retention, and jurisdictional controls are essential.

Revenue outcomes depend heavily on demand connectivity, traffic quality, inventory quality, geography, formats, auction design, latency, floors, identity/addressability, and publisher relationships.

Made for publishers, media companies, app developers, CTV operators, ad-tech engineers, programmatic teams, and developers building publisher-owned advertising infrastructure.
Let's make supply-side advertising more transparent, programmable, interoperable, data-driven, and open-source.
