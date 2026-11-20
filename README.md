<div align="center">

# Harmain Mughal

**AI Research · Transformer Interpretability · Reproducible ML · Software Engineering**

I publish research as **Harmain Dastgir** (Independent Researcher). I investigate how model behavior changes under targeted weight-space interventions, and I build open, inspectable tools around the evidence.

[Research website](https://harmain11.github.io/fluid-tensors/) · [Hugging Face](https://huggingface.co/Harmain1) · [ORCID](https://orcid.org/0009-0004-1090-545X) · [LinkedIn](https://www.linkedin.com/in/harmain-mughal-7b1845379)

[![Fluid Tensors — open transformer weight-space research](https://raw.githubusercontent.com/Harmain11/fluid-tensors/main/docs/assets/social-cover.png)](https://harmain11.github.io/fluid-tensors/)

</div>

## 🔬 Featured research: Fluid Tensors

**Paper 1 — *One Frozen Edit, Four Ways to Ask: Prompt-Conditioned Functional Effects in a Transformer***

What changes when the **same frozen weight intervention** is evaluated with different wording? Fluid Tensors investigates prompt-conditioned final-token logit responses in a selected Qwen2.5-1.5B-Instruct checkpoint. The project includes a paper, reproducible code, archived results, uncertainty analyses, and control experiments.

**Explore the evidence**

- 📊 **[Interactive Paper 1 explorer on Hugging Face](https://huggingface.co/spaces/Harmain1/fluid-tensors-paper1)** — experimental contrasts, question-level visualization, and eight figures.
- 📄 **[Paper / Zenodo DOI](https://doi.org/10.5281/zenodo.24338059)** — Version 3 working preprint.
- 🌐 **[Research article and visualizations](https://harmain11.github.io/fluid-tensors/papers/one-frozen-edit.html)** — readable account of methods, results, and limits.
- 💻 **[Fluid Tensors source and evidence](https://github.com/Harmain11/fluid-tensors)** — scripts, records, figure generation, and citation metadata.
- 🔁 **[Independent replication challenge](https://github.com/Harmain11/fluid-tensors/blob/main/docs/REPLICATION_CHALLENGE.md)** — known gaps and ways to test them.

### Recorded evidence snapshot

| Paper 1 confirmation measure | Recorded observation |
| --- | ---: |
| Fresh questions in the within-model check | **64** |
| Positive matched signed-edit contrasts | **62 / 64** |
| Mean matched signed-edit contrast | **+0.193491** |
| Question-bootstrap 95% interval | **[+0.166896, +0.219002]** |
| Mean matched rotated-direction control | **+0.004060** |

<p align="center">
  <a href="https://github.com/Harmain11/fluid-tensors/blob/main/docs/assets/p1_confirmation_condition_contrasts.png"><img src="https://raw.githubusercontent.com/Harmain11/fluid-tensors/main/docs/assets/p1_confirmation_condition_contrasts.png" alt="Fresh-question response contrast and rotated-direction control, with bootstrap intervals" width="48%"></a>
  <a href="https://github.com/Harmain11/fluid-tensors/blob/main/docs/assets/p1_confirmation_matched_vs_raw.png"><img src="https://raw.githubusercontent.com/Harmain11/fluid-tensors/main/docs/assets/p1_confirmation_matched_vs_raw.png" alt="Raw versus token-count matched response contrasts across 64 questions" width="48%"></a>
</p>

> **Scientific boundary:** These are **final-token logit-response contrasts**, not percentages or improvements in math-answer accuracy. The evidence concerns one selected checkpoint and frozen edit; it does **not** establish general-purpose model repair, independent-model replication, or semantic-only causality. The paper is a **preprint, not peer reviewed**.

## 🛠️ Selected engineering work

- **[Cross-Chain-Hub](https://github.com/Harmain11/Cross-Chain-Hub)** — AI-assisted smart-contract development tooling.
- **[Fluid Tensors research infrastructure](https://github.com/Harmain11/fluid-tensors)** — Python analysis, archived experiment results, scientific figures, and a public research website.

## 🧭 Current interests

Transformer interpretability · Model behavior under weight edits · Causal controls · Reproducibility · Evaluation methodology · Applied AI systems

I'm interested in **constructive criticism, independent replications, and collaborations** that test both positive findings and limitations. The research repository's [issues](https://github.com/Harmain11/fluid-tensors/issues) and [discussions](https://github.com/Harmain11/fluid-tensors/discussions) are open.

<sub>Research author: Harmain Dastgir · Independent Researcher · [ORCID 0009-0004-1090-545X](https://orcid.org/0009-0004-1090-545X)</sub>
