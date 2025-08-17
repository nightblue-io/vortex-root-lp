---
title: Introducing Vortex
image: /uploads/vortex-intro-03.png
date: 2025-08-10
tags:
  - product
---

##

A small group of engineers at [Alphaus Inc.](https://alphaus.cloud/) are deep in the trenches building a new utility to monitor AI traffic. Specifically, we're tracking LLM prompts and responses. The main goals are sniffing out security issues, and keeping an eye on sentiment.

The tool is called "Vortex". It is designed to be non-intrusive. It hooks in at the kernel level, so you won't need to refactor your existing apps to use it.

Right now, our focus is on getting it running for Kubernetes, AWS ASGs, and GCP MIGs. Main downside: it needs root privileges to do its thing, which is a showstopper for some environments, and it's definitely a point of discussion as we move forward.

Still in the build phase, so we're not dropping the full release notes just yet. But definitely keep an eye out for more details down the line. We're pretty excited about the potential here for better visibility and control.

Best,  
Chew
