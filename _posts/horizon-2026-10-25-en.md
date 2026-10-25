# Horizon Daily - 2026-10-25

> From 10 items, 9 important content pieces were selected

---

1. [10-year-old CNN beats frontier LLMs in skin cancer diagnosis](#item-1) ⭐️ 7.0/10
2. [Oregon Police Charge News Outlet $2.5M for Records on One Cop](#item-2) ⭐️ 7.0/10
3. [UC Berkeley Math Professor Sees 'No Point' in Grading Homework Due to AI](#item-3) ⭐️ 7.0/10
4. [Dan Luu's Essay on Software Ambition Sparks Hacker News Debate](#item-4) ⭐️ 7.0/10
5. [Cerebras Deploys Trillion-Parameter Models on Wafer-Scale Hardware](#item-5) ⭐️ 7.0/10
6. [Small Programs and Languages: A Reflection on Minimalist Coding](#item-6) ⭐️ 7.0/10
7. [FOSDEM Talk on Resisting Internet Censorship Sparks Debate](#item-7) ⭐️ 6.0/10
8. [Show HN: Visualizing S&P 500 Market Cap Bubbles with Employee Stick Figures](#item-8) ⭐️ 6.0/10
9. [fheroes2: Open-Source Recreation of Heroes of Might and Magic II Engine](#item-9) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [10-year-old CNN beats frontier LLMs in skin cancer diagnosis](https://lynchlab.net/llm-skin-cancer) ⭐️ 7.0/10

A blog post by the Lynch Lab reports that a 10-year-old Inception v3 convolutional neural network, fine-tuned on 68,011 dermoscopic and clinical images from the ISIC Archive, outperformed two frontier large language models (LLMs) in diagnosing skin cancer on a test set of 200 lesions. The result highlights that specialized, smaller models can still outperform much larger general-purpose LLMs on narrow, high-stakes tasks like medical image classification, raising questions about how LLM capabilities are evaluated and where they are most appropriately deployed. The CNN was trained on a single H100 GPU, and the test lesions (along with all other images of the same lesion or patient) were strictly excluded from training and validation to prevent data leakage; however, critics argue the comparison may be a case of 'benchmaxxing' because the CNN was specifically tuned for this benchmark while the LLMs were not.

hackernews · sungam · Oct 25, 17:15 · [Discussion](https://news.ycombinator.com/item?id=50233779)

**Background**: Inception v3 is a convolutional neural network architecture introduced by Google in 2015, known for its efficiency and widely used in transfer learning for medical imaging. Frontier LLMs are the most advanced general-purpose language models, often multimodal, but they are not specifically designed for fine-grained image classification tasks like skin lesion diagnosis.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Inception_(deep_learning_architecture)">Inception (deep learning architecture) - Wikipedia</a></li>
<li><a href="https://llmsguru.com/glossary/frontier-model/">What is Frontier Model? Plain-English... | LLMs Guru AI Dictionary</a></li>

</ul>
</details>

**Discussion**: Commenters largely agreed that a specialized model beating a general-purpose LLM is unsurprising, with some noting that LLMs can be used to cheaply generate such specialized models. Others criticized the comparison as 'benchmaxxing' and argued that LLMs' potential in diagnosis lies in integrating additional data like clinical notes and interactive questioning, rather than raw image classification.

**Tags**: `#machine-learning`, `#medical-ai`, `#llm-comparison`, `#computer-vision`, `#benchmarking`

---

<a id="item-2"></a>
## [Oregon Police Charge News Outlet $2.5M for Records on One Cop](https://theintercept.com/2026/10/01/oregon-police-misconduct-public-records-cost-fee/) ⭐️ 7.0/10

The Eugene Police Department in Oregon has told a local news outlet that fulfilling a public records request about a single police officer would require at least 44,816 hours of staff time and cost approximately $2,484,599.04. The request, which seeks records related to one cop, has sparked outrage over the use of prohibitive fees to block access to information. This case illustrates a growing tactic of using excessive fees to effectively deny public records requests, undermining government transparency and the ability of journalists to investigate police misconduct. It highlights systemic issues in how public records laws, such as FOIA, can be abused to conceal information from the public. The estimated 44,816 hours is equivalent to roughly 21 years of full-time work for a single employee, making the fee absurdly prohibitive. The quoted cost of nearly $2.5 million is far beyond the budget of most local newsrooms, effectively shutting down the request.

hackernews · tdeck · Oct 25, 18:04 · [Discussion](https://news.ycombinator.com/item?id=50234232)

**Background**: Public records laws, such as the Freedom of Information Act (FOIA) at the federal level and similar state statutes, are designed to give citizens and journalists access to government documents. However, agencies can charge fees for searching, reviewing, and duplicating records, and these fees can be used as a barrier. Police misconduct records are often particularly difficult to obtain, with many states imposing strict confidentiality rules or high costs.

<details><summary>References</summary>
<ul>
<li><a href="https://pulitzercenter.org/stories/police-misconduct-records-secret-difficult-access">Police Misconduct Records Secret, Difficult to Access | Pulitzer Center</a></li>
<li><a href="https://www.yahoo.com/news/city-detroit-wants-17-000-110309235.html">City of Detroit wants $17,000 to fill FOIA request on controversial...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed outrage at the absurdity of the fee, with one noting that 44,816 hours is about 21 years of work. Others shared personal anecdotes of agencies using slow-walking tactics, such as monthly partial releases, and compared the situation to the UK's FOIA system, which they said delivers information within 30 days without excessive fees. Another commenter pointed out that this is comparatively cheap next to a 2015 DoD request that was quoted at 15 million hours and $660 million.

**Tags**: `#public records`, `#government transparency`, `#FOIA`, `#police misconduct`, `#journalism`

---

<a id="item-3"></a>
## [UC Berkeley Math Professor Sees 'No Point' in Grading Homework Due to AI](https://www.dailycal.org/news/campus/academics/ai-use-leads-uc-berkeley-math-professor-to-see-no-point-in-grading-homework/article_bdf1eae2-c08b-491f-b9f1-81a7cea177de.html) ⭐️ 7.0/10

Richard Borcherds, a UC Berkeley math professor and Fields Medalist, has stopped grading homework after observing that many students used AI to consistently earn top scores. This highlights how AI is challenging traditional assessment methods in higher education, prompting discussions about the purpose of homework and the need for new evaluation approaches. Borcherds, a Fields Medalist known for proving the Monstrous Moonshine conjecture, typically delegates grading to teaching assistants, so his decision reflects a broader reconsideration of homework's role in learning.

hackernews · romanhn · Oct 25, 16:28 · [Discussion](https://news.ycombinator.com/item?id=50233304)

**Background**: Richard Borcherds is a mathematician at UC Berkeley who won the Fields Medal in 1998 for his work on the Monster group and modular forms. The debate over AI in education has intensified as tools like ChatGPT enable students to complete assignments with minimal effort, raising questions about academic integrity and the effectiveness of traditional grading.

<details><summary>References</summary>
<ul>
<li><a href="https://www.dailycal.org/news/campus/academics/ai-use-leads-uc-berkeley-math-professor-to-see-no-point-in-grading-homework/article_bdf1eae2-c08b-491f-b9f1-81a7cea177de.html">AI use leads UC Berkeley math professor to see ‘no point’ in grading ...</a></li>

</ul>
</details>

**Discussion**: Commenters debated the purpose of homework, with some noting the irony that Borcherds already delegated grading to assistants. Others argued that homework helps learning and that AI removes the forcing function for incremental practice, while some suggested separating mastery (exams) from conscientiousness (attendance).

**Tags**: `#AI in education`, `#grading`, `#academia`, `#assessment`, `#Hacker News`

---

<a id="item-4"></a>
## [Dan Luu's Essay on Software Ambition Sparks Hacker News Debate](https://danluu.com/ambitious/) ⭐️ 7.0/10

Dan Luu published an essay arguing that software developers should be more ambitious with the projects they build, which reached the front page of Hacker News and accumulated over 700 points and 644 comments. The discussion highlights a growing debate about whether AI tools enable developers to tackle more ambitious projects or instead encourage overfitted, unmaintainable code, reflecting broader industry tensions around software quality and ambition. Commenters shared concrete examples of AI-assisted ambitious projects, such as an open-source hardware AV1 video decoder and an e-ink app SDK for Kobo, while others cautioned that LLM-generated code often fails to generalize and becomes hard to maintain.

hackernews · ltratt · Oct 24, 21:47 · [Discussion](https://news.ycombinator.com/item?id=50225695)

**Background**: Dan Luu is a well-known software engineer and blogger who frequently writes about engineering practices and industry trends. Hacker News is a popular forum for technology discussion where essays often spark extensive debate. The rise of large language models (LLMs) has intensified conversations about how AI changes software development.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Artificial_intelligence">Artificial intelligence - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hacker">Hacker - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community response is mixed: some developers celebrate AI as a way to finally build ambitious side projects they lacked time for, while others warn that LLMs produce messy, overfitted code that harms maintainability and performance. A few commenters also note that software quality outside the tech bubble remains poor, underscoring the need for more ambitious thinking.

**Tags**: `#software-engineering`, `#ambition`, `#AI`, `#Hacker News`, `#discussion`

---

<a id="item-5"></a>
## [Cerebras Deploys Trillion-Parameter Models on Wafer-Scale Hardware](https://www.cerebras.ai/blog/how-we-deploy-trillion-parameter-frontier-models-on-cerebras) ⭐️ 7.0/10

Cerebras published a blog detailing how it serves trillion-parameter frontier AI models on its wafer-scale hardware, specifically mapping them across WSE-3 wafers to achieve 1,000–2,000+ tokens per second. The announcement sparked a Hacker News discussion with 334 points and 119 comments debating speed, model recency, and business sustainability. This demonstrates that wafer-scale hardware can serve the largest frontier models at extremely high inference speeds, potentially making real-time AI applications more feasible. It also highlights Cerebras's differentiation in the AI inference market, where it competes with GPU-based solutions and other specialized providers like Groq. Cerebras maps trillion-parameter models across its WSE-3 wafers, which are subdivided into a 2D mesh of processing elements (PEs) that stream data with consistent timing to neighboring cores. However, community members note that the models actually available on Cerebras are often older or smaller (e.g., GPT OSS 120B, Qwen 3.8 27B), and the company faces manufacturing constraints for its giant wafer nodes.

hackernews · gmays · Oct 25, 01:33 · [Discussion](https://news.ycombinator.com/item?id=50227356)

**Background**: Cerebras Systems develops wafer-scale chips, notably the WSE (Wafer Scale Engine), which are entire silicon wafers used as a single chip to provide massive on-chip memory and compute. This architecture is designed to accelerate AI training and inference by keeping data on-chip and reducing communication bottlenecks. Trillion-parameter models are among the largest neural networks, requiring enormous memory and compute for serving.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cerebras.ai/blog/how-we-deploy-trillion-parameter-frontier-models-on-cerebras">How Cerebras Deploys Trillion - Parameter AI Models</a></li>
<li><a href="https://en.wikipedia.org/wiki/Cerebras_Systems">Cerebras Systems - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters debated Cerebras's business viability, with some arguing it lacks the capital to meet demand and must offer cheap plans to attract customers. Others criticized the company for serving outdated or less capable models, though some expect it to soon offer better models at lower cost and higher speed. A few shared mixed professional experiences, praising the technology but questioning the team's adequacy.

**Tags**: `#cerebras`, `#ai-inference`, `#wafer-scale`, `#llm-serving`, `#hardware`

---

<a id="item-6"></a>
## [Small Programs and Languages: A Reflection on Minimalist Coding](https://ratfactor.com/cards/pl-small) ⭐️ 7.0/10

The article 'Small Programs and Languages' on ratfactor.com explores the appeal and techniques of writing very small programs and minimalist languages, sparking a Hacker News discussion with 178 points and 28 comments. Community members shared concrete examples, such as a 39-byte hex decoder and a bootloader-sized OS, and debated compiling directly to machine code. This discussion highlights the enduring appeal of code golf and minimalist programming as a way to deepen understanding of computation and language design, even if such techniques are not directly used in mainstream software development. It also showcases how constraints can drive creativity and learning, inspiring developers to explore esoteric languages and tiny programs. Community examples include a 39-byte hex decoder in Uxn, a 125-byte JSON-to-NDJSON converter, a 1024-byte BLAKE2s implementation, and a 1853-byte card game with graphics and sound. One commenter mentioned Binary Lambda Calculus, whose self-interpreter is only 168 bits (21 bytes), and another proposed using machine code as bytecode to simplify compilation.

hackernews · andsoitis · Oct 24, 21:44 · [Discussion](https://news.ycombinator.com/item?id=50225674)

**Background**: Code golf is a type of programming competition where participants strive to write the shortest possible code to achieve a given task. Minimalist programming languages, such as esoteric languages (esolangs), are designed to test the boundaries of language design and often prioritize simplicity or conceptual elegance over practicality. These pursuits are popular among hackers and academics as exercises in creativity and deep understanding of computation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Esoteric_programming_language">Esoteric programming language</a></li>
<li><a href="https://esolangs.org/">Esolang, the esoteric programming languages wiki</a></li>

</ul>
</details>

**Discussion**: The discussion is positive and engaged, with commenters sharing personal projects like a bootloader-sized OS and tiny Uxn programs, and debating the merits of compiling directly to machine code versus bytecode. Some express nostalgia and renewed interest in low-level programming, while others highlight theoretical constructs like Binary Lambda Calculus.

**Tags**: `#programming-languages`, `#code-golf`, `#minimalism`, `#compilers`, `#hacker-news`

---

<a id="item-7"></a>
## [FOSDEM Talk on Resisting Internet Censorship Sparks Debate](https://talkweb.eu/openweb/4558/) ⭐️ 6.0/10

A talk announcement titled 'I refuse to accept a censored Internet' for the upcoming FOSDEM conference has been published, accompanied by a Hacker News discussion with 240 points and 114 comments on the nuances of censorship and content moderation. The discussion highlights the growing tension between free speech and content moderation online, and the feasibility of an uncensored internet, which affects developers, activists, and platforms worldwide. The talk is scheduled for FOSDEM 27, an annual free and open-source software conference in Brussels, and the Hacker News thread includes perspectives on whether censorship is inevitable and the role of infrastructure providers.

hackernews · Tomte · Oct 25, 17:30 · [Discussion](https://news.ycombinator.com/item?id=50233929)

**Background**: FOSDEM is a non-commercial, volunteer-organized annual conference focused on free and open-source software, held at the Université libre de Bruxelles. Internet censorship circumvention involves methods to bypass legal control or suppression of online content, while content moderation is the practice of screening user-generated content on platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/FOSDEM">FOSDEM</a></li>
<li><a href="https://en.wikipedia.org/wiki/Internet_censorship_circumvention">Internet censorship circumvention - Wikipedia</a></li>
<li><a href="https://www.institutmontaigne.org/en/expressions/challenges-content-moderation">Challenges of Content Moderation | Institut Montaigne</a></li>

</ul>
</details>

**Discussion**: Commenters debated whether an uncensored internet is possible, with some arguing that moderation is a form of censorship and thus unavoidable, while others criticized the talk for focusing only on certain countries and ignoring broader issues. Overall sentiment was mixed, with interest in the talk but skepticism about solving censorship through software alone.

**Tags**: `#internet-censorship`, `#fosdem`, `#content-moderation`, `#privacy`, `#free-speech`

---

<a id="item-8"></a>
## [Show HN: Visualizing S&P 500 Market Cap Bubbles with Employee Stick Figures](https://bigwhalehunting.com/workforce/) ⭐️ 6.0/10

A Show HN project visualizes S&P 500 companies as market-cap bubbles with stick figures representing employee counts, revealing striking disparities such as Nvidia's $124 million market cap per employee versus Accenture's much lower ratio. This visualization offers an intuitive way to grasp the enormous differences in market value per employee across companies, sparking discussion about what such metrics reveal about business models and industry structure. Each stick figure represents 10,000 employees, and users can zoom in to explore individual companies; however, the employee counts may not fully account for part-time, seasonal, contract workers, or franchise employees, which can skew comparisons.

hackernews · vfxGer · Oct 25, 15:05 · [Discussion](https://news.ycombinator.com/item?id=50232312)

**Background**: The S&P 500 is a market-capitalization-weighted index of 500 large publicly traded U.S. companies, meaning larger companies have greater influence on the index's performance. Market cap per employee is a metric that divides a company's total market value by its number of employees, often used to gauge efficiency or compare business models, but it can be misleading without context about workforce composition.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Stock_market_index">Stock market index - Wikipedia</a></li>
<li><a href="https://www.spotmarketcap.com/blog/what-is-sp500-weighting">What is S & P 500 Weighting ? Index Construction... | SpotMarketCap</a></li>
<li><a href="https://www.linkedin.com/posts/tajventure-services-llc_nvidia-ai-techboom-activity-7359142121179705345-eTcT">Nvidia's $111M per employee : A market value metric , not... | LinkedIn</a></li>

</ul>
</details>

**Discussion**: Commenters noted that employee counts are not straightforward due to part-time, seasonal, contract workers, and franchise models, which can distort comparisons. Others pointed out inconsistencies in S&P 500 classifications, such as Alphabet and Meta being classified as communication services rather than information technology, and debated the classification of companies like Tesla and Amazon.

**Tags**: `#data-visualization`, `#S&P 500`, `#market-cap`, `#employment`, `#Show HN`

---

<a id="item-9"></a>
## [fheroes2: Open-Source Recreation of Heroes of Might and Magic II Engine](https://github.com/ihhub/fheroes2) ⭐️ 6.0/10

fheroes2, an open-source project that recreates the game engine of Heroes of Might and Magic II, was featured on the front page of Hacker News, drawing 184 points and 64 comments. The project allows players to run the original game with modern enhancements while requiring the original game's data files. This project demonstrates the value of open-source reverse engineering in preserving classic games and making them playable on modern systems, and it fosters community engagement around retro gaming. It also highlights the ongoing interest in the Heroes of Might and Magic series and related projects like VCMI. fheroes2 requires the original game's data files to function, and it offers improvements such as higher resolutions and bug fixes. The project is written in C++ and is actively maintained on GitHub, with a build guide available for Windows, macOS, and Linux.

hackernews · tosh · Oct 25, 11:09 · [Discussion](https://news.ycombinator.com/item?id=50230384)

**Background**: Heroes of Might and Magic II is a classic turn-based strategy game released in 1996 by New World Computing. Open-source engine recreations like fheroes2 and VCMI (for Heroes III) allow players to enjoy these games on modern hardware with enhancements, but they typically require the original game assets to avoid copyright issues. Such projects rely on reverse engineering to reimplement the game logic without distributing copyrighted content.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/ihhub/fheroes2">GitHub - ihhub/ fheroes2 : fheroes2 is a recreation of Heroes ...</a></li>
<li><a href="https://vcmi.eu/">Home - VCMI</a></li>
<li><a href="https://github.com/vcmi/vcmi">GitHub - vcmi / vcmi : Open-source engine for Heroes of Might ...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed nostalgia for the series, with some noting that the gameplay may not hold up for adults. One user shared an experiment using an MCP to let Claude play Heroes III, reporting that the AI performed poorly and slowly. Others mentioned VCMI as an alternative engine for Heroes III and discussed a dream of combining HoMM2's graphics with HoMM3's mechanics.

**Tags**: `#game-engine`, `#open-source`, `#reverse-engineering`, `#retro-gaming`, `#heroes-of-might-and-magic`

---

