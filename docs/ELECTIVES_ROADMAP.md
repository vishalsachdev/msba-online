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

**Credits:** 2 | **Term:** Spring 2027 (Weeks 1-4, concurrent with BADM 558) | **Status:** ✅ Ready for design

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
| **1** | LLM fundamentals + prompt engineering + AI for SQL | Lectures, interactive prompts, SQL demos | Write prompts for analytics tasks + SQL queries | Prompt & code evaluation |
| **2** | AI for Python code generation + feature engineering | Live demos of code generation, debugging, ML workflows | Generate project code + feature engineering | Code quality + efficiency |
| **3** | AI for data storytelling + statistics + model interpretation | Writing narratives, explaining statistical concepts | Analysis report + model interpretation | Writing + interpretation quality |
| **4** | Ethics, bias, responsible AI + Capstone project | Case studies, bias audits, design AI workflow | Create reusable prompt library + ethics checklist | Portfolio + presentation |

#### Projects (2 major)

**Project 1: AI Workflow Comparison (Weeks 1-2, Individual, 40% of grade)**
- **Task:** Complete a complex analytics task (e.g., build a classifier) both manually and with AI assist
- **Deliverables:**
  - Traditional approach: Code written from scratch, time logged
  - AI-assisted approach: Using Claude/ChatGPT, time logged
  - Comparison: Time saved, code quality, errors found
  - Write-up: When to use AI, when manual work is better
  - GitHub repo with both approaches

**Project 2: Capstone AI System (Weeks 3-4, Individual, 50% of grade)**
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

**Credits:** 2 | **Term:** Spring 2027 (Weeks 9-12, Spring 2 half) | **Instructor:** Abhijeet | **Status:** ✅ Curriculum Ready

#### Course Vision

**"Quantum Computing: Applications for Decision Making"** prepares business analytics students to understand and apply quantum computing to optimization and decision problems. This course emphasizes practical skills using Python/Qiskit simulators, focusing on when and how quantum methods improve business decisions. Students will build foundational quantum computing literacy while developing hands-on skills to identify quantum opportunities in their domains.

**Why This Course Matters:** Companies like Chase, Goldman Sachs, pharmaceutical firms, Shell, and Walmart are already assessing quantum integration. The biggest obstacle is the lack of business graduates who understand how to convert traditional decision problems into quantum-solvable problems. This course addresses that gap.

#### Prerequisites

**Required Knowledge (Pre-Course Self-Study):**
- Basic linear algebra (vectors, matrices, eigenvalues, eigenvectors)
- Trigonometry (sine, cosine, tangent, identities)
- Complex numbers (x + iy, De-Moivre's theorem)
- Python programming basics (Jupyter Notebooks)

**Pre-Course Assessment:** Students take a diagnostic quiz to verify comfort level with prerequisites.

#### Learning Outcomes (L-C-E Framework)

**Literacy:**
- L1: Explain quantum computing fundamentals (qubits, superposition, entanglement, unitary matrices) in business contexts
- L2: Understand quantum algorithms (Deutsch-Jozsa, Grover, Shor, QAOA, VQE) and their applications
- L3: Distinguish quantum advantage vs. hype for real-world business problems
- L4: Recognize when quantum computing can outperform classical methods

**Competency:**
- C1: Program quantum algorithms using IBM Qiskit in Python/Jupyter
- C2: Implement quantum optimization algorithms (QAOA, VQE) for business problems
- C3: Run quantum simulations and interpret results
- C4: Compare quantum vs. classical solution performance
- C5: Use quantum circuit diagrams to design algorithms

**Expertise:**
- E1: Identify business optimization problems suitable for quantum approaches
- E2: Design quantum-classical hybrid solutions for real decision problems
- E3: Evaluate quantum hardware readiness and timeline to production
- E4: Build business cases for quantum computing investments
- E5: Communicate quantum opportunities to non-technical stakeholders

#### Week-by-Week Breakdown

| Week | Topic | Learning Activities | Hands-On Labs | Deliverables |
|------|-------|---------------------|---------------|--------------|
| **1** | **Quantum Foundations + Algorithms** | Qubits, superposition, entanglement, unitary matrices, eigenvalues; Postulates of QM; Quantum circuits; Deutsch, Deutsch-Jozsa, Grover, Shor algorithms | Lab 1: Qiskit setup, run first quantum program; Lab 2: Implement basic algorithms | Project Milestone 1: Problem identification + classical baseline |
| **2** | **Optimization with Quantum** | Simple optimization problems; QAOA fundamentals; Max-cut problem; Applications in business domains | Lab 3: QAOA for Max-cut; Lab 4: Apply QAOA to business problem | Project Milestone 2: Quantum solution design + feasibility analysis |
| **3** | **VQE + Advanced Applications** | Variational Quantum Eigensolver (VQE); Applications in finance, supply chain, scheduling; Quantum hardware landscape | Lab 5: VQE implementation; Lab 6: Run simulations + performance comparison | Project Milestone 3: Implementation + quantum vs. classical comparison |
| **4** | **Quantum Readiness + Business Cases** | Quantum-classical hybrid systems; Timeline to production quantum; Building business cases; Industry adoption patterns | Lab 7: Hybrid approach design; Final Project: Business case presentation | Final Deliverable: Quantum Opportunity Portfolio |

#### Textbooks & Resources

**Required:**
- *Quantum Information: A First Course* by Asma Al-Qasimi and Daniel F. V. James (Cambridge University Press)

**Highly Recommended:**
- *Quantum Computation and Quantum Information* by Michael A. Nielsen and Isaac L. Chuang

**Other Recommended:**
- *Quantum Mechanics* by David Griffiths (for deeper mathematical foundations)

**Software:**
- IBM Qiskit (Python package) - primary platform
- Access to IBM Quantum simulators (guaranteed)
- Limited access to IBM Quantum hardware (not guaranteed, but available for exploration)

#### Assessment & Projects

**Project-Based Assessment (No Exams):**

**Continuous Labs (40% of grade):**
- 7 weekly hands-on labs using Qiskit
- Each lab: Implement quantum algorithms, run simulations, document findings
- Submit as Jupyter Notebooks with code + business interpretation
- Graded on: correctness, code quality, business insight

**Final Project: Quantum Opportunity Portfolio (60% of grade):**

**Task:** Identify a business optimization problem from your domain (or assigned domain) and develop a quantum computing solution strategy.

**Deliverables:**
1. **Problem Definition (Week 1):**
   - Business context + classical solution approach
   - Complexity analysis + computational bottlenecks
   - Why quantum might help

2. **Quantum Solution Design (Week 2):**
   - Quantum algorithm selection (QAOA, VQE, or hybrid)
   - Circuit design + implementation plan
   - Feasibility analysis

3. **Implementation + Comparison (Week 3):**
   - Qiskit implementation (simulator)
   - Quantum vs. classical performance comparison
   - Results visualization + interpretation
   - GitHub repo with documented code

4. **Business Case (Week 4):**
   - When quantum becomes cost-effective (timeline)
   - Hardware requirements + vendor options
   - ROI analysis + risk assessment
   - Executive summary (2-page memo)
   - 10-minute video presentation

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Technical Accuracy** | Quantum implementation correct, well-documented | Implementation functional with minor issues | Significant technical errors |
| **Business Insight** | Clear ROI, realistic timeline, actionable recommendations | Business case present but lacks depth | Weak business justification |
| **Code Quality** | Clean, well-commented Qiskit code in Jupyter Notebooks | Functional code, adequate documentation | Code difficult to understand or run |
| **Quantum vs. Classical Comparison** | Rigorous performance analysis with clear metrics | Basic comparison with some metrics | Incomplete or unfair comparison |
| **Communication** | Executive summary is clear, concise, persuasive | Adequate but lacks clarity or structure | Poor communication of findings |

#### Technology Stack

- **Programming:** Python 3.9+ with Jupyter Notebooks
- **Quantum Framework:** IBM Qiskit
- **Simulators:** Qiskit Aer (local), IBM Quantum simulators (cloud)
- **Hardware Access:** IBM Quantum (limited, not guaranteed)
- **Version Control:** GitHub (for project submission)
- **Visualization:** Matplotlib, Qiskit visualization tools

#### Why This Course Matters for Your Career

**Quantitative Foundation:**
- Quantum computing heavily uses linear algebra, which carries over to ML, statistics, and optimization
- Builds confidence in mathematical reasoning for business analytics

**Rare Market Skills:**
- Few business graduates understand quantum computing applications
- Demand for quantum-literate business professionals is growing faster than supply
- Companies are actively seeking talent who can bridge quantum computing and business strategy

**Transferable Skills:**
- Algorithm thinking (Qiskit) enhances Python/ML skills
- Optimization mindset applies to classical problems too
- Strategic thinking about emerging technologies

#### Course Philosophy

**Hands-On First:** Almost every week includes labs. You learn by doing, not just theory.

**Business Context Always:** Every quantum concept is tied to business applications (portfolio optimization, supply chain, scheduling, etc.).

**Realistic Expectations:** We balance quantum potential with honest assessment of current limitations and timelines.

**Python/Jupyter Native:** Aligns with MSBAi's common computational thread across all courses.

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
- **BADM 557:** Decision Intelligence with AI (case studies with financial data)
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

**Spring 1 2027 (Spring 2027, Weeks 1-8):**
- ✅ BADM 558: Big Data Infrastructure (4cr, required, weeks 1-8)
- ✅ Generative AI for Analytics (2cr, new elective, weeks 1-4)

**Spring 2 2027 (Spring 2027, Weeks 9-16):**
- ⚠️ Quantum Computing (2cr, optional/experimental, weeks 9-12)

**Summer 2027 (Summer 2027, Weeks 1-8):**
- ✅ BADM 557: Decision Intelligence with AI (4cr, required)

**Fall 1 2027 (Fall 2027, Weeks 1-8):**
- ✅ BADM 576: Data Science & ML (4cr, required)

**Fall 2 2027 (Fall 2027, Weeks 9-16):**
- **Specialization Elective** (4cr) — Finance, Healthcare, Marketing, or Data Engineering track

**Spring 1 2028 (Cohort 2):**
- Add 1-2 Option D (industry-specific) electives based on Cohort 1 demand + faculty availability

---

## Part 5: Faculty & Development Notes

### Courses Ready for Development:
1. ✅ **Generative AI for Analytics** — Design doc complete, can start immediately
2. ✅ **Quantum Computing** — Curriculum complete (Abhijeet), ready for course material development
3. ⏳ **Data Engineering Specialization** — Needs faculty assignment + curriculum design
4. ⏳ **Industry-Specific Electives** — Will develop based on pilot cohort feedback

### Resourcing:
- **New Elective Courses:** Each needs instructional designer + 1-2 weeks faculty time (Spring 2026)
- **Industry Tracks:** Minimal additional work; primarily curriculum mapping of existing courses
- **Specialization Certificates:** Marketing + registrar setup (minimal development)

### Faculty Skill Requirements:
- **Generative AI for Analytics:** Any data/tech faculty + AI tool experience (can be learned alongside course development)
- **Quantum Computing:** ✅ Abhijeet confirmed — quantum computing + business optimization expertise
- **Data Engineering:** Senior software engineer or data engineer with production experience
- **Industry Electives:** Subject-matter experts in respective domains (Finance, Healthcare, Marketing, etc.)

---

## Implementation Timeline

**Phase 1 (Jan-Mar 2026):** Finalize Generative AI curriculum + Quantum Computing curriculum (✅ Complete)
**Phase 2 (Mar-May 2026):** Develop course materials for both electives (Jupyter Books, videos, labs, projects)
**Phase 3 (May-Jul 2026):** Design Data Engineering specialization + map industry tracks
**Phase 4 (Jul-Aug 2026):** Pilot test Quantum Computing labs + Qiskit environment setup
**Phase 5 (Aug 2026+):** Teach Cohort 1, gather feedback, iterate on electives for Cohort 2

---

## Appendix: Sample Elective Course Syllabus Template

(Use COURSE_ADAPTATIONS.md structure for each new elective: 8-week format, 3 projects, learning outcomes, AI integration, studio sessions, assessment rubric)

---

*Document prepared: January 12, 2026*
*Status: Ready for faculty course development + curriculum decisions on Quantum Computing + industry tracks*
