# Learning log

Structured courses I am working through on Udemy, what they cover, and where the skills show up in
the things I build. These are in progress — no certificates claimed here.

| Course | Instructor | Focus | Started | Status |
|---|---|---|---|---|
| [The Complete Full-Stack Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/) | Dr. Angela Yu | HTML, CSS, JavaScript, React, Node, PostgreSQL, Web3 / DApps | Aug 2026 | In progress |
| [Java Masterclass 2025: 130+ Hours of Expert Lessons](https://www.udemy.com/course/java-the-complete-java-developer-course/) | Tim Buchalka | Core Java, OOP, collections, generics, streams, concurrency, Java 17 | Jul 2026 | In progress |
| [100 Days of Code: The Complete Python Pro Bootcamp](https://www.udemy.com/course/100-days-of-code/) | Dr. Angela Yu | Python, automation, Flask, APIs, pandas/NumPy, Selenium, BeautifulSoup, GUIs | Sep 2026 | In progress |
| [Mastering Linux: The Comprehensive Guide](https://www.udemy.com/course/mastering-linux/) | Jannis Seemann, Denis Panjuta | CLI, filesystem and permissions, processes, packages, Bash scripting, networking | Sep 2026 | In progress |
| [Ethical Hacking & Penetration Testing from Scratch](https://www.udemy.com/course/yousdnzk/) (Arabic) | Ahmed zoala | Recon, network attacks (MITM, DNS spoofing), packet capture, Metasploit, social engineering fundamentals | Sep 2026 | In progress |

## What I have covered so far

- **Full-stack** — semantic HTML, CSS layout, JavaScript fundamentals and the DOM, the request/response
  model, React components and state, Node/Express APIs, and relational data modelling with PostgreSQL.
- **Java** — the JVM toolchain, types and control flow, classes and inheritance, interfaces,
  collections, generics, lambdas and streams, exception handling, file I/O and concurrency basics.
- **Python** — data types and control flow, functions, OOP, file and error handling, modules, working
  with APIs and JSON, web scraping, automation scripts, Flask basics, and pandas/NumPy fundamentals.
- **Linux** — the command line, the filesystem, users and permissions, processes and signals, package
  management, SSH, system services, and Bash scripting for automation.
- **Security** — reconnaissance and scanning, how networks and IPs/ports work, packet capture and
  spoofing, man-in-the-middle and DNS attacks, payload and tooling fundamentals, and the attacker
  mindset used defensively (secrets hygiene, least privilege).

## Where it shows up

| Skill | In practice |
|---|---|
| JavaScript / DOM / canvas | [Pulse Desk](https://github.com/Soophere/pulse-desk-ui) — the dashboard UI, charts and page renderers |
| Python | The desk engine and automation behind Pulse Desk; [The City](https://github.com/Soophere/the-city) census and tooling |
| Linux / shell | Running a Proxmox home lab, containers, `scp`/`ssh` deploys and cron-style timers |
| Java | Coursework and small practice projects |
| Security | Keeping keys out of public repos, least-privilege deployments, verifying what is downloaded |

## How I study

- Hands-on only: every module ends in something that runs.
- Notes and decisions go into a personal memory bank so they survive between sessions.
- When a course topic overlaps a real project, the project gets the first version — that is how the
  dashboard, the census tooling and the Linux server work were built.
