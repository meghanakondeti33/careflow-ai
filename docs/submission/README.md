# CareFlow AI — Submission Documentation Index

This directory contains the three official submission PDF documents for **CareFlow AI: Autonomous Multi-Hospital Patient Intake, Scheduling & Pre-Visit Voice Agent**, fully mapped to the PRD v2.0 requirements.

---

## 📄 Submission Documents

### 1. [`CareFlow_AI_Architecture_Documentation.pdf`](./CareFlow_AI_Architecture_Documentation.pdf)
- **Purpose:** Comprehensive technical architecture documentation suitable for engineering evaluation.
- **Key Contents:**
  - System Overview & Non-Clinical Safety Boundaries
  - PRD Goal & Core Workflow Comparison Matrix
  - Implemented User Roles (Platform Admin, Hospital Admin, Doctor, Patient)
  - Multi-Tier Architecture Diagram & Layer Descriptions
  - Frontend SPA & Backend FastAPI Component Structure
  - Database Architecture & 10 SQLAlchemy Model Schemas
  - AI Execution Graph (LangGraph State Machine)
  - Real Availability Calculation & Double-Booking Protection Logic
  - Mock EHR Connector & **PRD-Required Unknown Outcome Recovery Flow**
  - Security, Multi-Tenant Isolation & Privacy-Aware Audit Logging
  - 30-Item Implementation Status Matrix vs PRD

### 2. [`CareFlow_AI_AI_Tools_Usage_Documentation.pdf`](./CareFlow_AI_AI_Tools_Usage_Documentation.pdf)
- **Purpose:** Detailed specification of AI runtime usage, capabilities, model providers, and evaluation framework.
- **Key Contents:**
  - AI Models & Providers (Anthropic Sonnet, OpenAI GPT-4o-mini, Google Gemini 1.5 Pro, Deterministic Fallback NLU)
  - NLU Intent Classification Engine (10 Extracted Intents)
  - **Full Inventory of 17 Implemented AI Capabilities** (`AICapabilities`)
  - Voice AI Architecture & Telephony Connector (`MockTelephonyConnector`, TwiML)
  - AI Safety Guardrails & Clinical Emergency Escalation
  - **Automated AI Evaluation Framework** (18 Automated Eval Tests, 100% Passing)

### 3. [`CareFlow_AI_AI_Prompts_Used.pdf`](./CareFlow_AI_AI_Prompts_Used.pdf)
- **Purpose:** Complete prompt repository containing exact source code reproductions of all prompts used in the application.
- **Key Contents:**
  - Master Prompt Inventory Table
  - `HEALTHCARE_ADMIN_SYSTEM_PROMPT` (System & Safety Rules)
  - `LLM_NLU_SYSTEM_PROMPT` (Structured NLU Engine & Clarification Rules)
  - `EMERGENCY_ESCALATION_MESSAGE` (Emergency Clinical Safety Directive)
  - Context Injection Templates for Anthropic, OpenAI, and Gemini APIs
  - Voice & Telephony Greetings and TwiML XML Templates
  - Dynamic Capability Response Prompts

---

## 🎯 PRD Submission Requirements Mapping

| PRD Submission Requirement | Document Section Mapping |
| :--- | :--- |
| **High-level architecture & data model** | `Architecture Documentation` (Sections 4, 7) |
| **Booking sequence & EHR flow** | `Architecture Documentation` (Sections 9, 10) |
| **Failure & recovery flow** | `Architecture Documentation` (Section 10) |
| **Security & tenant model** | `Architecture Documentation` (Section 11) |
| **AI models & Voice technology** | `AI Tools & Usage Documentation` (Sections 1, 4) |
| **Runtime AI & Evaluation approach** | `AI Tools & Usage Documentation` (Sections 2, 6) |
| **Important Prompts used** | `AI Prompts Used` (Sections 1, 2, 3) |

---
*Generated automatically for CareFlow AI Submission Package.*
