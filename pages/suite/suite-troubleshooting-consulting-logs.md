---
title:  Consulting Logs
summary: "Log files are available in a format that should be understandable to most technically-oriented people."
sidebar: suite_sidebar
permalink: suite-troubleshooting-consulting-logs.html
---

If you are a technical person, you may be interested in consulting the logs of the different bots that run in the system.

Each bot keeps its own set of execution log files, stored under the ```Log-Files``` folder on the root of your Superalgos instalation.
```
Log files contain detailed information about each execution of the bot. As such, a new folder is created for each execution, labeled with the exact DateTime.

Each folder may contain more than one file. Lighter files tend to include data about the initialization stage, while heavier files usually feature the data corresponding to the actual work the bot does.
