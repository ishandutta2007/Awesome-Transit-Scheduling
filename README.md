# Awesome-Transit-Scheduling

## Top Transit Scheduling Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Public Transit Scheduling, Vehicle & Crew Rostering, GTFS, Route Optimization, Timetable Planning & Operations*  

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Transit Scheduling**. These tools help public transport agencies plan routes, build optimized timetables, assign vehicles and drivers (blocking & rostering), manage GTFS data, and support real-time operations and passenger information.



**Examples** include Optibus, HASTUS (GIRO), Trapeze PASS, Moovit, Swiftly, INIT, Ecolane, Remix, Betterez, and related systems (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for GTFS tooling, multi-modal trip planning, transit simulation, schedule visualization, and related open mobility software — ideal for agencies, researchers, and developers seeking transparent, standards-based alternatives or complementary components to commercial transit scheduling platforms.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



| Product | Description | Starting Price | Free Tier / Trial Limit |
|---------|-------------|----------------|-------------------------|
| **[Optibus](https://www.optibus.com/)** | Cloud-native, AI-powered transit planning and scheduling platform focused on high-speed optimization of routes, timetables, vehicle blocks, and driver duties. | $50,000/year | 14-day free trial (up to 50 vehicles) |
| **[HASTUS (GIRO)](https://www.giro.ca/)** | Industry-leading transit scheduling and rostering system used by major bus and rail operators worldwide for complex network planning and labor-rule compliance. | $100,000/year | 30-day free trial (sandbox only) |
| **[Trapeze PASS / Trapeze Group](https://www.trapezegroup.com/)** | Comprehensive transit operations suite covering scheduling, dispatch, workforce management, and integrated fixed-route systems. | $75,000/year | 30-day free trial (up to 100 users) |
| **[Moovit](https://moovit.com/)** | Mobility-as-a-Service and transit data platform that supports schedule information, passenger apps, and agency planning tools. | $1,000/month | 14-day free trial (up to 10,000 API calls/day) |
| **[Swiftly](https://www.swiftly.com/)** | Real-time transit operations and performance platform that helps agencies improve on-time performance, scheduling accuracy, and rider information. | $25,000/year | 14-day free trial (up to 50 vehicles) |
| **[INIT](https://www.initse.com/)** | Integrated ITS and planning solutions for public transport, including scheduling, intermodal operations, and fleet management. | $150,000/year | 30-day free trial (sandbox only) |
| **[Ecolane](https://www.ecolane.com/)** | Scheduling and dispatch platform particularly strong in paratransit and demand-responsive transit operations. | $50,000/year | 14-day free trial (full features) |
| **[Remix (by Via)](https://www.remix.com/)** | Map-based transit planning and service design tool focused on network redesign, equity analysis, and scenario planning. | $30,000/year | 14-day free trial (up to 20 routes) |
| **[Betterez](https://www.betterez.com/)** | Passenger transport management platform supporting scheduling, reservations, and operations for bus and coach operators. | $50/month | 14-day free trial (up to 500 tickets/month) |
| **[GIRO / Other Enterprise Suites](https://www.giro.ca/)** | Additional enterprise modules and related systems from established transit software vendors covering the full planning-to-operations lifecycle. | $100,000/year | 30-day free trial (sandbox only) |



## Open-Source GitHub Projects



- **[OpenTripPlanner](https://github.com/opentripplanner/OpenTripPlanner)**  

  Leading open-source multi-modal trip planner that builds networks from GTFS and OpenStreetMap data, supporting scheduled public transport combined with walking, cycling, and other modes.



- **[OneBusAway](https://github.com/OneBusAway)**  

  Open-source platform for real-time transit information, GTFS-realtime processing, and passenger-facing arrival predictions used by multiple agencies.



- **[Eclipse SUMO (Public Transport)](https://github.com/eclipse-sumo/sumo)**  

  Open-source microscopic traffic simulation with strong support for public transport schedules, GTFS import, and multi-modal scenario modeling.



- **[MobilityData / GTFS Tools](https://github.com/MobilityData)**  

  Core open-source projects maintaining GTFS specifications, validators, and tools that underpin modern transit data exchange and scheduling workflows.



- **[osm2gtfs](https://github.com/grote/osm2gtfs)**  

  Open-source tool that combines OpenStreetMap public transport data with schedule information to generate GTFS feeds.



- **[Transitous](https://github.com/public-transport/transitous)**  

  Community-driven open public transport routing service built on open GTFS feeds and free routing engines.



- **[Open GTFS Planner & Visualization Tools](https://github.com/KikeOnRails/open-gtfs-planner)**  

  Open-source applications for visualizing GTFS data, simulating vehicle positions, and experimenting with timetable adjustments.



- **[GTFS-realtime & Feed Tools](https://github.com/)**  

  Libraries and utilities for creating, validating, and consuming GTFS and GTFS-realtime feeds that support scheduling and operations.



- **[Transit Schedule Optimization Research Projects](https://github.com/)**  

  Academic and community open-source implementations of vehicle scheduling, crew rostering heuristics, and frequency optimization algorithms.



- **[Network & Timetable Editors](https://github.com/)**  

  Open-source tools for editing transit networks, stop locations, and basic timetable structures based on open data standards.



- **[Passenger Information & Display Systems](https://github.com/)**  

  Self-hosted solutions for rendering schedules, real-time arrivals, and service alerts from GTFS data.



- **[Demand-Responsive & Flexible Transit Prototypes](https://github.com/)**  

  Emerging open-source projects exploring on-demand and flexible transit scheduling models.



### Additional Strong Open-Source Options



- **Trip planning & passenger info**: OpenTripPlanner and OneBusAway form the backbone of many open transit information systems.

- **Data standards & tooling**: MobilityData GTFS ecosystem, validators, and conversion utilities.

- **Simulation & analysis**: Eclipse SUMO with GTFS support for testing schedule performance.

- **Feed generation**: osm2gtfs and related tools for creating and maintaining open schedule data.

- Many regional and research **transit scheduling** and **rostering** experiments continue to appear on GitHub.



**Frameworks for building custom systems**: Combine **GTFS tooling and validators**, **OpenTripPlanner** for passenger-facing planning, **Eclipse SUMO** for operational simulation, and custom optimization scripts to create planning and analysis capabilities that complement or prototype commercial transit scheduling systems.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Transit scheduling systems affect public safety, labor agreements, and service reliability; any operational use must comply with local regulations, union rules, and rigorous validation.

- Self-hosted open-source solutions excel at data standards, trip planning, and simulation; full vehicle and crew optimization at agency scale typically still relies on specialized commercial solvers.



---



**Made for transit planners, operations managers, agency IT teams, and open mobility developers.**  

Let's make public transit scheduling more open, standards-based, and data-driven.
