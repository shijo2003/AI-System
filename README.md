# Zecpath AI Platform

> Fully Autonomous AI Hiring Platform (Phases 1–100) 

## Overview

Zecpath is an end-to-end AI-powered hiring platform that automates the complete recruitment lifecycle:

* AI Applicant Tracking System (ATS)
* Automated AI Voice Screening Calls
* HR AI Interviews
* Technical AI Interviews
* Machine Test Evaluation
* Salary Negotiation Intelligence
* Offer Letter Automation
* Recruiter Analytics & Paid Access

---

# Project Layout

```bash
zecpath-ai/
│
├── apps/
├── services/
├── ai-engines/
├── workflows/
├── integrations/
├── databases/
├── infrastructure/
├── shared/
├── data/
├── security-compliance/
├── tests/
├── docs/
│
├── docker-compose.yml
├── .env.example
├── README.md
└── package.json
```

---

# Directory Structure

## apps/

Frontend applications.

```bash
apps/
├── recruiter-dashboard/
├── candidate-portal/
├── admin-console/
└── ai-interview-studio/
```

### Modules

* **Recruiter Dashboard**
  Manage jobs, candidates, pipeline, interview reviews, analytics.

* **Candidate Portal**
  Candidate registration, applications, interview scheduling.

* **Admin Console**
  Platform monitoring, compliance controls, subscriptions.

* **AI Interview Studio**
  Browser-based video interview environment.

---

## services/

Core backend microservices.

```bash
services/
├── api-gateway/
├── auth-service/
├── job-service/
├── ats-engine/
├── candidate-eligibility-engine/
├── voice-call-engine/
├── interview-scheduler/
├── notification-service/
├── hr-interview-engine/
├── technical-interview-engine/
├── machine-test-engine/
├── salary-negotiation-engine/
├── offer-automation-engine/
├── scoring-decision-engine/
├── payment-access-service/
└── analytics-service/
```

### Responsibilities

* Candidate lifecycle orchestration
* Resume ranking
* AI screening calls
* Interview automation
* Multi-round scoring
* Offer automation
* Recruiter paid insights

---

## ai-engines/

AI/ML modules.

```bash
ai-engines/
├── resume-nlp/
├── conversational-ai/
├── speech-stack/
├── video-intelligence/
├── question-generation/
├── scoring-models/
└── recommendation-engine/
```

### AI Components

* Resume parsing & skill matching
* Natural AI voice conversations
* STT / TTS pipelines
* Face, eye, and behavior analysis
* Dynamic interview questions
* Recommendation scoring models

---

## workflows/

Workflow orchestration by product phases.

```bash
workflows/
├── phase1-job-foundation/
├── phase2-ats-screening/
├── phase11-video-interviews/
├── phase26-technical-round/
├── phase51-machine-test/
├── phase76-negotiation/
└── phase91-offer-automation/
```

Maps directly to PRD phases 1–100. 

---

## integrations/

External integrations.

```bash
integrations/
├── twilio/
├── aws-connect/
├── openai/
├── google-calendar/
├── outlook/
└── payment-gateway/
```

Includes:

* Voice infrastructure
* Calendar scheduling
* LLM integrations
* Payments

---

## databases/

Data layer.

```bash
databases/
├── postgres/
├── mongodb/
├── redis/
└── vector-db/
```

Stores:

* Candidate records
* Jobs
* Interview data
* Transcripts
* Scoring results
* Audit logs

---

## infrastructure/

Deployment & DevOps.

```bash
infrastructure/
├── docker/
├── kubernetes/
├── terraform/
└── monitoring/
```

Includes:

* Containerization
* Orchestration
* Cloud provisioning
* Logging & observability

---

## shared/

Reusable code and common libraries.

```bash
shared/
├── ui-components/
├── common-libs/
├── prompt-library/
├── schemas/
└── utils/
```

---

## data/

Generated platform data.

```bash
data/
├── resumes/
├── interview-recordings/
├── transcripts/
├── reports/
└── audit-logs/
```

---

## security-compliance/

Security and compliance modules.

```bash
security-compliance/
├── consent-management/
├── encryption/
├── access-control/
└── audit-trails/
```

Supports:

* GDPR-style compliance
* Consent tracking
* Secure storage
* Access logs

---

## tests/

Testing suites.

```bash
tests/
├── unit/
├── integration/
├── workflow/
├── ai-model-tests/
└── load/
```

---

## docs/

Documentation.

```bash
docs/
├── architecture/
├── api-specs/
├── workflows/
└── diagrams/
```

Contains:

* System architecture
* APIs
* Data flows
* Workflow diagrams

---

# Hiring Pipeline Flow

```text
Candidate Applies
   ↓
AI ATS Screening
   ↓
AI Voice Screening
   ↓
HR Interview AI
   ↓
Technical Interview AI
   ↓
Machine Test Evaluation
   ↓
Salary Negotiation AI
   ↓
Offer Automation
```

---

# Tech Stack

## Frontend

* React / Next.js
* TypeScript

## Backend

* Node.js
* Python FastAPI

## AI

* LLM Orchestration
* NLP Models
* Speech AI
* Computer Vision

## Database

* PostgreSQL
* MongoDB
* Redis
* Vector DB

## Infrastructure

* Docker
* Kubernetes
* AWS

(Aligned with PRD recommendations.) 

---

# Local Setup

## Clone Repo

```bash
git clone https://github.com/yourusername/zecpath-ai.git
cd zecpath-ai
```

## Install

```bash
npm install
pip install -r requirements.txt
```

## Start

```bash
docker-compose up
```

---

# Branch Strategy

```bash
main
develop
feature/*
release/*
hotfix/*
```

---

# Product Phases

| Phase Range | Module               |
| ----------- | -------------------- |
| 1–10        | Job Portal + ATS     |
| 11–25       | AI HR Interviews     |
| 26–50       | Technical Interviews |
| 51–75       | Machine Tests        |
| 76–90       | Salary Negotiation   |
| 91–100      | Offer Automation     |

---

# Contributing

```bash
git checkout -b feature/new-module
git commit -m "Add feature"
git push origin feature/new-module
```

Create a Pull Request.

---

# License

Proprietary © Zecpath
