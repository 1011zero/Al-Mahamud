<h1 align="center">Al Mahamud</h1>

<p align="center">
  Graduate Engineer at <b>Kona SL</b> &nbsp;·&nbsp; Competitive Programmer &nbsp;·&nbsp; CSE, KUET '25
</p>

<p align="center">
  <a href="https://codeforces.com/profile/1011zero"><img src="https://img.shields.io/badge/Codeforces-Specialist%20(1577)-1F8ACB?style=flat&logo=codeforces&logoColor=white" alt="Codeforces Specialist" /></a>
  <a href="https://www.codechef.com/users/one0110"><img src="https://img.shields.io/badge/CodeChef-4%E2%98%85%20(1903)-5B4638?style=flat&logo=codechef&logoColor=white" alt="CodeChef 4 star" /></a>
  <img src="https://img.shields.io/badge/ICPC%20Dhaka%20Regional%202024-45th-C1272D?style=flat" alt="ICPC Dhaka Regional 2024, 45th" />
  <img src="https://komarev.com/ghpvc/?username=al-mahamud&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>

---

I write backend software in Dhaka. Day to day that means **enterprise fintech systems** at Kona SL — Java, Spring Boot, MyBatis and Oracle on the server, Next.js on the front — and building production AI-powered tooling with the AI Engineering team.

Before that I spent five years doing competitive programming, which is still how I think about problems: find the constraint, prove the bound, then write the smallest thing that satisfies it. **1700+ problems solved** across online judges and **200+ contests**, online and onsite.

- 🔭 Currently building **distributed-systems-flavoured backends** — caching, queues, and the kind of database work that only shows up under load
- 🌱 Learning **machine learning, computer networks, and network security**
- 💬 Ask me about **algorithms, contest problems, or anything backend**
- 📫 Reach me at **almahamud207@gmail.com**

---

### 🚀 Featured project

**[url-shortener](https://github.com/Al-Mahamud/url-shortener)** — a URL shortener built against three hard constraints instead of a feature list: *reads must be served from cache, codes must never collide under concurrent writes, and analytics must never slow the redirect.*

<table>
  <tr><th align="left">Measurement</th><th align="left">Before</th><th align="left">After</th></tr>
  <tr><td>p99 redirect latency</td><td>324.4 ms</td><td><b>51.0 ms</b></td></tr>
  <tr><td>Throughput</td><td>513 req/s</td><td><b>2,421 req/s</b></td></tr>
  <tr><td>DB reads on the redirect path</td><td>16,074 of 16,074</td><td><b>1 of 50,264</b></td></tr>
  <tr><td>Synchronous writes on the hot path</td><td>16,074</td><td><b>0</b></td></tr>
  <tr><td>Enumeration flood reaching the DB</td><td>100%</td><td><b>0%</b></td></tr>
  <tr><td>Stats query cost</td><td>3,220 consistent gets</td><td><b>3</b></td></tr>
</table>

Cache-aside over Redis with negative caching and single-flight stampede protection; a Bloom filter that answers *"definitely absent"* with no network call; collision-free codes from a modular multiplicative bijection over an Oracle sequence — no retry loop, no uniqueness check; and click analytics that leave the request thread via a bounded queue into a Redis Stream. Every number above is measured, not asserted.

`Java` `Spring Boot` `MyBatis` `Oracle` `Redis` `Docker` `Flyway` `k6`

---

### 🛠️ Tech I work with

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat&logo=databricks&logoColor=white)

**Backend & frameworks**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-C74634?style=flat&logo=apachemaven&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)

**Data & infrastructure**

![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

### 💼 Experience

**Graduate Engineer** — Kona SL, Dhaka · *Sep 2025 – Present*
Enterprise-grade fintech solutions in Next.js, Java, Spring Boot, MyBatis and Oracle. Building production AI-powered software with the AI Engineering team.

**R&D Engineer (Trainee)** — BDCOM, Dhaka · *Jun 2025 – Sep 2025*
C/C++ software development and networking R&D; analysed, implemented and tested components alongside senior engineers.

---

### 🏆 Competitive programming

| | |
|---|---|
| **Codeforces** | [1011zero](https://codeforces.com/profile/1011zero) — Specialist, max rating **1577** |
| **CodeChef** | [one0110](https://www.codechef.com/users/one0110) — 4★, max rating **1903** |
| **ICPC Asia Dhaka Regional 2024** | Ranked **45th** *(Team: KUET_Helicopter)* |
| **Khulna Regional IUPC 2024** | Ranked **24th** *(Team: KUET_Helicopter)* |
| **IUT ICT Fest 2024** | Ranked **66th** *(Team: KUET_Helicopter)* |
| **Intra KUET Programming Contest 2023** | Ranked **7th** *(Team: KUET_Bicycle)* |

Over **1700 problems** solved and **200+ contests** entered.

---

### 🎓 Education & community

**B.Sc. in Computer Science and Engineering** — Khulna University of Engineering & Technology (KUET), Jan 2020 – Aug 2025 · CGPA **3.56 / 4.00** · Dean's List, 2019–2020.

Outside coursework I mentor junior contestants at **SGIPC, KUET** (2022 – present), served as **Head of Management** for the IUPC at BitFest 2025 — directing 20 core members and 100+ volunteers — and was **Assistant General Secretary** of the CSE Association.

---

### 📫 Connect

<p align="left">
  <a href="mailto:almahamud207@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://codeforces.com/profile/1011zero"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" /></a>
  <a href="https://www.codechef.com/users/one0110"><img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef" /></a>
  <a href="https://www.leetcode.com/1011zero"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
</p>

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=al-mahamud&theme=github_dark" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=al-mahamud&theme=github" alt="GitHub profile summary" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=al-mahamud&hide_border=true&theme=dark" />
    <img src="https://streak-stats.demolab.com/?user=al-mahamud&hide_border=true" alt="GitHub streak" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=al-mahamud&theme=github_dark" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=al-mahamud&theme=github" alt="Most used languages" />
  </picture>
</p>
