---
title: "Marimo OSS Python Notebook RCE: From Disclosure to Exploitation in Under 10 Hours"
url: "https://webflow.sysdig.com/blog/marimo-oss-python-notebook-rce-from-disclosure-to-exploitation-in-under-10-hours"
date: "2026-04-09"
author: ""
feed_url: "https://sysdig.com/blog/rss.xml"
---
On April 8, 2026, a critical vulnerability was disclosed in marimo, an open-source reactive Python notebook platform. Currently being tracked as GHSA-2679-6mx9-h9xc, it is a pre-authentication remote code execution (RCE) vulnerability in the terminal WebSocket endpoint that allows attackers to obtain a full interactive shell on any exposed marimo instance through a single WebSocket connection – no credentials required. At the time of this writing, a CVE number has yet to be assigned.
