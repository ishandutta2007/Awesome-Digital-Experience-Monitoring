# Awesome-Digital-Experience-Monitoring

## Top Digital Experience Monitoring (DEM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on End-User Experience, Synthetic Monitoring, Network Path Visibility, DEX Metrics & Application Performance from the User Perspective*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Experience Monitoring (DEM)**. These systems measure how applications and networks perform for real users—combining endpoint, RUM, and synthetic data to find issues before tickets pile up.



**Examples** include Nexthink, Aternity, ControlUp, ThousandEyes, Lakeside SysTrack, Dynatrace DEM, Catchpoint, EG Innovations, and New Relic DEM (the category leaders).



**Open-source emphasis**: Full commercial DEM/DEX suites dominate enterprises. Open options include **Grafana Faro**, **OpenTelemetry RUM**, **k6**, **Blackbox exporter**, **OpenReplay**, and endpoint metrics stacks. This section lists every significant relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Nexthink, ControlUp, Lakeside SysTrack, Aternity](https://www.nexthink.com/)**  

  Digital employee experience (DEX) and EUC monitoring platforms focused on endpoint and workspace performance.



- **[ThousandEyes (Cisco), Catchpoint](https://www.thousandeyes.com/)**  

  Internet and network path monitoring—synthetic and BGP/visibility for digital experience across the public internet.



- **[Dynatrace DEM, New Relic DEM](https://www.dynatrace.com/)**  

  Full-stack observability platforms with digital experience and RUM modules.



- **[EG Innovations and other DEM specialists](https://www.eginnovations.com/)**  

  Additional user-centric and infrastructure experience monitoring products.



- **[Other commercial DEM platforms](https://www.nexthink.com/)**  

  Hybrid DEX + synthetic offerings for enterprise IT.



## Open-Source GitHub Projects



- **[Grafana Faro](https://github.com/grafana/faro-web-sdk)**  

  Open Web SDK for real user monitoring—performance, errors, and user events into Grafana stacks.



- **[OpenTelemetry Client / RUM instrumentation](https://github.com/open-telemetry/opentelemetry-js)**  

  Open standard for browser and mobile telemetry feeding any OTel-compatible backend.



- **[k6](https://github.com/grafana/k6)**  

  Open modern load and synthetic testing tool—scriptable checks for critical user journeys.



- **[Prometheus Blackbox Exporter](https://github.com/prometheus/blackbox_exporter)**  

  Open probe exporter for HTTP/TCP/ICMP synthetic monitoring of endpoints and services.



- **[OpenReplay](https://github.com/openreplay/openreplay)**  

  Open-source session replay and product analytics—self-hosted experience debugging.



- **[Grafana Synthetic Monitoring / worldPing patterns](https://github.com/grafana/synthetic-monitoring-agent)**  

  Open components for continuous synthetic checks integrated with Grafana Cloud or self-hosted.



- **[osquery + endpoint metrics](https://github.com/osquery/osquery)**  

  Open endpoint instrumentation useful for DIY digital employee experience signals.



- **[Checkmk / Zabbix user-experience plugins](https://github.com/Checkmk/checkmk)**  

  Open monitoring systems extensible with synthetic and application checks.



### Additional Strong Open-Source Options



- **Browser RUM**: Grafana Faro or OpenTelemetry JS.

- **Synthetics**: k6 + Blackbox exporter.

- **Session context**: OpenReplay for reproduction.

- **Composable stacks**: Faro/OTel → Grafana Tempo/Prometheus/Loki; k6 for journey SLOs; osquery for endpoint health.

- Commercial DEM still leads in DEX scoring, agent depth, and internet-path intelligence (ThousandEyes-class).



**Frameworks for building custom systems**:  

**OpenTelemetry** + **Grafana Faro** for RUM; **k6** / **Blackbox** for synthetics; **OpenReplay** for session insight; **osquery** for endpoints.  

Commercial DEM (Nexthink, Aternity, ControlUp, ThousandEyes, Dynatrace, etc.) provides unified DEX and path visibility.  

Teams can assemble open DEM-like stacks for web apps; enterprise EUC experience usually needs commercial DEX agents. Fully open DEM is partial but strong for web/synthetic layers.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Experience monitoring collects user and device signals. Apply privacy notices, minimize PII, and comply with employment and data-protection law. Synthetic checks should not overload production systems.

- Open-source tools offer control and cost efficiency but require integration. Commercial DEM platforms shift agent coverage and analytics to the vendor. Neither replaces good incident response and application ownership.



---



**Made for SRE, EUC, and digital workplace teams who measure experience, not just uptime.**  

Let's expand open RUM and synthetic monitoring while recognizing the DEX and internet-path depth that leading commercial DEM platforms deliver.
