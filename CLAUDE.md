# MSBAi - Online Master of Science in Business Analytics

**Type:** Program Development (Master's Degree Planning)
**Audience:** Faculty, curriculum design team, prospective online students
**Status:** Planning Phase (Q1 2026)

This repository contains curriculum design, learning design, and program development documents for the MSBAi (Master of Science in Business Analytics - Online), a new online degree program launching Fall 2026 or Spring 2027 at Gies College of Business, University of Illinois.

---

## Program Overview

**Name:** Master of Science in Business Analytics - Online (MSBAi)
**Duration:** 16 months (accelerated) or 24 months (standard pace)
**Credit Hours:** 32 credit hours
**Start Term:** Fall 2026 or Spring 2027 (TBD)

**Foundation:** Adapted from the on-campus MSBA program (Fall 2025 cohort) with online-first course design, asynchronous flexibility, and integrated AI capabilities.

---

## Current Focus

> **Phase 1: Curriculum Adaptation** - Redesign 16-week on-campus courses to 8-week online-first format with Python + Jupyter as common thread

**Immediate priorities:**
1. [x] Extract on-campus course structure from MSBA Fall 2025
2. [x] Understand MSBAi online design constraints (8-week, async-first, Python/Jupyter common)
3. [ ] Define TBD courses (AI Analytics Elective, Quantum Computing, Fall 3 flex elective)
4. [ ] Create detailed 8-week course adaptations for all 6 core/elective courses
5. [ ] Design capstone/practicum with portfolio + client project approach

---

## Roadmap

### Phase 1: Curriculum Adaptation (Q1 2026) [IN PROGRESS]
- [ ] Core course documentation
  - [x] BADM 554 (Database Management) - 4 credits
  - [x] BDI 513 (Data Storytelling) - 4 credits
  - [x] BADM 557 (Business Intelligence) - 2-4 credits
  - [x] FIN 550 (Big Data Analytics in Finance) - 4 credits
- [ ] Analyze weekly workload patterns and assessment clusters
- [ ] Document technology stack and tool requirements by course
- [ ] Map prerequisite pathways and skill development
- [ ] Extract reference materials from undergrad-ai (BADM syllabi as elective/foundation models)

### Phase 2: Online Course Design (Q1-Q2 2026)
- [ ] Design asynchronous-first course format
  - [ ] Video lecture strategy and recording plan
  - [ ] Interactive assignments and hands-on labs
  - [ ] Synchronous session strategy (office hours, group projects, review sessions)
- [ ] Create student cohort experience model
  - [ ] Cohort size recommendations
  - [ ] Peer learning opportunities
  - [ ] Networking and community building
- [ ] Design capstone/culminating experience
- [ ] Plan assessment and feedback mechanisms

### Phase 3: Elective & Specialization Design (Q2 2026)
- [ ] Identify high-demand elective areas (created from existing graduate courses)
  - [ ] Advanced Finance & Risk Analytics
  - [ ] Advanced Statistics/Causal Inference
  - [ ] Industry-specific specializations (based on student demand)
- [ ] Design elective course outlines and specialization tracks
- [ ] Determine elective delivery timeline (concurrent or sequential)

### Phase 4: Program Operations (Q2-Q3 2026)
- [ ] Admissions strategy and student profile
- [ ] Cohort scheduling and enrollment targets
- [ ] Faculty and TA staffing model
- [ ] Recruitment and marketing materials
- [ ] Learning management system (Canvas) setup and organization
- [ ] Technology and tool licensing/access

### Phase 5: Launch Preparation (Q3 2026)
- [ ] Course recording and material production
- [ ] Faculty training for online delivery
- [ ] Test run with beta cohort (optional)
- [ ] Final QA and course refinements

### Phase 6: Implementation (Fall 2026 / Spring 2027)
- [ ] Launch first cohort
- [ ] Monitor student experience and engagement
- [ ] Collect feedback and iterate

---

## Key Files & Artifacts

### Program Planning
| File | Purpose |
|------|---------|
| `CORE_COURSES.md` | Detailed analysis of each core course (from msba2025) |
| `COURSE_ADAPTATIONS.md` | Online design decisions for each core course |
| `WORKLOAD_ANALYSIS.md` | Weekly patterns, assessment clusters, pacing |
| `TECHNOLOGY_STACK.md` | Tools, software, and access requirements |
| `ELECTIVES_ROADMAP.md` | Proposed elective courses and specializations |

### Learning Design
| File | Purpose |
|------|---------|
| `COHORT_MODEL.md` | Student cohort experience, community, support |
| `ASSESSMENT_FRAMEWORK.md` | Learning outcomes, rubrics, feedback mechanisms |
| `CAPSTONE_DESIGN.md` | Culminating project/experience for students |

### Program Operations
| File | Purpose |
|------|---------|
| `ADMISSIONS_PROFILE.md` | Target student, prerequisites, recruitment |
| `STAFFING_MODEL.md` | Faculty, TA, and support roles |
| `LMS_STRUCTURE.md` | Canvas course organization and templates |
| `LAUNCH_CHECKLIST.md` | Pre-launch readiness checklist |

### Reference Materials
| Directory | Purpose |
|-----------|---------|
| `reference/msba2025/` | Extracted course details from on-campus program |
| `reference/500plus-courses/` | 500+ level courses for potential reference (analytics, finance) |

---

## Data Sources

### On-Campus Program (Fall 2025)
**Source:** `/Users/vishal/admin/msba2025/`

**Core Courses:**
1. **BADM 554** - Enterprise Database Management (4 credits)
   - Instructor: [TBD]
   - Tech: SQL, MySQL, MongoDB, DataCamp, Knime
   - Assessment: Quizzes, assignments, labs, 2 exams (Test 1, Test 2), 3 mini-projects

2. **BDI 513** - Data Storytelling (4 credits)
   - Instructor: [TBD]
   - Tech: Wolfram Notebooks, Tableau, Python, Bloomberg Terminal, APIs
   - Assessment: Homeworks (H1-H6), presentations, final project (company analysis)

3. **BADM 557** - Business Intelligence (2-4 credits)
   - Instructor: [TBD]
   - Tech: Python (scikit-learn), Tableau, various data sources
   - Assessment: Cases, projects, Python certification requirement, quizzes
   - Enrollment: ~45-50 students (elective)

4. **FIN 550** - Big Data Analytics in Finance (4 credits)
   - Instructor: [TBD]
   - Tech: R, RStudio, ISLR textbook
   - Assessment: Labs (15), problem sets, midterm exam, final project, final exam

**Cohort Size:** ~90 students (all take 3 mandatory courses, ~50% take BADM 557)
**Semester Length:** 16 weeks (Aug 25 - Dec 12, 2025)

**Key Observations from On-Campus Program:**
- Heavy workload weeks: 3-6 (foundations), 15-16 (finals)
- Topic overlaps: Visualization (wks 3-4), regression (wks 5-10), text mining (wks 12-13)
- Assessment clusters: Early Oct (Test 1), late Oct-Nov (midterms + projects), Dec (finals)
- Cross-course portfolio opportunities identified in cross-course-leverage-strategy.md

### Undergraduate AI Curriculum (Reference)
**Source:** `/Users/vishal/admin/undergrad-ai/badm-syllabi/`

**BADM Courses Available (excluding Finance, Accounting, BDI):**
- BADM 210 - Business Analytics I
- BADM 211 - Business Analytics II
- BADM 275 - Fundamentals of Operations Management
- BADM 300 - The Legal Environment of Business
- BADM 310 - Management and Organizational Behavior
- BADM 320 - Principles of Marketing
- BADM 350 - Technology and AI Strategy
- BADM 449 - Business Policy and Strategy

**Use Case:** Map these syllabi to potential graduate electives and foundational modules

---

## Design Principles for MSBAi

1. **Asynchronous-First:** Students in diverse time zones; core content accessible 24/7
2. **Cohort Cohesion:** Regular synchronous touchpoints (weekly office hours, monthly webinars)
3. **Hands-On Learning:** Labs, projects, and real data (same rigor as on-campus)
4. **Flexible Pacing:** Support both accelerated (16 months) and standard (24 months) pathways
5. **AI-Native:** Integrate AI tools and prompt engineering across curriculum
6. **Professional Networks:** Career services, alumni community, industry guest speakers
7. **Accessible:** Support working professionals with jobs, families, diverse backgrounds

---

## Session Log

### 2026-01-12 - Program Initiation & Curriculum Structure Finalization
- **Completed (Session 1):**
  - Created msba-online folder structure
  - Extracted core course data from msba2025 (16-week structure, workload patterns)
  - Created CORE_COURSES.md and WORKLOAD_ANALYSIS.md

- **Completed (Session 2 - Today):**
  - ✅ Identified correct BADM 557 variant (Subramanyam BI version, not Bahrini)
  - ✅ Extracted Subramanyam 557 syllabi to JSON (sp25 & fa25)
  - ✅ Extracted learning objectives/topics for BADM 558, 576
  - ✅ **Understood online design constraints:**
    - **8-week format** (vs. 16 weeks on-campus) = 50% time compression
    - **Python + Jupyter** as common thread across ALL courses
    - **Asynchronous-first** design (no synchronous exams typically)
    - **Project-based assessment** (replace exams with continuous projects)
  - ✅ Created ONLINE_CURRICULUM_STRUCTURE.md with full program timeline, TBD identification

- **Identified TBD Courses:**
  - **Spring 1:** AI Analytics Elective (2 credits) - content spec needed
  - **Spring 1:** Quantum Computing (2 credits) - course rubric needed
  - **Fall 3:** Analytics or General Elective (4 credits) - required vs. flexible?

- **Next:**
  - [ ] Define TBD course specs (AI elective focus, Quantum content, Fall 3 elective)
  - [ ] Create COURSE_ADAPTATIONS.md (8-week specs for 554, 513, 550, 557, 558, 576)
  - [ ] Design ELECTIVES_ROADMAP.md (specialization tracks, stackable certificates)
  - [ ] Create COHORT_MODEL.md (sync touchpoints, office hours, community)

---

## Quick Navigation

```bash
# Start working on MSBAi
cd msba-online

# Reference the on-campus program
cd ../msba2025

# Reference undergraduate syllabi
cd ../undergrad-ai/badm-syllabi
```

---

*Last Updated: January 12, 2026*
