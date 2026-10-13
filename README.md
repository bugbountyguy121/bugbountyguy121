<!--
  README for Oussama (bugbountyguy121)
  Purpose: present a personal, learning-focused SOC journey and study system.
  Accuracy rules observed: no invented certifications or outcomes; OFPPT diploma included per request.
-->

<div align="center">

# Oussama — Building Practical SOC Skills, One Lab at a Time

[![GitHub](https://img.shields.io/badge/GitHub-bugbountyguy121-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bugbountyguy121)

</div>

---

## Who I am

I’m Oussama. I hold an OFPPT Specialized Technician diploma in Cybersecurity and I genuinely enjoy exploring how systems work, how attackers leave traces, and how defenders convert noisy data into useful decisions.

I’m not presenting a finished résumé — I’m publishing my learning process. My focus is to build real SOC competence through deliberate practice, reproducible labs, and a learning system that helps me stay focused and make steady progress.

---

## What I’m working toward

- Transitioning into practical SOC work: data collection, detection engineering, triage, and incident response.
- Learning how to learn: develop mental models, connect concepts, test understanding by reproducing and explaining, then document the results.
- Building a sustainable focus system to reduce distractions and keep consistent progress.

---

## Learning Philosophy (my workflow)

I use a simple progression for every topic I study:

Understand → Observe → Reproduce → Connect → Explain → Test → Document

- Understand: learn *why* a thing exists and the core concept.
- Observe: collect real telemetry or examples that show the concept in practice.
- Reproduce: recreate the behaviour in a small, repeatable lab.
- Connect: map how this piece relates to other systems or techniques (e.g., how a syscall shows up in logs).
- Explain: write a short explanation in my own words and produce a minimal demonstration.
- Test: design a simple validation case or test harness to confirm the detection or analysis works.
- Document: keep a concise, reproducible lab note in my Obsidian vault (git-backed).

This progression keeps learning active and produces evidence rather than claims.

---

## How I manage focus (sustainable habits)

- Small, realistic sessions: when concentration is hard I prefer one 30–50 minute focused session to an unsustainable marathon.
- Deep blocks when possible: 90–120 minutes of single-task work for labs or complex problems.
- Single-MIT rule: each session has one Most Important Task — a clear, small outcome (e.g., "parse SSH logs" or "write one Sigma rule").
- Minimise friction: terminal-first setup, phone away, browser site-blocker during deep blocks.
- Weekly 30-minute retrospective: what worked, what distracted me, and what one change I’ll try next week.

These are habits I practice and adapt — not a rigid productivity prescription.

---

## Current technical priorities (ongoing & near-term)

Ongoing (currently learning / practising):
- Foundations: Linux, networking basics, and common log sources (auth, syslog, web, Windows event basics).
- SIEM fundamentals: log ingestion, parsing, and simple correlation (Wazuh / Filebeat concepts in labs).
- Detection engineering basics: ATT&CK-mapped detections, Sigma rules, and simple Suricata/IDS signatures.
- Incident triage: building timelines and extracting relevant artifacts from logs and disk images.

Planned (next projects):
- Reproducible SIEM lab (Docker): ingest sample telemetry, write 10 validated detection rules, and a tuning checklist.
- Small automation: Python scripts that parse log samples and produce test cases for detection rules.
- One-week learning sprints: short, focused projects that end with a documented lab note.

---

## Projects (clear status)

I separate projects into Completed (evidence present), Ongoing, and Planned. I avoid claiming finished outcomes until I have reproducible evidence.

Completed
- Personal notes and examples in my Obsidian vault (private): small writeups, parsing examples, and checklists.

Ongoing
- SIEM Modernization Lab — building a minimal Docker lab with log generators and basic rule tests.
- HTB CDSA Path — in progress (practical exercises and challenges; progress recorded in private vault).

Planned
- Mobile Forensics Toolkit: short, reusable scripts for APK inspection and artifact extraction.
- DevSecOps container checks: SBOM-based scans and a pipeline demonstration.

If you want to see a public demonstration for any of the above, I can extract a minimal, reproducible example and publish it as a focused repo.

---

## Weekly rhythm (example)

- Monday — Foundations (reading + one micro-lab, 30–90 min)
- Tuesday — Hands-on lab (build or reproduce a behaviour, 60–120 min)
- Wednesday — Detection writing & testing (write one Sigma/Suricata rule + test)
- Thursday — Automation (small script or test harness, 30–60 min)
- Friday — Document & reflect (write a 15–30 min lab note and update vault)
- Weekend — Optional light practice or CTFs (short sessions)

This is a flexible rhythm — I prioritise consistency over intensity.

---

## How I record progress

- Obsidian (git-backed): primary lab notes and learning artifacts (private). When a lab is small and reproducible, I publish it as a public repo.
- This GitHub profile: a public snapshot of what I’m learning and building.

---

## A few concrete examples I can share on request

- A small Docker lab that generates SSH and web logs and shows how a simple correlation reduces noise.
- One Sigma rule with a short test harness that shows a true positive and a controlled false positive.
- A Python script that parses sample logs and extracts fields used by simple detections.

Tell me which example you'd like first and I’ll publish a focused, minimal repo for it.

---

## Notes and accuracy checks

- Diploma: OFPPT Specialized Technician in Cybersecurity — please confirm the exact diploma title/translation if you want it worded differently.
- HTB CDSA: stated as "in progress" — I have not claimed completion.
- Obsidian vault: private unless you ask me to publish selected notes.

If any of these facts need correction, tell me which line to change.

---

_Last updated: 2026-10-13_
