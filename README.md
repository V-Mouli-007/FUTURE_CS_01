# 🛡️ Read-Only Vulnerability Assessment (Internal Scope)

## 🎯 Objective
This repository contains a professional Vulnerability Assessment Report conducted on a permitted, internal testing environment. The goal was to identify security misconfigurations and vulnerabilities using strict, non-intrusive, read-only techniques.

## 🔍 Scope & Target
* 📍 **Target Environment:** Internal Development Server (Localhost / `192.168.x.x`)
* 🚪 **Target Port(s):** `8080` (HTTP)
* 👁️ **Type of Testing:** Passive reconnaissance, header analysis, and banner grabbing.
* 🛑 **Out of Scope:** Active exploitation, brute forcing, DoS, automated intrusive scanning, and external/public network testing.

## 🛠️ Tools Utilized
* 🗺️ **Nmap:** Used for local network service enumeration and version detection.
* 🕸️ **OWASP ZAP:** Utilized as an intercepting proxy for passive vulnerability detection on the local web application.
* 💻 **Browser DevTools:** Used for manual HTTP response header inspection.

## 📦 Deliverables
Please view the `Report/` directory for the full 📄 **PDF presentation** detailing the findings, risk levels, business impacts, and remediation steps. Raw scan outputs and tool evidence are available in the 📁 `Evidence/` folder
