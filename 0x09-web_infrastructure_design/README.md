# Web Infrastructure Design

## Overview

This repository contains visual designs and documentation for various **web infrastructure configurations** built for [www.foobar.com](http://www.foobar.com). Each configuration builds upon the previous one, gradually introducing features like distribution, security, encryption, monitoring, and scalability.

## Repository Structure

```
.
├── 0-simple_web_stack                   # Single-server setup hosting the website
├── 1-distributed_web_infrastructure     # Three-server setup with load balancing & component separation
├── 2-secured_and_monitored_web_infrastructure  # Adds firewalls, SSL encryption, and monitoring
├── 3-scale_up                            # Five-server setup with clustered load balancers
├── images                                 # Design diagrams (JPG format)
├── mermaid_md                             # Mermaid diagrams for each configuration
└── README.md                              # This file
```

## Usage

1. **Follow the progression** – Start from `0-simple_web_stack` and move through each configuration to understand the incremental improvements.
2. **Study the diagrams** – Visuals in the `images/` folder and Mermaid diagrams in `mermaid_md/` help illustrate each setup.
3. **Apply concepts** – Adapt the architecture designs for planning, educational purposes, or real-world deployments.

## Key Concepts

* **Load Balancing:** HAProxy configurations in Active-Passive mode.
* **Component Separation:** Dedicated servers for web, application, and database layers.
* **Database Replication:** Primary-replica setups for improved performance and redundancy.
* **Security:** Firewalls and HTTPS encryption to secure traffic and services.
* **Monitoring:** Collection of metrics and logs to detect and troubleshoot issues early.

## Visual References

* `images/` contains JPG diagrams for each configuration.
* `mermaid_md/` contains text-based Mermaid diagrams for version-controlled visualizations.
