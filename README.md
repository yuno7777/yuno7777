<div align="center">

# abhishek satarkar

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2800&pause=900&color=FFFFFF&center=true&vCenter=true&width=850&lines=ai%2Fml+engineer+%C2%B7+systems+builder;llm+agents+%C2%B7+rag+%C2%B7+inference;researching+machine+intelligence;building+towards+human-like+machine+intelligence" />

<br/>

<img src="https://img.shields.io/badge/ai%2Fml-111111?style=flat-square&labelColor=000000&color=ffffff"/>
<img src="https://img.shields.io/badge/llm%20agents-111111?style=flat-square&labelColor=000000&color=ffffff"/>
<img src="https://img.shields.io/badge/systems-111111?style=flat-square&labelColor=000000&color=ffffff"/>
<img src="https://img.shields.io/badge/research-111111?style=flat-square&labelColor=000000&color=ffffff"/>

<br/><br/>

<a href="https://moonlitstudio.online">portfolio</a>
&nbsp;·&nbsp;
<a href="https://www.linkedin.com/in/abhishek-satarkar-9742">linkedin</a>
&nbsp;·&nbsp;
<a href="mailto:abhisheksatarkar098@gmail.com">email</a>
&nbsp;·&nbsp;
<a href="https://huggingface.co/kaii07">hugging face</a>
&nbsp;·&nbsp;
<a href="https://orcid.org/0009-0003-4847-3288">orcid</a>

</div>

---

## about

ai/ml engineer interested in **model architecture, inference engines, autonomous agents, and systems engineering**.

i build across the stack, from low-level rust inference and model experiments to distributed execution and ml infrastructure.

currently pursuing a **b.e. in information technology** and working toward an **ms in ai/ml**.

<br/>

`python` `pytorch` `rust` `c++` `typescript` `next.js` `fastapi`

---

## selected work

<table>
<tr>

<td width="50%" valign="top">

### [looped hybrid qwen](https://github.com/yuno7777/looped-qwen35-visual-sre)

experimental 0.8b multimodal model for visual incident triage, exploring recurrent computation, reinforcement learning and kv-cache compression.

`pytorch` `qwen` `rlvr` `cuda`

</td>

<td width="50%" valign="top">

### [embodied worlds](https://github.com/yuno7777/embodied-ai)

research platform for evaluating ai policies in deterministic, partially observed simulated environments with reproducible trajectories.

`rust` `python` `next.js`

</td>

</tr>

<tr>

<td width="50%" valign="top">

### [atlas mlops](https://github.com/yuno7777/atlas-mlops)

self-hosted ml lifecycle platform for dataset validation, training, experiment tracking, model registration, inference and drift monitoring.

`python` `mlflow` `celery` `fastapi`

</td>

<td width="50%" valign="top">

### [geostat](https://github.com/yuno7777/geostat)

satellite-based flood mapping using sentinel-1 sar, u-net segmentation and geospatial road and building exposure analysis.

`pytorch` `rasterio` `shapely` `fastapi`

</td>

</tr>

<tr>

<td width="50%" valign="top">

### [opticore](https://github.com/yuno7777/opticore)

c++20 vehicle routing solver with capacity and time-window constraints, independent validation and reproducible or-tools comparisons.

`c++20` `cmake` `or-tools`

</td>

<td width="50%" valign="top">

### [kestrel](https://github.com/yuno7777/kestrel)

streaming fraud detection platform with kafka ingestion, redis-backed behavioral features, ml inference and operational monitoring.

`python` `kafka` `redis` `prometheus`

</td>

</tr>

<tr>

<td width="50%" valign="top">

### [project black monolith](https://github.com/yuno7777/project-black-monolith)

defense-in-depth middleware for agent tool integrity, retrieval memory and reasoning protection.

`rust` `python` `next.js`

</td>

<td width="50%" valign="top">

### [learnflow ai](https://github.com/yuno7777/learnflow-ai)

multi-tenant training platform with citation-backed retrieval, course generation, supervised grading and workflow automation.

`next.js` `fastapi` `postgresql` `n8n`

</td>

</tr>

<tr>

<td width="50%" valign="top">

### [ferrite](https://github.com/yuno7777/ferrite)

dependency-free rust inference engine for gguf models, with native quantization kernels, simd and memory-mapped weights.

`rust` `gguf` `simd`

</td>

<td width="50%" valign="top">

### [swarm platform](https://github.com/yuno7777/swarm-platform)

rust multi-agent execution prototype with task dags, scheduling, retries, event streaming and journal-based crash recovery.

`rust` `async systems` `prometheus`

</td>

</tr>
</table>

---

## open source & other work

- [sleepers code](https://github.com/yuno7777/sleeperscode) · an open-source fork of [t3 code](https://github.com/pingdotgg/t3code), adapted into a local-first workspace for coding agents.
- [luminary rag](https://github.com/yuno7777/luminary-rag) · structure-aware hierarchical document retrieval.
- [robo rl](https://github.com/yuno7777/robo-rl) · simulated autonomous robot navigation with ros 2, gazebo, slam and nav2.
- [compute](https://github.com/yuno7777/compute-roadmap) · interactive computing curriculum from transistors to transformer inference.
- [sleepers researcher](https://github.com/yuno7777/sleepers-researcher) · local-first desktop research agent with tool use and persistent retrieval memory.

[all repositories](https://github.com/yuno7777?tab=repositories)

---

## research outputs

**looped hybrid qwen3.5 for visual sre incident triage**

independent experimental work on a 0.8b multimodal model, exploring recurrent decoder computation, supervised fine-tuning, reinforcement learning with verifiable rewards, and vision-aware kv-cache quantization.

[technical paper (pdf)](https://github.com/yuno7777/looped-qwen35-visual-sre/blob/main/docs/Looped_Hybrid_Qwen35_Visual_SRE_Paper.pdf) · [model weights (v2.1)](https://huggingface.co/kaii07/looped-qwen35-0.8b-visual-sre-v2.1) · [benchmark results](https://github.com/yuno7777/looped-qwen35-visual-sre/blob/main/HARD_BENCHMARK_RESULTS.md) · [engineering diary](https://github.com/yuno7777/looped-qwen35-visual-sre/blob/main/docs/Visual_SRE_Looped_Qwen35_Dev_Diary.pdf)

---

## experimental results

| project | documented result | scope |
|:---|:---|:---|
| [looped qwen](https://github.com/yuno7777/looped-qwen35-visual-sre/blob/main/HARD_BENCHMARK_RESULTS.md) | stock 0% → v2.1 84% accuracy | 50 unseen visual sre dashboards, bf16, rtx 4060 8 gb |
| [looped qwen](https://github.com/yuno7777/looped-qwen35-visual-sre/blob/main/HARD_BENCHMARK_RESULTS.md) | 3.93 → 4.88 tokens/s | fused deltanet kernels vs eager, 2 loops, 50 generated tokens |
| [opticore](https://github.com/yuno7777/opticore#benchmark-results) | matched or-tools cost on 8- and 20-customer instances; 0.298% higher cost on 50 customers | three fixed routing instances; or-tools ran to its configured time limit |
| [ferrite](https://github.com/yuno7777/ferrite/blob/main/docs/benchmarking.md) | q5_k kernel: 1.214 ms vs 1.971 ms for ggml | 4096 × 4096 gemv, 4 threads, ryzen 5 2500u; not end-to-end inference |

<sub>results are from repository experiments, not independent evaluations. model adaptation trades off generalization across tasks: v2.1 chartqa scored 74% vs stock 80% on a 50-sample subset. see linked methodology and limitations.</sub>

---

## research methodology

- [embodied worlds](https://github.com/yuno7777/embodied-ai/blob/main/docs/research-readiness.md) · deterministic simulation, disjoint evaluation seeds, trajectory provenance and explicit capability limits.
- [black monolith](https://github.com/yuno7777/project-black-monolith/blob/main/EVALUATION.md) · detector calibration, deterministic regression fixtures and documented real-model failure modes.
- [opticore](https://github.com/yuno7777/opticore/blob/main/docs/EXPERIMENTS_AND_BENCHMARKS.md) · fixed benchmark instances, independent feasibility validation and reference solver comparisons.

---

## research

<div align="center">

**model architecture · efficient inference · embodied intelligence · safety · interpretability**

</div>

<br/>

| area | focus |
|:---|:---|
| **model architecture** | recurrent computation · multimodal models · efficient adaptation |
| **embodied intelligence** | partial observability · policy evaluation · reproducible simulation |
| **safety** | jailbreak durability · robustness · alignment behavior |
| **interpretability** | activation patching · linear probes · representation analysis |
| **inference** | kv-cache behavior · quantization · optimization |
| **fine-tuning** | qlora · efficient adaptation · overfitting |
| **agent security** | tool integrity · retrieval poisoning · reasoning protection |

<br/>

[looped hybrid qwen experiments](https://github.com/yuno7777/looped-qwen35-visual-sre) · [embodied worlds](https://github.com/yuno7777/embodied-ai) · [ferrite](https://github.com/yuno7777/ferrite)

`jailbreak decay` · `kv-cache autopsy` · `where does alignment live` · `qwen qlora`

---

## stack

<div align="center">

**ai / ml**

`python` · `pytorch` · `tensorflow` · `scikit-learn` · `transformers`

<br/>

**systems**

`rust` · `c++` · `fastapi` · `postgresql` · `redis`

<br/>

**full stack**

`typescript` · `next.js` · `react` · `tailwind`

<br/>

**infrastructure**

`aws` · `docker` · `kafka` · `mlflow` · `prometheus` · `vercel` · `supabase` · `git`

</div>

---

## github

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=yuno7777&show_icons=true&hide_border=true&bg_color=000000&title_color=ffffff&text_color=999999&icon_color=ffffff&ring_color=ffffff&include_all_commits=true&count_private=true" height="170"/>

<img src="https://streak-stats.demolab.com/?user=yuno7777&hide_border=true&background=000000&ring=ffffff&fire=ffffff&currStreakLabel=ffffff&sideLabels=777777&currStreakNum=ffffff&sideNums=ffffff&dates=555555" height="170"/>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yuno7777&layout=compact&langs_count=8&hide_border=true&bg_color=000000&title_color=ffffff&text_color=999999" height="160"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=yuno7777&bg_color=000000&color=888888&line=ffffff&point=ffffff&area=true&hide_border=true" />

</div>

---

## contribution graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuno7777/yuno7777/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yuno7777/yuno7777/output/github-contribution-grid-snake.svg">
  <img alt="github contribution snake" src="https://raw.githubusercontent.com/yuno7777/yuno7777/output/github-contribution-grid-snake.svg">
</picture>

</div>

---

## current research directions

- how does recurrent computation change reasoning quality, latency and memory in small multimodal models?
- which quantization and kernel optimizations improve local inference without unacceptable accuracy loss?
- how can policies generalize across unseen environments under partial observability?

---

## currently

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=16&duration=2600&pause=1000&color=AAAAAA&center=true&vCenter=true&width=700&lines=building+native+inference+engines;experimenting+with+model+architectures;exploring+embodied+intelligence;engineering+distributed+agent+systems" />

</div>

---

<div align="center">

<sub>building towards human-like machine intelligence.</sub>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=14&duration=3500&pause=1400&color=666666&center=true&vCenter=true&width=500&lines=build.;break.;understand.;repeat." />

</div>
