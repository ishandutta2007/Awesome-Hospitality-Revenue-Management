# Awesome-Hospitality-Revenue-Management

## Top Revenue Management (Hospitality) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Hotel Dynamic Pricing, Demand Forecasting, Rate Shopping, RevPAR Optimization & Channel Strategy*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Hospitality Revenue Management Systems (RMS)**. These tools help hotels and hospitality groups set and optimize room rates, forecast demand, monitor competitors, and improve RevPAR, occupancy, and total revenue across channels.



**Examples** include Duetto, IDeaS, Atomize, Pace Revenue, BEONx, RoomPriceGenie, RateGain, Infor EzRMS, OTA Insight, and Lybra Tech (the category leaders).



**Open-source emphasis**: Purpose-built open-source hotel RMS platforms are rare. Useful building blocks exist in open hotel PMS projects (e.g. QloApps), pricing/analytics demos, and general forecasting libraries. This section lists the most relevant open options while acknowledging the commercial concentration of the category.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Starting Price | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Duetto](https://www.duetto.com/)** | Cloud-native hospitality revenue platform known for Open Pricing, real-time dynamic decisioning, multi-property forecasting, and casino/upscale hotel optimization. | ~$1,000 / month (base tier depending on room count and property type) | No free forever tier; live personalized demo and customized product walkthrough available upon request (0 trial days). |
| **[IDeaS (SAS)](https://ideas.com/)** | Enterprise-grade RMS (G3 RMS) providing demand forecasting, continuous automated pricing, and total RevPAR management for independent hotels and large chains. | ~$1,200 / month (base tier for independent and boutique properties) | No free forever tier; guided interactive demo and custom pilot evaluation on request (0 trial days). |
| **[Atomize](https://www.atomize.com/)** | Real-time, AI-driven RMS (part of SiteMinder) specializing in automated dynamic rate setting with minimal manual intervention for independent and boutique hotels. | €299 / month (~$325 / month for entry-level tier / smaller properties) | No free forever tier; live interactive pilot and product demonstration upon request (0 trial days). |
| **[FLYR Hospitality (Pace)](https://www.pacerevenue.com/)** | AI-driven revenue management and commercial intelligence engine offering continuous pricing recommendations and granular demand forecasting. | ~$700 / month (base platform tier; or ~€4.00–€13.00/room/month) | No free forever tier; custom platform walkthrough and revenue simulation upon request (0 trial days). |
| **[BEONx](https://beonx.com/)** | Total revenue management and Hotel Quality Index (HQI) pricing platform focused on optimizing RevPAR, occupancy, and guest lifetime value. | ~$800 / month (base tier for mid-size properties) | No free forever tier; customized live proof-of-concept demonstration available upon request (0 trial days). |
| **[RoomPriceGenie](https://www.roompricegenie.com/)** | Automated dynamic pricing platform built specifically for independent hotels, boutique properties, B&Bs, and serviced apartments. | $119 / month (Core plan, billed annually; $139/month billed monthly) | 14-day free trial with full platform access, complimentary onboarding, and no credit card required. |
| **[RateGain](https://rategain.com/)** | Hospitality rate intelligence, real-time rate shopping (Navigator), distribution, and revenue optimization suite. | $25 / month (entry-level Navigator rate shopper tier; bundle plans ~$400/month) | 14-day free trial for Navigator rate shopper with competitive set tracking; demo available for enterprise RMS. |
| **[Infor EzRMS](https://www.infor.com/)** | Enterprise revenue management software featuring demand forecasting and optimization algorithms integrated with the Infor Hospitality suite. | ~$950 / month (base tier for standard hotel deployments) | No free forever tier; tailored enterprise consultation and guided software demo on request (0 trial days). |
| **[Lighthouse (OTA Insight)](https://www.lighthouse-hq.com/)** | Market intelligence, rate-shopping, and pricing platform providing real-time competitor tracking and forward-looking demand signals. | $59 / month (entry-level Rate Insight tier; Pricing Manager tiers scale up) | Free trial upon request (typically 7–14 days customized compset access) + free Market Alerts tier with 90 days of market trend data. |
| **[Lybra Tech](https://www.lybra.tech/)** | AI-powered Assistant RMS delivering real-time demand collection, automated competitor rate tracking, and dynamic pricing suggestions. | $400 / month (base tier for single properties) | No free forever tier; 1-on-1 personalized live demonstration and revenue assessment upon request (0 trial days). |



## Open-Source GitHub Projects

- **[QloApps](https://github.com/Qloapps/QloApps)**  

  Leading open-source hotel PMS and booking engine. Not a full RMS, but provides occupancy, rate, and reservation data that can feed custom pricing logic.



- **[Hotel RMS demos and research apps](https://github.com/)**  

  Full-stack demo applications for hotel pricing optimization, demand forecasting, competitor benchmarking, and natural-language exploration of revenue data (typically using synthetic data).



- **[Open forecasting and time-series libraries](https://github.com/)**  

  General open-source forecasting stacks (Prophet, statsmodels, modern ML libraries) applied by hotels to build internal demand models.



- **[Rate-shopping and market-data open scrapers / APIs](https://github.com/)**  

  Community scripts for collecting public rate information (use carefully and in line with terms of service and law).



- **[Pricing rule engines and decision frameworks](https://github.com/)**  

  Open rule and optimization engines that can encode simple BAR and restriction strategies on top of PMS data.



- **[Odoo / ERPNext hospitality and pricing modules](https://github.com/)**  

  Community modules that extend open ERPs with hotel or rate-management features for smaller properties.



- **[Revenue analytics notebooks](https://github.com/)**  

  Open Jupyter/Observable-style analyses for RevPAR, pickup, pace, and segmentation reporting.



- **[Channel and inventory open connectors](https://github.com/)**  

  Experimental connectors between open PMS systems and channel managers or booking engines.



- **[Sustainable and total-revenue open experiments](https://github.com/)**  

  Research code exploring ancillary and total-hotel revenue optimization beyond room rate alone.



- **[Data pipeline patterns for PMS extracts](https://github.com/)**  

  ETL examples that pull reservation and occupancy data into open analytics stacks for revenue reporting.



### Additional Strong Open-Source Options

- Combining QloApps (or another open PMS) with custom Python/R forecasting and a simple rate-push script.

- Using open BI tools (Metabase, Superset) on top of PMS data for pace and pickup dashboards.

- Local-first pricing spreadsheets version-controlled in Git for very small properties (with clear limits).

- Academic datasets and papers on hotel demand forecasting implemented as open notebooks.

- Integration of open weather, events, and search-trend data as demand signals.



**Frameworks for building custom systems**: For small independents, extract occupancy and booking data from an open or commercial PMS, run open forecasting models, apply transparent pricing rules, and push rates back via channel manager APIs. This can support basic dynamic pricing without a full commercial RMS. Production revenue management for mid-size and large hotels — real-time open pricing, robust competitor intelligence, multi-segment controls, and proven RevPAR lift — remains the domain of commercial platforms (Duetto, IDeaS, Atomize, RoomPriceGenie, Pace, Lybra, etc.).



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Revenue management decisions directly affect hotel financial performance and guest pricing fairness. Open-source and custom pricing systems must be validated carefully, monitored for unintended outcomes, and operated in compliance with local pricing, competition, and consumer regulations. Commercial RMS vendors typically provide implementation support, best-practice configuration, and ongoing model refinement that pure open approaches leave to the property.

- This list is not financial or revenue-management advice.



---

**Made for revenue managers, hoteliers, and hospitality technologists optimizing rate and demand strategy.**

Let's encourage more transparent and data-owned approaches to hospitality pricing where they make sense.
