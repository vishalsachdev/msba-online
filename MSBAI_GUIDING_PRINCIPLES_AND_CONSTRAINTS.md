# MSBAi: Guiding Principles & Constraints

**Version:** 1.0  
**Last Updated:** January 12, 2026  
**Status:** Finalized for implementation planning

---

## Core Guiding Principles

### 1. **AI-First, Not AI-Optional**
- Every MSBAi course integrates practical AI tool usage
- AI is treated as a *productivity accelerator*, not theoretical topic
- Students graduate with hands-on LLM experience + prompt engineering skills
- "AI tools" (generic term: ChatGPT, Claude, Copilot, open-source models, etc.) are standard part of analytical workflow
- AI literacy → competency → expertise progression across all courses

### 2. **Projects Are the Primary Learning Vehicle**
- **Integral to design:** 2-3 major projects per 8-week course (not optional extras)
- **Live project sessions:** Separate, branded tutorial sessions dedicated to:
  - Hands-on project work (guided problem-solving)
  - Tool showcasing (Tableau, SQL, AWS, etc.)
  - AI-augmented analysis demos (how AI accelerates work)
  - Q&A and debugging support
  - **Key differentiator from competitors**
- **Portfolio-driven:** All projects contribute to GitHub portfolio
- **Real data:** Projects use public datasets, case studies, or simulated business problems
- **Authentic assessment:** No traditional exams; grading based on project quality

### 3. **Python + Jupyter Notebooks as Universal Backbone**
- **Common computational environment:** All students work in Jupyter (Colab or cloud-hosted)
- **Reproducibility:** Code + narrative + visualizations in single document
- **Career asset:** Portfolio of Jupyter notebooks demonstrates skills to employers
- **Flexibility:** Supplementary tools allowed (Tableau, AWS, R, etc.) but Python is primary
- **GitHub integration:** All project repos hosted on GitHub (version control habit-building)

### 4. **Synchronous Live Sessions for High Engagement** (Differentiator)
- **Project tutorial sessions:** Weekly guided project work (not lectures)
  - Real-time demonstration of tools + AI-assisted workflows
  - Student Q&A and live debugging
  - Showcase best practices + common pitfalls
- **High-engagement discussions:** Monthly or bi-weekly topics (current events, case studies)
  - Bring in practitioners, guest speakers, industry insights
  - Student-led discussions (builds communication skills)
- **Office hours:** 1-on-1 or small group mentoring
- **Brand these distinctly:** "Studio Sessions" (project-focused), "Analytics Conversations" (discussions), "Office Hours" (support)
- **Async-first, sync-supplementary:** All sessions recorded; attendance optional for flexibility

### 5. **Stackable, Modular Pathways**
- **No single "right path":** Students choose based on career goals
- **Three primary pathways:**
  1. **Core Analytics Certificate** (12 months, 12 credits) — Foundation + finance
  2. **AI Analytics Certificate** (18 months, 18 credits) — AI-focused specialization
  3. **Industry Specialization** (24 months, 36 credits) — Custom tracks (Finance, Marketing, Supply Chain, Healthcare)
- **Coherent progression:** Each pathway has clear learning objectives and career outcomes
- **Exit points:** Students can complete certificate and apply for jobs, then re-enroll

### 6. **Affordability & Accessibility**
- **Target:** 20% cheaper than peer programs (UT Austin, Penn State, Michigan)
- **Flexible scheduling:** 8-week courses allow working professionals to take 1-2 courses while employed
- **Global accessibility:** No time zone requirement; all async content available 24/7
- **Diverse learners:** Support for non-traditional backgrounds (career changers, underrepresented groups)

### 7. **Applied Experiential Learning**
- **Real capstones:** Research Park partnerships + corporate consulting projects (Recommended in Fall 4)
- **Alternative capstone:** Independent research with real business impact
- **Portfolio + Project:** Capstone split into portfolio curation (weeks 1-2) + new project (weeks 3-8)
- **Public artifact:** Final portfolio published on personal GitHub/website (career visibility)

### 8. **Coherent Course Naming & Rubrics**
- **Naming convention:** Use "MSBAi" prefix or thematic titles
  - Option A: MSBAi554, MSBAi513, etc. (emphasizes program cohesion)
  - Option B: Thematic names (Data Foundations, Data Storytelling, Analytics for Business, etc.)
- **Consistent learning outcome structure:** All courses use L-C-E (Literacy → Competency → Expertise)
- **Clear prerequisites:** First core (554, 513, 550) have no prerequisites; electives assume core completion

### 9. **Version Control & Reproducibility**
- **GitHub as default:** All student code lives on GitHub
- **Best practice teaching:** Students learn version control as part of course workflow
- **Public portfolios:** Final projects have public GitHub repos (career visibility)
- **Reproducibility:** README files, requirements.txt, documentation standards enforced

### 10. **Alignment with Gies Campus AI Framework**
- **Four campus tracks:** MSBAi courses contribute to official Campus AI curriculum
  - AI Basics/Fundamentals ← Core courses
  - AI & ML Technologies ← Electives (557, 558, 576, GenAI elective)
  - Agentic Systems & Workflows ← Advanced electives + capstone
  - Human-Centric AI ← Ethics woven throughout
- **Credential pathway:** MSBAi students can earn Campus AI certificates alongside MSBAi degree

---

## Hard Constraints (Non-Negotiable)

### Curricular Constraints
1. **Total program:** 36 credits (fixed)
2. **Core courses:** BADM 554, BDI 513, FIN 550, BADM 557 (required for all paths)
3. **8-week format:** All courses run 8 weeks (enables flexible, modular scheduling)
4. **Fall 2026 launch:** BADM 554, BDI 513 Part 1 must be ready Aug 2026
5. **Python + Jupyter primary:** All courses must use this as computational backbone
6. **Project-based assessment:** No traditional final exams; all courses graded on projects + participation

### Course-Specific Constraints
**BADM 554 (Data Foundations)**
- Focus: SQL + data wrangling + basic data modeling
- Tools: Python (pandas, sqlalchemy), SQLFiddle, cloud SQL
- No constraint on rubric name (could be MSBAi554 or stay as 554)

**BDI 513 (Data Storytelling with AI)**
- Split: 2 credits Fall 1 + 2 credits Fall 2 (semester-long project)
- Tools: Python (pandas, matplotlib, seaborn, plotly), Tableau Public, financial APIs
- Project: Company deep-dive analysis (public company)

**FIN 550 / MSBAi550 (Big Data Analytics)**
- **Rename constraint:** Remove "Finance" from title for broader appeal
- **Rubric option:** FIN 550 → MSBAi550 or "Business Analytics" or similar
- **Content constraint:** Skip causal inference methods; focus on ML + prediction
- **Orientation only:** Brief introduction to causal thinking (not detailed methods)
- **Project focus:** Finance-oriented (stock prediction, portfolio analysis, etc.)
- **Timing:** Fall 2 (weeks 9-16 of academic year)

**BADM 557 (Decision Intelligence with AI)**
- Keep Subramanyam on-campus version as foundation
- Add AI-augmented features (Claude for case analysis, model interpretation)
- Tools: Python (scikit-learn), Tableau, HBS cases

**BADM 558 (Big Data Infrastructure)**
- Keep Khandelwal on-campus content (condensed)
- Tools: Python (PySpark, boto3), AWS
- AI tools for architecture guidance

**BADM 576 (Data Science & Machine Learning)**
- Keep Khandelwal ML curriculum
- Tools: Python (scikit-learn), DataCamp, real datasets
- AI tools for feature engineering ideas + code review

### Technology Constraints
1. **AI tools:** Generic term; no specific vendor lock-in (support multiple platforms)
2. **Python version:** 3.10+ (modern, stable)
3. **Jupyter environment:** Google Colab (free) + JupyterHub (paid, institutional option)
4. **Cloud infrastructure:** AWS Free Tier + student credits (reimbursable, optional)
5. **LMS:** Canvas (institutional standard)
6. **GitHub:** Required for all coursework (public portfolios)

### Capstone Constraints (Fall 4)
1. **Split structure:**
   - **Part 1 (Weeks 1-2):** Portfolio curation + refinement
   - **Part 2 (Weeks 3-8):** New project (individual or small team)
2. **Portfolio component:**
   - Select 3-4 best projects from all courses
   - Write reflection narratives
   - Create public GitHub portfolio
   - Practice portfolio pitch (3 min)
3. **New project component:**
   - Option A: Real consulting project via Research Park (Recommended)
   - Option B: Independent research on self-selected business problem
   - AI assist allowed (documented)
4. **Output:** GitHub repo + Jupyter notebook + executive summary + video presentation

---

## Soft Constraints (Flexible)

1. **Course naming:** Can use different rubric (554 vs. MSBAi554) as long as clear
2. **Synchronous session timing:** Flexible, accommodate global time zones (record all)
3. **Capstone project type:** Either real client OR independent, based on student preference
4. **Elective flexibility:** Industry tracks can evolve based on student demand
5. **Tool choices:** Supplementary tools flexible (R, Scala, different cloud platforms) as long as Python primary

---

## Design Constraints from Context

### From IBC Market Research
- **Employer demand:** AI/GenAI, applied learning, communication skills (addressed ✅)
- **Student drivers:** Flexibility, affordability, ROI, career outcomes (addressed ✅)
- **Market gap:** Cost, industry integration, emerging skills (addressed ✅)
- **Differentiation needed:** Not just "another MSBA" (MSBAi AI-first positioning ✅)

### From Undergrad AI Strategy
- **L-C-E progression:** All learning outcomes follow this model ✅
- **Campus AI alignment:** Contribute to four campus tracks ✅
- **Responsible AI:** Ethics + governance woven throughout ✅
- **AI literacy for all:** Every student graduates AI-ready ✅

### From On-Campus MSBA Analysis
- **Working professional focus:** Adapted for asynchronous, 8-week format ✅
- **Hands-on labs:** Preserved in cloud-native way ✅
- **Real data:** Finance, business datasets maintained ✅
- **Project-based:** Shifted from exams to continuous projects ✅

---

## Implementation Constraints (Timeline)

### Phase 1: Content Development (Jan-Apr 2026)
- **By April 1:** All 8-week syllabi finalized + Jupyter Books started
- **By June 1:** All content complete + pilot tested

### Phase 2: Recruitment (May-Aug 2026)
- **By Aug 1:** Recruitment messaging + marketing live
- **By Aug 15:** First cohort enrolled

### Phase 3: Launch (Aug 2026)
- **Aug 25:** Fall 1 courses start (BADM 554, BDI 513 Part 1)
- **Oct 1:** Fall 2 courses start (FIN 550, BDI 513 Part 2)
- **Jan 2027:** Spring 1 starts (BADM 557, electives)
- **Mar 2027:** Spring 2 starts (BADM 558)
- **Jun 2027:** Summer starts (BADM 576)
- **Aug 2027:** Fall 3 starts (specialization electives)
- **Oct 2027:** Fall 4 starts (capstone)

---

## Success Criteria

### Must-Have
1. ✅ Every course has 2-3 major projects
2. ✅ All students use Python + Jupyter + GitHub
3. ✅ Weekly project-focused live sessions
4. ✅ Fall 1 (554, 513 Part 1) ready by Aug 2026
5. ✅ All 36 credits accounted for
6. ✅ Capstone split into portfolio + new project

### Nice-to-Have
1. Real consulting capstones via Research Park
2. Industry-specific elective tracks
3. Stackable certificates (Core, AI Analytics)
4. Guest speaker series (monthly)
5. Student peer learning communities

---

## Red Flags (What Could Go Wrong)

1. **Content development delays:** Risk if Jupyter Book infrastructure not ready by March 1
2. **Faculty availability:** 5+ instructors needed; ensure course development time allocated
3. **Cloud infrastructure costs:** AWS + JupyterHub must be affordable (pass-through model)
4. **Enrollment:** Conservative first cohort (50-75 students); recruitment messaging must differentiate
5. **Tool ecosystem changes:** Keep "AI tools" generic to adapt to platform changes

---

## Approval Sign-Off

**Document prepared by:** Claude Code  
**Status:** Ready for implementation planning  
**Next step:** Create detailed COURSE_ADAPTATIONS.md with week-by-week syllabi

---
