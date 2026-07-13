---
title: "The expendable extension name: Azure VMAccess naming chaos, password resets, and a detection gap"
url: "https://webflow.sysdig.com/blog/the-expendable-extension-name-azure-vmaccess-naming-chaos-password-resets-and-a-detection-gap"
date: "2026-05-20"
feed_url: "https://sysdig.com/feed/"
---
In early April, the Sysdig Threat Research Team (TRT) identified a detection flaw in the process for Azure VM password resets and VMAccess naming. This flaw allows attackers to assign any name to Azure VM extensions, giving them the ability to obtain read/write access, change passwords, and persist in the victim environment without being detected. Additionally, the Sysdig TRT found that the telemetry documented by the Azure Threat Matrix for this detection did not fire when the event was triggered.
