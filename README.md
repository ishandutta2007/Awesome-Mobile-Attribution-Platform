# Awesome-Mobile-Attribution-Platform

## Top Mobile Attribution Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Mobile Measurement Partners (MMP), Install & Event Attribution, Deep Linking, Fraud Prevention, SKAN & Privacy-Centric App Marketing Analytics*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Mobile Attribution**. These systems (often called Mobile Measurement Partners or MMPs) attribute app installs and in-app events to marketing sources, support deep linking, help measure campaign ROI, and navigate privacy changes such as ATT and SKAdNetwork.



**Examples** include AppsFlyer, Adjust, Branch, Singular, Kochava, Airbridge, Tenjin, Adobe Attribution, Rockerbox, and Northbeam (the category leaders and adjacent attribution tools).



**Open-source emphasis**: Full-featured commercial MMPs with broad ad-network integrations, fraud suites, and SKAN support dominate the market. Open-source activity is limited but includes the **OpenAttribution** project aiming to give app developers ownership of their attribution data, plus SDKs, analytics building blocks, and research tools. This section lists every significant relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AppsFlyer](https://www.appsflyer.com/)**  

  Leading mobile attribution and marketing analytics platform with extensive partner integrations, deep linking, fraud protection, and support for modern privacy frameworks including SKAdNetwork.



- **[Adjust](https://www.adjust.com/)**  

  Privacy-focused mobile measurement platform strong in attribution, automation, and fraud prevention, widely used by gaming and app marketers.



- **[Branch](https://www.branch.io/)**  

  Platform specializing in deep linking, web-to-app journeys, and attribution, often chosen when linking and deferred deep links are central to growth.



- **[Singular](https://www.singular.net/)**  

  Marketing analytics and mobile attribution platform known for cost aggregation, ROI visibility, and unified reporting across channels.



- **[Kochava, Airbridge, Tenjin](https://www.kochava.com/)**  

  Additional MMPs offering attribution, audience tools, and measurement solutions with varying strengths in privacy, cost, and regional coverage.



- **[Adobe Attribution, Rockerbox, Northbeam](https://business.adobe.com/)**  

  Broader or multi-touch attribution platforms that extend beyond pure mobile MMP use cases into web and cross-channel measurement.



- **[Other commercial mobile attribution & measurement platforms](https://www.appsflyer.com/)**  

  Solutions supporting install attribution, in-app event tracking, and campaign optimization under current privacy constraints.



## Open-Source GitHub Projects



- **[OpenAttribution](https://github.com/OpenAttribution/open-attribution)**  

  Open-source mobile measurement platform (MMP) project focused on giving developers ownership of their advertising and attribution data. Includes tracking components, attribution logic (including customizable SQL), SDKs, and analytics dashboard concepts (early-stage / alpha).



- **[OpenAttribution SDKs](https://github.com/OpenAttribution)**  

  Companion open iOS and Android SDKs intended for in-app event and attribution signal collection under the OpenAttribution architecture.



- **[Mobile analytics & event open SDKs](https://github.com/search?q=mobile+analytics+SDK+OR+app+event+tracking+open+source)**  

  Open libraries for collecting app events that can feed custom attribution or product analytics pipelines.



- **[Deep linking open libraries](https://github.com/search?q=deep+link+OR+deferred+deep+link+open+source)**  

  Community tools and patterns for implementing deep links and deferred deep linking outside full commercial platforms.



- **[Privacy & SKAN-related open tools](https://github.com/search?q=SKAdNetwork+OR+ATT+OR+privacy+sandbox+mobile)**  

  Experimental and research projects around Apple’s SKAdNetwork, privacy sandbox concepts, and privacy-preserving measurement.



- **[Fraud detection research & heuristics](https://github.com/search?q=ad+fraud+OR+click+fraud+detection)**  

  Open approaches and datasets related to click/install fraud that some teams study or adapt.



- **[Self-hosted analytics stacks](https://github.com/search?q=PostHog+OR+Matomo+OR+self-hosted+analytics)**  

  Open product analytics platforms that can be combined with custom attribution logic for partial measurement ownership.



- **[Ad cost & marketing data connectors](https://github.com/search?q=ad+cost+API+OR+marketing+ETL+open+source)**  

  Open connectors and pipelines for pulling spend data that complement attribution results in a warehouse.



### Additional Strong Open-Source Options



- **OpenAttribution**: The primary open-source effort explicitly aiming to be a self-hosted MMP alternative with data ownership.

- **Custom pipelines**: Event SDKs + warehouse + SQL attribution models for teams willing to build and maintain their own logic.

- **Deep linking libraries**: Open components for link routing when full MMP deep-linking suites are not required.

- **Privacy-first experiments**: Research code around aggregated and delayed measurement models.

- Full commercial MMP feature sets (partner integrations, fraud suites, SKAN dashboards, support) remain far more mature.



**Frameworks for building custom systems**:  

**OpenAttribution** is the most visible open-source project positioned as an MMP alternative focused on data ownership.  

Beyond that, teams can assemble event collection SDKs, deep-linking libraries, and warehouse-based attribution logic.  

Commercial platforms (AppsFlyer, Adjust, Branch, Singular, Kochava, etc.) provide the partner ecosystem, fraud prevention, SKAN support, and operational tooling that most paid user-acquisition teams need.  

Privacy changes have made pure deterministic attribution harder; both commercial and open approaches must work within platform constraints (ATT, SKAN, Privacy Sandbox). Many organizations use a commercial MMP for core measurement and retain flexibility via data export into their own warehouse.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Mobile attribution operates under evolving platform privacy rules (ATT, SKAdNetwork, etc.). Measurement accuracy and available signals change over time; no system can fully restore pre-ATT deterministic attribution on iOS.

- Open-source attribution tools offer data ownership and transparency but require significant engineering for integrations, fraud defense, compliance, and ongoing maintenance. Commercial MMPs shift that burden to the vendor. Evaluate data governance, security, and regulatory requirements carefully.



---



**Made for mobile growth teams, UA managers, app developers, and measurement specialists.**  

Let's expand options for transparent, owned attribution data while recognizing the partner coverage, fraud tooling, and operational maturity that leading commercial mobile attribution platforms deliver.
