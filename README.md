# Dhyey Daftary

<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&pause=1000&color=F59E0B&center=true&vCenter=true&width=600&lines=Full-stack+engineer%2C+exploring+AI%2FML;Building+explainable+ML+%26+backend+systems;Currently%3A+RSNA+Knee+MRI+Challenge+on+Kaggle;Occasionally+solving+problems+on+LeetCode)

</div>

---

### ~/ whoami

> Early-career engineer, still figuring out where full-stack ends and AI
> begins. Based in Ahmedabad, India. I write code that mostly works, and
> bugs that look intentional.

---

### ~/ currently building

**RSNA Knee Abnormality Detection** — Kaggle competition, predicting 12
clinically important knee abnormality findings from multimodal MRI (image and radiology report text at train
time, image-only at inference). The real
problem isn't the modeling — it's that only 58 of 4,407 training studies
carry direct labels; the rest have to be handled as a weak-supervision
problem built on noisy report-derived signal. Currently deep in data
verification: confirmed patient-level leakage isn't a risk (4,407 unique
patients, one study each, verified against DICOM headers), resolved
laterality coverage across manufacturers, and now designing a validation
strategy that can be trusted with a 58-study labeled core. No model
trained yet — getting the data and validation right first.

`Python · PyTorch · pydicom`

[github.com/dhyeydaftary/rsna-knee-abnormality-detection](https://github.com/dhyeydaftary/rsna-knee-abnormality-detection)

---

### ~/ toolbox

**Core**  
![Python](https://img.shields.io/badge/-Python-1b1f24?style=flat-square&logo=python&logoColor=F59E0B)
![JavaScript](https://img.shields.io/badge/-JavaScript-1b1f24?style=flat-square&logo=javascript&logoColor=F59E0B)
![TypeScript](https://img.shields.io/badge/-TypeScript-1b1f24?style=flat-square&logo=typescript&logoColor=F59E0B)
![Flask](https://img.shields.io/badge/-Flask-1b1f24?style=flat-square&logo=flask&logoColor=F59E0B)
![React](https://img.shields.io/badge/-React-1b1f24?style=flat-square&logo=react&logoColor=F59E0B)
![Node.js](https://img.shields.io/badge/-Node.js-1b1f24?style=flat-square&logo=nodedotjs&logoColor=F59E0B)
![Express](https://img.shields.io/badge/-Express-1b1f24?style=flat-square&logo=express&logoColor=F59E0B)
![Git](https://img.shields.io/badge/-Git-1b1f24?style=flat-square&logo=git&logoColor=F59E0B)  
<sub>Node · Express · MongoDB — the MERN stack</sub>

**Working with**  
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-1b1f24?style=flat-square&logo=postgresql&logoColor=F59E0B)
![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-1b1f24?style=flat-square&logo=sqlalchemy&logoColor=F59E0B)
![Socket.IO](https://img.shields.io/badge/-Socket.IO-1b1f24?style=flat-square&logo=socketdotio&logoColor=F59E0B)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-1b1f24?style=flat-square&logo=tailwindcss&logoColor=F59E0B)
![MongoDB](https://img.shields.io/badge/-MongoDB-1b1f24?style=flat-square&logo=mongodb&logoColor=F59E0B)
&nbsp;·&nbsp; Java

**Exploring**  
![Solidity](https://img.shields.io/badge/-Solidity-1b1f24?style=flat-square&logo=solidity&logoColor=F59E0B)
&nbsp;·&nbsp; AI/ML (SHAP-style explainable ML) · Web3 / Arbitrum

---

### ~/ engineering map

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-cross-section-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/stack-cross-section-light.svg">
  <img alt="Engineering map: an isometric cross-section of Frontend, Backend, Data, and AI/ML layers, with a Web3 branch. Amber paths trace each project's real coverage — campus-connect spans Frontend through Data; womens-safety-alert-system spans Backend through Data; AMR-Insight spans Backend through Data through AI/ML; originchain spans Backend through Data, bridging into Web3." src="assets/stack-cross-section-dark.svg">
</picture>

---

### ~/ selected work

<table width="100%">
<tr><td>
<b>campus-connect</b><br>
Full-stack social platform for university communities — 90+ REST endpoints across 10 Flask blueprints, real-time chat over WebSockets, an 18-table PostgreSQL schema, 333 automated tests at 83% coverage.<br>
<code>Flask · PostgreSQL · Tailwind/Jinja2 · Socket.IO</code><br>
<i>Creator, Lead Developer &amp; Architect — with Urva Shah (design) &amp; Twisha Agrawal</i><br>
<a href="https://github.com/dhyeydaftary/campus-connect">github.com/dhyeydaftary/campus-connect</a>
</td></tr>
</table>

<table width="100%">
<tr><td>
<b>womens-safety-alert-system</b><br>
Java-based real-time emergency response system — three-tier RBAC, FIFO alert dispatching, geospatial nearest-responder assignment, multithreaded background monitoring, MySQL/JDBC persistence. Singleton, Factory, and Observer patterns throughout.<br>
<code>Java · MySQL · JDBC</code><br>
<i>Solo — Semester 2 coursework</i><br>
<a href="https://github.com/dhyeydaftary/womens-safety-alert-system">github.com/dhyeydaftary/womens-safety-alert-system</a>
</td></tr>
</table>

<table width="100%">
<tr><td>
<b>AMR-Insight</b><br>
Explainable ML platform predicting antibiotic resistance across 15 antibiotics — 15 CatBoost models with native SHAP explainability, WHO AWaRe classification, and Gemini-assisted lab-report extraction. 98 automated tests, a 13-phase security hardening pass.<br>
<code>Django/DRF · CatBoost · Node/Express · MongoDB</code><br>
<i>ML backend &amp; gateway; led security hardening — with Urva Shah &amp; Ansh Patel (frontend)</i><br>
<a href="https://github.com/dhyeydaftary/antibiotic-resistance-intelligence-platform">github.com/dhyeydaftary/antibiotic-resistance-intelligence-platform</a>
</td></tr>
</table>

<table width="100%">
<tr><td>
<b>originchain</b><br>
Decentralized creator-identity and proof-of-origin platform on Arbitrum — client-side content hashing, IPFS pinning, on-chain registration via Rust/Stylus smart contracts, wallet-based auth via Sign-In With Ethereum.<br>
<code>Express · Prisma/PostgreSQL · Rust/Arbitrum Stylus · Next.js</code><br>
<i>Backend &amp; smart contracts — built with Nandish Patel &amp; Frenil Patel</i><br>
<a href="https://github.com/originchain-labs/originchain">github.com/originchain-labs/originchain</a> · <a href="https://originchain-dev.vercel.app/">Live</a>
</td></tr>
</table>

---

### ~/ contribution activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/contribution-calendar-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/contribution-calendar-light.svg">
  <img alt="GitHub contribution activity over the past year, shown as an isometric calendar." src="assets/contribution-calendar-dark.svg">
</picture>

---

### ~/ connect

[![GitHub](https://img.shields.io/badge/GitHub-dhyeydaftary-181717?style=flat-square&logo=github)](https://github.com/dhyeydaftary)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dhyey--daftary-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/dhyey-daftary/)
[![Email](https://img.shields.io/badge/Email-dhyeydaftary%40gmail.com-F59E0B?style=flat-square&logo=gmail&logoColor=white)](mailto:dhyeydaftary@gmail.com)
