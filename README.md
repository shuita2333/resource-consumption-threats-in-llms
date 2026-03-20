# Awesome Resource Consumption Threat Papers

A curated repository for literature on resource consumption threats in large models, reasoning systems, and agentic workflows.

This repository focuses on organizing papers by research direction so that readers can quickly move from the main index to a dedicated topic page and then into the corresponding paper list.

---

## Introduction

This repository is designed as the public-facing paper index for our review project on resource consumption threats. We organize papers around a small set of stable research categories instead of mixing all papers into one long list.

The repository is intended to support three common use cases:

- quick browsing from the main index
- topic-based reading and backtracking
- later automated updates from the maintenance workflow in the project root

At this stage, the topic pages are initialized as structured paper tables and will be filled incrementally as papers are processed.

## What You Can Find Here

- attack papers on resource exhaustion, inference inflation, and abuse of agent workflows
- interpretability papers that explain resource usage patterns and bottlenecks
- defense papers on mitigation, isolation, monitoring, and cost control
- benchmarks and datasets for evaluation and measurement
- survey papers that synthesize the landscape

## How To Use This Repository

- Start from the topic index below to choose a research direction.
- Enter the corresponding topic page to browse the paper table.
- Use the table fields to compare publication time, institution, venue, title, and keywords.

## Table of Contents

- [Introduction](#introduction)
- [What You Can Find Here](#what-you-can-find-here)
- [How To Use This Repository](#how-to-use-this-repository)
- [Topic Index](#topic-index)
- [Topic Highlights](#topic-highlights)
- [Repository Structure](#repository-structure)
- [Table Schema](#table-schema)
- [Maintenance Note](#maintenance-note)

---

## Topic Index

| Topic | Description | Paper List |
|:--|:--|:--|
| Attack | Resource exhaustion attacks, inference inflation, adversarial cost amplification, and related threat studies | [Attack](./topics/attack.md) |
| Interpretability | Analyses that explain where, why, and how resource consumption emerges in large-model systems | [Interpretability](./topics/interpretability.md) |
| Defense | Defense, mitigation, scheduling, isolation, monitoring, and cost-control mechanisms | [Defense](./topics/defense.md) |
| Bench & Dataset | Benchmarks, datasets, measurement suites, and evaluation resources | [Bench & Dataset](./topics/bench_dataset.md) |
| Survey | Surveys, reviews, taxonomies, and broader synthesis papers | [Survey](./topics/survey.md) |

## Topic Highlights

### Attack

Focuses on how adversaries or malformed workloads trigger abnormal cost growth, excessive reasoning depth, tool abuse, or service degradation.

Go to: [Attack](./topics/attack.md)

### Interpretability

Focuses on understanding where resource overhead comes from and how compute, memory, or execution paths expand during system operation.

Go to: [Interpretability](./topics/interpretability.md)

### Defense

Focuses on mechanisms that reduce abuse, cap resource cost, isolate workloads, or monitor unsafe execution patterns.

Go to: [Defense](./topics/defense.md)

### Bench & Dataset

Focuses on reusable evaluation assets, including benchmarks, datasets, and measurement settings for resource-related studies.

Go to: [Bench & Dataset](./topics/bench_dataset.md)

### Survey

Focuses on high-level synthesis papers, taxonomies, and review articles that help structure the overall field.

Go to: [Survey](./topics/survey.md)

---

## Repository Structure

- Project entry: [`../README.md`](../README.md)
- Topic directory: [`topics/`](./topics/)
- Topic pages:
  - [Attack](./topics/attack.md)
  - [Interpretability](./topics/interpretability.md)
  - [Defense](./topics/defense.md)
  - [Bench & Dataset](./topics/bench_dataset.md)
  - [Survey](./topics/survey.md)

## Table Schema

All topic pages use the same paper table format:

| Published | First Author Institution | Venue | Title | Keywords |
|:--|:--|:--|:--|:--|

Field meaning:

- `Published`: earliest public publication date used in the repository
- `First Author Institution`: normalized first-author affiliation
- `Venue`: publication venue, workshop, journal, or archive source
- `Title`: paper title with link
- `Keywords`: short research descriptors for filtering and quick scanning

## Maintenance Note

This subdirectory is the repository presentation layer. The future maintenance workflow will be driven from the project root and will write new entries into the correct topic page after classification and metadata completion.
