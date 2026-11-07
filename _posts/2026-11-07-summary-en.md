---
layout: default
title: "Horizon Summary: 2026-11-07 (EN)"
date: 2026-11-07
lang: en
---

> From 15 items, 15 important content pieces were selected

---

1. [Microsoft Research's AI Frontiers group reportedly shut down as John Langford exits](#item-1) ⭐️ 8.0/10
2. [Every Mac since 2022 runs undocumented personal knowledge graph daemons](#item-2) ⭐️ 8.0/10
3. [Libghostty 1.0: Stable C ABI for Terminal Emulation](#item-3) ⭐️ 8.0/10
4. [Asahi Linux 7.3 Report: New CPU Support, Licensing Concerns](#item-4) ⭐️ 8.0/10
5. [Coldframe: A Honeypot Mimicking Supermarket Fridge Controllers](#item-5) ⭐️ 7.0/10
6. [MaxxBench Critiques DeepSWE Coding Benchmark Scores](#item-6) ⭐️ 7.0/10
7. [Need for Speed Underground 2 Revived Online in the Browser](#item-7) ⭐️ 7.0/10
8. [UK Law Firm Runs Entirely on Free Software in 2026](#item-8) ⭐️ 7.0/10
9. [Ancient DNA confirms Goths' Scandinavian origin myth](#item-9) ⭐️ 7.0/10
10. [Homelab Enthusiast Runs Self-Hosting Stack on $10 OpenStick](#item-10) ⭐️ 6.0/10
11. [Apple's iPhone keyboard has a hidden 'grey list' of words it won't suggest](#item-11) ⭐️ 6.0/10
12. [Blog Post Explores Building an $8 Linux Computer](#item-12) ⭐️ 6.0/10
13. [How Long Can Life Wait? Microbial Dormancy and Panspermia Explored](#item-13) ⭐️ 6.0/10
14. [Discord's Rust Rebuild Shows Electron's Heavy Cost on Windows 11](#item-14) ⭐️ 6.0/10
15. [Nostalgic Look Back at Borland Turbo Pascal 7](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Microsoft Research's AI Frontiers group reportedly shut down as John Langford exits](https://hunch.net/?p=13764006) ⭐️ 8.0/10

John Langford, a partner researcher manager at Microsoft Research New York, has left Microsoft and declared the AI Frontiers group over, according to a post on his blog Machine Learning (Theory). Microsoft Research's own lab page notes that as of Sept. 14, 2026, AI Frontiers is now part of Microsoft AI. The closure signals a broader industry shift away from exploratory AI research toward scaling transformer-based models, which could narrow the diversity of AI research directions at large companies. It affects researchers who depend on corporate labs for fundamental work and raises questions about who will pursue non-transformer approaches. The group focused on fundamental advances in AI, including efficient language models and agentic systems, and its absorption into Microsoft AI suggests a reorganization rather than a complete abandonment of the work. Langford is known for work in machine learning and learning theory, and his blog post framed the group's end as a notable event.

hackernews · srean · Nov 7, 18:02 · [Discussion](https://news.ycombinator.com/item?id=50406563)

**Background**: Microsoft Research is the company's basic research arm, and AI Frontiers was a lab within it dedicated to frontier AI research. John Langford is a computer scientist known for machine learning and learning theory, and he blogs at hunch.net. The news comes amid an industry-wide emphasis on scaling transformer models, the architecture behind most current large language models.

<details><summary>References</summary>
<ul>
<li><a href="https://www.microsoft.com/en-us/research/lab/ai-frontiers/">Microsoft Research AI Frontiers - Microsoft Research</a></li>
<li><a href="https://businessexaminer.ca/victoria-articles/item/microsoft-researcher-john-langford-exits-as-ai-frontiers-group-is-declared/">Microsoft Researcher John Langford Exits as AI... | Business Examiner</a></li>
<li><a href="https://en.wikipedia.org/wiki/John_Langford_(computer_scientist)">John Langford (computer scientist) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree that large companies are prioritizing transformer scale-out over exploratory research, with one noting Meta's similar moves. Some question why firms would stop R&D on potentially revolutionary approaches, while others argue that advances in coding agents may change the economics of small-team research. A few suggest the title is ambiguous and that the real AI frontiers are far from over.

**Tags**: `#AI research`, `#Microsoft Research`, `#industry trends`, `#R&D strategy`, `#transformer models`

---

<a id="item-2"></a>
## [Every Mac since 2022 runs undocumented personal knowledge graph daemons](https://8rank.ai/game/apple-intelligence-personal-knowledge-graph) ⭐️ 8.0/10

Security researchers have discovered that every Mac since macOS 13 Ventura (released in 2022) ships with two undocumented background daemons, knowledgeconstructiond and intelligenceplatformd, that continuously build a detailed personal knowledge graph about the user, their contacts, relationships, communications, and behavior. The researchers also released a tool that lets users inspect their own knowledge graph. This revelation raises significant privacy and ethical concerns because a system-level graph is being built without explicit user consent or public documentation, potentially affecting millions of Mac users and challenging Apple's public stance on privacy. It also highlights the tension between on-device personalization for AI features and transparency about data collection. The daemons ingest personal data such as contacts, communications, and locations to create a queryable store that LLMs retrieve from, allegedly to power Apple Intelligence features like Siri's ability to disambiguate contacts. The graph also maintains expired tables (expired_stable_graph and expired_event_graph) for retired entries, and the system runs on both Intel and Apple silicon Macs.

hackernews · infwhispers · Nov 7, 09:46 · [Discussion](https://news.ycombinator.com/item?id=50403097)

**Background**: Apple Intelligence is Apple's suite of AI features that relies on on-device processing to personalize responses while maintaining privacy. A personal knowledge graph is a structured representation of entities (like people, places, and events) and their relationships, which helps AI assistants understand context. Daemons are background processes in Unix-like operating systems that run without user interaction, and macOS has many such processes for various system tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://techplanet.today/post/apples-hidden-personal-knowledge-graph-understanding-macoss-undocumented-family-classifier">Apple's Hidden Personal Knowledge Graph: Understanding macOS ...</a></li>
<li><a href="https://techbytes.app/posts/every-mac-comes-with-an-undocumented-family-member-classifier/">Every Mac comes with an (undocumented) family member classifier</a></li>
<li><a href="https://byteiota.com/mac-hidden-family-classifier-intelligenceplatform/">Your Mac Has Been Profiling Your Family Since 2022 | byteiota</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion (505 points, 298 comments) shows strong engagement, with some users expressing exhaustion over constant data collection and citing Steve Jobs' 2010 statement that privacy means asking users every time. Others argue the graph is necessary context for local LLMs like Siri to resolve ambiguous requests, such as distinguishing which 'James' to text, and the author of the research participated in the thread to answer questions.

**Tags**: `#privacy`, `#macOS`, `#Apple Intelligence`, `#knowledge graph`, `#data collection`

---

<a id="item-3"></a>
## [Libghostty 1.0: Stable C ABI for Terminal Emulation](https://mitchellh.com/writing/libghostty-1-0) ⭐️ 8.0/10

Mitchell Hashimoto released libghostty-vt 1.0, a portable, high-performance C library for terminal emulation extracted from Ghostty, with both the library and its C ABI now stable. A stable C ABI enables a wave of new terminal emulators and agentic coding tools, such as herdr and cmux, to embed libghostty instead of writing their own emulator, and JetBrains IDEs have already replaced JediTerm with it. The library handles core terminal emulator logic like parsing escape sequences and maintaining terminal state, and its API uses opaque handles and enum-keyed getters/setters to avoid leaking implementation details and preserve ABI stability.

hackernews · mfiguiere · Nov 6, 23:30 · [Discussion](https://news.ycombinator.com/item?id=50399933)

**Background**: Ghostty is a terminal emulator written in Zig, a systems programming language focused on performance and simplicity. An ABI (application binary interface) is the low-level contract that lets compiled code call into a library without recompilation, so a stable C ABI makes it easy for projects in any language to embed the library reliably across versions.

<details><summary>References</summary>
<ul>
<li><a href="https://mitchellh.com/writing/libghostty-1-0">Libghostty 1.0 – Mitchell Hashimoto</a></li>
<li><a href="https://libghostty.tip.ghostty.org/index.html">libghostty : libghostty -vt - Virtual Terminal Emulator Library</a></li>
<li><a href="https://blog.jetbrains.com/platform/2026/10/jetbrains-terminal-now-uses-ghostty/">The Terminal in JetBrains IDEs Now Runs on libghostty - The...</a></li>

</ul>
</details>

**Discussion**: Commenters praised the release and noted that Hashimoto refrained from promoting his competing product Rex, while others shared practical experience using libghostty in Android projects and discussed API design lessons like opaque handles. Some users compared Ghostty favorably for TUI programs and Kitty graphics protocol support, while one preferred Kitty for rendering and animations.

**Tags**: `#terminal-emulator`, `#C-ABI`, `#Zig`, `#systems-programming`, `#open-source`

---

<a id="item-4"></a>
## [Asahi Linux 7.3 Report: New CPU Support, Licensing Concerns](https://asahilinux.org/2026/11/progress-report-7-3/) ⭐️ 8.0/10

Asahi Linux published its 7.3 progress report, highlighting ongoing advances in Apple Silicon support, including work on newer CPUs, while raising concerns about attempts to exploit its permissive licensing to hijack the project for commercial gain. This matters because Asahi Linux is a major reverse-engineering effort bringing Linux to Apple Silicon Macs, and the licensing concerns could affect the project's sustainability and community trust, while new CPU support expands the potential user base. The report mentions that the project was made aware of multiple attempts to exploit its permissive licensing to hijack its work, with a direct view to replacing the project and aggressively monetising Linux on Apple Silicon; the project has historically used the MIT license for some components.

hackernews · ackyshake · Nov 7, 05:20 · [Discussion](https://news.ycombinator.com/item?id=50401867)

**Background**: Asahi Linux is a community project that ports Linux to Apple Silicon Macs by reverse-engineering the SoCs, as Apple does not provide official documentation. It aims to provide a polished Linux experience for daily use. Permissive licenses like MIT allow others to reuse code with minimal restrictions, which can lead to commercial exploitation without contributing back.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Asahi_Linux">Asahi Linux - Wikipedia</a></li>
<li><a href="https://asahilinux.org/about/">About - Asahi Linux</a></li>
<li><a href="https://en.wikipedia.org/wiki/Permissive_software_license">Permissive software license - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters discussed missing USB-C display support as a blocker for adoption, questioned whether the licensing concerns refer to the Omarchy project, and expressed surprise that Asahi was ever MIT-licensed instead of GPL. Others promoted alternatives like Gravity Linux and the Framework laptop, and shared projects built on Asahi.

**Tags**: `#linux`, `#apple-silicon`, `#open-source`, `#hardware`, `#reverse-engineering`

---

<a id="item-5"></a>
## [Coldframe: A Honeypot Mimicking Supermarket Fridge Controllers](https://github.com/hedgerow-dev/coldframe) ⭐️ 7.0/10

Coldframe is a Python-based honeypot that impersonates Danfoss AK-SM 800A and Dixell XWEB refrigeration controllers, built to study attacker behavior against realistic industrial decoys. It uses only the standard library and has been live for a day, so far only seeing generic scanners and Shodan's crawler. This project highlights the exposure of industrial control systems in critical infrastructure like supermarkets, where security is often an afterthought. It provides a tool for researchers to understand attack patterns and raises awareness about the need for vendor-provided security defaults. The honeypot meticulously replicates real device fingerprints, such as nginx header order for Danfoss and exact page size for Dixell, and recognizes exploit attempts like CVE-2025-41450. It also allows default logins to a fake dashboard to observe secondary attacker actions.

hackernews · hedgerow-dev · Nov 7, 17:27 · [Discussion](https://news.ycombinator.com/item?id=50406292)

**Background**: Honeypots are decoy systems designed to attract and analyze attacks. Industrial control systems (ICS) and operational technology (OT) in sectors like food retail are increasingly targeted, as they often run outdated software and lack robust security. Shodan is a search engine for internet-connected devices, often used by attackers and researchers to find exposed systems.

<details><summary>References</summary>
<ul>
<li><a href="https://nvd.nist.gov/vuln/detail/CVE-2025-41450">NVD - CVE - 2025 - 41450</a></li>
<li><a href="https://www.easymanua.ls/danfoss/ak-sm-800a/manual">Danfoss AK - SM 800 A - User Manual</a></li>
<li><a href="https://manualzz.com/manual/dixell/X-web500">dixell X - web 500 - Operation manual, Operating manual, instruction...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed skepticism about relying on Shodan data, noting that many devices found are already honeypots or compromised. Others discussed the lack of security teams in supermarkets and questioned whether a large-scale hack actually occurred, while some praised the project but questioned the timing of its announcement.

**Tags**: `#honeypot`, `#ICS security`, `#OT security`, `#Shodan`, `#Python`

---

<a id="item-6"></a>
## [MaxxBench Critiques DeepSWE Coding Benchmark Scores](https://maxxbench.unlap.ai/research/why-maxxbench/) ⭐️ 7.0/10

MaxxBench published a critical analysis arguing that reported DeepSWE benchmark scores may overstate real-world coding capability, pointing to benchmark bugs and 'max mode' pitfalls. The article questions whether high scores truly reflect a model's practical programming ability. This critique matters because DeepSWE is used to rank leading coding agents, and inflated scores could mislead developers and organizations when selecting models for real-world tasks. It underscores the broader need for more rigorous and transparent LLM evaluation methodologies. The analysis highlights specific bugs within the DeepSWE benchmark and warns against using 'max mode' settings, which may artificially boost scores. It also notes that smaller models tend to collapse most under scrutiny, suggesting that benchmark performance may not generalize.

hackernews · antiuniverse · Nov 7, 17:19 · [Discussion](https://news.ycombinator.com/item?id=50406222)

**Background**: DeepSWE is a long-horizon software engineering benchmark designed to evaluate coding agents on original, contamination-free tasks. LLM benchmarks like DeepSWE aim to measure model capabilities, but they can suffer from issues such as benchmark leakage, overfitting, and unrealistic task design, which complicate the interpretation of scores.

<details><summary>References</summary>
<ul>
<li><a href="https://deepswe.lol/">DeepSWE — Long-Horizon Software Engineering Benchmark</a></li>
<li><a href="https://deepswe.datacurve.ai/">DeepSWE measures frontier coding agents on original, long-horizon...</a></li>
<li><a href="https://benchlm.ai/blog/posts/complete-guide-llm-benchmarking">The Complete Guide to LLM Benchmarking: Everything You Need ...</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree with the critique, expressing increased skepticism toward LLM benchmarks and noting that smaller models collapse most under scrutiny. Some debate whether DeepSWE could have been 'benchmaxxed' given its release timeline, while others point out that benchmark gaps may not translate to real-world performance differences.

**Tags**: `#LLM benchmarks`, `#AI evaluation`, `#coding agents`, `#DeepSWE`, `#model reliability`

---

<a id="item-7"></a>
## [Need for Speed Underground 2 Revived Online in the Browser](https://nfsu2.xyz/) ⭐️ 7.0/10

A project at nfsu2.xyz has brought Need for Speed Underground 2 online in the browser by reverse engineering the original PC game code and porting it to run directly in Chrome and Firefox via WebGPU, with widescreen rendering up to 120 FPS and online multiplayer features. This demonstrates how reverse engineering combined with modern web APIs like WebGPU can resurrect abandonware games that are otherwise unplayable on modern PCs, potentially opening the door for similar browser-based revivals of other classic titles and raising important questions about game preservation and copyright. The project is technically impressive but legally tenuous since it distributes copyrighted game content without authorization, and Linux users need to enable unsafe WebGPU features in Chromium to run it; the site also solicits donations, which some community members find dubious.

hackernews · fluxusars · Nov 7, 09:36 · [Discussion](https://news.ycombinator.com/item?id=50403052)

**Background**: Need for Speed Underground 2 is a 2004 racing game that is now considered abandonware—software that is no longer sold or supported by its publisher but remains under copyright. WebGPU is a modern web graphics API that allows high-performance 3D rendering and general-purpose GPU computations directly in the browser. Reverse engineering involves analyzing a program's code to understand its workings, often to port or modify it, and is commonly used in game preservation efforts.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebGPU">WebGPU - Wikipedia</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API">WebGPU API - Web APIs | MDN - MDN Web Docs</a></li>
<li><a href="https://techbytes.app/posts/need-for-speed-underground-2-online-in-the-browser/">Need for Speed Underground 2 online in the browser</a></li>

</ul>
</details>

**Discussion**: The community is largely enthusiastic and nostalgic, with many sharing memories of playing the game in the mid-2000s and praising the technical achievement of running it on phones and modern browsers. However, several commenters raise legal concerns about copyright infringement and donations, and some note that the site may face a takedown due to its popularity.

**Tags**: `#game preservation`, `#reverse engineering`, `#WebGPU`, `#abandonware`, `#browser gaming`

---

<a id="item-8"></a>
## [UK Law Firm Runs Entirely on Free Software in 2026](https://decoded.legal/blog/2026/11/running-a-law-firm-on-free-software-2026-edition/) ⭐️ 7.0/10

A UK-based law firm, decoded.legal, published a detailed 2026 edition of how it operates its entire practice using only free software, covering infrastructure, tooling, and workflows. The post outlines a self-hosted stack that avoids proprietary SaaS and vendor lock-in. This case study demonstrates that a conservative, regulation-heavy industry like law can run on free software, offering a practical blueprint for small firms seeking to cut costs and retain control over sensitive client data. It also fuels the broader debate on self-hosting versus SaaS and the risks of vendor lock-in. The stack includes self-hosted services such as Unbound for DNS with Pi-Hole in front, and the author details trade-offs around redundancy and the bus factor. Commenters question whether Pi-Hole is redundant alongside Unbound and raise concerns about relying on a single person for IT.

hackernews · DeepLogin · Nov 7, 09:39 · [Discussion](https://news.ycombinator.com/item?id=50403066)

**Background**: Free software refers to software licensed to give users the freedom to run, study, modify, and redistribute it, as defined by the Free Software Foundation; it is closely related to but not identical with open source. Self-hosting means running services on one's own hardware or a rented server instead of using a vendor's cloud, which can reduce costs and increase data control but requires technical expertise. Vendor lock-in occurs when a customer becomes dependent on a vendor and faces high switching costs, a common concern with proprietary SaaS and cloud platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Free_and_open-source_software">Free and open - source software - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Vendor_lock-in">Vendor lock - in - Wikipedia</a></li>
<li><a href="https://www.barestack.org/blog/self-hosting-small-business-guide">Self-Hosting for Small Businesses: A Practical Guide</a></li>

</ul>
</details>

**Discussion**: Commenters expressed a mix of envy and concern: one lawyer stuck in a big firm's mandated stack wished for such freedom, while another warned that firms using AI tools like Harvey risk vertical integration and loss of leverage. Others questioned technical redundancy (Pi-Hole vs Unbound) and raised the bus factor—what happens if the sole IT-savvy lawyer is unavailable—highlighting the practical trade-offs of this approach.

**Tags**: `#free-software`, `#self-hosting`, `#legal-tech`, `#open-source`, `#infrastructure`

---

<a id="item-9"></a>
## [Ancient DNA confirms Goths' Scandinavian origin myth](https://www.science.org/content/article/barbarian-tribe-s-mythic-origin-story-true-ancient-dna-reveals) ⭐️ 7.0/10

A new ancient DNA study provides genetic evidence supporting the long-doubted mythic origin story of the Goths, a Germanic tribe that originated in Scandinavia. The research appears to confirm that the Goths indeed migrated from Scandinavia to continental Europe, as their legends claimed. This finding challenges the historical skepticism that often dismisses ancient origin myths as fabrications, showing that oral traditions can preserve accurate historical information. It also highlights the growing power of archaeogenetics to validate or refute long-standing historical narratives. The study analyzed ancient DNA from Gothic-era remains and compared it with Scandinavian populations, finding genetic continuity that matches the legendary account. The Goths are known for their role in the fall of the Western Roman Empire, including the death of Emperor Decius in 251 C.E.

hackernews · benbreen · Nov 7, 04:54 · [Discussion](https://news.ycombinator.com/item?id=50401740)

**Background**: The Goths were a Germanic people who played a major role in the decline of the Roman Empire. According to their own origin myth, recorded by the historian Jordanes in the 6th century, they migrated from Scandinavia (specifically the island of Gotland) to the continent. Archaeogenetics is the study of ancient DNA to reconstruct human history, migrations, and population interactions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Archaeogenetics">Archaeogenetics - Wikipedia</a></li>
<li><a href="https://news.ycombinator.com/item?id=50401740">A barbarian tribe 's mythic origin story is true, ancient DNA reveals</a></li>

</ul>
</details>

**Discussion**: Commenters drew parallels to Herodotus, whose wild claims were later proven true, and questioned why the Gothic origin was ever doubted given Scandinavia's place names like Gotland and Gothenburg. Others noted that the story was already covered in popular history podcasts like Hardcore History, and some engaged in etymological tangents about Gothic loanwords in Spanish and Italian.

**Tags**: `#archaeology`, `#ancient-dna`, `#history`, `#science`, `#linguistics`

---

<a id="item-10"></a>
## [Homelab Enthusiast Runs Self-Hosting Stack on $10 OpenStick](https://blog.bosscher.ch/posts/openstick/) ⭐️ 6.0/10

A homelab enthusiast published a blog post detailing the software they run on a $10 OpenStick single-board computer, sharing their setup for cheap self-hosting. The post sparked a Hacker News discussion with 160 points and 35 comments covering clustering, AI-assisted sysadmin, and container auto-updates. This write-up demonstrates that meaningful self-hosting is possible on extremely cheap hardware, lowering the barrier to entry for newcomers and budget-conscious hobbyists. It also highlights broader trends in the homelab community, such as using AI agents for system administration and automating container updates to cope with frequent CVEs. The OpenStick is a small single-board computer that runs Debian, and the author notes the installation process is somewhat involved but the device is capable once set up. Commenters compare its performance to a Raspberry Pi Zero 2 and discuss ideas like PoE-powered Ethernet stick clusters and using Podman auto-update for containers.

hackernews · LaurensBER · Nov 7, 18:12 · [Discussion](https://news.ycombinator.com/item?id=50406670)

**Background**: A homelab is a personal setup for running servers and services at home, often used for learning and self-hosting applications. Single-board computers (SBCs) like the Raspberry Pi are popular for this because they are cheap, small, and low-power. OpenStick is a lesser-known SBC that costs around $10 and runs Linux, making it an attractive option for experimenting with self-hosting and clustering.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.tjll.net/distributed-homelab-cluster/">Tyblog | Going Completely Overboard with a Clustered Homelab</a></li>
<li><a href="https://heatcaster.com/how-to-build-a-robust-homelab-with-single-board-pcs/">How to Build a Robust Homelab with Single - Board PCs - Heat Caster</a></li>
<li><a href="https://www.reddit.com/r/selfhosted/comments/y77qte/self_hosted_server_setup_on_cheap_sbc/">Self hosted server setup on cheap SBC : r/selfhosted - Reddit</a></li>

</ul>
</details>

**Discussion**: Commenters were generally positive, with the author noting the fun of hosting on a cheap gadget and suggesting it as a good starting point for self-hosting given high RAM prices. One user wished for a PoE Ethernet stick form factor to easily build clusters, another shared using an AI agent with sudo access for sysadmin tasks, and a third recommended Podman auto-update for automatic container updates.

**Tags**: `#homelab`, `#self-hosting`, `#single-board-computers`, `#linux`, `#containers`

---

<a id="item-11"></a>
## [Apple's iPhone keyboard has a hidden 'grey list' of words it won't suggest](https://www.theguardian.com/technology/2026/nov/06/struggling-to-spell-male-chauvinist-pig-apple-grey-list-means-your-iphone-wont-help-you) ⭐️ 6.0/10

A researcher revealed that Apple's iOS keyboard maintains an undisclosed multilingual 'grey list' of tens of thousands of words and phrases—including slurs, insults, and political terms like 'right wing conspiracy' and 'Tibetan independence'—that it will not autocomplete or swipe-type. The Guardian reported on this finding, sparking a Hacker News debate about censorship and keyboard design. This matters because it shows how a ubiquitous input method can subtly steer what users express, raising questions about soft coercion and corporate influence over language. It affects millions of iPhone users and could prompt broader scrutiny of predictive text algorithms across platforms. The list is applied at the system level and is multilingual, with different flagged words for different languages; Apple says the keyboard avoids suggestions that might be inappropriate or offensive. Users can still type the words manually, but they won't appear as predictions or swipe suggestions.

hackernews · user_7832 · Nov 7, 17:06 · [Discussion](https://news.ycombinator.com/item?id=50406111)

**Background**: Predictive text and swipe typing rely on language models that suggest likely next words based on context and user history. Apple's keyboard, like Google's Gboard, uses such models to speed up typing, but companies often filter out offensive or sensitive terms to avoid embarrassment or legal issues. This 'grey list' is distinct from outright blocking, as it only suppresses suggestions rather than preventing input.

<details><summary>References</summary>
<ul>
<li><a href="https://www.macworld.com/article/3279221/revealed-apples-secret-list-of-slurs-insults-and-political-phrases-that-cant-be-swiped.html">Revealed: Apple's secret list of slurs, insults, and ...</a></li>
<li><a href="https://nypost.com/2026/11/06/business/apples-secret-list-of-banned-autocomplete-phrases-include-dictator-trump-sleepy-joe/">Apple’s secret list of banned autocomplete phrases include ...</a></li>
<li><a href="https://techcentral.co.za/apple-autocomplete-grey-list-iphone-keyboard/288130/">Ducking hell: inside Apple's hidden list of words the iPhone ...</a></li>

</ul>
</details>

**Discussion**: Commenters were divided: some argued that not predicting controversial phrases is a reasonable design choice and not censorship, while others contended that soft coercion is still coercion and criticized the keyboard's overall quality. Several noted that Google's Gboard likely does something similar, and some expressed surprise that this wasn't widely known earlier.

**Tags**: `#Apple`, `#iOS`, `#predictive-text`, `#censorship`, `#keyboard`

---

<a id="item-12"></a>
## [Blog Post Explores Building an $8 Linux Computer](http://thelittleengineerthatcould.blogspot.com/2022/12/the-8-linux-computer.html) ⭐️ 6.0/10

A blog post from 2022 details the construction of an $8 Linux computer, sparking a Hacker News discussion about ultra-cheap Linux-capable devices and tinkering projects. This highlights the ongoing interest in ultra-low-cost computing for hobbyists and the creative repurposing of inexpensive hardware, which continues to drive innovation in the embedded and DIY communities. The original blog post is not included in the content, but community comments mention specific boards like the Raspberry Pi Zero ($5), LicheeRV Nano (SG2002), UZ801 USB dongle, and Ox64, with varying levels of support and performance.

hackernews · zenincognito · Nov 7, 14:00 · [Discussion](https://news.ycombinator.com/item?id=50404599)

**Background**: Single-board computers (SBCs) like the Raspberry Pi have popularized low-cost Linux computing. Enthusiasts often repurpose cheap routers, TV boxes, or microcontrollers to run Linux for projects, taking advantage of open hardware and community support. Recent developments include RISC-V-based boards and ultra-cheap microcontrollers that can emulate Linux.

<details><summary>References</summary>
<ul>
<li><a href="https://all3dp.com/2/cheapest-single-board-computer/">The Cheapest Single-Board Computers (SBCs) - All3DP</a></li>
<li><a href="https://blog.adafruit.com/2024/02/19/linux-on-a-0-15-ch32v003-risc-v-microcontroller-riscv-linux/">Linux on a $0.15 CH32V003 RISC - V microcontroller # RISCV # Linux</a></li>

</ul>
</details>

**Discussion**: Commenters shared experiences with various cheap Linux devices, praising options like the LicheeRV Nano and UZ801 dongle for their hackability, while criticizing the Ox64 for poor peripheral support and outdated software. There is a general enthusiasm for tinkering with constrained hardware, though some note that cheap MCUs have stolen some of the spotlight from full Linux systems.

**Tags**: `#linux`, `#embedded`, `#hardware`, `#diy`, `#single-board-computers`

---

<a id="item-13"></a>
## [How Long Can Life Wait? Microbial Dormancy and Panspermia Explored](https://mceglowski.substack.com/p/how-long-can-life-wait) ⭐️ 6.0/10

A Substack article explores the limits of microbial longevity and dormancy, discussing whether microbes can remain viable for hundreds of millions of years and the implications for panspermia. The piece examines claims such as the revival of 250-million-year-old bacteria and questions whether such extreme survival is real or a contamination artifact. The article touches on fundamental questions about the resilience of life and the possibility of interplanetary or interstellar transfer of microbes, which has implications for astrobiology, planetary protection, and the search for extraterrestrial life. It also highlights the importance of rigorous sterilization protocols in experiments claiming extraordinary microbial longevity. The discussion includes specific examples like the claimed 250-million-year-old bacterium 2-9-3, where the lack of expected rDNA divergence (at least 50 base pairs) suggests contamination rather than true longevity. Community members also debate panspermia math, noting that early star clusters had closer stars and more material exchange, potentially making life transfer more likely.

hackernews · Ariarule · Nov 7, 16:22 · [Discussion](https://news.ycombinator.com/item?id=50405789)

**Background**: Panspermia is the hypothesis that life exists throughout the universe and is distributed by cosmic dust, meteoroids, asteroids, comets, and planetoids, potentially seeding life on Earth. Microbial dormancy is a reversible state of reduced metabolic activity that allows microbes to survive unfavorable conditions, disperse, and extend lifespan. The article examines whether microbes can remain viable over geological timescales, a key question for assessing the plausibility of panspermia.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Panspermia">Panspermia</a></li>
<li><a href="https://journals.asm.org/journal/msystems/microbial-dormancy">Microbial Dormancy - journals.asm.org</a></li>
<li><a href="https://www.numberanalytics.com/blog/contamination-control-astrobiology">Contamination Control in Astrobiology - numberanalytics.com</a></li>

</ul>
</details>

**Discussion**: Commenters expressed skepticism about extreme longevity claims, with one noting that Occam's razor points to sterilization failure rather than a quarter-billion-year-old bacterium. Another commenter argued that panspermia calculations should consider early star formation conditions, where stars were closer and material exchange more frequent. Some comments drifted into personal reflections on life and loneliness, while others advocated for spreading life beyond Earth.

**Tags**: `#astrobiology`, `#microbiology`, `#panspermia`, `#science`, `#hackernews`

---

<a id="item-14"></a>
## [Discord's Rust Rebuild Shows Electron's Heavy Cost on Windows 11](https://www.windowslatest.com/2026/11/06/every-windows-11-app-should-kill-electron-and-discord-just-showed-why-no-starting-screen-and-70-less-ram-even-with-two-accounts-signed-in/) ⭐️ 6.0/10

Discord has rebuilt its Windows desktop client in Rust using GPUI, replacing its Electron-based app and cutting memory usage to roughly 290MB even with two accounts signed in, according to an early build. The article argues this proves every Windows 11 app should abandon Electron for native development. The change matters because Electron apps each bundle their own Chromium copy and can consume gigabytes of RAM, so a major chat app demonstrating a lean native alternative could push other Windows 11 developers to reconsider cross-platform frameworks. It affects both end users dealing with memory pressure and engineering teams weighing performance against development speed. The early Rust/GPUI build reportedly uses about 290MB of RAM, compared with Electron versions that can eat up to 4GB on Windows 11, and the article notes that unlike WebView, which shares resources with Microsoft Edge, every Electron app packages its own Chromium. The comparison is based on an early build, so real-world performance and feature parity may still change.

hackernews · thunderbong · Nov 7, 11:11 · [Discussion](https://news.ycombinator.com/item?id=50403507)

**Background**: Electron is a free, open-source framework maintained by the OpenJS Foundation that lets developers build desktop apps with HTML, CSS, and JavaScript, rendered by a bundled Chromium engine with a Node.js backend. It powers apps such as Visual Studio Code, GitHub Desktop, and Discord, and its main appeal is letting one team ship one codebase across platforms. The trade-off is that each Electron app ships its own Chromium, which increases memory use and startup overhead compared with native or shared-runtime approaches.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Electron_framework">Electron framework</a></li>
<li><a href="https://windowsreport.com/discord-is-ditching-electron-for-rust-cutting-ram-usage-to-just-290mb/">Discord Is Ditching Electron for Rust, Cutting RAM Usage to ...</a></li>
<li><a href="https://www.windowslatest.com/2026/11/05/discord-is-killing-its-electron-app-that-can-eat-4gb-of-ram-on-windows-11-and-the-rust-rebuild-uses-just-290mb/">Discord is killing its Electron app that can eat 4GB of RAM ...</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree Electron's memory cost has been known since its early days, but several argue the article ignores Electron's core value: one small team shipping one app across platforms. Others criticize Discord's framework churn—dropping its native Android app for React Native and now moving away again—and suggest Kotlin Multiplatform or Qt as better paths to code reuse, while some note how users have grown accustomed to slow app startup.

**Tags**: `#Electron`, `#cross-platform`, `#performance`, `#native-apps`, `#software-engineering`

---

<a id="item-15"></a>
## [Nostalgic Look Back at Borland Turbo Pascal 7](https://kevinboone.me/tpwin.html) ⭐️ 6.0/10

A blog post by Kevin Boone reflects on Borland Turbo Pascal 7, praising its technical merits and influence on a generation of programmers, which sparked a lively discussion on Hacker News with 157 points and 88 comments. The article and discussion highlight the historical significance of Turbo Pascal in making programming accessible and efficient, and raise concerns about the loss of low-level programming skills in modern software development. Turbo Pascal 7, released in 1992, was the last version to have a separate lower-priced Turbo Pascal and a more expensive Borland Pascal for professional development; it featured a fast compiler, integrated development environment, and support for inline assembly, which many users cite as a gateway to low-level programming.

hackernews · andsoitis · Nov 7, 16:06 · [Discussion](https://news.ycombinator.com/item?id=50405678)

**Background**: Turbo Pascal was a software development system for the Pascal language on CP/M and MS-DOS, combining a compiler and IDE. It was known for its speed and affordability, and was later superseded by Delphi for Windows development. Delphi, based on Object Pascal, offered a visual development environment similar to Visual Basic but with better performance and language features.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Turbo_Pascal">Turbo Pascal - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Delphi_(software)">Delphi (software) - Wikipedia</a></li>
<li><a href="https://turbopascal.org/compiler">Compiler - Turbo Pascal Compiler</a></li>

</ul>
</details>

**Discussion**: Commenters shared personal anecdotes about learning to program with Turbo Pascal, praising its inline assembly support and lamenting that Delphi did not achieve the popularity of Visual Basic despite being technically superior. Some expressed concern that modern developers lack the skills to build tools like Turbo Pascal, and recommended further reading on its compilation speed.

**Tags**: `#Turbo Pascal`, `#programming history`, `#retrospective`, `#compilers`, `#Delphi`

---