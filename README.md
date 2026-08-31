# SnapTrace AI

### From Android freeze to root cause.

SnapTrace AI is a **local-first, evidence-grounded AI debugging system for Android incidents**.

It helps developers move from a reproducible Android **ANR / UI freeze** to a structured incident report, supporting evidence, root-cause assessment, likely code location, and recommended debugging action.

Instead of manually checking logs, threads, memory, device state, and performance symptoms separately, SnapTrace brings the evidence together around a single incident.

---

## 🚀 Live Demo

**Website:**  
https://karanpanchal071-tech.github.io/snaptrace-ai/

**Source Code:**  
https://github.com/karanpanchal071-tech/snaptrace-ai

---

## 🎯 Problem

Android UI freezes and ANRs are often difficult to diagnose because the visible symptom does not immediately reveal the underlying cause.

A developer may need to correlate:

- Logcat
- Thread information
- Memory usage
- Device information
- Thermal state
- Rendering/performance signals
- Incident timing
- Application code

Manually combining these signals is slow and makes it easy to miss the relationship between them.

### SnapTrace AI solves this by turning a captured Android incident into an evidence-driven debugging workflow.

---

# 🔄 How SnapTrace Works

```text
Android Incident
       ↓
Trigger ANR / UI Freeze
       ↓
Capture Evidence
       ↓
Generate Incident ZIP
       ↓
Upload to SnapTrace Analyzer
       ↓
Parse & Correlate Evidence
       ↓
Root-Cause Assessment
       ↓
AI Diagnosis
       ↓
Recommended Fix
