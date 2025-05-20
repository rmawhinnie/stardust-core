# 🤝 Contributing to Project Stardust

Welcome, contributor!
Thank you for your interest in improving **Project Stardust**, the galaxy’s premier open-source kyber-reactor framework. Whether you're squashing bugs, optimizing exhaust flow, or questioning the ethics of space-scale vaporization, your input is valued.

---

## 📋 Ground Rules

Before contributing, please review the following:

- All pull requests must:
  - Pass static analysis via the **BICE Jenkins Compliance Pipeline™**
  - Include relevant `#justification` comments for any flagged vulnerabilities
  - Avoid references to “weapons,” “superlasers,” or “intentional sabotage” (see [LICENSE](../LICENSE))

- All new features must:
  - Support planetary-scale energy use cases
  - Be easily misinterpreted as peaceful
  - Fit within the existing theme of “benevolent domination through infrastructure”

---

## 🛠️ Development Setup

```bash
git clone https://git.holonet.gov/imp-energy/stardust-core.git
cd stardust-core
make install
```

To simulate kyber feedback loops locally, use:

```bash
Copy
Edit
./ignite-core.sh --env=staging
```

DO NOT TEST ON LIVE PLANETS.
This violates the Imperial Benevolence License and may attract Jedi.

## 🧪 Running Tests
Test suite located in /test includes:
- Reactor loop stress tests
- Fail-safe recursion simulations
- Targeting API drift under "rebellious" conditions

```bash
Copy
Edit
pytest test/
If any test fails, blame caching or sabotage. Then fix it.
```

## 🐛 Reporting Bugs
Please report vulnerabilities via the Empire Bug Bounty Portal, or whisper them to a trusted Bothan.

We are contractually obligated to pretend to read all reports.
Serious vulnerabilities will be marked as “duplicate” or “won’t fix” depending on mood.

## 🚫 What Not to Submit
- Refactors of stardust_protocol() (trust us, it’s perfect)
- Shielding requests for the thermal exhaust port (intentional design)
- Ethical objections (will be forwarded to HR—aka Vader)
- Documentation changes that contradict official narrative

## ✨ Code of Conduct
All contributors must adhere to the Empire’s Holonet Community Standards.
Violation may result in reassignment to Mustafar QA, or “performance evaluation” by Director Krennic.

## 📦 Recognition
Significant contributors may receive:

- A personal thank-you note from Orson Krennic (or his assistant)
- Fast-tracked access to the Imperial DevSecOps guild
- Early access to project-stardust-v2 (working title: “Project Cinder”)

“The power to shape the stars belongs to those who submit clean pull requests.”
— G.E.

---
