<a id="readme-top"></a>

<div align="center">

<h1>Awesome Agent Abstention</h1>

<p align="center">
  <img src="assets/agent-abstention.png" width="400" alt="Agent Abstention: a robot holding up a hand to stop in front of a warehouse">
</p>

<strong>A curated collection of research on knowing when to act, ask, defer, or abstain.</strong>

<p>
  <!--
  <a href="#-paper-list"><img alt="Papers: 40" src="https://img.shields.io/badge/Papers-40-6C5CE7?style=flat-square"></a>
  <a href="#-table-of-contents"><img alt="Research categories: 6" src="https://img.shields.io/badge/Categories-6-008C95?style=flat-square"></a>
  <a href="#-news"><img alt="Updated: October 2026" src="https://img.shields.io/badge/Updated-Oct_2026-3776AB?style=flat-square"></a>
  -->
  <a href="https://awesome.re"><img alt="Awesome" src="https://awesome.re/badge-flat2.svg"></a>
  <img alt="Focus: Agent Abstention" src="https://img.shields.io/badge/Focus-Agent_Abstention-6C5CE7?style=flat-square">
  <a href="https://github.com/WBChe/awesome-agent-abstention/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/WBChe/awesome-agent-abstention?style=flat-square&amp;color=E5A50A"></a>
  <a href="#contribute"><img alt="Contributions welcome" src="https://img.shields.io/badge/Contributions-Welcome-2E8B57?style=flat-square"></a>
</p>

<p>
  <a href="#-overview">🌍 Overview</a> &nbsp;•&nbsp;
  <a href="#-table-of-contents">🧭 Taxonomy</a> &nbsp;•&nbsp;
  <a href="#-table-of-contents">📚 Browse Papers</a> &nbsp;•&nbsp;
  <a href="#contribute">🤝 Contribute</a>
</p>

<sub>⭐ Star this repository to follow research on reliable agent decision-making.</sub>

</div>

---

## 🔥 News

- **October 25, 2026** — The collection now includes **40 papers** across **6 research categories**, covering agent abstention and closely related LLM abstention research.

<a id="contribute"></a>

> 🤝 **Contributions are welcome!** Submit an issue or pull request with a paper link, a brief explanation of its relevance, and an official GitHub code repository when available.

## 🔗 Citation

Please cite the **original papers** when using their methods, benchmarks, or evaluation protocols. Each entry links directly to its research record.

---

## 🌍 Overview

**When should an agent stop acting?** Missing requirements, unavailable tools, conflicting evidence, and risks discovered during execution can make further action unjustified. **Agent abstention** studies when to withhold a tool call, stop an unresolvable task, ask for clarification, or defer to human assistance.

The collection covers **tool selection**, **sequential stopping**, **clarification**, **embodied help seeking**, and **embodied answerability**. Related language-model, retrieval, and multimodal studies appear together in **LLM Abstention** at the end of the paper list.

> 🎯 **Scope:** Works must directly study a decision to act, answer, clarify, defer, or abstain. General agent architectures, hallucination detection, and broad safety research are included only when they address this boundary. Epistemic abstention, safety refusal, and human escalation have distinct triggers and evaluation requirements.

## 📒 Table of Contents

- [Tool Availability and Action Selection](#tool-availability-and-action-selection)
- [Sequential Stopping and Runtime Abstention](#sequential-stopping-and-runtime-abstention)
- [Selective Clarification in Language and Tool Agents](#selective-clarification-in-language-and-tool-agents)
- [Embodied Planning and Help Seeking](#embodied-planning-and-help-seeking)
- [Visual and Embodied Answerability](#visual-and-embodied-answerability)
- [📚 Other resources: LLM Abstention](#-other-resources-llm-abstention)

---

## 📄 Paper List

### Tool Availability and Action Selection

| Date | Title | Paper | Code |
|:-:|:-:|:-|:-:|
| 2608 | Repair, Not Improvement: Decomposing Constrained Decoding in Tool-Call Abstention<br>*arXiv, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2608.13959) | - |
| 2510 | The Reasoning Trap: How Enhancing LLM Reasoning Amplifies Tool Hallucination<br>*ACL, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2510.22977) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/albert-y1n/Reasoning_Trap) |
| 2504 | When2Call: When (not) to Call Tools<br>*NAACL, 2025* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2504.18851) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/NVIDIA/When2Call) |
| 2406 | ToolBeHonest: A Multi-level Hallucination Diagnostic Benchmark for Tool-Augmented Large Language Models<br>*EMNLP, 2024* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2406.20015) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/ToolBeHonest/ToolBeHonest) |

---

### Sequential Stopping and Runtime Abstention

| Date | Title | Paper | Code |
|:-:|:-:|:-|:-:|
| 2610 | HERA: Harness-Environment Co-Evolution for Reliable Agentic Abstention<br>*arXiv, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2610.06563) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/lhannnn/HERA-Bench) |
| 2610 | When Is a Memory Safe Enough to Act On? Action-Conditioned Verification for Long-Lived Agents<br>*arXiv, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2610.31446) | - |
| 2607 | AgentAbstain: Do LLM Agents Know When Not to Act?<br>*NeurIPS, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2607.10059) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/AntiQuality/agentabstain) |
| 2606 | Designing for Doubt: The Case for Informed Abstention in Autonomous Agents<br>*AIES, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2606.02965) | - |
| 2606 | Agentic Abstention: Do Agents Know When to Stop Instead of Act?<br>*NeurIPS, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2606.28733) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/lhannnn/agentic-abstention) |

---

### Selective Clarification in Language and Tool Agents

| Date | Title | Paper | Code |
|:-:|:-:|:-|:-:|
| 2607 | Structured Uncertainty guided Clarification for LLM Agents<br>*Findings of ACL, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://aclanthology.org/2026.findings-acl.2028/) | - |
| 2606 | When Search Agents Should Ask: DiscoBench for Clarification-Aware Deep Search<br>*arXiv, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2606.27669) | - |
| 2604 | HiL-Bench (Human-in-Loop Benchmark): Do Agents Know When to Ask for Help?<br>*arXiv, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2604.09408) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/hilbenchauthors/hil-bench) |
| 2603 | Ask or Assume? Uncertainty-Aware Clarification-Seeking in Coding Agents<br>*EMNLP, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2603.26233) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/nedwards99/ask-or-assume) |

---

### Embodied Planning and Help Seeking

| Date | Title | Paper | Code |
|:-:|:-:|:-|:-:|
| 2402 | Introspective Planning: Aligning Robots' Uncertainty with Inherent Task Ambiguity<br>*NeurIPS, 2024* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2402.06529) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/kevinliang888/IntroPlan) |
| 2307 | Robots That Ask For Help: Uncertainty Alignment for Large Language Model Planners<br>*CoRL, 2023* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2307.01928) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/google-research/google-research/tree/master/language_model_uncertainty) |

---

### Visual and Embodied Answerability

| Date | Title | Paper | Code |
|:-:|:-:|:-|:-:|
| 2512 | When Robots Should Say "I Don't Know": Benchmarking Abstention in Embodied Question Answering<br>*CVPR, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2512.04597) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/gibrantaowu/AbstainEQA) |

---

## 📚 Other resources: LLM Abstention

| Date | Title | Paper | Code |
|:-:|:-:|:-|:-:|
| 2610 | Strong yet Controllable LLM Abstention without Learning to Abstain<br>*arXiv, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2610.16318) | - |
| 2610 | DeclineCraft: A RAG Abstention Benchmark for Jointly Measuring Combined Retrieval and Parametric Knowledge<br>*arXiv, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2610.28340) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/Thakur-Atharva/declinecraft-benchmark) |
| 2609 | When and How Should an Agent Clarify? CIGAsk: Teaching LLMs to Clarify via Counterfactual Information Gain<br>*Findings of EMNLP, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2609.24290) | - |
| 2609 | The Commit-Abstain Circuit: Why Language Models Hallucinate Instead of Abstaining<br>*NeurIPS, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2609.32964) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/vnht/commit-abstain-circuit) |
| 2608 | REIN: Bridging the Gap between Reasoning and Reliability via Reflection and Abstention Alignment<br>*arXiv, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2608.07931) | - |
| 2605 | Bridging the Detection-to-Abstention Gap in Reasoning Models under Insufficient Information<br>*arXiv, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2605.28070) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/AQ-MedAI/Judge-Then-Solve) |
| 2604 | Knowing When Not to Answer: Evaluating Abstention in Multimodal Reasoning Systems<br>*arXiv, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2604.14799) | - |
| 2604 | Abstain-R1: Calibrated Abstention and Post-Refusal Clarification via Verifiable RL<br>*ACL, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2604.17073) | - |
| 2604 | Knowing When to Quit: A Principled Framework for Dynamic Abstention in LLM Reasoning<br>*ICML, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2604.18419) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/HenDav/mid-gen-abs) |
| 2602 | When Silence Is Golden: Can LLMs Learn to Abstain in Temporal QA and Beyond?<br>*ICLR, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2602.04755) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/Blackzxy/AbstentionTemporalQA) |
| 2509 | OffTopicEval: When Large Language Models Enter the Wrong Chat, Almost Always!<br>*ICLR, 2026* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2509.26495) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/declare-lab/OffTopicEval) |
| 2506 | AbstentionBench: Reasoning LLMs Fail on Unanswerable Questions<br>*NeurIPS, 2025* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2506.09038) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/facebookresearch/AbstentionBench) |
| 2502 | CAP: Conformalized Abstention Policies for Context-Adaptive Risk Management for LLMs and VLMs<br>*ACML, 2025* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://proceedings.mlr.press/v304/tayebati26a.html) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/sinatayebati/vlm-uncertainty) |
| 2412 | Unanswerability Evaluation for Retrieval Augmented Generation<br>*ACL, 2025* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2412.12300) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/SalesforceAIResearch/Unanswerability_RAGE) |
| 2409 | Measuring and Enhancing Trustworthiness of LLMs in RAG through Grounded Attributions and Learning to Refuse<br>*ICLR, 2025* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2409.11242) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/declare-lab/trust-align) |
| 2407 | Do LLMs Know When to NOT Answer? Investigating Abstention Abilities of Large Language Models<br>*COLING, 2025* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2407.16221) | - |
| 2407 | Know Your Limits: A Survey of Abstention in Large Language Models<br>*TACL, 2025* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2407.18418) | - |
| 2405 | LLMs can learn self-restraint through iterative self-reflection<br>*TMLR, 2025* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2405.13022) | - |
| 2404 | Mitigating LLM Hallucinations via Conformal Abstention<br>*arXiv, 2024* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2405.01563) | - |
| 2402 | Don't Hallucinate, Abstain: Identifying LLM Knowledge Gaps via Multi-LLM Collaboration<br>*ACL, 2024* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2402.00367) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/BunsenFeng/AbstainQA) |
| 2311 | R-Tuning: Instructing Large Language Models to Say 'I Don't Know'<br>*NAACL, 2024* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2311.09677) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/shizhediao/R-Tuning) |
| 2305 | Do Large Language Models Know What They Don't Know?<br>*Findings of ACL, 2023* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2305.18153) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/yinzhangyue/SelfAware) |
| 2212 | CLAM: Selective Clarification for Ambiguous Questions with Generative Language Models<br>*arXiv, 2022* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2212.07769) | - |
| 2204 | Reliable Visual Question Answering: Abstain Rather Than Answer Incorrectly<br>*ECCV, 2022* | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge)](https://arxiv.org/abs/2204.13631) | [![Code](https://img.shields.io/badge/Code-A42C25?style=for-the-badge&color=black)](https://github.com/facebookresearch/reliable_vqa) |
