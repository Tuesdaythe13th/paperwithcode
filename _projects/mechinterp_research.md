---
layout: page
title: Mechanistic Interpretability Research
description: Forensic analysis and causal diagnostics for frontier AI systems under deployment conditions
img: assets/img/mechinterp_preview.jpg
importance: 4
category: research
related_publications: true
---

## Mechanistic Interpretability Under Deployment Conditions

Most interpretability research assumes cooperative models, static weights, and benign prompts. Real systems operate under distribution shift, fine-tuning drift, and adversarial interaction. This research program develops interpretability methods that remain valid under deployment pressure.

## Research Agenda

### Causal Assays for Explanation Faithfulness

Investigating the gap between model behavior and model narration:
- Behavior vs. explanation dissociation testing
- Causal intervention protocols
- Faithfulness metrics for interpretability tools
- Deception detection in model explanations

### Circuit-Level Diagnostics for Agentic Models

Extending mechanistic interpretability to agentic systems:
- Planning circuit identification
- Tool-use pathway tracing
- Memory formation and retrieval mechanisms
- Goal representation and modification tracking

### Stress-Testing Interpretability Tools

Evaluating interpretability methods against adversarial conditions:
- Jailbreak resistance of explanation systems
- Interpretability under fine-tuning attacks
- Robustness to prompt injection
- Cross-model transferability of insights

### Open to Closed Weight Transfer

Understanding how failure modes transfer:
- Mapping vulnerabilities from open-weight to closed models
- Generalization of interpretability findings
- Forensic reverse engineering protocols
- Zero-knowledge verification methods

## Technical Stack

**Core Tools:**
- PyTorch, TransformerLens
- Hugging Face Transformers
- Transluce Docent, Neuropedia
- Custom forensic suites

**Methodologies:**
- Activation patching and ablation
- Causal tracing
- Circuit discovery algorithms
- Adversarial probing

## Outputs

- **Reusable Forensic Protocols** - Standardized methods for model analysis
- **Ablation-Based Metrics** - Quantitative measures of mechanistic understanding
- **Open Evaluation Suites** - Public benchmarks for interpretability tools
- **Neural Forensic Suite** - Toolkit for mechanistic analysis

## Related Work

**Dossier:** MECHINTERP_DOSSIER_mats2026
Comprehensive collection of mechanistic interpretability protocols, case studies, and forensic analyses.

**Collaborations:**
- Contributing to open interpretability research
- MATS (ML Alignment & Theory Scholars) program participation
- Standards development for model transparency

## Problem Statement

Current interpretability methods fail when needed most—under adversarial pressure, deployment drift, and deceptive behavior. This research builds interpretability that works in the wild, not just in the lab.

## Strategic Impact

Enables:
- Audit-grade model analysis
- Regulatory compliance verification
- Security vulnerability assessment
- Failure mode prediction and prevention
