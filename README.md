
**[seekgb.com](https://www.seekgb.com)** · **[LinkedIn](https://linkedin.com/in/gautamgb)**

<a href="https://www.seekgb.com">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=16&duration=2500&pause=1500&color=6E7681&vCenter=true&repeat=true&width=600&height=28&lines=I+build+products.;I+build+platforms.;I+build+the+infrastructure+that+makes+AI+systems+actually+work+in+production." alt="Typing animation" />
</a>

# Product Manager blending strategy with execution

I constantly am thinking about Developer Platforms, Public APIs, and agentic AI (incl MCP, RAG, workflow orchestration) powered ecosystems.

###  How I Build Product
  - **Start with the problem**, not the technology. Every tool I've built exists because I hit a real friction point — not because the tech was interesting. If nobody needs it, it's shelfware.
  - **Prototype before you spec**. I build working POCs to pressure-test ideas before committing engineering resources. The best specs come from building, not theorizing.
  - **Stay close to the users**. I run discovery calls, read support tickets, and use my own products. You can't build for developers if you've never felt their friction firsthand.
  - **Ship small, learn fast, iterate faster**. I'd rather validate with a rough working version this week than debate a polished spec for a month. Assumptions are cheap to hold and expensive to ship.

Every tool here started as a proof-of-concept to solve friction I hit while shipping enterprise AI infrastructure. I prototype before I spec.

---

### What I've Built

**[Agent Universe](https://github.com/gautamgb/agent-universe)** `Python`
Enterprise-grade agent builder factory. A composable framework for building governed AI agents with structured tool access, memory, and orchestration patterns.

**[MCP Server Generator](https://github.com/gautamgb/mcp-server-generator)** `TypeScript`
Paste an OpenAPI spec, get a production-ready MCP server. Built to eliminate the boilerplate that slows agentic adoption — the same friction I kept hitting when onboarding teams to MCP at scale.

**[Semantic Router](https://github.com/gautamgb/Context-Aware-Semantic-Router)** `TypeScript`
Classifies user queries by complexity and routes them to the right LLM — fast model for simple questions, heavy model for complex reasoning. Cuts inference costs without sacrificing quality. Exposes latency, model, and cost telemetry per request.

**[Zero-Trust PII Proxy Agent](https://github.com/gautamgb/Zero-Trust-PII-Proxy-Agent)** `TypeScript`
A privacy-preserving proxy that sits between your application and your LLM. A fast model sanitizes input (replaces PII with placeholders), the heavy model processes only clean text, and the response is unmasked before returning. Enterprise compliance without crippling AI capability.

**[Persona Extractor](https://www.seekgb.com/persona-extractor)** `TypeScript`
Extracts structured behavioral personas from writing samples — communication style, decision-making patterns, values, expertise markers, and 15 behavioral dimensions. Feed it emails, docs, or feedback; get a portable PERSONA.md that evolves over time. The cognitive fingerprint that demographics miss.

**[AI Cost Estimator](https://github.com/gautamgb/AI_Cost_Estimator)** `TypeScript`
Agentic workflows cost 10-50x more than the pricing page implies. This calculator models what no other tool does: context accumulation across multi-step agent loops, tool call overhead, orchestration pattern multipliers, and prompt caching savings. Eight interview-ready presets with dual API/Bedrock pricing and per-component stack breakdowns.

All deployed and live at **[seekgb.com](https://www.seekgb.com)**

---

### The Pattern

I've spent 12+ years building platforms at Microsoft (Power BI/Synapse, Windows Shell), T-Mobile, Trend Micro, and Qualtrics. The recurring problem: powerful infrastructure exists, but the people who need it can't reach it. These tools are my way of closing that gap — building the missing pieces I couldn't find when I needed them.

---
