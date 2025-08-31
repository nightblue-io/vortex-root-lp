---
title: Vortex security checks
image: "/uploads/vortex-blog-00003-sec-checks.png"
date: 2025-08-31
tags:
  - product
---

##

Quick updates on Vortex:

In building Vortex, our approach is to treat prompts and responses as two distinct surfaces to monitor.

**Input checks**

* Prompt injection - We're building detection for adversarial prompts. This covers direct attacks ("Ignore previous instructions..."), indirect attacks hidden in documents, and the role-playing scenarios used for jailbreaking.
* Sensitive data leakage - We're building filters to detect a range of sensitive information in (near) real-time against a trusted source:
  * Credentials like API_KEYS, etc;
  * Proprietary source code;
  * PII;
  * Confidential information / file contents

**Output checks**

* Harmful/offensive content - Catch toxic, illegal, or otherwise malicious content that might get past the model’s built-in safety layers.
* Illegal activities, misinformation, and disinformation (might be tricky, this).
* Sensitive data leakage

![](/uploads/vortex-features-01.png)

If you're interested in checking this out or want to know more about Vortex, try it out [here](https://vortex-ui.vercel.app/), or contact us [here](https://forms.gle/4brzs1jAewBgyAWw9).

Best,  
Chew
