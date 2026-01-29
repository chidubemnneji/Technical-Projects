# Technical-Projects# Technical Projects Portfolio

A collection of production-grade AI and automation projects demonstrating cloud-native development, agentic AI systems, and developer tooling.

---

## 🤖 Agentic Calendar System

Voice-activated AI agent that autonomously manages calendar scheduling using GPT-4.

**Tech Stack:** Python, FastAPI, OpenAI GPT-4, Apple Calendar API, iOS Shortcuts

**Architecture:**
```
iPhone Action Button → iOS Shortcut → Python Backend → GPT-4 Analysis → Calendar API
```

**How It Works:**
1. Press iPhone Action Button and speak: "I need 2 hours tomorrow for client proposal"
2. AI analyzes calendar context and meeting importance
3. Autonomously reschedules non-critical meetings
4. Updates calendar and confirms changes

**Key Features:**
- **Context-Aware Decisions:** Evaluates meeting type, participant seniority, lead time
- **Autonomous Execution:** Makes changes within defined guardrails
- **Natural Language Interface:** Plain English commands → AI interprets and executes
- **Smart Constraints:** Never reschedules customer meetings, respects notice periods

**Decision Engine:**

The AI evaluates multiple factors:
- Meeting type (customer-facing vs. internal)
- Participant seniority and relationships
- Lead time for rescheduling (24-hour minimum)
- Task urgency from user's phrasing
- Historical patterns and preferences

**Impact Metrics:**
- 80% reduction in manual calendar management
- 4-5 hours/week saved for productive work
- 100% adherence to critical meeting constraints
- Daily active use in production

**Technical Implementation:**
- **FastAPI Backend:** Async request handling for low latency
- **GPT-4 Integration:** Structured prompts with constraint definitions
- **EventKit API:** Native macOS Calendar access via PyObjC
- **iOS Shortcuts:** Custom URL scheme for seamless voice interface
- **Context Management:** Efficient calendar data serialization for LLM input

**Engineering Challenges Solved:**
1. Natural language understanding for diverse user inputs
2. Reliable constraint enforcement (no catastrophic errors)
3. iOS Shortcuts integration with error handling
4. OAuth flow for persistent Calendar access
5. Timezone handling for multi-timezone meetings

**Use Cases:**
- Quickly blocking focus time for urgent projects
- Rearranging schedule for last-minute customer demos
- Creating time blocks for POC development
- Optimizing calendar to reduce context-switching

**Skills Demonstrated:**
- Agentic AI system design and implementation
- LLM prompt engineering for autonomous decision-making
- Python backend development (FastAPI)
- API integration (OpenAI, Apple Calendar)
- Mobile platform integration (iOS Shortcuts)
- Constraint-based decision systems
- Production automation workflow design

---

## 🚀 SoulGuide AI - Full-Stack AI Platform

**Repository:** [Spirit-Guide-AI](https://github.com/thebookplug1/Spirit-Guide-AI)

Full-stack iOS application with AI-powered conversation management, real-time features, and production deployment on GKE.

**Tech Stack:** iOS (SwiftUI), Node.js, PostgreSQL, Claude/GPT-4, Kubernetes (GKE)

**Key Features:**
- Hybrid AI system with automatic failover (99.5% uptime)
- Real-time WebSocket/SSE for concurrent users
- Deployed on GKE with horizontal pod autoscaling
- GRACE persona system with psychological profiling
- Crisis detection and safety protocols

**Performance:**
- <2s API response time for streaming
- Supports 100+ concurrent users
- PostgreSQL with optimized queries and connection pooling

[See full documentation →](https://github.com/thebookplug1/Spirit-Guide-AI)

---

## 🛠️ Infrastructure & Developer Tools Experience

**Cloud & Orchestration:**
- Production Kubernetes deployments on GKE
- Docker containerization with multi-stage builds
- CI/CD pipelines with GitHub Actions
- Horizontal pod autoscaling and health monitoring

**Backend Development:**
- Node.js + TypeScript + Express
- Python + FastAPI
- RESTful API design
- Real-time systems (WebSocket, Server-Sent Events)

**Database:**
- PostgreSQL with Drizzle ORM
- Schema design for complex relationships
- Query optimization and indexing
- Connection pooling for scale

**AI/ML:**
- LLM integration (Claude Sonnet 4, GPT-4)
- Hybrid architectures with intelligent failover
- Prompt engineering for production systems
- Agentic workflow design with guardrails

---

**Built by Chidubem Nneji**  
Solutions Engineer | Cloud-Native Platforms | AI/ML | Kubernetes  
[LinkedIn](https://linkedin.com/in/chidubem-nneji) | [GitHub](https://github.com/chidubemneji)
