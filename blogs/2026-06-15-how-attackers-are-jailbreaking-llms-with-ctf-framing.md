---
title: "How attackers are jailbreaking LLMs with CTF framing and how to catch them"
url: "https://sysdig.com/blog/how-attackers-are-jailbreaking-llms-with-ctf-framing-and-how-to-catch-them"
date: "2026-06-15"
author: "Michael Clark, Director of Threat Research"
feed_url: "https://sysdig.com/feed/"
---
Threat actors are bypassing LLM guardrails by framing exploit requests as legitimate security research, such as capture-the-flag (CTF) challenges or CVE-hunting exercises, causing models to generate working exploit code. That framing leaks into fields like User-Agent headers, passwords, AWS session names, and API aliases, creating detectable fingerprints that reveal the LLM-assisted origin of attacks against AI infrastructure such as PraisonAI, LiteLLM, and Open-WebUI.
