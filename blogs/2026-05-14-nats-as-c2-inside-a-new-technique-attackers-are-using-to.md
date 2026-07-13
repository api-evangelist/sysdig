---
title: "NATS-as-C2: Inside a new technique attackers are using to harvest cloud credentials and AI API keys"
url: "https://webflow.sysdig.com/blog/nats-as-c2-inside-a-new-technique-attackers-are-using-to-harvest-cloud-credentials-and-ai-api-keys"
date: "2026-05-14"
feed_url: "https://sysdig.com/feed/"
---
Sysdig Threat Research Team (TRT) has identified what appears to be the first published case of a threat actor using a NATS server as command-and-control (C2) infrastructure — a technique dubbed “NATS-as-C2.” Discovered during an investigation into exploitation of CVE-2026-33017 in Langflow, the operation used cloud-native messaging infrastructure, including pub/sub orchestration and durable task queues, to coordinate a distributed credential-hunting worker pool targeting AWS and AI credentials.
