# Horizon Daily - 2026-06-14

> From 15 items, 11 important content pieces were selected

---

1. [Pyodide 314.0 Enables Direct PyPI Publishing of WASM Wheels](#item-1) ⭐️ 9.0/10
2. [Rio's Homegrown LLM Revealed as Weighted Merge](#item-2) ⭐️ 8.0/10
3. [Jane Street on Formal Methods in Production](#item-3) ⭐️ 8.0/10
4. [2014 Talk on JavaScript's Rise and Fall Revisited](#item-4) ⭐️ 8.0/10
5. [AI Adoption Is More Mixed Than Hype Suggests](#item-5) ⭐️ 7.0/10
6. [How to Earn a Billion Dollars](#item-6) ⭐️ 7.0/10
7. [Mapping SQLite Result Columns to Source Tables](#item-7) ⭐️ 7.0/10
8. [Kage: Shadow Any Website to a Single Binary for Offline Viewing](#item-8) ⭐️ 6.0/10
9. [Zeroserve claims 3x throughput, 70% lower latency with Caddy compat](#item-9) ⭐️ 6.0/10
10. [Alan Perlis's Epigrams in Programming Resurface on HN](#item-10) ⭐️ 6.0/10
11. [Linux 7.1 Removes Old Drivers to Curb AI Bug Reports](#item-11) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Pyodide 314.0 Enables Direct PyPI Publishing of WASM Wheels](https://simonwillison.net/2026/Jun/13/publishing-wasm-wheels/#atom-everything) ⭐️ 9.0/10

Pyodide 314.0 allows Python package maintainers to publish WebAssembly (WASM) wheels directly to PyPI, using the new PyEmscripten platform tag defined in PEP 783. Previously, Pyodide maintainers had to manually build and host over 300 packages. This removes a major bottleneck for Python in the browser, enabling any package author to distribute WASM wheels without waiting for Pyodide maintainers. It significantly expands the ecosystem of Python packages available in browser-based environments like Pyodide. The feature is backed by PEP 783, which defines the PyEmscripten platform tag, and a PR to PyPI's warehouse repository that landed on April 21st. Tools like cibuildwheel and pyodide-build now support building and uploading these wheels.

rss · Simon Willison · Jun 13, 23:55

**Background**: Pyodide is a port of CPython to WebAssembly/Emscripten, allowing Python to run in the browser. Previously, distributing Python packages with C or Rust extensions as WASM wheels required manual hosting and was not supported by PyPI. PEP 783 standardizes the platform tag for Emscripten-based Python runtimes.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/13/publishing-wasm-wheels/">Publishing WASM wheels to PyPI for use with Pyodide</a></li>
<li><a href="https://peps.python.org/pep-0783/">PEP 783 – Emscripten Packaging | peps.python.org</a></li>
<li><a href="https://discuss.python.org/t/pep-783-emscripten-packaging-is-accepted/107393">PEP 783 – Emscripten Packaging is accepted - WebAssembly - Discussions on Python.org</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion (referenced in the article) shows strong positive sentiment, with many users excited about the reduced maintenance burden and the potential for more Python packages in the browser. Some commenters noted the importance of PEP 783 and the collaborative effort behind the change.

**Tags**: `#Pyodide`, `#WASM`, `#Python`, `#PyPI`, `#WebAssembly`

---

<a id="item-2"></a>
## [Rio's Homegrown LLM Revealed as Weighted Merge](https://github.com/nex-agi/Nex-N2/issues/4) ⭐️ 8.0/10

Rio de Janeiro's claimed homegrown LLM, Rio-3.5-Open-397B, was found to be a weighted merge of approximately 60% Nex-N2 Pro and 40% Qwen3.5-397B-A17B, rather than a fine-tuned model as claimed. This incident highlights the lack of transparency in AI model development and raises ethical concerns about attribution and misrepresentation in open-source AI, potentially eroding trust in claimed innovations. The analysis showed that every weight tensor in the Rio model is a 0.6/0.4 blend of Nex and Qwen across all 60 layers, with no evidence of additional training or distillation.

hackernews · unrvl22 · Jun 14, 15:37 · [Discussion](https://news.ycombinator.com/item?id=48528371)

**Background**: Model merging is a technique that combines the weights of two or more pre-trained models without additional training, often used to blend capabilities. The practice has gained popularity but can lead to attribution issues if not disclosed properly.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2212.09849">[2212.09849] Dataless Knowledge Fusion by Merging Weights of Language Models</a></li>
<li><a href="https://arxiv.org/abs/2408.07666">[2408.07666] Model Merging in LLMs, MLLMs, and Beyond: Methods...</a></li>
<li><a href="https://medium.com/@jonathan.raia40/model-merge-and-its-methods-c9b3e7ba8d96">Supercharging Large Language Models through Model Merging | by Jonathan Rai | Medium</a></li>

</ul>
</details>

**Discussion**: Community comments express skepticism about the claimed homegrown development, with some noting the lack of disclosure and potential profit from others' work. Others discuss the technical aspects of model merging and its robustness.

**Tags**: `#AI`, `#open-source`, `#model merging`, `#ethics`, `#LLM`

---

<a id="item-3"></a>
## [Jane Street on Formal Methods in Production](https://blog.janestreet.com/formal-methods-at-jane-street-index/?from_theconsensus=1) ⭐️ 8.0/10

Jane Street published a blog post summarizing their decade-long experience integrating formal methods into production systems, highlighting practical benefits and challenges. This demonstrates that formal methods can be practically applied in high-stakes environments like quantitative trading, potentially influencing broader adoption in the software industry. The blog is part of a series covering topics such as using OCaml's type system for verification and integrating SAT solvers into development workflows.

hackernews · eatonphil · Jun 14, 12:35 · [Discussion](https://news.ycombinator.com/item?id=48526633)

**Background**: Formal methods are mathematically rigorous techniques for specifying, developing, and verifying software and hardware systems. They aim to prove correctness rather than relying solely on testing. Jane Street, a quantitative trading firm, has been a prominent user of OCaml and formal methods in production.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Formal_methods">Formal methods - Wikipedia</a></li>
<li><a href="https://blog.janestreet.com/formal-methods-at-jane-street-index/">Jane Street Blog - Formal methods and the future of programming</a></li>
<li><a href="https://news.ycombinator.com/item?id=48526633">Formal Methods and the Future of Programming | Hacker News</a></li>

</ul>
</details>

**Discussion**: Commenters shared experiences with formal methods, with some noting the human effort required for theorem proving, while others debated whether formal specs are just another form of testing. The discussion also touched on the role of AI in shifting human effort toward verification.

**Tags**: `#formal methods`, `#programming`, `#verification`, `#Jane Street`, `#software engineering`

---

<a id="item-4"></a>
## [2014 Talk on JavaScript's Rise and Fall Revisited](https://www.destroyallsoftware.com/talks/the-birth-and-death-of-javascript) ⭐️ 8.0/10

A 2014 talk by Gary Bernhardt predicting JavaScript's dominance as a compilation target and its eventual replacement has resurfaced, with the community reflecting on how WebAssembly and TypeScript have partially fulfilled that vision. The talk's predictions are highly relevant today as WebAssembly matures and TypeScript becomes ubiquitous, highlighting the ongoing evolution of web development and the role of JavaScript as a compilation target. The talk specifically mentioned asm.js as an early compilation target, which has since been superseded by WebAssembly; TypeScript, a typed superset of JavaScript, has also become a major language that compiles to JavaScript.

hackernews · subset · Jun 14, 12:38 · [Discussion](https://news.ycombinator.com/item?id=48526661)

**Background**: JavaScript was originally designed as a simple scripting language for browsers, but its ubiquity led to efforts to use it as a compilation target for other languages. Asm.js was an early attempt to enable near-native performance by compiling C/C++ to a subset of JavaScript, but it was later replaced by WebAssembly, a binary instruction format designed for efficient execution and compact representation. TypeScript, developed by Microsoft, adds static typing to JavaScript and compiles to plain JavaScript, improving developer productivity for large-scale applications.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly - Wikipedia</a></li>
<li><a href="https://webassembly.org/">WebAssembly</a></li>
<li><a href="https://github.com/appcypher/awesome-wasm-langs">GitHub - appcypher/awesome-wasm-langs: 😎 A curated list of languages that compile directly to or have their VMs in WebAssembly</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the talk accurately predicted a global disaster between 2020-2025, just the wrong type. Some observed that WebAssembly hasn't improved as fast as predicted, lacking direct DOM access, so JavaScript remains necessary as glue code. Others highlighted that TypeScript and Electron have extended web technologies into desktop apps.

**Tags**: `#JavaScript`, `#WebAssembly`, `#Programming Languages`, `#History`, `#Tech Predictions`

---

<a id="item-5"></a>
## [AI Adoption Is More Mixed Than Hype Suggests](https://gabrielweinberg.com/p/people-are-consuming-ai-like-they) ⭐️ 7.0/10

A recent article argues that despite widespread AI hype, many people are not using AI extensively, with real-world adoption being more mixed and cautious than portrayed. The piece cites a study showing over 50% of people use AI less than once per week. This challenges the dominant narrative that AI is universally adopted and highlights the gap between hype and reality, which matters for businesses, policymakers, and technologists planning AI integration. It also underscores the need for nuanced understanding of user behavior and workplace dynamics. The article notes that AI usage is often measured by self-reported frequency, which may miss embedded AI features in existing software. Community comments reveal that employers ask about LLM use in interviews, and users find AI helpful for coding but requiring supervision.

hackernews · yegg · Jun 14, 14:44 · [Discussion](https://news.ycombinator.com/item?id=48527700)

**Background**: AI adoption has been a hot topic, with many claiming that everyone is using AI tools like ChatGPT. However, real-world usage data suggests a more fragmented picture, where some people use AI heavily while others rarely or never do. This article provides a counterpoint to the hype.

**Discussion**: Commenters share mixed experiences: some note that employers expect AI knowledge in interviews, while others find AI integration slow and overhyped. A key insight is that AI adoption may grow through embedded features rather than standalone chat interfaces.

**Tags**: `#AI adoption`, `#technology skepticism`, `#workplace`, `#LLMs`, `#hacker news`

---

<a id="item-6"></a>
## [How to Earn a Billion Dollars](https://paulgraham.com/earn.html) ⭐️ 7.0/10

Paul Graham published an essay arguing that creating a billion-dollar startup requires solving a rare, scalable problem and building a product people want. This essay sparks debate on wealth creation and inequality, influencing startup culture and venture capital thinking. The essay emphasizes that billion-dollar fortunes come from creating value at scale, not from zero-sum extraction.

hackernews · kingstoned · Jun 14, 11:50 · [Discussion](https://news.ycombinator.com/item?id=48526360)

**Background**: Paul Graham is a well-known venture capitalist and co-founder of Y Combinator, a startup accelerator. His essays often shape entrepreneurial thinking.

**Discussion**: Comments are mixed: some defend Graham's view as realistic, while others criticize wealth concentration and argue that billionaires often exploit labor.

**Tags**: `#startups`, `#wealth`, `#entrepreneurship`, `#venture capital`

---

<a id="item-7"></a>
## [Mapping SQLite Result Columns to Source Tables](https://simonwillison.net/2026/Jun/13/sqlite-column-provenance/#atom-everything) ⭐️ 7.0/10

Simon Willison explored techniques to programmatically identify the source table.column for each result column in arbitrary SQL queries, using Claude Code to find solutions via apsw, ctypes, and EXPLAIN analysis. This capability would enable Datasette to enrich query results with column-level metadata, improving data exploration and tooling for SQL users. The solutions include using the apsw library, accessing SQLite's C function sqlite3_column_table_name() via ctypes, and parsing EXPLAIN output. The work was done with Claude Code (Opus 4.8) due to Fable being banned by the US government.

rss · Simon Willison · Jun 13, 23:05

**Background**: Datasette is a tool for exploring and publishing relational databases. SQL queries often involve joins and CTEs, making it non-trivial to determine which source table each result column originates from. SQLite's C API provides functions like sqlite3_column_table_name() that are not exposed in Python's standard sqlite3 module.

**Tags**: `#SQL`, `#Datasette`, `#database`, `#AI-assisted development`

---

<a id="item-8"></a>
## [Kage: Shadow Any Website to a Single Binary for Offline Viewing](https://github.com/tamnd/kage) ⭐️ 6.0/10

Kage is a new open-source tool that shadows any website into a single binary executable for offline viewing, enabling users to serve and browse archived sites without a network connection. This tool simplifies offline access to documentation, wikis, and other web content, making it valuable for scenarios with limited or no connectivity, such as remote field work or air travel. Kage creates a static binary that includes all site assets, but requires a built-in server to serve the content; it does not produce a single HTML file that can be opened directly in a browser.

hackernews · tamnd · Jun 14, 17:25 · [Discussion](https://news.ycombinator.com/item?id=48529990)

**Background**: Offline website archiving tools like SingleFile and HTTrack have long existed, but Kage's approach of packaging a site into a single binary is novel. The binary acts as both the archive and the server, simplifying distribution and execution.

<details><summary>References</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48529990">Show HN: Kage – Shadow any website to a single binary for offline viewing | Hacker News</a></li>

</ul>
</details>

**Discussion**: Community comments on Hacker News show interest in practical use cases like offline company wikis, but also raise comparisons to alternatives such as SingleFile and HTTrack. Some users question the necessity of a server for static content and suggest improvements like a single HTML entry point.

**Tags**: `#offline`, `#archiving`, `#web`, `#tool`, `#static-site`

---

<a id="item-9"></a>
## [Zeroserve claims 3x throughput, 70% lower latency with Caddy compat](https://su3.io/posts/zeroserve-caddy-compat) ⭐️ 6.0/10

Zeroserve, a zero-config web server using eBPF and io_uring, announced Caddy compatibility, achieving 3x throughput and 70% lower latency compared to standard Caddy. This demonstrates the potential of io_uring and eBPF for web serving, but the lack of ACME and plugin support limits its practical use for most users. The compatibility is achieved via a Caddy module, but it does not support ACME automatic certificate management or Caddy plugins, which are core features for many deployments.

hackernews · losfair · Jun 14, 13:43 · [Discussion](https://news.ycombinator.com/item?id=48527145)

**Background**: Zeroserve is a high-performance web server written in Rust that leverages Linux's io_uring for async I/O and eBPF for packet processing. Caddy is a popular web server known for its automatic HTTPS via ACME. io_uring is a Linux kernel interface for efficient asynchronous I/O, but it has raised security concerns in some contexts.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Io_uring">Io uring</a></li>
<li><a href="https://sesamedisk.com/zeroserve-ebpf-web-server-infrastructure/">Zeroserve : An eBPF-Powered Web Server Without... - Sesame Disk</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some users note the lack of ACME support as a dealbreaker, while others question the security of io_uring for web servers. One commenter also observed that NGINX still holds up well in benchmarks.

**Tags**: `#web server`, `#performance`, `#io_uring`, `#Caddy`, `#Rust`

---

<a id="item-10"></a>
## [Alan Perlis's Epigrams in Programming Resurface on HN](https://www.cs.yale.edu/homes/perlis-alan/quotes.html) ⭐️ 6.0/10

A collection of aphorisms by Alan Perlis, known as 'Perlisisms', originally published in 1982, has been shared on Hacker News, sparking discussion among programmers. Perlis's epigrams offer timeless insights into programming, language design, and the nature of thought, remaining relevant decades later, especially in the age of LLMs. The collection includes 120 epigrams, such as 'A language that doesn't affect the way you think about programming, is not worth knowing.' Some quotes are noted as particularly relevant to modern AI and natural language processing.

hackernews · tosh · Jun 14, 14:56 · [Discussion](https://news.ycombinator.com/item?id=48527820)

**Background**: Alan Perlis was a pioneering computer scientist, first recipient of the Turing Award, and a key figure in early programming language design (ALGOL). His 'Epigrams in Programming' are a set of concise, witty observations about software development that have become classic references.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Alan_Perlis">Alan Perlis</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted favorite epigrams, with one noting that several quotes seem prescient about LLMs. Another user bought the domain perl.is to display the quotes, while a few initially misread 'Perlisisms' as 'Perlism'.

**Tags**: `#programming`, `#quotes`, `#history`, `#philosophy`

---

<a id="item-11"></a>
## [Linux 7.1 Removes Old Drivers to Curb AI Bug Reports](https://lore.kernel.org/lkml/CAHk-=wi4BF4bMhZNZ1tqs+FFV4OuZRe3ZqdWB+LxRLmRweUzQw@mail.gmail.com/T/#u) ⭐️ 6.0/10

Linux kernel 7.1 has been released, notably removing obsolete driver code such as ISDN and other old network drivers to reduce the influx of AI-generated bug reports targeting rarely used hardware. This release highlights an emerging trend where AI-assisted bug reporting drives kernel maintainers to clean up legacy code, potentially improving kernel maintainability and reducing noise for developers. The removal targets drivers for hardware that is rarely used today, such as ISDN, which are often the source of low-quality AI-generated bug reports. This is a proactive measure to streamline maintenance.

hackernews · berlianta · Jun 14, 16:01 · [Discussion](https://news.ycombinator.com/item?id=48528729)

**Background**: Linux kernel versioning uses a major.minor.patch scheme; the jump to 7.1 is a routine increment after 7.0 accumulated enough patches. AI-assisted bug reporting tools have become more common, sometimes generating false or irrelevant reports for obsolete code.

**Discussion**: Commenters generally support the removal, with one calling it "one of the best consequences ever of AI" for trimming kernel fat. Others joke about the slow adoption in stable distributions like Debian, and one user questions the significance of the version bump.

**Tags**: `#Linux`, `#kernel`, `#AI`, `#open source`

---

