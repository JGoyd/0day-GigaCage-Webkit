# WebKit Gigacage iOS 26.2  

### **Advisory ID:** [CVE Pending]
---
**Webkit Bug:** #304711 
**Apple Tracking ID:** OE01004904221848

## Overview

This repository documents an active zero-day integer overflow vulnerability in WebKit’s Gigacage implementation, affecting iOS 26.2 and related platforms. The flaw enables out-of-bounds memory access and process termination, with elevated risk of remote code execution if Gigacage protections are bypassed.

## Contents

- **TECHNICAL_DISCLOSURE.md:** Full technical advisory, including proof-of-concept code examples and analysis
- **crash_logs/**: Crash logs from affected iOS 26.2 devices demonstrating reproducibility

## Impact

- **Affected devices:** iOS 26.2, potentially macOS Sequoia 15.x and WKWebView-based browsers
- **Current risk:** Persistent Denial of Service (DoS)
- **Potential risk:** Remote Code Execution (RCE)
- **Confirmed:** 100% reproducibility on iOS 26.2

## Purpose

Accelerate vendor triage and support mitigations. Intended for use by security engineers, defenders, and Apple’s security response teams.

### Disclosure

See`VULNERABILITY_REPORT.md` for PoC details, crash evidence, and remediation recommendations.

---

*For authorized research and mitigation only. Unauthorized exploitation is prohibited.*
