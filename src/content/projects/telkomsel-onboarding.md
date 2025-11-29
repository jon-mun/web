---
title: "Telkomsel Onboarding (Cloud Infrastructure Provisioning System)"
description: "An internal system to digitize Telkomsel’s infrastructure request process, streamlining end-to-end onboarding."
pubDate: "2024-03-01"
role: "Full Stack Engineer"
year: "2024"
tags:
  [
    "Go (Fiber)",
    "SvelteKit",
    "PostgreSQL",
    "Docker",
    "Kubernetes",
    "Minio (S3)",
    "RedHat OpenStack",
  ]
heroImage: "../../assets/blog-placeholder-2.jpg"
---

### Overview

An internal system to digitize Telkomsel’s infrastructure request process. Previously, everything relied on manual paperwork, leading to slow turnaround times and poor traceability. The system streamlines end-to-end onboarding: submission, assessment, approval, provisioning, and confirmation.

### What I Did

- Designed the end-to-end business flow through interviews and SIPOC mapping.
- Built the full technical architecture using a microservices approach.
- Developed the backend services (authentication + onboarding) in Go.
- Implemented the frontend using SvelteKit based on the Figma designs I created.
- Containerized the system using Docker and deployed on internal VMs.
- Automated CI pipelines via GitHub Actions and wrote complete documentation.

### Challenges

- Turning an undocumented manual process into a structured digital workflow.
- Aligning multiple stakeholders (users, assessors, onboarding team).
- Ensuring the system met security and isolation requirements inside the Telkomsel network.

### Links

_(Private — internal Telkomsel system)_
