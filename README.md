<div align="center">

# Awesome Resource Consumption Threat Papers

<p>
  <strong>A curated reading hub for resource-consumption threats in large models, reasoning systems, and agentic workflows.</strong>
</p>

<p>
  <a href="./topics/attack.md">⚔️ Attack</a> •
  <a href="./topics/interpretability.md">🔍 Interpretability</a> •
  <a href="./topics/defense.md">🛡️ Defense</a> •
  <a href="./topics/bench_dataset.md">🧪 Bench & Dataset</a> •
  <a href="./topics/survey.md">🧭 Survey</a>
</p>

<p>
  <img alt="status" src="https://img.shields.io/badge/status-curated-blue">
  <img alt="scope" src="https://img.shields.io/badge/focus-resource%20consumption%20threats-0f766e">
  <img alt="content" src="https://img.shields.io/badge/content-topic--organized-orange">
</p>

</div>

## ✨ Overview

This repository is the public-facing paper index for our review project on resource consumption threats. Instead of placing every paper into one long timeline, we organize the literature into a compact set of research directions so readers can move quickly from the main page to the exact topic they need.

It is designed for three common workflows:

- quick scanning when you want a fast overview of the field
- topic-oriented reading when you are tracking one direction in depth
- structured maintenance when new papers are added from the review workflow in the project root

## Why This Repository

Resource consumption threats are no longer limited to simple denial-of-service settings. In modern large-model systems, abnormal cost growth can emerge through long-chain reasoning, inference inflation, tool misuse, memory pressure, scheduling failures, and agent workflow abuse.

This repository collects papers that help answer questions such as:

- how resource overhead is triggered, amplified, or weaponized
- how we can explain and measure resource-intensive behavior
- which defenses can cap, isolate, or monitor unsafe execution
- what benchmarks, datasets, and surveys already structure this area

## 🚀 Quick Start

| If you want to... | Start here |
|:--|:--|
| understand attack surfaces and cost-amplification patterns | [⚔️ Attack](./topics/attack.md) |
| study where resource usage comes from inside model or system behavior | [🔍 Interpretability](./topics/interpretability.md) |
| explore mitigation, scheduling, monitoring, or containment strategies | [🛡️ Defense](./topics/defense.md) |
| find reusable evaluation assets and measurement setups | [🧪 Bench & Dataset](./topics/bench_dataset.md) |
| get a high-level map of the area before diving deeper | [🧭 Survey](./topics/survey.md) |

## 🗺️ Topic Map

### ⚔️ Attack

Papers on resource exhaustion attacks, inference inflation, adversarial cost amplification, malformed workload design, and related threat studies.

Go to: [Attack](./topics/attack.md)

### 🔍 Interpretability

Papers that explain where, why, and how resource consumption emerges in large-model systems, including compute expansion, execution-path growth, and runtime bottlenecks.

Go to: [Interpretability](./topics/interpretability.md)

### 🛡️ Defense

Papers on mitigation, scheduling, isolation, monitoring, throttling, and broader cost-control mechanisms for unsafe or abusive workloads.

Go to: [Defense](./topics/defense.md)

### 🧪 Bench & Dataset

Benchmarks, datasets, measurement suites, and evaluation resources for studying resource-related risks and system behavior.

Go to: [Bench & Dataset](./topics/bench_dataset.md)

### 🧭 Survey

Survey papers, reviews, taxonomies, and synthesis work that help frame the broader landscape of resource consumption threats.

Go to: [Survey](./topics/survey.md)

## 📋 Table Schema

All topic pages share the same paper-table format:

| Published | First Author Institution | Venue | Title | Keywords |
|:--|:--|:--|:--|:--|

Field meanings:

- `Published`: earliest public publication date used in the repository
- `First Author Institution`: normalized first-author affiliation
- `Venue`: publication venue, workshop, journal, or archive source
- `Title`: paper title with link
- `Keywords`: short descriptors for filtering and quick scanning

## 🛠️ Maintenance Note

This subdirectory serves as the presentation layer of the review project. Future maintenance is driven from the project root, where papers can be classified, normalized, and then written into the appropriate topic page.
