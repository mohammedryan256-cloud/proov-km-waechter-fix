# The Legacy Fix — a ProoV Guided Project, powered by IBM Bob

This repo is the starting point of [The Legacy Fix](https://projectstudy.in/explore/experience-legacy-fix), a ProoV
challenge. You are fixing **KM-Wächter**, the service that decides when each of Vossberg
Mobility's 6,000 cars needs a service and prints the nightly fleet-health report. It has
hidden bugs, several tests fail, and the code is written in an old style. Your job is to
fix and modernize it — with IBM Bob (or another AI coding agent; another agent works just
as well) doing the heavy lifting while you direct and audit it.

 Ḍ# 🚗 The Legacy Fix — ProoV Guided Project (Powered by IBM Bob)

> **Certificate Earned:** IBM Bobathon: The Legacy Fix - Modernize a Real Car-Company Service  
> **Issued By:** IBM SkillsBuild  

This repository contains the solution and modernized codebase for **KM-Wächter**, the service responsible for determining service schedules and printing nightly fleet-health reports for **Vossberg Mobility's 6,000 cars**.

---

## 🎯 Project Overview & Objective

The objective of this challenge was to take a legacy 2013-era Python codebase riddled with technical debt, hidden bugs, and broken unit tests, and modernize it using AI-assisted engineering with **IBM Bob**, followed by rigorous developer verification.

### Key Achievements:
- 🛠️ **Bug Fixing & Refactoring:** Fixed logic errors in `km_wachter.py` and `fleet_report.py`.
- 🧪 **Test Suite Verification:** Fixed failing tests in `test_km_wachter.py` and `test_fleet_report.py` to turn the test suite green.
- 📊 **Data-Driven Risk Analysis:** Utilized `analyze.py` on 120 historical fleet records (`fleet_history.csv`) to isolate primary predictors of vehicle breakdown.
- 🔍 **AI Output Auditing:** Documented AI agent errors and code verification steps in `NOTES.md`.

---

## 📂 Repository Structure

* `TASK.md` — Project mission brief and constraints
* `NOTES.md` — Verification audit log showing agent corrections and data analysis findings
* `km_wachter.py` / `fleet_report.py` — Main business logic modules refactored and fixed
* `test_km_wachter.py` / `test_fleet_report.py` — Unit test suite verifying logic correctness
* `analyze.py` — Breakdown-risk analysis script
* `verify.py` — Acceptance check script confirming task completion
* `fleet_history.csv` — Labeled dataset used for breakdown analysis

LEAD BACKEND DEVELOPER: MOHAMMED RAIYAN
Contact E: mohammedryan256@gmail.com

## 🚀 How to Run & Verify

1. **Install Dependencies:**
   ```bash
   pip install pytest pandas

This challenge is part of the ProoV project "The Legacy Fix" — https://projectstudy.in/explore/experience-legacy-fix
