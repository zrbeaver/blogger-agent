# BloggerAgent: Autonomous Multi-Agent Content System

### The Problem
Traditional content creation workflows are manual, fragmented, and prone to bottlenecks. As a professional in Organizational Excellence and Development, I sought to explore how **Human Performance Technology (HPT)** frameworks could be codified into autonomous agents to streamline content generation and reduce manual drafting time.

### The Solution
This project implements a multi-agent architecture using the **Google Agent Development Kit (ADK)**. By separating concerns into specialized nodes—a **Planner** and a **Writer**—the system ensures that content strategy and technical execution are handled by distinct, validated steps.

* **Frameworks Used:** ADK (Agent Development Kit), ReAct Pattern, Gemini 1.5 Flash.
* **Infrastructure:** Deployed via Google Cloud Run, utilizing serverless architecture to ensure scalability and ease of access.

### Key Features
* **Autonomous Planning:** The Planner agent uses validated HPT-aligned structures to outline technical topics before a technical draft is written.
* **Quota-Optimized:** Designed with hard iteration limits to maintain efficiency and comply with API tier constraints.
* **Cloud-Native:** Fully containerized and served as a live web application, demonstrating an end-to-end CI/CD workflow.
