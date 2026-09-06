### Me

- Generalist engineer whose current interest is piqued by ML engineering, LLM training, evaluation, and low-latency serving.
- Currently building software and automating workflows at Wells Fargo.
- Previously worked at Neosapien and freelanced at Attenomics Labs, Kirloskar Ferrous Industries Ltd. (Setconnect) and as an IC.
- NITK '25 EEE.

---

### Now

- Reproducing published LLM architectures, agentic pipelines and recommender systems end to end, and further testing what the papers and tech blogs leave out.
- Inference internals: paged KV cache, prefix caching, speculative decoding. getting 1% better at it everyday (its slow but an honest days work).
- RL post-training and policy distillation
- Self stufy ;P . I love reading blogs, articles and papers -> discuss with my clanker and implement them.
- Still fighting between the dichotomy of rawdoging hand-written code to get an sense of self-satisfaction Vs using agents to implement e2e at the behest of time and producticity

---

### Selected work

**[genrec](https://github.com/mallikaakash/genrec)**
Reproduction of Netflix's LLM-native recommender. Qwen2.5-0.5B, two-phase training, catalog-aware ranking head over learned item embeddings.
Audited against the published design: four Phase-2 objective divergences and a context-truncation bug silently discarding over half of every prompt. MRR 0.218 to 0.275 at an unchanged training budget. An 8-arm ablation to attribute the gain, which reproduced two of the paper's claims and disproved three of my own. Served prefill-only at 23ms warm.
Item-kNN and S3-Rec still beat it. Sampled-negative protocol favours neighbourhood methods, and it trained on 46% of the data for 2 epochs. Details in the README.

**[nanovllm-cpu](LINK) [WIP]**
CPU inference engine written from primitives. Paged KV cache, prefix caching, n-gram speculative decoding, async OpenAI-compatible server. Benchmarked under open-loop Poisson load with DuckDB-backed analysis.

**[WalGraph](LINK)**
Decentralised graph database on Sui. Global runner-up, Programmable Storage track, SUI Overflow 2025.

**[Katha.Ai](https://github.com/mallikaakash/Katha.Ai)**
Iterative context engine for long-form generation, holding character consistency and storyline across a 107-page novel. 1st runner-up of 100+ teams, KukuFM National Project K.

**[TGBH-StackedPitha](https://github.com/mallikaakash/TGBH-StackedPitha)**
Masked autoencoder demand prediction with a rubric-based dynamic pricing system. Top 5 in track, The Great Bangalore Hackathon 2025.

---

### Find me on - 

[Portfolio](https://aakashmallik.vercel.app/) · [LinkedIn](https://linkedin.com/in/aakash-mallik-82b99423b/) · [X](LINK) · aakashmallik7777@gmail.com
