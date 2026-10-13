---
pubDatetime: 2026-10-13T12:00:00-07:00
title: "From Networking to Full Stack and AI: My 10-Year Engineering Journey"
slug: from-networking-to-full-stack-and-ai
featured: true
draft: false
tags:
  - career
  - dotnet
  - ai
description: "How I went from SDN controllers and NFV tooling to enterprise .NET, event-driven microservices and LLM multi-agent systems — and what each stage taught me."
---

Ten years ago I was writing Java service layers for a software-defined networking controller. Today I build enterprise .NET applications and LLM multi-agent systems. The path between those two points wasn't a straight line — and that's exactly why I wanted to write it down.

This is the story of how I got here, and what each stage taught me.

## Table of contents

## 2013 – 2015: Starting at the network layer

My career began as a System Engineer working on **software-defined networking (SDN)**. I implemented service layers using MD-SAL for the **OpenDaylight (ODL) Controller**, created **YANG models** and **RPC interfaces** for communication between network devices and controllers, and deployed Maven bundles as features in the controller.

It was low-level, protocol-heavy work in **Java** — and it gave me a foundation I still lean on: thinking in terms of contracts between systems. A YANG model is, at heart, a schema that two parties agree on. Years later, I'd find the same idea in Avro schemas and API contracts.

## 2015 – 2016: Automating virtualized networks

Next, as a Technology Consultant, I moved into **network functions virtualization (NFV)**. I designed and implemented a **command-line interface (CLI) tool** for operating NFV system components, wrote **Ansible playbooks** to configure, deploy and manage the tool's virtual machines, and built **Python** scripts for end-to-end cleanup of NFV hardware components, including SNMP configuration and status checks.

This was my first real taste of automation as a product — building tools that other people depend on to do their jobs.

## 2016 – 2018: Python, Java and measurable impact

As a Senior Software Engineer, I developed **Python scripts to automate the extraction of network timing device data**, streamlining auto-registration and **reducing manual extraction time by 40%**. I also deployed **Java applications for device discovery and auto-registration** through REST API calls.

The lesson here: automation is only as valuable as the time it gives back. A 40% reduction is a number people remember.

## 2018 – 2020: Going back to school for AI

In 2018 I made the biggest pivot of my career: I started an **M.S. in Computer Science with a focus on Generative AI** at Florida Institute of Technology.

My thesis was _Biometric Face Skin Tone Data Augmentation using a Generative Adversarial Network_. I used **GAN style transfer** (BeautyGAN, TensorFlow, Python) to generate six Fitzpatrick skin-tone classes, and analyzed **ArcFace face recognition** on a 440-image makeup dataset. Coursework covered artificial intelligence, deep learning, biometric authentication and software design methodologies.

Working on synthetic data generation back then turned out to be surprisingly relevant to what I'm building now.

## 2020 – 2024: Becoming a full stack .NET engineer

After graduating, I joined the insurance industry as a Software Engineer and went **full stack**: **C#, .NET Core, Vue.js and SQL Server**.

Some of the work I'm proudest of from this period:

- **Automating finance workflows** — multi-state tax report generation, refund and check processing with RESTful APIs and an end-of-day batch process, and monthly financial reports — replacing manual processes for the finance team.
- **Real-time processing** — adopting **Azure SignalR Service with Azure Functions** so users saw document-processing status instantly.
- **Data and performance** — re-designing the claims data model in SQL Server with indexing, constraints, partitioning and SEQUENCE-based numbering, building **Power BI** dashboards, and using **Application Insights and KQL** for root cause analysis.
- **Leading people** — leading the production support team, training new hires as full stack engineers, and mentoring interns.

This is where I learned what "owning a feature" really means: the UI, the API, the database, the deployment, and the support afterward.

## 2024 – today: Enterprise microservices meet GenAI

Today I'm a Senior Software Engineer in banking, where both halves of my background finally meet.

On the **.NET and cloud** side, I've managed a data center migration of a **25-component microservices application** from on-prem to SaaS cloud platforms, built a **.NET Core background service publishing Kafka events with Avro schemas** via Confluent Schema Registry, built resilient components with **Polly** retries, timeouts and circuit breakers, and helped set up **SAML SSO with Azure AD** and JWT-based OAuth 2.0.

On the **AI** side, I designed and built an **LLM multi-agent system** for enterprise synthetic data generation — agents built with **LangChain**, orchestrated with **LangGraph**, using **GCP Vertex AI Vector Search, embeddings and RAG**, with prompt engineering and guardrails to keep agents on task and reduce hallucinations.

Synthetic data again — this time with LLMs instead of GANs. My thesis work and my day job finally converged.

## What ten years taught me

1. **Fundamentals transfer.** Schemas, contracts and automation showed up in every role, whether the stack was Java, Python or C#.
2. **Measure the impact.** "Reduced manual extraction time by 40%" says more than "wrote some scripts."
3. **Own the whole feature.** Frontend, backend, data, cloud and now AI — the most valuable work happens across the layers.
4. **It's never too late to pivot.** Going back for a master's in AI after five years in industry was the best career decision I've made.

## What's next

I'll be writing here about what I build, break and learn — **.NET, full stack development, and AI agents**. Next up: a deeper look at building LLM multi-agent systems with LangGraph.

If you'd like to connect, find me on [LinkedIn](https://www.linkedin.com/in/rosalindash) or grab my resume from the [About page](../../about/#resume).
