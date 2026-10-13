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

## 2015 – 2016: Learning how infrastructure really works

Next, as a Technology Consultant, I moved into **network functions virtualization (NFV)**. I designed and implemented a **command-line interface (CLI) tool** for operating NFV system components, wrote **Ansible playbooks** to configure, deploy and manage the tool's virtual machines, and built **Python** scripts for end-to-end cleanup of NFV hardware components, including SNMP configuration and status checks.

This role taught me far more than what was on my task list. Working inside an NFV platform meant learning how **virtualization** really works — virtual machines, the hosts underneath them, and the network functions running on top — along with the **containerization** concepts that were changing how software gets packaged and deployed. I also got a close look at the **network details** most application developers never see: how traffic is routed between components, how devices are monitored and configured over SNMP, and what actually happens when something in the chain fails.

I didn't know it then, but this would become my upper hand once I moved into full stack development.

## 2016 – 2018: Python, Java and measurable impact

As a Senior Software Engineer, I developed **Python scripts to automate the extraction of network timing device data**, streamlining auto-registration and **reducing manual extraction time by 40%**. I also deployed **Java applications for device discovery and auto-registration** through REST API calls.

The lesson here: automation is only as valuable as the time it gives back. A 40% reduction is a number people remember.

## 2018 – 2020: Going back to school for AI

In 2018 I made the biggest pivot of my career: I started an **M.S. in Computer Science with a focus on Generative AI** at Florida Institute of Technology.

My thesis was _Biometric Face Skin Tone Data Augmentation using a Generative Adversarial Network_. I used **GAN style transfer** (BeautyGAN, TensorFlow, Python) to generate six Fitzpatrick skin-tone classes, and analyzed **ArcFace face recognition** on a 440-image makeup dataset. Coursework covered artificial intelligence, deep learning, biometric authentication and software design methodologies.

Working on synthetic data generation back then turned out to be surprisingly relevant to what I'm building now.

## 2020 – 2024: Full stack at a startup — learning the language of the business

After graduating, I joined an insurance startup as a Software Engineer and went **full stack**: **C#, .NET Core, Vue.js and SQL Server**.

A startup changes how you think about code. There's no buffer between you and the people who use what you build, so I worked closely with the teams behind finance, claims and underwriting. That's where I learned the **language of the business** — premiums and commissions, tax reporting, refunds and checks, claims and policy risk. And I learned that my real job wasn't just writing code: it was **translating business needs into working software**, then translating the results back into something the business could see and act on.

That showed up in everything I built:

- **Turning manual processes into software** — automating multi-state tax report generation, refund and check processing (RESTful APIs, a Vue.js interface and an end-of-day batch process), and monthly premium and commission reports, replacing manual workflows for the finance team.
- **Turning data into visualizations** — building **Power BI** dashboards on SQL Server stored procedures and views for claims statistics and tax, check and refund discrepancies, giving finance first-time visibility to catch errors before reporting. I also cleaned third-party location data with **Python (pandas)** to fix geographic risk misalignment, improving policy risk analysis and underwriting accuracy.
- **Building for real-time and scale** — adopting **Azure SignalR Service with Azure Functions** for real-time document processing, re-designing the claims data model in SQL Server, and using **Application Insights and KQL** for root cause analysis on performance.
- **Growing the team** — leading the production support team, training new hires as full stack engineers, and mentoring interns.

This is where I learned what owning a feature really means: understanding the business problem first, then building the UI, the API, the database and the dashboard that solves it.

## 2024 – today: Enterprise microservices meet GenAI

Today I'm a Senior Software Engineer in banking, where every chapter of my background finally comes together.

On the **.NET and cloud** side, I've managed a data center migration of a **25-component microservices application** from on-prem to SaaS cloud platforms, built a **.NET Core background service publishing Kafka events with Avro schemas** via Confluent Schema Registry, built resilient components with **Polly** retries, timeouts and circuit breakers, and helped set up **SAML SSO with Azure AD** and JWT-based OAuth 2.0.

This is where my infrastructure years paid off. A data center migration isn't only a code problem — it's dependency mapping, firewall rules, ingress port mapping, IP allowlisting and cutover planning. Understanding how networks, virtual machines and containers behave meant I could reason past the application code to the host, the network and the deployment, and work with infrastructure teams in their own language.

On the **AI** side, I designed and built an **LLM multi-agent system** for enterprise synthetic data generation — agents built with **LangChain**, orchestrated with **LangGraph**, using **GCP Vertex AI Vector Search, embeddings and RAG**, with prompt engineering and guardrails to keep agents on task and reduce hallucinations.

My AI and ML background came in handy here. Because I'd studied deep learning and trained generative models myself, LLMs weren't a black box to me. I understood why models hallucinate, why grounding them with retrieval matters, and why generated data has to be validated against real rules — and that shaped how I designed the agents, the guardrails, and the RAG pipeline that aligns generated test data to the closest rule-engine match.

Synthetic data again — this time with LLMs instead of GANs. My thesis work and my day job finally converged.

## What ten years taught me

1. **Infrastructure knowledge is a developer superpower.** Knowing how virtualization, containers and networks work makes you better at building, debugging and deploying applications.
2. **Learn the language of the business.** The most valuable code translates a business need into something people can use — and the results into something they can see.
3. **Measure the impact.** "Reduced manual extraction time by 40%" says more than "wrote some scripts."
4. **Own the whole feature.** Frontend, backend, data, cloud and now AI — the most valuable work happens across the layers.
5. **Deep foundations pay off.** Going back for a master's in AI after five years in industry is what let me build with LLMs from understanding, not guesswork.

## What's next

I'll be writing here about what I build, break and learn — **.NET, full stack development, and AI agents**. Next up: a deeper look at building LLM multi-agent systems with LangGraph.

If you'd like to connect, find me on [LinkedIn](https://www.linkedin.com/in/rosalindash) or grab my resume from the [About page](../../about/#resume).
