---
title: "MedLA: A Logic-Driven Multi-Agent Framework for Complex Medical Reasoning with Large Language Models"
collection: publications
category: conferences
permalink: /publication/2026-medla-aaai
excerpt: 'This paper proposes MedLA, a novel logic-driven multi-agent framework to enhance LLM reasoning in complex medical tasks.'
date: 2026-02-01
venue: 'AAAI Conference on Artificial Intelligence (AAAI 2026)(Oral).'
---

## Abstract

Answering complex medical questions requires not only domain expertise and patient-specific information, but also structured and multi-perspective reasoning. Existing multi-agent approaches often rely on fixed roles or shallow interaction prompts, limiting their ability to detect and resolve fine-grained logical inconsistencies. To address this, we propose \textsc{MedLA}, a logic-driven multi-agent framework built on large language models. Each agent organizes its reasoning process into an explicit logical tree based on syllogistic triads (major premise, minor premise, and conclusion), enabling transparent inference and premise-level alignment. Agents engage in a multi-round, graph-guided discussion to compare and iteratively refine their logic trees, achieving consensus through error correction and contradiction resolution. We demonstrate that \textsc{MedLA} consistently outperforms both static role-based systems and single-agent baselines on challenging benchmarks such as MedDDx and standard medical QA tasks. Furthermore, \textsc{MedLA} scales effectively across both open-source and commercial LLM backbones, achieving state-of-the-art performance and offering a generalizable paradigm for trustworthy medical reasoning.

## Key Contributions

- Proposed a logic-driven multi-agent framework for medical reasoning
- Developed a self-checking optimization method to improve model reliability
- Validated the framework's performance through extensive experiments
