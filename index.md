---
layout: cv
title: Robin Bryce, CV
---

# Robin Bryce

[github](https://github.com/robinbryce/)
[linkedin](https://www.linkedin.com/in/robin-bryce-02b3464/)
[medium](https://robinbryce.medium.com/)
[games credits](https://www.mobygames.com/person/120567/robin-bryce/credits/)

## Currently

Principle Engineer, [Datatrails](https://www.datatrails.ai/).
Co-Founder, [Polysensus](https://www.polysensus.com/).

## Career summary

* 2018 - Current: Leading the research and development of Datatrails digital provenance solution and generally responsible for product architecture.
* 2022: Founded Polysensus to explore the possibilities of blockchains with an increasing focus on games.
* 2005 - 2018: Enjoyed a 13 year freelance contracting career mostly specialized in security applications and HSM firmware, with some exposure to medical devices and post processing gene sequencing data.
* 2003: Founded Wiretooth, initially conceived as a maker of multi player SMS games.
* 1994 - 2003: During my early career in the games industry I was credited on many successful and popular console and pc games, primarily as a graphics engine programmer.

## Publications & Articles

<!-- A list is also available [online](http://scholar.google.co.uk/citations?user=LTOTl0YAAAAJ) -->
### Datatrails & IETF

* [COSE Merkle Mountain Range Proofs](https://datatracker.ietf.org/doc/draft-bryce-cose-merkle-mountain-range-proofs/) (author)
* IETF Conference intro for [draft-bryce-cose-merkle-mountain-range-proof](https://youtu.be/hI2y44NykwQ?list=PLC86T-6ZTP5iW_EW2fpjMvIhLb1uTEkMQ&t=5475)
* [SCITT](https://datatracker.ietf.org/doc/draft-birkholz-scitt-architecture/) contributor
* [Google Transparency Dev 2024 talk](https://www.youtube.com/watch?v=pfMVQBUZfbQ) on the Datatrails choice of MMR's for their ledger layer.
* [If you go down to the woods today](https://www.datatrails.ai/if-you-go-down-to-the-woods-today/) A deep dive on MMR's contrasted against RFC 6962 (Certificate Transparency)

### Personal and gaming/blockchain related

* [The persistence of ten-year-olds](https://robinbryce.medium.com/the-persistence-of-ten-year-olds-and-reading-trie-leaves-in-fog-40417f9c85bf) Backgrounder and introduction to the Chaintrap game I made for Optimism Builders Grant, cycle 11.
* [From Pages to Tree Leaves](https://robinbryce.medium.com/from-pages-to-tree-leaves-c44ea9c81fa2) A deep dive on a generalized commit reveal system for "choose your own adventure" games on a blockchain (also Chaintrap related).
* [Autonomous Worlds Hack 2024](https://robinbryce.medium.com/autonomous-worlds-2024-c7833daa111a) Got ERC 6551 going on redstone and demonstrated how holding a token in one game could authorize activity in a second with no code changes in the origin game.
* Participated in the Redstone launch hackathon by creating a frontend for the AW 2024 Tug of War hack. In tug of war, players in two discrete game worlds participate in a tug of war by pulling on a "rope" the connects their realities.

## Significant open source & public repositories

### Tiled transparency logs using MMR's - 2023

* [go-datatrails-merklelog](https://github.com/datatrails/go-datatrails-merklelog) (production)
* [mmriver-tiles-ts](https://github.com/robinbryce/mmriver-tiles-ts) - not production, made for contrast with the [Sunlight CT](https://docs.google.com/document/d/1YsxLGZxYE1KTCTjDK2Ol-bcTzbrI313SZ1QWgqmnRDc/edit?tab=t.0#heading=h.2tc8kbu84230) implementation

### Chaintrap - 2022

A commit / reveal "nearly finished" choose your own adventure system, part funded by a builders [grant from Optimism](https://gov.optimism.io/t/final-chaintrap-builders-cycle-11/5526)

[chaintrap-ifw.vercel.app](https://chaintrap-ifw.vercel.app/)

The following links refer to work funded by a [Optimism builders grant](https://gov.optimism.io/t/final-chaintrap-builders-cycle-11/5526)

* [game client](https://github.com/polysensus/chaintrap-ifw) svelte
* [game contracts](https://github.com/polysensus/chaintrap-contracts) forge foundry
* [game middleware](https://github.com/polysensus/chaintrap-arenastate) essentially an in browser indexer

I've most recently been adding support maps from [watabou](https://watabou.itch.io/)


### RRR L1 Implementation - 2021

An implementation of the [RRR](https://arxiv.org/pdf/1804.07391?) consensus algorithm for [go-quorum](https://docs.goquorum.consensys.io/), which is itself a fork of go-ethereum.
Tested to a scale of 100 nodes at 500+ TPS, with a block latency of about 1.5 seconds.

This [video demo](https://www.youtube.com/watch?v=ACJ1o5oYE3E), introduces RRR. The original version of Chaintrap was made as an application to test the network in a fun way. It later "grew legs" when it qualified for an optimism builders grant. The video shows the game running concurrently on the RRR network and the Polygon network "head to head".

* [go-rrr](https://github.com/RobustRoundRobin/go-rrr)
* [quorum](https://github.com/RobustRoundRobin/quorum)
* [test infra and results](https://github.com/robinbryce/benchblock)

### Iona - almost zero cost at idle cloud services infra - 2020

This infrastructure was used for various projects that benefited from kubernetes style deployment. Its goal was to minimize operational costs, while enabling services for various projects to be conveniently deployed in a git ops manner.

https://github.com/robinbryce/iona/

### Patents

`2021` Recording changes to an assets attributes using distributed ledger smart contracts - [GB2614297](https://www.ipo.gov.uk/p-ipsum/Case/PublicationNumber/GB2614297)

`2024` A system for combining merkle mountain ranges with commodity cloud storage for cost effective, performant, transparency and tamper evidence where a single gatekeeper for additions is acceptable - [PC933720GB]

## Employment History

### 2018 - Current: Principal Engineer - Datatrails

* Research and development of Datatrails digital provenance ledger [Forestrie](https://www.datatrails.ai/we-are-not-a-blockchain-company/).
* Blockchain operations and smart contract development.
* Driving architecture, performance and scaling for the general datatrails platform.
* Innovating all aspects of engineering practice.
* Program manager for Datatrails Media Authenticity & Auditability product line.

### 2016 - 2018 Thales / Entrust: Contracted Engineer

[Entrust](https://www.entrust.com/)
[Thales UK](https://www.thalesgroup.com/en/countries/europe/united-kingdom)

* Added support for the Python 3 run time environment to the Secure Execution Environment on the HSM.
* Supported EIDAs re-certification for the nShield HSM's in brazil by defending the firmware code in lab review.
* Supported original EIDAs certification for the nShield HSM's by meticulously accounting for all security relevant aspects of the firmware.

Entrust Data Card acquired the nCipher HSM line through a divestment by Thales, who had originally purchased nCipher.

### 2014 - 2016 Illumina - RGH: Contracted Engineer

[Illumina - RGH/Cambridge](https://emea.illumina.com/services/training/solutions-centers/europe/cambridge.html)

Undertook many projects where an eclectic range of skills were helpful.

Server build and application software providing for private cloud  hosted secondary gene sequencing analysis. Involved everything from root causing incompatible hardware component selection (RAM modules) to providing secure ldap integration and user management for the analyses application software.

### 2005 - 2013 (Multiple contracts): Contracted Engineer - nCipher / Thales

[Thales UK](https://www.thalesgroup.com/en/countries/europe/united-kingdom)

During this period I typically worked for 8-10 months of the year under contract to nCipher / Thales making myself as generally useful as possible. For the remainder I indulged my passion and obsession for skiing by regularly seasoning in Tignes and Verbier. Possibly the best work/life balance I've achieved so far! 

Projects undertaking during this time included,

* Developing patches for apache2 and mod_ssl enabling PKCS#11 interfaced use of keys hosted in HSM's.
* Developing a core component of a distributed key management solution.
* A great deal of work supporting distributed build systems for very diverse platforms, including hpux, aix, solaris.
* Bespoke distributed build system creation and development (pre jenkins era)
* Migrating very large source code repositories and rapidly replacing the related crucial infrastructure.

### 2004 - 2005: Contracted Engineer - miscellaneous contracts
* Film asset browser prototype using the XEROX PARC startree algorithm for large dataset visualization. C++,  OpenGL, (Linux & Windows). 
* Web tools and services in Python supporting a geographically distributed film production
* Optimization project for a cloud gaming solution that used MPEL mpeg tricks in combination with Direct X dll trampolining to live stream gaming content. Raised the frame rate from 3 fps to 30 in a couple of days. But also identified that the approach was a technical dead end due to the industry transition away from fixed function graphics pipelines to pixel and vertex shader architectures.

### 2003 - 2005: Directory & co-founder - Wiretooth Ltd

* I co-founded Wiretooth Ltd. in 2003 with the objective of building and operating online and mobile games services that capitalize on the social and creative needs fuelling massive growth in the online, mobile and casual gaming sectors.
* We worked around the payments strangle hold of mobile operators by block purchasing SMS messages from a south african sms reseller and using premium rate sms messages for billing transactions.
* In August 2004 I visited China as part of China-UK ICT trade delegation and met with many companies and individuals active in the online / mobile games industry. During the trip we were asked if we were willing to buy a Chinese book company and distribute their content in the UK. I since wish I had understood leveraged finance at the time! We also had discussions about delivering our SMS racing game in time for the Beijing summer Olympics.
* In 2005 Wiretooth failed to secure further funding and the project was set aside.

### 1999 - 2003 Frontier Developments Ltd

* 2001 – 2003: Xbox Lead Engineer, Senior Software Engineer. Xbox, GameCube, and PC engine development. Primarily responsible for Xbox skew of multi platform game engine. 
* 2000 – 2001: Project Lead - Dogs Tale. Responsible for managing a team comprising of 6 programmers and 6 artists. Delivered content and game play that secured full PS2 development contract.
* 1999 - 2000: Lead Programmer - Dogs Tale. Tasked with re-gearing a projects technologies and art direction from Sony Play Station 1 to suit Play Station 2 and modern PC hardware.

### 1997 – 1999: Senior Software Engineer (Graphics specialist) - Kuju Entertainment Ltd

* Worked on various aspects of Kuju's bespoke graphics engine.
* Ported Xenocracy to the Sega Dreamcast in two weeks (of a flat food diet).
* Was particularly involved in ensuring feature compatibility and performance of the engine across the range of bespoke GPU's of that era.

### 1996 - 1997: Walrond Software Research
* Developed an oct tree based terrain system for a flight simulation game.

### 1994 - 1996: Programmer - Revolution Software Ltd.

The computer science degree I was enrolled on had an industrial placement year. To secure a placement with Revolution Software, I traveled from Edinburgh to London to attend the ECTS trade show where I lurked outside the hospitality suite for Revolution's publisher. I had a copy of Edge magazine in hand so as to be sure to recognize Charles Cecil if he emerged. Which he did after some hours! He very kindly agreed to interview me and, subject to a reference from my tutors, offered me my first job in the games industry. I managed to catch their attention because they were seeking a grant from the DTI based on the use of artificial intelligence in games. I had some undergraduate track record studying genetic algorithms and simple neural networks.

During this paid internship, I developed a neural network to simulate "human like" exploration behavior. I presented this to the DTI and Revolution secured a grant  7x my salary as a result and won the DTI's SMART award for innovation.

## Education

* 1994 completed 3 years of (Hons) B.S.c Computing
* 1990 5 Higher Grade (Scottish A-Level) Physics, Computing, English, Modern Studies, Art.