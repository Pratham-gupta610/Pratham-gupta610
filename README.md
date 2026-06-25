<div align="center">

<!-- HERO -->
<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0D0D14,40:1E0A3C,100:4C1D95&height=300&section=header&text=PRATHAM%20GUPTA&fontSize=62&fontColor=A78BFA&animation=fadeIn&fontAlignY=38&desc=Systems%20programmer.%20Kernel%20tinkerer.%20Rust%20enthusiast.&descAlignY=58&descSize=18&descColor=6D6D8A&descAlign=50" />

<br/>

<!-- TYPING SVG -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3000&pause=1200&color=7C3AED&center=true&vCenter=true&width=700&lines=Writing+eBPF+programs+in+Rust+with+Aya;XDP+packet+processing+%40+wire+speed;1BRC+%E2%80%94+1+billion+rows%2C+3.2+seconds;Lock-free+data+structures+%7C+SIMD+%7C+mmap;The+kernel+is+just+code+you+haven't+read+yet" />

</div>

---

```
$ uname -a && whoami --verbose
Linux systems 6.x #1 SMP PREEMPT Rust — not garbage collected
pratham :: CS undergrad | systems programmer | kernel curious
```

I write software where performance isn't a feature — it's the contract. Currently deep in **eBPF/XDP** territory, building network observability tooling from the kernel up. I care about what happens below the abstraction layer.

<div align="center">

| 🦀 Low-level Systems | ⚡ eBPF / XDP | 🔒 Lock-free Data Structures |
|:---:|:---:|:---:|
| ![](https://img.shields.io/badge/-Rust-7C3AED?style=flat-square&logo=rust&logoColor=white) | ![](https://img.shields.io/badge/-eBPF-9333EA?style=flat-square&logoColor=white) | ![](https://img.shields.io/badge/-Atomics-C026D3?style=flat-square&logoColor=white) |
| **🚀 SIMD & Performance** | **🌐 Backend Architecture** | **☁️ Cloud Infrastructure** |
| ![](https://img.shields.io/badge/-AVX2-7C3AED?style=flat-square&logoColor=white) | ![](https://img.shields.io/badge/-Distributed_Systems-9333EA?style=flat-square&logoColor=white) | ![](https://img.shields.io/badge/-Cloud_Native-C026D3?style=flat-square&logoColor=white) |

</div>

---

## 🔭 Currently Building

<table>
<tr>
<td width="12px"><img src="https://img.shields.io/badge/●-10B981?style=flat-square" /></td>
<td><strong>eBPF Network Telemetry Engine</strong> &nbsp;<code>in progress</code></td>
</tr>
</table>

> A production-grade **eBPF packet analyzer** built in Rust using **Aya** and **Tokio** — attaching XDP programs at the NIC driver level for zero-copy packet inspection, per-flow telemetry, and anomaly detection. This is not a toy.

```
Architecture
├── XDP layer        — kernel-side eBPF programs (Aya)  
├── Perf event ring  — kernel→userspace data pipeline  
├── Async runtime    — Tokio-based userspace processing  
├── Flow tracking    — per-connection state machine  
├── Anomaly engine   — [WIP] statistical detection  
└── Observability    — [WIP] metrics export + tracing
```

**Stack:** `Rust` · `Aya` · `Tokio` · `XDP` · `eBPF` · `Linux kernel`

---

## 🚀 Projects

| Project | What it does | Stack |
|---|---|---|
| **1BRC in Rust** | 1 billion rows parsed in **3.2s** — `mmap` + AVX2 SIMD + branchless parsing + custom open-addressed hash table | `Rust` `AVX2` `SIMD` |
| **Hosptell** <br/><sub>(group project)</sub> | Real-time emergency hospital dispatch and coordination system | `Node.js` `MongoDB` |
| **Notes CLI** | Terminal-based notes manager with ANSI UI, hierarchical menu system, and custom storage format | `Rust` |
| **Bankist Website** | Interactive banking UI with animations, lazy loading, and DOM manipulation | `JavaScript` `HTML` `CSS` |
| **URL Shortener** | URL shortening service with redirect handling and link management | `Node.js` `Express` |

---

## ⚙️ Stack

**Low-level & Systems**

![Rust](https://img.shields.io/badge/Rust-0D0D14?style=for-the-badge&logo=rust&logoColor=A78BFA)
![C](https://img.shields.io/badge/C-0D0D14?style=for-the-badge&logo=c&logoColor=A78BFA)
![C++](https://img.shields.io/badge/C++-0D0D14?style=for-the-badge&logo=cplusplus&logoColor=A78BFA)
![eBPF](https://img.shields.io/badge/eBPF-0D0D14?style=for-the-badge&logoColor=A78BFA)
![Linux](https://img.shields.io/badge/Linux-0D0D14?style=for-the-badge&logo=linux&logoColor=A78BFA)
![Bash](https://img.shields.io/badge/Bash-0D0D14?style=for-the-badge&logo=gnubash&logoColor=A78BFA)

**Backend & Infra**

![JavaScript](https://img.shields.io/badge/JavaScript-0D0D14?style=for-the-badge&logo=javascript&logoColor=A78BFA)
![Express](https://img.shields.io/badge/Express-0D0D14?style=for-the-badge&logo=express&logoColor=A78BFA)
![Node.js](https://img.shields.io/badge/Node.js-0D0D14?style=for-the-badge&logo=node.js&logoColor=A78BFA)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D0D14?style=for-the-badge&logo=postgresql&logoColor=A78BFA)
![MongoDB](https://img.shields.io/badge/MongoDB-0D0D14?style=for-the-badge&logo=mongodb&logoColor=A78BFA)
![Redis](https://img.shields.io/badge/Redis-0D0D14?style=for-the-badge&logo=redis&logoColor=A78BFA)
![Docker](https://img.shields.io/badge/Docker-0D0D14?style=for-the-badge&logo=docker&logoColor=A78BFA)
![AWS](https://img.shields.io/badge/AWS-0D0D14?style=for-the-badge&logo=amazonaws&logoColor=A78BFA)

---

## 📊 Most Used Languages

<div align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Pratham-gupta610&layout=compact&hide_border=true&bg_color=0D0D14&title_color=A78BFA&text_color=E2E8F0&langs_count=8&cache_seconds=300" />
</div>

---

## 📈 Activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Pratham-gupta610&theme=tokyo-night&hide_border=true&bg_color=0D0D14&color=A78BFA&line=7C3AED&point=10B981" />
</div>

---

## 🌐 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D0D14?style=for-the-badge&logo=linkedin&logoColor=A78BFA)](https://www.linkedin.com/in/pratham-gupta-430315368)
[![GitHub](https://img.shields.io/badge/GitHub-0D0D14?style=for-the-badge&logo=github&logoColor=A78BFA)](https://github.com/Pratham-gupta610)

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4C1D95,100:0D0D14&height=100&section=footer&reversal=true" />
</div>
