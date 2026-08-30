# Dhyey Daftary

---

### ~/ whoami

> Early-career engineer, still figuring out where full-stack ends and AI
> begins. Based in Ahmedabad, India. I write code that mostly works, and
> bugs that look intentional.

---

### ~/ currently building

**RSNA Knee Abnormality Detection** — Kaggle competition, predicting 12
clinically important knee abnormality findings from multimodal MRI (image
+ radiology report text at train time, image-only at inference). The real
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
Python · JavaScript/TypeScript · Flask · React (Node/Express/MongoDB from MERN) · Git

**Working with**  
PostgreSQL · SQLAlchemy · Socket.IO/WebSockets · Tailwind CSS · Java · MongoDB

**Exploring**  
AI/ML (SHAP-style explainable ML) · Web3/Solidity (Arbitrum)

---

### ~/ engineering map

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-cross-section-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/stack-cross-section-light.svg">
  <img alt="Engineering map: an isometric cross-section of Frontend, Backend, Data, and AI/ML layers, with a Web3 branch. Amber paths trace each project's real coverage — campus-connect spans Frontend through Data; womens-safety-alert-system spans Backend through Data; AMR-Insight spans Backend through Data through AI/ML; originchain spans Backend through Data, bridging into Web3." src="assets/stack-cross-section-dark.svg">
</picture>

---

### ~/ selected work

**campus-connect**  
Full-stack social platform for university communities — 90+ REST endpoints
across 10 Flask blueprints, real-time chat over WebSockets, an 18-table
PostgreSQL schema, 333 automated tests at 83% coverage.  
`Flask · PostgreSQL · Tailwind/Jinja2 · Socket.IO`  
*Creator, Lead Developer & Architect — with Urva Shah (design) & Twisha Agrawal*  
[github.com/dhyeydaftary/campus-connect](https://github.com/dhyeydaftary/campus-connect)

**womens-safety-alert-system**  
Java-based real-time emergency response system — three-tier RBAC, FIFO
alert dispatching, geospatial nearest-responder assignment, multithreaded
background monitoring, MySQL/JDBC persistence. Singleton, Factory, and
Observer patterns throughout.  
`Java · MySQL · JDBC`  
*Solo — Semester 2 coursework*  
[github.com/dhyeydaftary/womens-safety-alert-system](https://github.com/dhyeydaftary/womens-safety-alert-system)

**AMR-Insight**  
Explainable ML platform predicting antibiotic resistance across 15
antibiotics — 15 CatBoost models with native SHAP explainability, WHO
AWaRe classification, and Gemini-assisted lab-report extraction. 98
automated tests, a 13-phase security hardening pass.  
`Django/DRF · CatBoost · Node/Express · MongoDB`  
*ML backend & gateway; led security hardening — with Urva Shah & Ansh Patel (frontend)*  
[github.com/dhyeydaftary/antibiotic-resistance-intelligence-platform](https://github.com/dhyeydaftary/antibiotic-resistance-intelligence-platform)

**originchain**  
Decentralized creator-identity and proof-of-origin platform on Arbitrum —
client-side content hashing, IPFS pinning, on-chain registration via
Rust/Stylus smart contracts, wallet-based auth via Sign-In With Ethereum.  
`Express · Prisma/PostgreSQL · Rust/Arbitrum Stylus · Next.js`  
*Backend & smart contracts — built with Nandish Patel & Frenil Patel*  
[github.com/originchain-labs/originchain](https://github.com/originchain-labs/originchain) · [Live](https://originchain-dev.vercel.app/)

---

### ~/ contribution activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/contribution-calendar-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/contribution-calendar-light.svg">
  <img alt="GitHub contribution calendar for the current year." src="assets/contribution-calendar-dark.svg">
</picture>

---

### ~/ connect

- GitHub: [github.com/dhyeydaftary](https://github.com/dhyeydaftary)
- LinkedIn: [linkedin.com/in/dhyey-daftary](https://www.linkedin.com/in/dhyey-daftary/)
- Email: [dhyeydaftary@gmail.com](mailto:dhyeydaftary@gmail.com)
