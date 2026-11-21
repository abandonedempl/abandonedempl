<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6a11cb,50:8e2de2,100:2575fc&height=160&section=header&text=Hi%2C%20I%27m%20Guanxuan&fontSize=48&fontColor=ffffff&fontAlignY=40&desc=AI%20Agents%20%C2%B7%20Evaluation%20%C2%B7%20LLM%20Apps&descSize=16&descAlignY=68&animation=fadeIn" alt="header" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/abandonedempl">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3500&pause=1000&color=6C9BFF&center=true&vCenter=true&width=720&height=70&lines=Building%20reliable%20AI%20agents;Tool%20use%2C%20memory%2C%20and%20evaluation;MSc%20Computer%20Science%20%40%20HKU" alt="Typing SVG" />
  </a>
</p>

---

| 🧭 **About Me** | |
|---|---|
| 🎓 | **吴官炫** — MSc in Computer Science and Technology @ [The University of Hong Kong](https://www.hku.hk) (2026.09–2027.07); BEng in Computer Science and Technology @ [Nanjing Normal University](https://www.njnu.edu.cn) (2022.09–2026.06) |
| 💼 | AI application development intern at **Vanjna (杭州梵域智能科技)** — built **FarmGuard**, a long-running compliance and anomaly-investigation agent (2026.06–2026.09) |
| 🛠️ | Independently designed and built a **cross-border customer-operations agent** for WhatsApp sales follow-up (2026.09–2026.11) |
| 📍 | Hangzhou, China |
| 📫 | [felix815811045@outlook.com](mailto:felix815811045@outlook.com) · [Personal site](https://abandonedempl.github.io) |

## 🎓 Education

| Institution | Degree | Period |
|---|---|---|
| [The University of Hong Kong](https://www.hku.hk) | MSc, Computer Science and Technology | 2026.09–2027.07 |
| [Nanjing Normal University](https://www.njnu.edu.cn) | BEng, Computer Science and Technology | 2026.09–2026.06 |

English: IELTS 7.5; CET-6.

## 💼 Selected Work

| Project | What I did | Period |
|---|---|---|
| **FarmGuard** · Vanjna (杭州梵域智能), AI Application Development Intern | Built a long-running compliance agent for livestock operations. Unified domain schemas and MCP / CLI tools for environment, veterinary drug, inventory, mortality, and vaccination data; turned investigation steps into executable SOPs; budgeted context with prioritized blocks; retrieved structured memory (fact / decision / lesson / open loop) via FTS5 and BM25; and ran a trace-based evaluation loop on normal, abnormal, and ambiguous cases. The system reached an internal pilot. | 2026.06–2026.09 |
| **Cross-border customer-operations agent** · Independent design and development | Built a workbench for WhatsApp customer communication and opportunity follow-up. Assembled MCP servers per request with schema and permission checks; graded tool effects so outbound messages require human approval; injected versioned wiki knowledge; ran a durable PostgreSQL task queue (serial per customer, parallel across customers); verified evidence with read-only specialist agents; and organized regression replay across tool calls, task execution, and evidence quality. | 2026.09–2026.11 |
| **[CRM Agent Lab (public demo)](https://github.com/abandonedempl/crm-agent-lab-demo)** | Browser demo of a personal CRM agent workbench: review sample opportunities, inspect tool returns, confirm pending actions, and replay desensitized model runs. The full source remains private. | Public demo |
| **[agent-reliability-repros](https://github.com/abandonedempl/agent-reliability-repros)** | Minimal, runnable reproductions of agent SDK reliability issues, including a Mastra `fetchWithRetry` cancellation case that was later fixed upstream. | 2026.10 |

Full write-ups: [abandonedempl.github.io](https://abandonedempl.github.io)

## 🌱 Open Source

The pull request links below are the original, verifiable records. Counts as of 2026-11-21.

<p align="center">
  <img src="https://img.shields.io/badge/MERGED_PRS-17-2EA043?style=flat-square&labelColor=24292F" alt="merged pull requests" /> &nbsp; <img src="https://img.shields.io/badge/PROJECTS-7-0969DA?style=flat-square&labelColor=24292F" alt="projects" />
</p>

| Project | Language | Merged |
|---|---|---|
| [<b>langflow-ai/langflow</b>](https://github.com/langflow-ai/langflow) | Python | 1 |
| [<b>bytedance/deer-flow</b>](https://github.com/bytedance/deer-flow) | Python | 10 |
| [<b>upstash/context7</b>](https://github.com/upstash/context7) | TypeScript | 1 |
| [<b>QwenLM/qwen-code</b>](https://github.com/QwenLM/qwen-code) | TypeScript | 1 |
| [<b>vercel/ai</b>](https://github.com/vercel/ai) | TypeScript | 1 |
| [<b>TencentCloud/Octop</b>](https://github.com/TencentCloud/Octop) | — | 2 |
| [<b>assistant-ui/assistant-ui</b>](https://github.com/assistant-ui/assistant-ui) | TypeScript | 1 |

Full write-ups: [Open Source](https://abandonedempl.github.io/oss/)

## 🔎 Selected Merged Contributions

| Project | My contribution | Merged PR | Date (Asia/Shanghai) |
|---|---|---|---|
| langflow-ai/langflow | Allow consecutive variable-list requests after concurrent database provider settings updates. Add regression coverage for standard, project-scoped, and prefixed deployment URLs. | [#16104](https://github.com/langflow-ai/langflow/pull/16104) | 2026-11-17 |
| upstash/context7 | Preserve JSONC comments and layout when the Context7 CLI adds or removes MCP server entries. | [#3508](https://github.com/upstash/context7/pull/3508) | 2026-11-05 |
| TencentCloud/Octop | Refresh AUTO agents whose harness config only carries a baked-in resolved fallback model when a provider is disabled, so background paths stop calling the removed provider. | [#2394](https://github.com/TencentCloud/Octop/pull/2394) | 2026-11-02 |
| bytedance/deer-flow | Make document chunk reads cancellation-safe across file-worker handoffs. | [#7496](https://github.com/bytedance/deer-flow/pull/7496) | 2026-10-25 |
| bytedance/deer-flow | Preserve link destinations in web_fetch on Windows when Readability extraction silently drops links. | [#7412](https://github.com/bytedance/deer-flow/pull/7412) | 2026-10-25 |
| bytedance/deer-flow | Reject boolean values in the knowledge_search LightRAG / RAGFlow provider settings so they are not coerced into timeouts or top_k. | [#7042](https://github.com/bytedance/deer-flow/pull/7042) | 2026-10-20 |
| TencentCloud/Octop | Make the frameless Linux desktop window edge- and corner-resizable. | [#1657](https://github.com/TencentCloud/Octop/pull/1657) | 2026-10-19 |
| bytedance/deer-flow | Preserve a concurrent peer's sandbox quarantine fence when directory retirement races a new record. | [#6961](https://github.com/bytedance/deer-flow/pull/6961) | 2026-10-17 |
| bytedance/deer-flow | Bound the re-injected view_image context with per-request budgets and recency-aware merge. | [#6829](https://github.com/bytedance/deer-flow/pull/6829) | 2026-10-14 |
| bytedance/deer-flow | Treat a scalar buzz allowed_users entry as a single member pubkey instead of per-character iteration. | [#6811](https://github.com/bytedance/deer-flow/pull/6811) | 2026-10-14 |
| QwenLM/qwen-code | Add regression tests pinning the unfinished-invocation guard that rejects a second submit while a turn is still running. | [#13257](https://github.com/QwenLM/qwen-code/pull/13257) | 2026-10-13 |
| bytedance/deer-flow | Preserve escaped pipes and empty cells in DingTalk Markdown tables. | [#6741](https://github.com/bytedance/deer-flow/pull/6741) | 2026-10-12 |
| bytedance/deer-flow | Bound skill-directory file reads before inspection to limit scanner memory use. | [#6359](https://github.com/bytedance/deer-flow/pull/6359) | 2026-10-06 |
| vercel/ai | Correct Telnyx transcription and speech examples to use the SDK's stable export names. | [#21996](https://github.com/vercel/ai/pull/21996) | 2026-10-06 |
| assistant-ui/assistant-ui | Repair the TAP example's client implementation link after its source directory moved. | [#8745](https://github.com/assistant-ui/assistant-ui/pull/8745) | 2026-10-06 |
| bytedance/deer-flow | Normalize local HTTP host classification, including case, IPv6 and userinfo. | [#6280](https://github.com/bytedance/deer-flow/pull/6280) | 2026-10-05 |
| bytedance/deer-flow | Detect download-to-shell pipe variants and real LF/CRLF continuations; remove exponential regex backtracking. | [#6312](https://github.com/bytedance/deer-flow/pull/6312) | 2026-10-05 |

## 🤝 Contributions Integrated Upstream

| Project | My contribution | Integration evidence | Original PR | Date (Asia/Shanghai) |
|---|---|---|---|---|
| langflow-ai/langflow | Pin Playwright runner defaults to Ubuntu 24.04 across frontend CI and restore browser installation for related jobs. | [Merged #16064](https://github.com/langflow-ai/langflow/pull/16064) · [Co-authored commit](https://github.com/langflow-ai/langflow/commit/d336c4fff5c1ea19bab95dd0df112aec9cf53ace) | [#16105](https://github.com/langflow-ai/langflow/pull/16105) | 2026-11-03 |

## 🧪 Bug Reports & Reproductions

| Project | My contribution | Outcome | Evidence |
|---|---|---|---|
| pydantic/pydantic-ai | Reported an unresolvable RealtimeEvent public export and submitted a tested lazy-import fix. The maintainer credited the report and removed the invalid export in a separate PR. | A credited bug report, not a merged PR of mine. | [Issue #10119](https://github.com/pydantic/pydantic-ai/issues/10119) · [My PR #10120](https://github.com/pydantic/pydantic-ai/pull/10120) · [Upstream fix #10189](https://github.com/pydantic/pydantic-ai/pull/10189) |
| mastra-ai/mastra | Published a runnable reproduction of cancelled fetches retrying through backoff. | Upstream fix merged. | [Issue #25889](https://github.com/mastra-ai/mastra/issues/25889) · [Upstream fix #26164](https://github.com/mastra-ai/mastra/pull/26164) · [Reproduction](https://github.com/abandonedempl/agent-reliability-repros) |
| bytedance/deer-flow | Reported unbounded skill-directory file reads, then submitted the bounded-read fix. | Fixed by my merged PR #6359, not an additional merged PR. | [Issue #6358](https://github.com/bytedance/deer-flow/issues/6358) · [PR #6359](https://github.com/bytedance/deer-flow/pull/6359) |
| bytedance/deer-flow | Reported reproducible Windows MAX_PATH failures in document staging and router tests. | Upstream fix merged; implemented by GodBlf. | [Issue #6460](https://github.com/bytedance/deer-flow/issues/6460) · [Upstream fix #6467](https://github.com/bytedance/deer-flow/pull/6467) |

Merged [deer-flow PR #6829](https://github.com/bytedance/deer-flow/pull/6829) was selected for the XERJ Corpus Hub as a reference example.


## 🛠️ Tech Stack

**Agents & evaluation:** Agent runtime and harness, MCP and tool calling, context budgeting, structured memory, trace-based evaluation and authorization checks.

**Engineering:**

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white" alt="Hono" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

---

<p align="center">
  吴官炫 · Hangzhou · <a href="mailto:felix815811045@outlook.com">felix815811045@outlook.com</a> · <a href="https://abandonedempl.github.io">abandonedempl.github.io</a>
</p>
