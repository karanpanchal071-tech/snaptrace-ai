# SnapTrace AI

### From Android freeze to root cause.

LINK : https://karanpanchal071-tech.github.io/snaptrace-ai/

SnapTrace AI is a local-first, evidence-grounded debugging system for Android incidents.

It helps developers move from a reproducible Android UI freeze/ANR to a structured incident report, root-cause assessment, supporting evidence, and an actionable debugging recommendation.

## Live Demo

https://karanpanchal071-tech.github.io/snaptrace-ai/

## What SnapTrace AI Does

Instead of manually collecting logs and trying to understand an Android freeze, SnapTrace creates a structured evidence bundle and analyzes it through a local web-based debugging interface.

### Core workflow

**Trigger incident → Capture evidence → Create ZIP → Analyze evidence → Identify root cause → Explain evidence → Suggest fix**

The complete workflow is demonstrated using a real Android test application and the SnapTrace analyzer.

---

## Key Features

### 1. Android Incident Reproduction

The Android application provides a controlled environment for reproducing a UI freeze / ANR scenario.

The app can:

- Trigger an ANR / UI freeze scenario
- Display a severely degraded FPS condition
- Capture incident evidence
- Generate a structured evidence bundle

Example incident:

```text
Trigger: ANR_UI_FREEZE
Duration: 3000 ms
Observed FPS: 2 FPS
