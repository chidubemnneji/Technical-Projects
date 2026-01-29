# Technical Projects Portfolio

A collection of production-grade AI and automation projects demonstrating cloud-native development, agentic AI systems, and developer tooling.

---

## 🚀 SoulGuide AI - Full-Stack AI Platform

**Repository:** [Spirit-Guide-AI](https://github.com/chidubemnneji/Spirit-Guide-AI)

Full-stack iOS application with AI-powered conversation management, real-time features, and production deployment on GKE.

**Tech Stack:** iOS (SwiftUI), Node.js, TypeScript, PostgreSQL, Claude/GPT-4, Kubernetes (GKE)

**Key Highlights:**
- Hybrid AI system with automatic failover between Claude and GPT-4 (99.9% uptime)
- Real-time WebSocket/SSE supporting 100+ concurrent users
- Deployed on GKE with horizontal pod autoscaling and CI/CD pipelines
- GRACE persona system with psychological profiling and adaptive responses
- Crisis detection and safety protocols with trauma-informed responses
- PostgreSQL with Drizzle ORM for type-safe queries and complex relationships

**Performance Metrics:**
- <2s API response time for streaming AI responses
- Production-ready deployment with health checks and monitoring
- Competing against established apps with 20M+ users

**[→ View full project documentation](https://github.com/chidubemnneji/Spirit-Guide-AI)**

---

## 🤖 Agentic Calendar System

Voice-activated AI agent that autonomously manages calendar scheduling using GPT-4.

**Tech Stack:** Python, FastAPI, OpenAI GPT-4, Apple Calendar API, iOS Shortcuts

### Architecture
```
iPhone Action Button → iOS Shortcut → Python Backend → GPT-4 Analysis → Calendar API
```

### How It Works

1. Press iPhone Action Button and speak: *"I need 2 hours tomorrow for client proposal"*
2. AI analyzes calendar context and meeting importance
3. Autonomously reschedules non-critical meetings
4. Updates calendar and confirms changes

### Key Features

**Context-Aware Decisions**
- Evaluates meeting type, participant seniority, lead time
- Understands implicit priorities (customer meetings > internal syncs)
- Considers rescheduling etiquette and notice periods

**Autonomous Execution with Guardrails**
- Makes changes automatically within defined constraints
- Never reschedules customer-facing meetings
- Enforces minimum 24-hour notice for changes
- Preserves meeting duration and recurring patterns

**Natural Language Interface**
- *"Block tomorrow morning for urgent customer issue"*
- *"Give me 4 hours this week for POC development"*
- *"Make room for 90-minute technical deep dive"*
- AI interprets intent and finds optimal solution

### Decision Engine

The AI evaluates multiple factors:
- **Meeting Type:** Customer-facing vs. internal
- **Participant Seniority:** VP/C-level vs. peers
- **Lead Time:** How much notice to give attendees
- **Task Urgency:** Implicit priority from user's phrasing
- **Historical Patterns:** Learns from past decisions

### Impact Metrics

- **80%** reduction in manual calendar management
- **4-5 hours/week** saved for productive work
- **100%** adherence to critical meeting constraints
- Daily active use in production environment

### Technical Implementation

**Backend Architecture:**
- FastAPI for async request handling
- GPT-4 integration with structured prompts
- EventKit API for native macOS Calendar access
- iOS Shortcuts custom URL scheme integration

**Engineering Challenges Solved:**
1. Natural language understanding for diverse user inputs
2. Reliable constraint enforcement (preventing catastrophic errors)
3. iOS Shortcuts integration with error handling and recovery
4. OAuth flow for persistent Calendar API access
5. Timezone handling for multi-timezone meetings

### Use Cases

- Quickly blocking focus time for urgent projects
- Rearranging schedule for last-minute customer demos
- Creating time blocks for POC development
- Optimizing calendar to reduce context-switching overhead

### Skills Demonstrated

- Agentic AI system design and implementation
- LLM prompt engineering for autonomous decision-making
- Python backend development (FastAPI)
- API integration (OpenAI, Apple Calendar)
- Mobile platform integration (iOS Shortcuts)
- Constraint-based decision systems
- Production automation workflow design

---

## 🛠️ Infrastructure & Cloud Experience

### Kubernetes & Orchestration
- Production deployments on Google Kubernetes Engine (GKE)
- Horizontal pod autoscaling based on CPU/memory metrics
- Liveness and readiness probes for health monitoring
- Docker containerization with multi-stage builds
- CI/CD pipelines with GitHub Actions

### Backend Development
- **Node.js + TypeScript + Express:** Type-safe API development
- **Python + FastAPI:** High-performance async services
- **RESTful API Design:** Proper error handling and validation
- **Real-time Systems:** WebSocket and Server-Sent Events

### Database & Data
- PostgreSQL with Drizzle ORM for type-safe queries
- Schema design for complex data relationships
- Query optimization and indexing strategies
- Connection pooling for scalability

### AI/ML Engineering
- LLM integration (Claude Sonnet 4, GPT-4)
- Hybrid architectures with intelligent failover
- Prompt engineering for production reliability
- Agentic workflow design with safety guardrails
- Context management and token optimization

---

**Built by Chidubem Nneji**  
Solutions Engineer | Cloud-Native Platforms | AI/ML | Kubernetes  
📧 chidubem.nneji@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/chidubem-nneji) | [GitHub](https://github.com/chidubemnneji)
```

4. **Commit changes:** "Update portfolio with complete project documentation and correct links"

---

## **FINAL CV UPDATE:**

Update your CV contact header and projects section:

### **Contact Header:**
```
A: London, UK | P: 07513 664 708
E: Chidubem.nneji@gmail.com
L: linkedin.com/in/chidubem-nneji | GitHub: github.com/chidubemnneji
