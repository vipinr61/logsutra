# 🧘 LogSutra

**Advanced log parsing, Regex generation, and data extraction engine for modern SOC operations.**

[![Antigravity CLI](https://img.shields.io/badge/Antigravity_CLI-Skill-blue.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](#)

## 📖 The Problem
During a high-severity incident, Tier 1 and Tier 2 analysts waste critical time trying to write Regular Expressions to parse malformed, proprietary, or hybrid logs. LogSutra eliminates this friction. It is a specialized, AI-driven CLI engine that instantly translates chaotic, unstructured text into production-grade SIEM configurations and automated extraction scripts.

## 🚀 Features
Give LogSutra a raw log sample, and it will automatically generate:
1. **Optimized Regex:** High-performance Regular Expressions with standard named capture groups.
2. **Splunk Configurations:** Ready-to-use `transforms.conf` and `props.conf` stanzas aligned with CIM.
3. **Microsoft Sentinel / KQL:** Native parsing blocks mapped to ASIM.
4. **Google Chronicle (SecOps):** UDM search queries to immediately hunt for extracted fields.
5. **Python CSV Extractor:** A complete Python script that rips large log files into a structured `.csv` for rapid DFIR analysis.

## 🛠️ Usage (via Antigravity CLI)
LogSutra is built as a skill for the Antigravity CLI workspace. Drop your raw log into the prompt:

> Use the logsutra skill to parse this raw log: 
> <165>1 2026-05-23T13:10:04.000Z BLR-FW-01 vpn_gateway - - [meta sequenceId="4992"] User 'vramachandran' disconnected from 10.45.2.100...

## 👨‍💻 Author
Built by a cybersecurity professional with 10 years of deep-dive experience in SOC, IR, and SIEM engineering. Designed to help analysts speed up the triage process.