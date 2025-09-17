# McMaster EcoCAR – Year 4 PCM Development Challenge

## Overview
This repository contains resources and instructions for the **Year 4 Propulsion Controls & Modeling (PCM) Development Challenge** as part of the **2022–2026 EcoCAR EV Challenge**. The focus of this challenge is on the **Electronic Transmission Range Selector (ETRS)** feature, which interprets driver gear selections (Park, Reverse, Neutral, Drive) and ensures safe, logical transitions based on vehicle conditions.

Your task is to:
- Implement **logical and temporal assessments** for ETRS requirements.
- Validate the provided Simulink model against these requirements using **Simulink Test** and **Requirements Toolbox**.
- Optionally, complete advanced tasks to test failure modes and robustness.

---

## What is the ETRS Feature?
The ETRS system replaces traditional mechanical linkages with electronic controls. It ensures:
- Safe transitions between Park, Reverse, Neutral, and Drive.
- Proper coordination with the parking brake and propulsion system.
- Compliance with conditions like vehicle speed and brake application.

---

## What’s Included in This Repo?
- **Simulink Model**: `DevChallengeETRS.slx` – Represents the ETRS feature logic.
- **Requirements File**: `DevChallengeETRSReqs.slreqx` – All requirements to validate.
- **Test Suite**: `ETRSTests.mldatx` – Preconfigured tests for requirement verification.
- **Input Data**: `ETRSInputs.mat` – Pre-mapped inputs for running tests.
- **Guide**: *McMaster EcoCAR_PCM Development Challenge_Fall 2025.pdf* – Complete instructions for setup, testing, and submission.
- **Guide**: *Using the Requirements and Simulink Test Toolboxes.pdf* - Complete instructions for working with Simulink Test Manager and the Requirements Toolbox
---

## Getting Started
1. Install **MATLAB R2023a** with all required add-ons (Simulink Test, Requirements Toolbox).
2. Load the MATLAB Project: `DevChallenge2025.prj`.
3. Open the test suite (`ETRSTests.mldatx`) in **Simulink Test Manager**.
4. Map the provided input file (`ETRSInputs.mat`) to the model.
5. Implement logical and temporal assessments for each requirement.

---

## Advanced Task
After completing the base challenge:
- Create **failure mode tests** to ensure the system behaves correctly under invalid conditions.
- Add these tests to the suite and document your results.

---

## Final Deliverables
- **Test Report** generated from Simulink Test Manager.
- **Presentation** summarizing your approach, results, and challenges.

---

## Need More Details?
For full instructions, diagrams, and requirement details, **please read the complete guide**:  
**DevChallenge Year 4 Writeup FINAL.docx**

---

## Support
If you need help, contact the team via Microsoft Teams
---
