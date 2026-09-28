<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=2800&pause=900&color=7AA2F7&center=true&vCenter=true&width=700&lines=Raj+Rathod;Software+Developer;Building+a+matching+engine+in+C%2B%2B;Writing+a+type+inferencer+in+Python;Distributed+systems+%26+correctness" alt="Raj Rathod" />

<br />

<a href="https://linkedin.com/in/raj-rathod1"><img src="https://img.shields.io/badge/LinkedIn-7AA2F7?style=for-the-badge&logo=linkedin&logoColor=1A1B27" alt="LinkedIn" /></a>
<a href="https://leetcode.com/u/popple_1"><img src="https://img.shields.io/badge/LeetCode-F0B45C?style=for-the-badge&logo=leetcode&logoColor=1A1B27" alt="LeetCode" /></a>
<a href="https://github.com/rajrathod-1/portfolio"><img src="https://img.shields.io/badge/Portfolio-BB9AF7?style=for-the-badge&logo=react&logoColor=1A1B27" alt="Portfolio" /></a>
<a href="mailto:rajrathod23232@gmail.com"><img src="https://img.shields.io/badge/Email-9ECE6A?style=for-the-badge&logo=gmail&logoColor=1A1B27" alt="Email" /></a>

</div>

---

```console
raj@portfolio:~$ whoami
```

Computer science at the **University of Manitoba** (co-op, graduating 2026).
Most recently a software developer intern at **Citigroup**; before that
**Ericsson** and **Proofpoint**.

I care about programming languages and type systems, testing and correctness,
and distributed systems. I like finding out *why* something is slow before
making it faster.

<br />

<div align="center">

### Tools

<img src="https://skillicons.dev/icons?i=python,cpp,java,ts,react,flask,spring,postgres&theme=dark" alt="Languages and frameworks" />
<br />
<img src="https://skillicons.dev/icons?i=linux,git,docker,kubernetes,aws,kafka,elasticsearch,redis&theme=dark" alt="Infrastructure" />

</div>

<br />

---

```console
raj@portfolio:~$ cat now.txt
```

### Limit order book and matching engine · `C++` `Python`

A price-time priority engine supporting limit, market and cancel orders, with
sorted price levels and an order-id index so cancels don't scan the book.

I test it by replaying randomly generated order streams against a deliberately
simple Python reference implementation and diffing every fill. That caught the
partial-fill and cancel edge cases my hand-written unit tests missed.

### Interpreter for a small functional language · `Python`

A parser and evaluator for a language with closures, algebraic data types and
pattern matching. Adding Hindley-Milner type inference so ill-typed programs
are rejected before they run, with errors that point at the offending
expression.

<br />

---

```console
raj@portfolio:~$ ls experience/
```

<table>
<tr>
<td width="33%" valign="top">

**Citigroup**<br />
<sub>Software Developer Intern · May – Sep 2026</sub>

Full-stack user management platform in React and TypeScript over Spring Boot
APIs. Reshaped the API around how the data grid actually paged — **40%** lower
retrieval latency. Event-driven services in Java 21 with Kafka and Oracle DB,
plus Elasticsearch search over **500K+** records.

</td>
<td width="33%" valign="top">

**Ericsson**<br />
<sub>Software Developer Intern · Jan – Apr 2026</sub>

Backend services in Java and Python on multi-cluster Kubernetes, **25%** better
uptime by isolating faults in code I inherited rather than wrote. Added
monitoring to services that had none, so the team heard about failures before
users did.

</td>
<td width="33%" valign="top">

**Proofpoint**<br />
<sub>Software Developer Intern · Oct 2024 – Dec 2025</sub>

Python and Flask services on MySQL handling **10,000+** daily requests at
**99.9%** uptime, with circuit breakers and retries so downstream failures
degraded gracefully. Automated operations workflows on AWS.

</td>
</tr>
</table>

<br />

---

```console
raj@portfolio:~$ ls projects/
```

- **[Retrieval-augmented question answering](https://github.com/rajrathod-1/AI-Content-Generation)** · `Python` `Flask` `FAISS` `Redis`<br />
  <sub>Timed every stage before optimising and found retrieval, not the model call, was the bottleneck. p95 under 200ms after caching.</sub>
- **TCP proxy server** · `C++` `POSIX sockets`<br />
  <sub>Multithreaded Layer 4 proxy with event-driven I/O, routing and load balancing, plus per-connection telemetry to see where throughput dropped.</sub>
- **[Interactive portfolio](https://github.com/rajrathod-1/portfolio)** · `React` `TypeScript` `Tailwind`<br />
  <sub>A terminal you can actually type in — <code>ls</code>, <code>cd</code>, <code>cat</code> and tab completion all work.</sub>

<br />

---

<div align="center">

```console
raj@portfolio:~$ git log --stat
```

<img height="165" src="https://github-readme-stats.vercel.app/api?username=rajrathod-1&show_icons=true&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=7AA2F7&icon_color=F0B45C&text_color=A9B1D6&include_all_commits=true&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rajrathod-1&layout=compact&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=7AA2F7&text_color=A9B1D6&langs_count=8" alt="Top languages" />

<br /><br />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=rajrathod-1&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=7AA2F7&line=BB9AF7&point=F0B45C&area=true" alt="Contribution activity" width="98%" />

<br /><br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rajrathod-1/rajrathod-1/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rajrathod-1/rajrathod-1/output/snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/rajrathod-1/rajrathod-1/output/snake.svg" width="98%" />
</picture>

<br /><br />

<sub>Winnipeg, MB · open to new grad software roles</sub>

</div>
