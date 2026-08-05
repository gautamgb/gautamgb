<div align="center">

**[seekgb.com](https://www.seekgb.com)** · **[LinkedIn](https://linkedin.com/in/gautamgb)** · **[mcpindex.ai](https://mcpindex.ai)** · **[ORCID](https://orcid.org/0009-0001-4448-1438)**

<a href="https://www.seekgb.com">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=16&duration=2500&pause=1500&color=6E7681&vCenter=true&repeat=true&width=600&height=28&lines=I+build+products.;I+build+platforms.;I+build+the+infrastructure+that+makes+AI+systems+actually+work+in+production." alt="Typing animation" />
</a>

<br />

[![Peer Reviewed](https://img.shields.io/badge/Peer--Reviewed-Elsevier%20Chapter-b31b1b?style=flat-square)](https://doi.org/10.1016/B978-0-443-32884-8.00015-5)
[![Datasets](https://img.shields.io/badge/Open%20Datasets-4%20on%20Zenodo-1682D4?style=flat-square&logo=zenodo&logoColor=white)](#open-datasets)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0001--4448--1438-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0001-4448-1438)
[![Experience](https://img.shields.io/badge/Platform%20PM-12%2B%20Years-64748b?style=flat-square)]()
[![License](https://img.shields.io/badge/Data-CC--BY--4.0-10b981?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)

**Product Manager blending strategy with execution** · Developer Platforms · Public APIs · Agentic AI & MCP

</div>

---

## Focus

Developer platforms and the trust layer under agentic AI. The thesis in one line: **a tool's contract can change after you approved it — no version bump, no republish event, nothing the consumer sees — so verification has to be continuous, not a one-time review at onboarding.**

```
contract.pinned_at    = approval_time      // the snapshot, not the docs
served.contract       ≠ pinned.contract    // drift, with no republish event
verification          = continuous         // advisory evidence, not a gate
```

I measure this at registry scale and publish the data openly. 3,500+ MCP servers observed daily; four datasets on Zenodo under CC-BY.

---

## Standards & Research

| Work | Status | Scope |
|---|---|---|
| **OWASP GenAI Data Security Best Practices v2** | ![Contributor](https://img.shields.io/badge/-Contributor-10b981?style=flat-square) | Authored Ch9 Pattern 8, "Tool-Contract Capture & Drift Verification"; amended the P7 Tier 1 contract-capture control |
| **OWASP FIASSE** | ![Active](https://img.shields.io/badge/-Active%20Work-f59e0b?style=flat-square) | Dependency stewardship for agentic dependencies — contracts that change with no version bump ([Discussion #20](https://github.com/OWASP/FIASSE/discussions/20)) |
| **MITRE ATLAS** | ![Under Review](https://img.shields.io/badge/-Under%20Review-64748b?style=flat-square) | Mitigation submitted for AML.T0104 (Publish Poisoned AI Agent Tool), covering post-approval contract mutation |
| **OWASP AISVS C9** | ![Active](https://img.shields.io/badge/-Active%20Work-f59e0b?style=flat-square) | Real-data conformance fixtures for action-class and reversibility controls ([reference repo](https://github.com/gautamgb/aisvs-c9-action-class-conformance)) |
| **Adversarial ML for IoMT Security** | ![Peer Reviewed](https://img.shields.io/badge/-Peer%20Reviewed-b31b1b?style=flat-square) | Elsevier, *Internet of Multimedia Things Security* — third author ([DOI](https://doi.org/10.1016/B978-0-443-32884-8.00015-5)) |

### Open Datasets

All published under **Bharti, Gautam** ([ORCID 0009-0001-4448-1438](https://orcid.org/0009-0001-4448-1438)), CC-BY-4.0. DOIs below are concept DOIs — they always resolve to the latest version.

| Record | Type | DOI |
|---|---|---|
| mcpindex Drift Report — Edition v1 (contract-drift corpus) | Dataset | [10.5281/zenodo.21449149](https://doi.org/10.5281/zenodo.21449149) |
| mcpindex Source Liveness — Baseline v1 (reachability census) | Dataset | [10.5281/zenodo.21501867](https://doi.org/10.5281/zenodo.21501867) |
| MCP Registry Drift Panel v1 (longitudinal observation panel) | Dataset | [10.5281/zenodo.21709945](https://doi.org/10.5281/zenodo.21709945) |
| MCP Declared-Effect Coverage and Contract Binding v1 | Dataset | [10.5281/zenodo.21778281](https://doi.org/10.5281/zenodo.21778281) |
| Registry Descriptions Go Stale Unevenly: An 89-Day Measurement | Preprint | [10.5281/zenodo.21728369](https://doi.org/10.5281/zenodo.21728369) |

---

## What I've Built

Every tool here started as a proof-of-concept to solve friction I hit while shipping enterprise AI infrastructure. I prototype before I spec.

<table>
<tr>
<td width="50%" valign="top">

### [mcpindex.ai](https://mcpindex.ai)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
[![GitHub](https://img.shields.io/badge/-mcpindex--ai-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mcpindex-ai)

The agent-native index of MCP servers. Recommendation API + drop-in MCP server (`mcp-server-mcpindex` on npm) for finding the right MCP at inference time — not the developer browsing a sidebar. 3,500+ servers indexed daily from the official registry, ranked by an open Quality Score. Built because every existing directory was built for humans, not agents.

</td>
<td width="50%" valign="top">

### [Agent Universe](https://github.com/gautamgb/agent-universe)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

Enterprise-grade agent builder factory. A composable framework for building governed AI agents with structured tool access, memory, and orchestration patterns.

### [MCP Server Generator](https://github.com/gautamgb/mcp-server-generator)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

Paste an OpenAPI spec, get a production-ready MCP server. Built to eliminate the boilerplate that slows agentic adoption — the same friction I kept hitting when onboarding teams to MCP at scale.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Semantic Router](https://github.com/gautamgb/Context-Aware-Semantic-Router)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

Classifies user queries by complexity and routes them to the right LLM — fast model for simple questions, heavy model for complex reasoning. Cuts inference costs without sacrificing quality. Exposes latency, model, and cost telemetry per request.

### [Zero-Trust PII Proxy Agent](https://github.com/gautamgb/Zero-Trust-PII-Proxy-Agent)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

A privacy-preserving proxy between your application and your LLM. A fast model replaces PII with placeholders, the heavy model processes only clean text, and the response is unmasked before returning. Enterprise compliance without crippling AI capability.

</td>
<td width="50%" valign="top">

### [Persona Extractor](https://www.seekgb.com/persona-extractor)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

Extracts structured behavioral personas from writing samples — communication style, decision-making patterns, values, expertise markers, and 15 behavioral dimensions. Feed it emails, docs, or feedback; get a portable PERSONA.md that evolves over time. The cognitive fingerprint that demographics miss.

### [AI Cost Estimator](https://github.com/gautamgb/AI_Cost_Estimator)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

Agentic workflows cost 10-50x more than the pricing page implies. Models what no other tool does: context accumulation across multi-step agent loops, tool call overhead, orchestration pattern multipliers, and prompt caching savings.

</td>
</tr>
</table>

All deployed and live at **[seekgb.com](https://www.seekgb.com)**

---

## How I Build Product

- **Start with the problem**, not the technology. Every tool I've built exists because I hit a real friction point — not because the tech was interesting. If nobody needs it, it's shelfware.
- **Prototype before you spec**. I build working POCs to pressure-test ideas before committing engineering resources. The best specs come from building, not theorizing.
- **Stay close to the users**. I run discovery calls, read support tickets, and use my own products. You can't build for developers if you've never felt their friction firsthand.
- **Ship small, learn fast, iterate faster**. I'd rather validate with a rough working version this week than debate a polished spec for a month. Assumptions are cheap to hold and expensive to ship.

---

## The Pattern

I've spent 12+ years building platforms at Microsoft (Power BI/Synapse, Windows Shell), T-Mobile, Trend Micro, and Qualtrics. The recurring problem: powerful infrastructure exists, but the people who need it can't reach it. These tools are my way of closing that gap — building the missing pieces I couldn't find when I needed them.

---

<div align="center">

[![Website](https://img.shields.io/badge/seekgb.com-4dd0e1?style=for-the-badge&logoColor=white)](https://www.seekgb.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gautamgb-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gautamgb)
[![mcpindex](https://img.shields.io/badge/mcpindex.ai-1d4ed8?style=for-the-badge&logoColor=white)](https://mcpindex.ai)

📍 Seattle, WA · ⏱ GMT-07:00

</div>
