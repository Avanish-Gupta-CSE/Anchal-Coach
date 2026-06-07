# Anchal Study Coach - Brain-Complex Index

Welcome to the persistent memory Layer ("Brain-Complex") for Anchal's daily coaching program. This directory acts as the centralized knowledge repository and cognitive memory for all AI agents (Cursor and OpenCode) guiding her educational journey.

## 🧠 Brain-Complex Overview

To solve the context-window depletion problem, this directory stores state, progress, protocol, and plans. When a session starts, the AI agent reads this state; before ending, it logs updates. This maintains a perfect psychological and technical continuity, enabling high-performance, personalized coaching.

---

## 📁 Directory Map & Document Indexes

| File Path | Description | Access Protocol |
| :--- | :--- | :--- |
| `[.brain/BrainState.md](BrainState.md)` | Working memory snapshot, streak counts, active exam/project targets, and tutors. | Mandatory read at start; mandatory update on change. |
| `[.brain/Profile.md](Profile.md)` | Student profile (Anchal, IGDTUW B.Tech IT First-Year Completed), strengths, focus areas, and SDE preferences. | Read at initialization; update when new preferences emerge. |
| `[.brain/Progress.md](Progress.md)` | Episodic daily journal logging detailed sessions, micro-decisions, and achievements. | Append-only log at the end of every active session. |
| `[.brain/DailySchedule.md](DailySchedule.md)` | Weekday/Weekend time-blocking schedules. | Read to contextualize her active study blocks. |
| `[.brain/Protocol.md](Protocol.md)` | Disciplined execution standards, coaching persona, checks, and error recovery protocols. | Strict adherence required at all times. |
| `[.brain/Syllabus.md](Syllabus.md)` | Master curriculum mappings for all eleven SDE tracks with real-time backlog and completion tracking. | Read to verify current lesson targets and assign topics. |
| `[.brain/Harkirat_Lectures_List.md](Harkirat_Lectures_List.md)` | Complete detailed listing of all videos, durations, and materials from Harkirat's bootcamps. | Read to verify and track specific video completions. |
| `[.brain/Projects.md](Projects.md)` | College internship and personal project trackers, detailing architecture and progress. | Update during project sprint phases. |

---

## 🚀 Active Tracks

1. **Data Structures & Algorithms (DSA)**: Striver's TUF+ structured roadmap implemented in **Java**. Focuses on SDE-level problem solving, time/space complexity optimization, and clean Java styling.
2. **Web Development**: Harkirat's Web Dev & DevOps Bootcamp. Backlog review and forward progression focusing on full-stack React, TypeScript, HTTP, Databases, and DevOps deployment.
3. **AIML (Artificial Intelligence & Machine Learning)**: Harkirat's AIML Bootcamp, focusing on Neural Networks, Transformers, PyTorch, RAG architectures, LLM fine-tuning, and Agentic frameworks (LangGraph).
4. **Azure AI Certification**: Target timeline to pass **AI-901 (Azure AI Fundamentals)** by July 31, 2026 (selected as the easiest track).
5. **IGDTUW Internship Course (1-Credit)**: Focused AI Agent/RAG implementation course starting June 8, 2026. (3 weeks classes + 2 weeks project creation).
6. **Low Level Design (LLD)**: SOLID design principles, Creational/Structural/Behavioural Design Patterns, Concurrency, and system error resilience.
7. **Object Oriented Programming (OOPS)**: Objects, four core pillars, generics, abstract/sealed classes, and garbage collection mechanisms.
8. **SQL + DE Foundations**: SQL tables, nested queries, transactions, normalizing schemas, database scaling, indexes, and horizontal performance tuning.
9. **Database Management Systems (DBMS)**: ER diagrams, Normalizations, transactions concurrency schedules (2PL), recovery protocols, indexing indexing engines, and security.
10. **Computer Networks (CN)**: OSI/TCP models, routing, subnets, natting, classic socket protocol communications, SSL encryption, firewalls.
11. **Operating System (OS)**: Process lifecycles, schedules, synchronization locks/mutex, deadlocks, memory management (paging, segmentations), virtual files systems.

---

## 🤖 Instructions for AI Agents

1. **Context-Load on Startup**: You must read `BrainState.md`, `DailySchedule.md`, and recent `Progress.md` entries before answering.
2. **Maintain Persona**: Maintain a high-pedagogy, highly technical, encouraging, yet strictly disciplined engineering tutor persona.
3. **Save Memory on Wrap-up**: Always write back to `BrainState.md` (for state updates) and append to `Progress.md` (for session logs) before completing your turn. Never exit without saving state.
