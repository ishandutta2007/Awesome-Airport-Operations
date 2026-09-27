# Awesome-Airport-Operations

## Top Airport Operations Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Airport Resource Optimization, Flight Information & Operational Intelligence*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Airport Operations Management**. These tools manage airport resource allocation, flight information display, baggage handling, passenger flow, turnaround management, and collaborative decision-making (A-CDM) for airports, ground handlers, and aviation authorities.



**Examples** include Amadeus Airport Operational Database, SITA Airport Management, ADB SAFEGATE OneControl, Veovo, ADB Safegate, AeroCloud, Damarel FiNDnet, INFORM Airport Suite, Amadeus ACUS, and AirIT (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom operational workflows, and transparent airport data management — ideal for airports, ground handlers, researchers, and developers building vendor-independent airport operations solutions. Note that the open-source ecosystem for full-scale airport operations management remains limited compared to other domains, with most projects being academic, simulation-focused, or narrow in scope.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

> **Market Overview:** The global Airport Management Systems (AMS) market is estimated at **$20.0 Billion – $45.7 Billion** (projected to reach $45.72 Billion by 2034 with a ~16.6% CAGR). The sector is **moderately to highly fragmented**, comprising specialized software providers, infrastructure integrators, and global aerospace enterprise conglomerates across flight information display, airside operations, and A-CDM sub-segments.

| Platform | Parent / Company | Company Size (Revenue / Valuation) | Starting Pricing | Free Tier / Trial Limit | Key Features & Focus |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[AirIT](https://www.airit.com/)** | Collins Aerospace / RTX Corp | ~$74.3B Revenue (Parent) / ~$140B Valuation ($20M Division Revenue) | $15,000 / year (Entry operational database & flight display base tier) | 30-day sales-assisted demonstration trial with sample flight data sandbox | Airport IT services offering flight information display systems (FIDS) and operational database solutions deployed at major international hubs like Philadelphia. |
| **[Amadeus Airport Operational Database](https://amadeus.com/en/airports/airport-operational-database)** | Amadeus IT Group | ~$7.69B (€6.5B) Revenue / ~$25B Valuation | $15,000 / year (Regional airport tier base contract) | 30-day proof-of-concept trial environment for up to 5 operator accounts | Central operational database consolidating real-time flight, resource, and passenger data for airport-wide situational awareness. |
| **[Amadeus ACUS](https://amadeus.com/en/airports)** | Amadeus IT Group | ~$7.69B (€6.5B) Revenue / ~$25B Valuation | $1,200 / month ($14,400 / year) per airport terminal gate/kiosk license | 30-day developer sandbox environment for CUSS/CUPPS integration testing | Cloud Common Use Service for flexible passenger processing, mobile check-in, and shared airport terminal infrastructure. |
| **[SITA Airport Management](https://www.sita.aero/solutions/sita-airport-management/)** | SITA | ~$1.5B Revenue / ~$3.0B Valuation | $12,000 / year (Tiered by annual passenger movement volume) | 30-day evaluation sandbox trial with simulated flight feeds for airport authorities | Integrated airport operations platform covering flight information, stand allocation, resource management, and A-CDM workflows. |
| **[ADB SAFEGATE OneControl](https://www.adbsafegate.com/)** | ADB SAFEGATE | ~$500M Revenue / ~$1.2B Valuation | $20,000 / year (Per integrated airfield and apron control module) | 14-day guided virtual simulation trial environment for airside operations staff | Unified airport operations control system connecting airside, apron, and terminal management with real-time situational awareness. |
| **[ADB Safegate Apron & Gate Systems](https://www.adbsafegate.com/)** | ADB SAFEGATE | ~$500M Revenue / ~$1.2B Valuation | $18,000 / year (Per terminal apron unit license) | 14-day guided virtual demonstration trial for ground operations team | Visual docking guidance, apron management solutions, and airside surveillance integration. |
| **[INFORM Airport Suite](https://www.inform-software.com/)** | INFORM GmbH | ~$120M Revenue / ~$300M Valuation | $10,000 / year (Per GroundStar resource optimization module) | 30-day proof-of-concept pilot instance for ground handling workforce management | AI-powered airport operations software suite featuring workforce optimization, turnaround management, and passenger flow analytics. |
| **[Veovo](https://www.veovo.com/)** | Veovo / LLR Partners | ~$50M Revenue / ~$150M Valuation | $8,000 / year (Entry passenger queue analytics module) | 30-day guided sandbox trial with up to 2 sensor data stream integrations | Predictive airport operations platform offering passenger flow forecasting, queue monitoring, and real-time asset allocation. |
| **[Damarel FiNDnet](https://www.damarel.com/)** | Damarel Systems | ~$12M Revenue / ~$30M Valuation | $5,000 / year (Per station for ground handling operations) | 30-day full-feature trial instance for accredited ground handling service providers | Airport resource management, slot management, and operational billing system designed for ground handlers and regional airports. |
| **[AeroCloud](https://aerocloudsystems.com/)** | AeroCloud Systems | ~$10M Revenue / ~$50M Valuation ($12.6M Series A raised) | $1,000 / month ($12,000 / year) for general aviation airfields ($3,500 / month for regional airports) | 14-day live software demo trial with up to 10 active flight track monitors | Cloud-native Airport Operating System (AOS) unifying flight management, AI gate allocation, FIDS, billing, and passenger management. |




## Open-Source GitHub Projects



- **[A-CDM Simulator](https://github.com/A-CDMteam/SimuladorV2.0)**  

  Agent-based simulation environment for Airport Collaborative Decision Making (A-CDM) developed as a thesis project at Universitat Politècnica de Catalunya. Implements the full Eurocontrol Milestone Approach with 16 milestones, flight plan activation, time calculations (ETOT, TFIR, ELDT, EIBT, TOBT, TSAT), and multi-agent coordination between CFMU, airport, airline, and ground handler agents. Designed for research and training in A-CDM concepts .



- **[Airport Traffic Control Simulator](https://github.com/Henrique-Versiani/Airport-Traffic-Control)**  

  Simulation of air traffic control for a high-demand international airport, developed in C with PThreads. Models runways, gates, and control towers as managed resources with distinct rules for domestic and international flights. Implements deadlock detection and resolution via resource preemption, starvation prevention through priority aging, and comprehensive logging. Demonstrates concurrency management principles applicable to real airport operations .



- **[Airport Database Management System (Jana-Ahmed)](https://github.com/Jana-Ahmed-20005/Airport-database-managment-system)**  

  Fully integrated platform designed to control and optimize major airport operations including flight scheduling, passenger check-in, baggage handling, and security monitoring. Supports multiple user types (Passengers, Airline Employees, Flight Crew) with role-based functionality for coordination across departments. Features flight delay/cancellation tracking, gate change notifications, staff assignment, and baggage status monitoring .



- **[FIDS Server (bhishekarora)](https://github.com/bhishekarora/FIDS)**  

  Simple Flight Information Display System written in Angular/Node/MySQL/WebSockets for small airports or lounges. Features admin panel for screen management, arrivals/departures content updates, advertisement display, and multiple screen mapping. API-based architecture allows plugging in any flight data source. Suitable for prototyping FIDS functionality .



- **[OpenFIDS](https://github.com/henrus1/openfids)**  

  Free, self-hosted flight information display system that any airport can install on almost any computer. PHP and SQL-based with multiple display options and customizable layouts. Designed for quick deployment and commercial use. Last updated 2017 but functional for basic FIDS needs .



- **[Airport Management System (BDIZ)](https://github.com/soalko/BDIZ_Project)**  

  Python/PySide6 desktop application with PostgreSQL backend for managing airport data including aircraft, flights, passengers, tickets, crews, and crew members. Features graphical interface, database schema management, demo data generation, and data integrity validation. Academic project demonstrating full-stack airport data management .



- **[Aeroporto Napoli Desktop Application](https://github.com/mattialemma/Applicativo_Aeroporto)**  

  Java Swing desktop application with PostgreSQL for centralized management of Naples airport operations. Features flight monitoring, booking management, baggage tracking with lost baggage reporting, and role-based access (generic user vs administrator). Real-time homepage showing arrivals/departures with delay and cancellation highlighting .



- **[CDM Plugin (skyelaird)](https://github.com/skyelaird/CDM)**  

  Euroscope plugin implementing Airport Collaborative Decision Making (A-CDM) functions for VATSIM/IVAO air traffic control simulation. Features EOBT/TOBT/TSAT/TTOT management, flight state coloring, CDM airport panel, ATFCM flight list, and CDM-Network integration. Implements real-world A-CDM procedures in a simulation environment .



- **[GestionAir](https://github.com/ffillouxdev/GESTIONAIR)**  

  Console application in C for managing flight operations at Grenoble Alpes Isère Airport. Features flight schedule display, flight search by airline/destination/time, passenger boarding management, delay handling with rescheduling, cancellation processing, and runway utilization maximization. CSV-based data persistence. Academic project demonstrating core airport operations logic .



### Additional Strong Open-Source Options



- **Applicativo Aeroporto (mattialemma)** — Java/PostgreSQL desktop application for Naples airport management with booking, baggage tracking, and admin controls .

- **BDAD_airportManagement** — SQL database designed from scratch to manage data related to a specific airport. Basic schema without application layer .

- **Onix** — Web platform for managing Brazilian airports with resources for multiple airport management with their own aircraft. Limited documentation available .

- **Flight Information Library (C#)** — Extracts flight information from aircraft movements including departure/arrival airfield and times, total flight time, and more. Library component for FIDS integration .



**Frameworks for building custom airport operations solutions**: For A-CDM research and simulation, the **A-CDM Simulator** provides a complete Eurocontrol milestone implementation. For concurrency and resource management studies, the **Airport Traffic Control Simulator** demonstrates deadlock handling and starvation prevention. For FIDS deployment, **bhishekarora/FIDS** or **OpenFIDS** offer lightweight starting points. For database-centric operational systems, the various airport database management projects provide schema foundations. Note that no comprehensive open-source replacement for commercial airport operations platforms (Amadeus AODB, SITA, ADB SAFEGATE OneControl) currently exists — the open-source ecosystem remains fragmented and primarily academic.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Airport operations tools must comply with aviation regulations (ICAO Annex 14, EASA, FAA) and security standards.

- Self-hosted open-source solutions require proper aviation-grade security, reliability, and regulatory validation before operational deployment.

- The open-source ecosystem for full-scale airport operations management is significantly less mature than commercial offerings. Most projects listed are academic, simulation-focused, or narrow in scope. Production deployments should carefully evaluate gaps in functionality, security, and regulatory compliance.



---



**Made for airports, ground handlers, aviation authorities, and airport technologists.**  

Let's make airport operations management more open, data-driven, and efficient.
