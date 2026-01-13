# MSBAi Electives Roadmap

**Version:** 1.0
**Last Updated:** January 12, 2026
**Status:** Ready for faculty course development

---

## Document Purpose

This document specifies the TBD elective courses and industry-specific specialization tracks for MSBAi. It addresses:

1. **New Electives to Create:**
   - Generative AI for Analytics (2 credits, Spring 1)
   - Quantum Computing for Optimization (2 credits, Spring 1, optional)
   - Fall 3 flexible elective (4 credits, TBD)

2. **Industry Specialization Tracks:**
   - Finance Analytics
   - Healthcare Analytics
   - Technology/Marketing Analytics
   - Supply Chain & Operations Analytics

3. **Stackable Certificate Programs:**
   - Core Analytics Certificate (12 months, 12 credits)
   - AI Analytics Certificate (18 months, 18 credits)
   - Full Master's Degree (24-36 months, 36 credits)

---

## Part 1: New Elective Courses

### Elective 1: Generative AI for Analytics (BADM 5XX or MSBAi550A)

**Credits:** 2 | **Term:** Spring 1 (Weeks 17-24, concurrent with BADM 557) | **Status:** ✅ Ready for design

#### Course Vision

Students master generative AI tools (Claude, ChatGPT, Copilot) applied to analytics workflows. Focus on prompt engineering, AI-augmented analysis, ethical use, and prompt engineering for data science. By course end, students are expert AI tool users who can dramatically accelerate their analytical work.

#### Learning Outcomes (L-C-E Framework)

**Literacy:**
- L1: Explain how large language models work (transformer architecture, token prediction)
- L2: Understand different AI tools and their strengths (Claude for analysis, ChatGPT for code, etc.)
- L3: Recognize limitations, biases, and ethical issues in AI

**Competency:**
- C1: Write effective prompts for data analysis, code generation, and report writing
- C2: Use AI to accelerate SQL query writing, Python code generation, and troubleshooting
- C3: Apply AI to feature engineering, model interpretation, and statistical analysis
- C4: Audit AI outputs for accuracy, bias, and ethical concerns

**Expertise:**
- E1: Design AI-augmented workflows that combine human judgment with AI capabilities
- E2: Fine-tune AI use (when to trust AI vs. verify manually)
- E3: Build custom prompts and systems for domain-specific analytics problems

#### Week-by-Week Breakdown

| Week | Topic | Activities | Projects | Assessment |
|------|-------|-----------|----------|------------|
| **17** | LLM fundamentals + prompt engineering 101 | Lectures (2 videos), interactive prompts | Hands-on: Write prompts for 5 analytics tasks | Prompt evaluation |
| **18** | AI for SQL + data exploration | Live demos of Claude/ChatGPT for SQL | Write 10+ SQL queries with AI assist | Code quality review |
| **19** | AI for Python code generation + debugging | Live demos of code generation + fixing errors | Generate project code using AI | Code review + efficiency |
| **20** | AI for feature engineering + ML workflows | Feature ideation with AI, prompt engineering | Feature engineering ideas + implementation | Feature analysis |
| **21** | AI for data storytelling + communication | Writing narratives with AI, editing | Create analysis report with AI assist | Writing quality |
| **22** | AI for statistics + model interpretation | Explaining statistical concepts with AI | Interpret model results using AI | Interpretation quality |
| **23** | Ethics, bias, and responsible AI use | Case studies of AI failures, bias audits | Audit AI outputs for bias + risks | Bias analysis |
| **24** | Capstone: Building AI-augmented systems | Design your own AI+human workflow | Create reusable prompt templates | Portfolio + presentation |

#### Projects (2 major)

**Project 1: AI Workflow Comparison (Weeks 17-20, Individual, 40% of grade)**
- **Task:** Complete a complex analytics task (e.g., build a classifier) both manually and with AI assist
- **Deliverables:**
  - Traditional approach: Code written from scratch, time logged
  - AI-assisted approach: Using Claude/ChatGPT, time logged
  - Comparison: Time saved, code quality, errors found
  - Write-up: When to use AI, when manual work is better
  - GitHub repo with both approaches

**Project 2: Capstone AI System (Weeks 21-24, Individual, 50% of grade)**
- **Task:** Design a reusable AI-augmented workflow for your domain
- **Deliverables:**
  - Prompt library (10+ prompts for common tasks)
  - Workflow documentation (how to use AI effectively)
  - Case study: Apply system to real problem
  - Ethics checklist: How to audit AI outputs
  - GitHub repo with prompt templates + examples

#### Rubric (5 dimensions)

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Prompt Quality** | Well-crafted, effective, reusable | Functional, some refinement needed | Generic or ineffective |
| **Critical Thinking** | Evaluates AI strengths/weaknesses | Uses AI appropriately | Accepts AI outputs uncritically |
| **Ethical Awareness** | Identifies bias, documents limitations | Mentions ethics | Ignores ethical concerns |
| **Code Quality** | AI-assisted code is production-ready | Functional with minor issues | AI code has problems |
| **Documentation** | Clear system design, reusable templates | Adequate documentation | Minimal documentation |

#### Technology Stack
- **AI Tools:** Claude (API + web), ChatGPT (Plus or API), GitHub Copilot
- **Environment:** Jupyter Notebooks with AI integration
- **Tools:** LangChain (optional, for chaining AI calls)

#### Prerequisites
- Completion of at least 2 core MSBAi courses (familiarity with analytics workflow)

---

### Elective 2: Quantum Computing for Optimization (BADM 5XX or MSBAi510Q)

**Credits:** 2 | **Term:** Spring 1 (Weeks 17-24, concurrent with BADM 557) | **Status:** ⚠️ Curriculum TBD

#### Course Vision

Students explore quantum computing fundamentals and applications to business optimization problems. Focus on practical understanding: when quantum helps, current limitations, and how to prepare for quantum era. NOT a deep math course—business-focused exploration.

#### Learning Outcomes (L-C-E Framework)

**Literacy:**
- L1: Explain quantum computing basics (qubits, superposition, entanglement) in plain language
- L2: Understand when quantum computing might help vs. classical computing
- L3: Recognize hype vs. realistic quantum applications

**Competency:**
- C1: Use quantum simulators to explore quantum algorithms
- C2: Identify optimization problems that quantum might solve (portfolio optimization, supply chain, scheduling)
- C3: Assess quantum readiness and limitations for your domain

**Expertise:**
- E1: Design a quantum-classical hybrid approach to a real business problem
- E2: Evaluate quantum hardware progress and timeline to practical applications

#### Week-by-Week Breakdown (Preliminary)

| Week | Topic | Activities | Projects |
|------|-------|-----------|----------|
| **17** | Quantum fundamentals (non-technical) | Lectures + interactive simulators | Understand qubits + superposition |
| **18** | Quantum algorithms overview | VQE, QAOA, Grover's explained simply | Implement simple algorithm |
| **19** | Optimization problems + quantum advantage | When quantum helps (TSP, portfolio, scheduling) | Map your domain problems |
| **20** | Portfolio optimization case study | Real-world example: optimize financial portfolio | Quantum vs. classical comparison |
| **21** | Quantum simulators hands-on | Use IBM Qiskit or Azure Quantum | Run algorithms on simulator |
| **22** | Quantum hardware + future roadmap | Current limitations, timeline to useful quantum | Assess readiness for production |
| **23** | Hybrid quantum-classical approaches | Combining quantum + classical for practical gain | Design hybrid system |
| **24** | Capstone: Your quantum opportunity | Identify real problem + propose quantum approach | Presentation + business case |

#### Projects (1-2)

**Project: Quantum Opportunity Analysis (Weeks 17-24, Individual, 100%)**
- **Task:** Identify a real business optimization problem + evaluate quantum computing potential
- **Deliverables:**
  - Problem definition + classical solution approach
  - Quantum computing feasibility analysis
  - Timeline to practical quantum solution (honest assessment)
  - Business case (when quantum becomes cost-effective)
  - GitHub repo with simulator exploration code

#### Status & Decisions Needed

**Critical Decisions Before Finalization:**

1. **Instructor:** Do we have faculty with quantum expertise? Or partner with quantum computing company/university?
2. **Depth vs. Breadth:** Mathematical depth (Qiskit, circuit design) vs. business focus (when quantum helps)?
3. **Platforms:** Use IBM Qiskit, Azure Quantum, D-Wave, or other?
4. **Real Hardware:** Provide access to real quantum computers (IBM, AWS)?

**Recommendation:** Start with **business-focused, simulator-based approach** in Year 1. As quantum hardware matures (2026-2028), evolve to real quantum experiments.

---

### Elective 3: Fall 3 Flexible Elective (4 credits)

**Options:**

#### Option A: Data Engineering Specialization (BADM 5XX)
- **Focus:** Building production data systems at scale
- **Topics:** Airflow, dbt, Kubernetes, real-time streaming (Kafka), data quality frameworks
- **Prerequisite:** BADM 558
- **Project:** Build end-to-end data platform for real business problem

#### Option B: Advanced Machine Learning Systems (BADM 5XX)
- **Focus:** Production ML systems, MLOps, A/B testing, feature stores
- **Topics:** ML monitoring, data drift, model retraining, feature engineering at scale
- **Prerequisite:** BADM 576
- **Project:** Deploy ML system with monitoring + A/B test framework

#### Option C: AI Strategy & Leadership (BADM 5XX)
- **Focus:** Strategy, governance, ethical implications of AI/analytics
- **Topics:** AI strategy, governance frameworks, bias & fairness, regulations (GDPR, etc.)
- **No prerequisites**
- **Project:** Develop AI strategy for a real company

#### Option D: Industry-Specific Deep-Dive (Rotating)
- **Rotating electives** based on faculty expertise + student demand:
  - Financial Risk Analytics (VaR, stress testing, portfolio theory)
  - Healthcare Analytics (patient stratification, clinical outcomes, privacy)
  - Marketing Analytics (customer LTV, attribution, personalization)
  - Supply Chain Analytics (demand forecasting, optimization, resilience)

**Recommendation:** Offer **Option A (Data Engineering)** in Year 1 as complement to BADM 558, then add others based on student demand and faculty availability.

---

## Part 2: Industry Specialization Tracks

Students can tailor their elective selections to focus on specific industries. Three example tracks below.

### Track 1: Finance Analytics Specialization

**Goal:** Prepare students for roles in investment management, trading, risk management, financial institutions.

**Core Courses (12 credits, required):**
- BADM 554: Data Foundations
- BDI 513: Data Storytelling
- FIN 550: Analytics for Business
- (One more from core + BADM 557 or 558 or 576)

**Specialization Electives (12 credits, choose 3 of 4):**
- **BADM 557:** Business Intelligence with AI (case studies with financial data)
- **BADM 576:** Data Science & ML (time series, prediction)
- **Fintech Elective:** Blockchain analytics, algorithmic trading, robo-advisors (Option D rotation)
- **Risk Analytics Elective:** VaR, stress testing, portfolio optimization (Option D rotation)

**Capstone:** Finance-specific project (e.g., build trading algorithm, portfolio optimizer, risk dashboard)

**Career Outcomes:** Quantitative Analyst, Risk Manager, Financial Data Scientist, Investment Analyst

### Track 2: Healthcare Analytics Specialization

**Goal:** Prepare students for roles in healthcare systems, biotech, pharmaceuticals, health tech.

**Core Courses (12 credits):**
- BADM 554: Data Foundations
- BDI 513: Data Storytelling
- FIN 550: Analytics for Business (with healthcare datasets)
- One more core

**Specialization Electives (12 credits):**
- **BADM 557:** Business Intelligence (hospital operational dashboards)
- **BADM 576:** Data Science & ML (patient outcomes prediction, clinical trials)
- **Healthcare Analytics Elective:** Patient segmentation, EHR data, health economics (Option D rotation)
- **Clinical Informatics Elective:** Privacy (HIPAA), data quality in healthcare systems (Option D rotation)

**Capstone:** Healthcare project (patient stratification, readmission prediction, hospital efficiency optimization)

**Career Outcomes:** Clinical Data Scientist, Health Informaticist, Epidemiologist, Hospital Analytics Manager

### Track 3: Technology & Marketing Analytics Specialization

**Goal:** Prepare students for roles in tech companies, marketing analytics, product management, consumer insights.

**Core Courses (12 credits):**
- BADM 554: Data Foundations
- BDI 513: Data Storytelling
- FIN 550: Analytics for Business
- One more core

**Specialization Electives (12 credits):**
- **BADM 557:** Business Intelligence (marketing dashboards, A/B testing)
- **BADM 558:** Big Data Infrastructure (event tracking at scale, real-time analytics)
- **Marketing Analytics Elective:** Customer LTV, attribution modeling, personalization (Option D rotation)
- **Product Analytics Elective:** Funnel analysis, cohort analysis, growth metrics (Option D rotation)

**Capstone:** Tech company project (growth analysis, user segmentation, product feature impact)

**Career Outcomes:** Marketing Data Scientist, Product Analyst, Growth Analyst, Analytics Manager at Tech Company

---

## Part 3: Stackable Certification Pathways

### Pathway 1: Core Analytics Certificate (12 months, 12 credits)

**For:** Professionals seeking foundational analytics skills + immediate employment

**Courses:**
- BADM 554: Data Foundations (4cr)
- BDI 513: Data Storytelling (4cr)
- FIN 550: Analytics for Business (4cr)

**Duration:** Fall 1 + Fall 2 (8 months) + optional Spring 1 (4 months)

**Career Outcomes:** Data Analyst, Business Analyst, Analytics Associate

**Stackable:** Can continue to AI Analytics Certificate or Full Master's

---

### Pathway 2: AI Analytics Certificate (18 months, 18 credits)

**For:** Professionals seeking AI/ML specialization with job-ready portfolio

**Courses:**
- Core Analytics Certificate (12cr)
  - BADM 554
  - BDI 513
  - FIN 550
- AI/ML Specialization (6cr)
  - BADM 576: Data Science & ML (4cr)
  - Generative AI for Analytics (2cr)

**Duration:** Fall 1 + Fall 2 + Spring 1 (16 months)

**Career Outcomes:** Machine Learning Engineer, AI Specialist, Data Scientist (junior to mid-level)

**Stackable:** Can complete to Full Master's with 18 more credits

---

### Pathway 3: Full Master's Degree (24-36 months, 36 credits)

**For:** Comprehensive preparation for advanced data/analytics leadership roles

**Structure:**
- Core Analytics (12cr)
- Advanced Analytics (8cr): BADM 557, 558, 576
- Specialization/Electives (12cr): Industry track + flexible courses
- Capstone (4cr)

**Duration:** Full academic year + 2-3 more semesters

**Career Outcomes:** Analytics Manager, Data Science Manager, Chief Data Officer, Analytics Director

---

## Part 4: Elective Offering Schedule

### Recommended Offering (Years 1-2)

**Spring 1 2027 (Weeks 17-24):**
- ✅ BADM 557: Business Intelligence with AI (4cr, required)
- ✅ Generative AI for Analytics (2cr, new elective)
- ⚠️ Quantum Computing (2cr, optional/experimental)

**Spring 2 2027 (Weeks 25-32):**
- ✅ BADM 558: Big Data Infrastructure (4cr, required)

**Summer 2027 (Weeks 33-40):**
- ✅ BADM 576: Data Science & ML (4cr, required)

**Fall 3 2027 (Weeks 41-48):**
- **Option A (Recommended):** Data Engineering Specialization (4cr, new)
- OR student choice of industry track elective (4cr)

**Spring 1 2028 (Cohort 2):**
- Add 1-2 Option D (industry-specific) electives based on Cohort 1 demand + faculty availability

---

## Part 5: Faculty & Development Notes

### Courses Ready for Development:
1. ✅ **Generative AI for Analytics** — Design doc complete, can start immediately
2. ⚠️ **Quantum Computing** — Needs curriculum decision + instructor identification
3. ⏳ **Data Engineering Specialization** — Needs faculty assignment + curriculum design
4. ⏳ **Industry-Specific Electives** — Will develop based on pilot cohort feedback

### Resourcing:
- **New Elective Courses:** Each needs instructional designer + 1-2 weeks faculty time (Spring 2026)
- **Industry Tracks:** Minimal additional work; primarily curriculum mapping of existing courses
- **Specialization Certificates:** Marketing + registrar setup (minimal development)

### Faculty Skill Requirements:
- **Generative AI for Analytics:** Any data/tech faculty + AI tool experience (can be learned alongside course development)
- **Quantum Computing:** Ideally physics/quantum expert OR partner with external provider
- **Data Engineering:** Senior software engineer or data engineer with production experience
- **Industry Electives:** Subject-matter experts in respective domains (Finance, Healthcare, Marketing, etc.)

---

## Implementation Timeline

**Phase 1 (Jan-Mar 2026):** Finalize Generative AI curriculum + assign instructor
**Phase 2 (Mar-May 2026):** Develop Generative AI course materials (Jupyter Books, videos, projects)
**Phase 3 (Apr-Jun 2026):** Decide on Quantum Computing approach + recruit instructor (if pursuing)
**Phase 4 (May-Jul 2026):** Design Data Engineering specialization + map industry tracks
**Phase 5 (Aug 2026+):** Teach Cohort 1, gather feedback, iterate on electives for Cohort 2

---

## Appendix: Sample Elective Course Syllabus Template

(Use COURSE_ADAPTATIONS.md structure for each new elective: 8-week format, 3 projects, learning outcomes, AI integration, studio sessions, assessment rubric)

---

*Document prepared: January 12, 2026*
*Status: Ready for faculty course development + curriculum decisions on Quantum Computing + industry tracks*
