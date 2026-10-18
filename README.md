<div align="center">
  <img src="./banner.svg" alt="Sulaiman Nasser — AI systems, developer tools, operator dashboards" width="100%" />
</div>

<br />

**I build operator-grade software and use coding agents as a real engineering tool — with harnesses,
captured payloads and verification, not vibes.**

Based in Muscat, Oman. I like problems where the numbers have to be honest: dashboards that operate
live money, fleets of AI models that may or may not actually answer, memory that survives the next
chat window.

## Selected work

<table>
<tr>
<td width="50%" valign="top">
<h3>Pulse Desk</h3>
<p><b>Operator dashboard for an automated crypto trading desk.</b> Thirteen pages, per-method
controls, an AI council, wallet tracking and an honest history — with paper and live money kept
strictly apart.</p>
<p>Vanilla HTML/CSS/JS and canvas. No framework, no build step. A Node harness renders every page
against captured live API payloads, and the UI swaps over SSH without restarting the trading
process.</p>
<p><a href="https://soophere.github.io/pulse-desk-ui/"><b>▶ Live interactive demo</b></a> ·
<a href="https://github.com/Soophere/pulse-desk-ui">repo</a> · MIT</p>
</td>
<td width="50%" valign="top">
<h3>The City</h3>
<p><b>A free-only fleet of AI workers, routed by job instead of by model.</b> Probed all 82 free
models the account listed, kept the 17 that actually answered, and routed jobs across
latency-measured pools with per-worker patience, retries, cooldowns and fallbacks.</p>
<p>Mixture-of-agents chat on top, build log included: what broke, what the catalog was lying about,
and why per-worker timeouts beat one global number.</p>
<p><a href="https://github.com/Soophere/the-city"><b>repo</b></a> · MIT</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>agent-memory</h3>
<p><b>Persistent memory for AI coding agents.</b> A plain-markdown bank plus a zero-dependency
Node CLI: it loads your profile, project notes, decisions and recent sessions before the first
reply, and saves what matters as one-line facts during work.</p>
<p>Built for DeepSeek Harness, used daily across 40+ sessions in 21 folders — because losing
context should be an engineering problem, not a personality trait.</p>
<p><a href="https://github.com/Soophere/agent-memory"><b>repo</b></a> · MIT</p>
</td>
<td width="50%" valign="top">
<h3>CS2 skin sniper</h3>
<p><b>Local dashboard + Discord alerter that hunts under-market Counter-Strike 2 items across eight
markets.</b> A multi-market price book, rate-limit-safe polling, anti-fake-profit guards,
urgency-tiered alerts and rejection telemetry.</p>
<p>FastAPI + asyncio behind a custom dashboard; no auto-buy — it surfaces the edge and links the buy,
the operator decides. The guard rules are documented in the README.</p>
<p><a href="https://github.com/Soophere/cs2-sniper"><b>repo</b></a> · MIT</p>
</td>
</tr>
</table>

## Track record

**Jul → Sep 2026:** from course basics to a live multi-engine trading desk, a public market
scanner, and my own AI tooling — built in long AI-assisted sessions and verified on running
systems, not notebooks.

- **Pulse Desk — engine and safety layer.** The public UI is the face; behind it I built and
  operated the desk itself: Core / Wish / Moonshot / On-chain Alpha engines with paper and live
  paths kept strictly separate, one-live-engine-per-coin-class locks, on-chain safety guards
  (honeypot probe, token-account rent reclaim, gas guard, rug filters), an AI council with a
  throttle and budget, a position ledger reconciled against the chain, and fill-vs-quote accounting.
  Each change was verified against live data before it shipped.
- **AI infrastructure.** Before DeepSeek Harness I ran my own AI stack: a fleet of free model
  workers ([The City](https://github.com/Soophere/the-city)), an OpenAI-compatible router, MCP
  servers, and agent skills that later became [agent-memory](https://github.com/Soophere/agent-memory).
- **AI-assisted engineering, measured.** 21 AI-attributed commits in a ten-week stretch
  (+41,861 / −902 lines, 186 files) across the desk and the sniper. Attribution comes from the IDE's
  code-tracking database, and every commit was reviewed and tested against a running system — the
  harness is what makes it my code.

## Toolbox

![Python](https://img.shields.io/badge/Python-1f2630?style=flat-square&logo=python&logoColor=7aa7ff)
![TypeScript](https://img.shields.io/badge/TypeScript-1f2630?style=flat-square&logo=typescript&logoColor=7aa7ff)
![Node.js](https://img.shields.io/badge/Node.js-1f2630?style=flat-square&logo=nodedotjs&logoColor=7aa7ff)
![Bun](https://img.shields.io/badge/Bun-1f2630?style=flat-square&logo=bun&logoColor=7aa7ff)
![Docker](https://img.shields.io/badge/Docker-1f2630?style=flat-square&logo=docker&logoColor=7aa7ff)
![Linux](https://img.shields.io/badge/Linux-1f2630?style=flat-square&logo=linux&logoColor=7aa7ff)
![Proxmox](https://img.shields.io/badge/Proxmox-1f2630?style=flat-square&logo=proxmox&logoColor=7aa7ff)
![Git](https://img.shields.io/badge/Git-1f2630?style=flat-square&logo=git&logoColor=7aa7ff)

Also: vanilla DOM and canvas (no chart libraries), LiteLLM / OpenAI-compatible routing, DSH plugins and
skills, static deployment over SSH, Windows native builds with clang-cl.

## How I work

1. **Measure before believing.** Model rosters come from probes; UI numbers come from captured
   payloads; "it works" means a harness says so.
2. **Make failure visible.** An offline dashboard must say it is offline. A silent model must be
   recorded as silent, not as a success.
3. **Keep the tooling boring.** Markdown over databases. Static files over build pipelines. One
   shell and two modules over a framework migration.
4. **Let agents do the typing, keep the verification.** AI writes code fast; the harness is what
   makes it my code.

## Learning (Udemy)

Structured learning alongside building. Currently working through:

- **The Complete Full-Stack Web Development Bootcamp** (Dr. Angela Yu) — HTML/CSS/JavaScript, React,
  Node, PostgreSQL, Web3 / DApps.
- **Java Masterclass 2025** (Tim Buchalka) — core Java, OOP, collections, generics, streams,
  concurrency, Java 17.
- **100 Days of Code: The Complete Python Pro Bootcamp** (Dr. Angela Yu) — Python, automation,
  Flask, APIs, pandas/NumPy, Selenium/BeautifulSoup, GUIs.
- **Mastering Linux: The Comprehensive Guide** (Jannis Seemann, Denis Panjuta) — CLI, filesystem
  and permissions, processes, packages, Bash scripting, networking.
- **Ethical Hacking & Penetration Testing from Scratch** (Ahmed zoala, Arabic) — reconnaissance,
  MITM/DNS spoofing, packet capture, Metasploit fundamentals.

All in progress. What each covers, and where the skills show up in my projects:
[LEARNING.md](LEARNING.md).

## Current focus

- Pulse Desk: the operator dashboard above, in daily use on my home lab.
- Expanding The City with a dispatcher that hedges slow workers and verifies answers across models.
- Open to **software engineering / AI engineering** roles — the easiest way to reach me is here on
  GitHub.

<br />

<div align="center">
  <sub>Built with <a href="https://github.com/deepseek-ai/deepseek-harness">DeepSeek Harness</a> as the coding agent — verified end to end.</sub>
</div>
