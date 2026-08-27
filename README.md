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

SaaS/Hosted Platforms

Magnite
Major independent sell-side advertising platform supporting programmatic monetization across CTV, video, display, mobile, and other digital media formats.

PubMatic
Cloud infrastructure platform for digital publishers and app developers, providing programmatic advertising, header bidding, yield optimization, analytics, and supply-path capabilities.

OpenX
Programmatic advertising exchange and publisher monetization platform connecting premium digital inventory with demand partners across display, mobile, video, and CTV.

Index Exchange
Global independent advertising exchange focused on transparent programmatic marketplaces and monetization for publishers across web, mobile, video, CTV, and other media.

Equativ
Independent advertising technology company providing sell-side and programmatic infrastructure across digital advertising formats, including video, CTV, mobile, and web.

TripleLift
Programmatic advertising platform specializing in native, display, video, CTV, and commerce media, with SSP capabilities connecting publishers and buyers.

Sharethrough
Independent advertising technology platform focused on native advertising, programmatic monetization, supply optimization, and publisher experiences.

Xandr Monetize
Microsoft/Xandr sell-side monetization technology connecting publishers and media owners to programmatic demand through auctions, direct deals, and marketplace infrastructure.

Google Ad Manager
Google's publisher advertising platform combining ad serving, programmatic demand, direct campaign management, inventory management, yield optimization, and reporting.

Sovrn
Publisher technology platform providing programmatic advertising, commerce monetization, analytics, and tools for independent publishers.

Amazon Publisher Services
Amazon's publisher monetization ecosystem providing programmatic demand, header bidding, marketplace services, and advertising infrastructure for digital publishers.

Yahoo SSP
Yahoo's advertising technology platform providing programmatic monetization and supply-side capabilities across digital media inventory.

Verizon Media / Yahoo SSP
Publisher monetization technology that evolved from Verizon Media's advertising infrastructure and is now part of Yahoo's advertising business.

Sharethrough Equativ
The Equativ ecosystem incorporates technology and capabilities spanning programmatic supply, native advertising, publisher monetization, and media buying.

Nexxen
Advertising technology platform combining media buying, data, identity, and sell-side capabilities across connected TV, video, display, and other digital channels.

StackAdapt
Programmatic advertising platform with extensive publisher and supply connectivity across display, video, CTV, native, audio, and emerging media.

Kevel
API-first ad infrastructure platform enabling companies and publishers to build custom ad servers, sponsored-product systems, retail media networks, and monetization products.

Adform
Integrated advertising technology platform providing programmatic infrastructure, media buying, data, identity, and publisher-side capabilities.

Yieldmo
Advertising exchange and optimization platform specializing in mobile and web inventory, contextual advertising, and programmatic yield optimization.

Sharethrough
Native advertising and programmatic supply platform designed around publisher monetization, ad quality, and user experience.

Onetag
Programmatic advertising and monetization platform providing publishers with auction and demand connectivity across digital inventory.

Bidtellect
Programmatic advertising technology provider focused on native advertising, contextual targeting, and publisher monetization.

AdButler
Hosted ad-serving platform providing publishers with direct-sold campaign management, programmatic integrations, targeting, reporting, and inventory management.

AdGlare
Cloud-based ad server for publishers and advertisers supporting display advertising, campaign management, targeting, and reporting.

Broadstreet
Publisher-focused advertising platform designed for direct-sold advertising, campaign management, reporting, and local/media publisher monetization.

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
