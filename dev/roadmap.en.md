---
layout: page
title: Roadmap
permalink: /roadmap/
page_id: roadmap
nav_order: 700
---

# Roadmap

## Macroscopic Roadmap

| Version | Date | Features |
|:---:|:---:|---|
| Papi-web 1.x | 2013–2023 | Initial version |
| Papi-web 2.0 | Nov 2023 | Improved display screens |
| Papi-web 2.1 | Dec 2023 | Connection to ChessEvent |
| Papi-web 2.2 | Mar 2024 | Performance improvements, illegal moves |
| Papi-web 2.3 | Apr 2024 | Check-in feature |
| Papi-web 2.4 | Oct 2024 | Open-source<br/>Multilingual support<br/>Web configuration<br/>SQLite storage |
| Papi-web 2.5 | Apr 2025 | Interface improvements<br/>Player management<br/>Ranking calculation, display, and printing |
| Papi-web 2.x | 2025 | **Functionality parity with Papi 3.3.8**<br/>Swiss pairings, round-robin and manual, draft/published<br/>Prize calculation<br/>Norm and certificate calculation<br/>Statistics, FIDE performances, TRF import/export, name cards |
| Sharly Chess 3.0 | 2025 | **Additional features not supported by Papi**<br/>Dropping Access format<br/>Results, tiebreaks |

## Detailed Roadmap

- LAN = local network usage (on a local server)
- SaaS = online usage (on a remote server)

|  | PW 1.19<br>Jan 2023 | PW 2.0<br/>Nov 2023 | PW 2.1<br/>Dec 2023 | PW 2.2<br/>Mar 2024 | PW 2.3<br/>Apr 2024 | PW 2.4<br/>Oct 2024 | PW 2.5<br/>Apr 2025 | PW 2.x<br/>2025 | SC 3.0<br/>2025 |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **LAN** | **PW 1.19** | **PW 2.0** | **PW 2.1** | **PW 2.2** | **PW 2.3** | **PW 2.4** | **PW 2.5** | **PW 2.x** | **SC 3.0** |
| Open source | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Free software license | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ AGPL | :heavy_check_mark:︎ AGPL | :heavy_check_mark:︎ AGPL | :heavy_check_mark:︎ AGPL |
| Built-in web server | :x:︎ XAMPP | :heavy_check_mark:︎ Django | :heavy_check_mark:︎ Django | :heavy_check_mark:︎ Litestar | :heavy_check_mark:︎ Litestar | :heavy_check_mark:︎ Litestar | :heavy_check_mark:︎ Litestar | :heavy_check_mark:︎ Litestar | :heavy_check_mark:︎ Litestar |
| Built-in database driver | :x:︎ ODBC | :x:︎ ODBC | :x:︎ ODBC | :x:︎ ODBC | :x:︎ ODBC | :x:︎ ODBC | :x:︎ ODBC | :x:︎ ODBC | :heavy_check_mark:︎ SQLite |
| Windows support | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Windows executable | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Windows executable signing | - | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ |:grey_question:|:grey_question:|
| Linux support | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ |
| Mac support | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ |
| Papi-web configuration | :x:︎ PHP | :heavy_check_mark:︎ INI | :heavy_check_mark:︎ INI | :heavy_check_mark:︎ INI | :heavy_check_mark:︎ INI | :heavy_check_mark:︎ INI | :heavy_check_mark:︎ INI | :heavy_check_mark:︎ INI | :heavy_check_mark:︎ INI/SQLite |
| Event configuration | :x:︎ PHP | :x:︎ INI | :x:︎ INI | :x:︎ INI | :x:︎ INI | :heavy_check_mark:︎ Web | :heavy_check_mark:︎ Web | :heavy_check_mark:︎ Web | :heavy_check_mark:︎ Web |
| Tournament storage | :x:︎ Access | :x:︎ Access | :x:︎ Access | :x:︎ Access | :x:︎ Access | :x:︎ Access | :x:︎ Access | :x:︎ Access | :heavy_check_mark:︎ SQLite |
| Event storage | - | :x:︎ File | :x:︎ File | :x:︎ File | :x:︎ File | :heavy_check_mark:︎ SQLite | :heavy_check_mark:︎ SQLite | :heavy_check_mark:︎ SQLite | :heavy_check_mark:︎ SQLite |

| **SAAS** | **PW 1.19** | **PW 2.0** | **PW 2.1** | **PW 2.2** | **PW 2.3** | **PW 2.4** | **PW 2.5** | **PW 2.x** | **SC 3.0** |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Availability | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ |:grey_question:|
| Open source | - | - | - | - | - | - | - | - |:grey_question:|
| Free software license | - | - | - | - | - | - | - | - |:grey_question:|
| Storage | - | - | - | - | - | - | - | - |:grey_question:|

| **PAIRINGS** | **PW 1.19** | **PW 2.0** | **PW 2.1** | **PW 2.2** | **PW 2.3** | **PW 2.4** | **PW 2.5** | **PW 2.x** | **SC 3.0** |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Swiss pairings | :heavy_check_mark:︎<br/>Papi 3.3.6 | :heavy_check_mark:︎<br/>Papi 3.3.6 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.8 | :heavy_check_mark:︎<br/>Papi 3.3.8 | :heavy_check_mark:︎<br/>bbp 5.0.1 | :heavy_check_mark:︎<br/>bbp 5.0.1 |
| FIDE Handbook C.04 compliance | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ PW 2.5 | :heavy_check_mark:︎ PW 2.6 | :heavy_check_mark:︎ SC 3.0 |
| Round-robin pairings | :heavy_check_mark:︎<br/>Papi 3.3.6 | :heavy_check_mark:︎<br/>Papi 3.3.6 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.8 | :heavy_check_mark:︎<br/>Papi 3.3.8 | :heavy_check_mark:︎ PW 2.6 | :heavy_check_mark:︎ SC 3.0 |
| Manual pairings | :heavy_check_mark:︎<br/>Papi 3.3.6 | :heavy_check_mark:︎<br/>Papi 3.3.6 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.8 | :heavy_check_mark:︎<br/>Papi 3.3.8 | :heavy_check_mark:︎ PW 2.6 | :heavy_check_mark:︎ SC 3.0 |
| Draft/Published status | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| TRF16 import/export | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ |
| TRF25 import/export | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ |

| **RANKINGS** | **PW 1.19** | **PW 2.0** | **PW 2.1** | **PW 2.2** | **PW 2.3** | **PW 2.4** | **PW 2.5** | **PW 2.x** | **SC 3.0** |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Ranking calculation | :heavy_check_mark:︎<br/>Papi 3.3.6 | :heavy_check_mark:︎<br/>Papi 3.3.6 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.8 | :heavy_check_mark:︎ PW 2.5 | :heavy_check_mark:︎ PW 2.x | :heavy_check_mark:︎ SC 3.0 |
| FIDE compliance for unplayed games | :heavy_check_mark:︎<br/>Papi 3.3.6 | :heavy_check_mark:︎<br/>Papi 3.3.6 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :x:︎ | :x:︎ | :heavy_check_mark:︎ PW 2.5 | :heavy_check_mark:︎ PW 2.x | :heavy_check_mark:︎ SC 3.0 |
| FIDE performance compliance | :x:︎ | :x:︎ | :heavy_check_mark:︎<br/>Papi 3.3.7 | :heavy_check_mark:︎<br/>Papi 3.3.7 | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ PW 2.x | :heavy_check_mark:︎ SC 3.0 |

| **INTERNATIONALIZATION** | **PW 1.19** | **PW 2.0** | **PW 2.1** | **PW 2.2** | **PW 2.3** | **PW 2.4** | **PW 2.5** | **PW 2.x** | **SC 3.0** |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| FR (French) | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Multilingual support | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ 2.4.19 | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| EN (English) | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ 2.4.19 | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |

| **FIDE APPROVAL** | **PW 1.19** | **PW 2.0** | **PW 2.1** | **PW 2.2** | **PW 2.3** | **PW 2.4** | **PW 2.5** | **PW 2.x** | **SC 3.0** |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Approval support | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ |:grey_question:| :heavy_check_mark:︎ |

| **USAGE** | **PW 1.19** | **PW 2.0** | **PW 2.1** | **PW 2.2** | **PW 2.3** | **PW 2.4** | **PW 2.5** | **PW 2.x** | **SC 3.0** |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| HTMX usage | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Multi-screen support | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Multi-column support | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Alphabetical pairings | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Rotating displays | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Illegal move recording | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Check-in management | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Result editing | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| FFE - Tournament upload | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| FFE - Data protection | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| ChessEvent - Data download | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Player management | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Pairing printing | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Ranking printing | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Cross-table printing | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| FIDE performances | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Prize calculation | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Norm calculation for players | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Name cards (chevalets) | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :heavy_check_mark:︎ | :heavy_check_mark:︎ |
| Raffle management (tombola) | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ |:grey_question:|:grey_question:|
| Arbiter norm certificates | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ |:grey_question:|
| Team competitions | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ | :x:︎ |:grey_question:|
