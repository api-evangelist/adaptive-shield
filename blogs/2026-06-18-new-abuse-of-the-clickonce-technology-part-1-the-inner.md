---
title: "New Abuse of the ClickOnce Technology, Part 1: The Inner Workings of ClickOnce Application Deployment"
url: "https://www.crowdstrike.com/en-us/blog/new-abuse-of-the-clickonce-technology-part-one/"
date: "2026-06-18"
author: "Mathilde Venault"
feed_url: "https://www.crowdstrike.com/en-us/blog/feed/"
---
Part 1 of CrowdStrike's technical deep-dive documents how Microsoft's ClickOnce deployment technology works internally, covering five deployment scenarios and the mechanics of rundll32.exe invoking dfshim.dll, dfsvc.exe COM server initialization, and ALPC messaging. It establishes how this legitimately-designed distribution mechanism could be misused, a topic explored in Part 2.
