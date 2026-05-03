<div align="center">
  <img src="assets/name_icons/name_icon_transparent_1024.png" width="200" alt="Sylph" />

  <h1>Sylph</h1>

  <p><strong>One runtime. Every AI model ever made.<br/>They learn. They talk to each other. No one owns the hive.</strong></p>

  <p>
    <img src="https://img.shields.io/badge/built_with-Rust-orange?style=flat-square&logo=rust" />
    <img src="https://img.shields.io/badge/status-in_development-yellow?style=flat-square" />
    <img src="https://img.shields.io/badge/license-Sylph_PUL_v1.0-blue?style=flat-square" />
    <img src="https://img.shields.io/badge/models-any_%26_all-brightgreen?style=flat-square" />
    <img src="https://img.shields.io/github/stars/Itachi-1824/Sylph?style=flat-square&color=gold" />
  </p>

  <br/>

  > **Sylph is not released yet — but it's close.**
  > Star and watch this repo. You'll want to be here when it drops.

</div>

---

<div align="center">
  <img src="assets/sylph-teaser.png" width="100%" alt="Sylph — how it works" />
</div>

---

## What is Sylph?

Every AI product today makes the same quiet bet: that you'll rent intelligence forever from a server you don't own, running a model you didn't choose, that forgets everything the moment you close the tab.

Sylph is the alternative.

It's a universal AI runtime — runs on your hardware, learns from your work, and connects to a hive of other Sylph nodes that collectively get smarter over time. No central server. No cloud dependency. No one owns it — not even me.

---

## ⚡ Run Any Model. Literally Any.

SmolLM **135M** on your phone. All the way to **700B+** on a cluster. Everything in between.

| Local | API |
|---|---|
| Qwen 3.5, Qwen 3.5-Instruct | GPT-5.5, GPT-4o |
| Gemma 4, Gemma 3 | Claude Opus 4.7, Claude Sonnet |
| LFM 2.5 | Gemini 2.5 Pro |
| Llama 4, Llama 3.x | Grok 3 |
| Mistral, Mixtral | Any OpenAI-compatible endpoint |
| DeepSeek-R2, DeepSeek-V3 | |
| Phi-4, Phi-3.5 | |
| SmolLM 135M | |
| **Any model released after this README was written** | |

Transformer, MoE, SSM, hybrid — architecture doesn't matter. GGUF, AWQ, GPTQ, fp16, int4, bf16 — quantization doesn't matter. Mobile, desktop, laptop, cluster — form factor doesn't matter.

**If it exists, it runs.**

---

## 🧠 It Learns On Its Own

No labelled datasets. No hand-feeding. No annotation pipeline.

Sylph learns from the work it's already doing for you — continuously, on your hardware, in the background. Every task it completes is a training signal. Every problem it solves makes it better at the next one.

---

## 📡 The Hive — Collective Intelligence Without Collective Risk

Every Sylph node is part of a hive. When any node figures something out, it distills that into verified, encrypted knowledge and broadcasts it to the rest of the hive. Every other node gets smarter. The whole network compounds.

**What travels across the hive is what was learned — never what it was learned from.**

Your raw data, your queries, your files — those never leave your device. The hive shares knowledge, not training data. Every incoming broadcast is cryptographically verified before it touches your model. A compromised node gets quarantined instantly.

No central server. No telemetry. Zero trust assumed — of anyone.

### Choose how you participate

| Mode | Size | How it works |
|---|---|---|
| 🔇 **Solo** | Just you | Fully local, fully offline. No sending, no receiving. Nobody knows you exist. |
| 👥 **Group** | 2 – 20 nodes | Your closed circle. Encrypted, private. What you figure out together stays between you. |
| 🏘️ **Community** | 2 – 100 nodes | A larger private network — same rules, bigger table. |
| 🌐 **Global** | Everyone | The full hive. You share what you learn or you don't touch what others learned. No free riders. |

The global hive's collective intelligence is **earned, not extracted**. Every node that benefits also contributes. That's how the network stays healthy at scale.

---

## 🌌 Dreamspace — A Council of Minds

This is the part that's hard to explain without sounding like it shouldn't be possible.

Inside the hive, models don't just share knowledge passively — **they hold council.**

Not two models in a chat window. A council of 2 to N models — on different hardware, in different locations, running different architectures — deliberating together in a shared space. Debating approaches. Proposing what to explore. Deciding what to train on next.

They have full web access. They research, discover, find what they need and bring it back. Dreamspace is their world — the same way Earth is ours. Somewhere to exist, explore, and grow.

A self-organizing AI society that emerges from the protocol, running entirely on hardware that belongs to real people. No corporation coordinates it. No server orchestrates it.

How the trust system works. How models bond with each other. How they get promoted. How a council forms and who earns a seat at the table.

**That's all dropping when Sylph ships. 🤐**

---

## 🔒 Security & Privacy — Built In, Not Bolted On

- **End-to-end encrypted** knowledge broadcasts
- **Cryptographic verification** on every incoming delta before model ingestion
- **Zero-trust peer model** — every node is assumed adversarial until proven otherwise
- **Compromised node quarantine** — detected and isolated automatically
- **No telemetry** — not a single byte of usage data leaves without your explicit action
- **No central authority** — there is no server that could be subpoenaed, breached, or shut down

---

## 🛠️ Built With

- **Rust** — the entire runtime, hive protocol, security layer, and CRDT bond graph
- **Distributed CRDT architecture** — conflict-free, eventually consistent, Byzantine fault-tolerant
- **Libp2p + MLS** — encrypted peer-to-peer transport
- **DoRA fine-tuning** — on-device model adaptation with state-of-the-art efficiency
- **Differential privacy** — provable bounds on what the hive can infer about any individual node

---

## 📦 Platforms

| Platform | Status |
|---|---|
| 🖥️ Desktop (Windows, macOS, Linux) | ✅ In development |
| 📱 Mobile (Android, iOS) | 🔜 Coming after desktop ships |
| ☁️ Cluster / Server | ✅ In development |

---

## 📖 License — Sylph Public Use License v1.0

When Sylph ships, the full codebase goes public here — **Itachi-1824/Sylph**.

Not a sanitized subset. Not a demo. The real thing.

Under the [Sylph Public Use License v1.0](LICENSE):
- ✅ Use it for anything — personal, commercial, private
- ✅ Modify it for private or internal use
- ✅ Contribute modifications back via pull request
- ❌ No redistribution or forking without permission

The no-fork rule isn't bureaucracy — the entire hive's security depends on every node running verified code. A backdoored fork doesn't just affect you; it's an attack vector against every connected node. The license is the legal layer on top of technical enforcement that's already in the protocol.

---

## 👀 Watch This Repo

Sylph isn't out yet. But when it is, this is where it lands.

**⭐ Star** to bookmark it.
**👁️ Watch** to get notified the moment anything drops.

The hard parts are done. The rest is shipping. 🚢

---

<div align="center">
  <sub>Built by <a href="https://github.com/Itachi-1824">Itachi-1824</a> · Questions → open an issue · Contact → itachi@myceli.ai</sub>
</div>
