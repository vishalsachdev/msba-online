# Core Courses - MSBAi Curriculum

**Source Data:** MSBA Fall 2025 On-Campus Program Analysis

This document provides detailed course-by-course breakdown of the four core courses and identifies online conversion challenges and opportunities.

---

## Course 1: BADM 554 - Enterprise Database Management (4 credits)

### On-Campus Structure
**Duration:** 16 weeks (Aug 25 - Dec 12, 2025)

**Weekly Components:**
- Lecture/discussion
- Hands-on SQL labs (in-class)
- Assignments and coding exercises (take-home)
- Quizzes (in-class)
- Mini-projects (team-based)

**Assessment Breakdown:**
- **Quizzes:** 10 quizzes (roughly weekly, weeks 1-10)
- **Assignments:** 5 assignments (SQL, data modeling, design problems)
- **Labs:** 7 hands-on labs (SQL 1-4, MySQL Workbench, Knime, MongoDB)
- **Mini-Projects:** 3 mini-projects (database design, ETL, normalization)
- **Exams:** Test 1 (week 6, Oct 2, 80 min), Test 2 (week 15, Dec 4, 80 min)

**Key Milestones:**
- Week 1-4: SQL fundamentals (SELECT, JOIN, subqueries)
- Week 6: Test 1 (SQL + relational model)
- Week 7-10: Advanced topics (APIs, database design, ER modeling, normalization)
- Week 11: Mini-Project 1 due (normalization)
- Week 13: Mini-Project 2 due (BI/warehousing), Mini-Project 3 assigned
- Week 15: Test 2 due (comprehensive)
- Week 16: Mini-Project 3 due (final submission)

**Technology Stack:**
- MySQL Workbench (ER modeling, SQL execution)
- Knime (ETL workflows)
- MongoDB (NoSQL)
- DataCamp (homework assignments)
- Yelp API (data acquisition)

**Synchronous Requirements:**
- In-class labs and quizzes
- Discussion of tricky SQL concepts
- Test administration
- Group project check-ins

---

### Online Conversion Strategy

#### Asynchronous Components ✅
- **Pre-recorded lectures** with SQL walkthroughs (separate video per topic: SELECT, JOIN, subqueries, etc.)
- **Interactive SQL tutorials** using browser-based SQL editor (e.g., SQLFiddle, Mode Analytics)
- **Recorded lab demonstrations** showing MySQL Workbench + Knime workflows
- **Assignments** (same as on-campus, but submission via Canvas)
- **DataCamp modules** (self-paced, with due dates)

#### Synchronous Components 🎥
- **Weekly office hours** (1 hour, optional but encouraged)
  - Database design Q&A
  - SQL troubleshooting for stuck students
  - Mini-project guidance
- **Lab review sessions** (optional, recorded if attendance is low)
- **Test administration**
  - Option 1: Proctored online exams (Proctorio, Honorlock)
  - Option 2: Take-home exams with time constraints
  - Option 3: Comprehensive project-based assessment (replace exams)

#### Hands-On Lab Challenges ⚠️
**On-campus labs:**
- Students log into lab computers with pre-installed MySQL, Knime, MongoDB
- Immediate instructor support for installation/setup issues

**Online approach:**
- **Option A (Cloud-Based):** Provide cloud-hosted environments (AWS RDS, MongoDB Atlas, Docker)
  - Pros: No install hassles, reproducible environment
  - Cons: Cost, account management, access troubleshooting
- **Option B (Local + Support):** Students install locally, extensive setup guides + office hours support
  - Pros: Lower cost, persistent local environment
  - Cons: More setup issues, OS-specific problems
- **Recommended:** Hybrid - cloud-hosted for critical labs (Knime, MongoDB), local for SQL labs

#### Mini-Projects
- **Team coordination:** Async project management (GitHub, Slack, Google Docs)
- **Submission:** Git repository + SQL scripts + documentation
- **Feedback:** Written feedback on design decisions, SQL quality, normalization correctness

#### Exams → Alternatives
- **Option 1: Keep as proctored online exams** (feasible for 4-hour span)
- **Option 2: Project-based assessment** - Replace exams with comprehensive database design projects
- **Option 3: Hybrid** - Proctored midterm exam (weeks 6-7), final project (week 15-16)

**Recommended:** Hybrid approach - Keep Test 1 as proctored exam (foundational SQL), replace Test 2 with comprehensive database design project

---

## Course 2: BDI 513 - Data Storytelling (4 credits)

### On-Campus Structure
**Duration:** 16 weeks

**Weekly Components:**
- Lecture/discussion on storytelling and visualization
- Live coding in Wolfram Notebooks
- Assignments with financial data analysis
- Final project (company deep-dive with storytelling)

**Assessment Breakdown:**
- **Homeworks (H1-H6):** 6 major homework assignments with code + analysis
- **In-class participation:** Discussion, problem-solving
- **Project deliverables (PCP_1 to PCP_3):** Intermediate presentations/deliverables
- **Final project presentations:** Live student presentations (Dec 1 & 3)
- **Final project submission:** Due Dec 10, 11:59pm

**Key Milestones:**
- Week 1-4: Financial data, visualization basics (1D, 2D, 3D, time, location, text)
- Week 5-7: Exploratory analysis, regression, decision-making (H1-H4 due)
- Week 8-11: Company analysis (Mag7 stories), 10K filing analysis, PCP submissions
- Week 12-13: Customer segmentation, storytelling with cases
- Week 14: Thanksgiving break
- Week 15: Student presentations (live, Dec 1 & 3)
- Week 16: Final project submission (Dec 10)

**Technology Stack:**
- Wolfram Notebooks (primary analysis environment)
- Tableau (visualization + dashboarding)
- Python (some exploratory analysis)
- APIs: Nasdaq Datalink, Yelp API
- Bloomberg Terminal (Excel add-in)
- LLMs (for analyzing founder backgrounds, earnings calls)

**Synchronous Requirements:**
- Lecture/discussion sessions (engaging storytelling, live coding demos)
- Final project presentations (live, in-person or Zoom)
- Feedback on drafts

---

### Online Conversion Strategy

#### Asynchronous Components ✅
- **Pre-recorded lectures** on storytelling principles, visualization theory
- **Live-coded walkthroughs** (recorded) showing Wolfram Notebooks + Tableau workflows
- **Homework assignments** (same as on-campus, submitted via Canvas)
- **Tutorial videos** on Bloomberg Terminal, API usage, LLM prompt engineering
- **Self-paced Wolfram/Tableau practice** with provided datasets

#### Synchronous Components 🎥
- **Weekly discussion sessions** (1.5 hours, optional)
  - Live coding Q&A
  - Storytelling principles discussion
  - Homework help + code review
- **Guest speakers** (industry analysts, data journalists) - recorded + live Q&A
- **Final project presentations** (mandatory for cohort engagement)
  - Option 1: Live Zoom presentations (Dec 1 & 3, adapted from on-campus schedule)
  - Option 2: Asynchronous video submissions + async peer feedback
  - **Recommended:** Live presentations (builds cohort community, practice for job interviews)

#### Hands-On Challenges ⚠️
**Wolfram Notebooks:**
- On-campus: Students bring laptops, TA help available
- Online: Wolfram Cloud (browser-based) or local installation + support
- **Recommended:** Wolfram Cloud (no setup, cloud-based)

**Tableau:**
- On-campus: Students use lab computers or personal laptops
- Online: Tableau Public (free) or institutional license (Tableau Desktop)
- **Recommended:** Provide Tableau Public for core assignments + optional Desktop license for advanced work

**APIs & Data Access:**
- Nasdaq Datalink, Bloomberg Terminal, CapitalIQ, S&P: May have licensing/access restrictions
- **Solution:** Provide pre-downloaded datasets + API credentials management guide + Docker containers with pre-loaded data

#### Project Deliverables
- **PCP_1-3 (Intermediate submissions):** Code notebooks + narrative write-ups
- **Final project:** Wolfram/Jupyter notebook + Tableau dashboard + 5-page analysis paper + video presentation
- **Peer feedback:** Structured peer review on projects (fosters community)

#### Presentations
- **Live presentations (preferred):** 15 min per student, 5 min Q&A via Zoom
- **Backup plan:** Video submission + pre-recorded Q&A feedback from instructor

---

## Course 3: BADM 557 - Business Intelligence (2-4 credits)

### On-Campus Structure
**Duration:** 16 weeks

**Weekly Components:**
- Lecture/discussion on BI concepts and Python data science
- Python hands-on exercises (Scipy, NumPy, Pandas, scikit-learn)
- Case studies and real-world applications
- Tableau assignments
- Final project (independent or team-based)

**Assessment Breakdown:**
- **Cases/Discussions:** Multiple case analyses (Restaurant Grades, Vispera retail, Infosys, Warriors, etc.)
- **Quizzes:** Multiple quizzes (Oct 1-Nov 19 content review, Dec 8 final quiz)
- **Python certification:** Assigned week 8, due March 10 (credential verification)
- **Projects:** Tableau + Python coding assignments, final project
- **Final submission:** Due Dec 12

**Key Milestones:**
- Week 1-4: BI framework, A/B testing, data exploration, Tableau intro
- Week 4-5: Visualization, classification algorithms
- Week 8: Python certification assigned (deadline: Mar 10, next semester)
- Week 8-13: Classification, clustering, text mining, supervised/unsupervised learning
- Week 13: Quiz (covering Oct 1-Nov 19), final project due Dec 12

**Technology Stack:**
- Python (Scipy, NumPy, Pandas, Scikit-learn)
- Tableau (dashboards, storytelling)
- Jupyter Notebooks
- Various data sources (10K filings, Mergent, Moody's, CapitalIQ, S&P)

**Synchronous Requirements:**
- Lecture/discussion (case-based learning, Python walkthroughs)
- Code review and Q&A
- Project check-ins

---

### Online Conversion Strategy

#### Asynchronous Components ✅
- **Pre-recorded lectures** on BI concepts, ML algorithms, Tableau workflows
- **Jupyter notebook tutorials** (downloadable, executable locally or in cloud)
- **Case analyses** (self-paced reading + reflection assignments)
- **Tableau practice** with provided datasets
- **Python certification** (already self-paced external credential)

#### Synchronous Components 🎥
- **Weekly office hours** (1 hour, optional)
  - Python coding help
  - Tableau troubleshooting
  - Case discussion
- **Monthly webinars** (optional, recorded)
  - Guest speakers from industry
  - Deep dives into advanced BI topics
  - Code walkthroughs
- **Quiz administration** (week 13)
  - Proctored online quiz or take-home
  - **Recommended:** Take-home (Python coding allows open-book exam)

#### Hands-On Challenges ⚠️
**Python environment:**
- On-campus: Lab computers with pre-installed Python + Jupyter
- Online: Students install locally OR use cloud-based Jupyter
- **Recommended:** Provide Docker image + quick setup guide + JupyterHub access (cloud-based notebook server)

**Data access:**
- Some datasets (10K filings, Mergent, Moody's, CapitalIQ, S&P) may have licensing/access limitations
- **Solution:** Provide cleaned/anonymized datasets + SQL queries for pulling data + API docs for authorized access

**Tableau:**
- Same as BDI 513: Tableau Public (free) or institutional Desktop license
- **Recommended:** Tableau Public for all assignments

#### Final Project
- **Format:** Python code (Jupyter notebook) + Tableau dashboard + 3-page write-up
- **Submission:** GitHub repo + Canvas zip submission
- **Evaluation:** Code quality, data storytelling, business insight, technical rigor

---

## Course 4: FIN 550 - Big Data Analytics in Finance (4 credits)

### On-Campus Structure
**Duration:** 16 weeks

**Weekly Components:**
- Lecture/discussion on statistical and ML methods
- R labs (RStudio) with real financial data
- Problem sets and problem-solving exercises
- Midterm and final exams
- Final project

**Assessment Breakdown:**
- **Labs:** 15 hands-on R labs (Labs 00-15)
- **Problem Sets:** 2 major problem sets (PS1 due week 11, PS2 due week 16)
- **Midterm exam:** Week 9 (Oct 23, comprehensive)
- **Final project:** Due week 15 (Dec 4) and week 16 (Dec 10 for write-up)
- **Final exam:** Week 16 (Dec 12, time varies by section)

**Key Milestones:**
- Week 1-3: Data wrangling and visualization (Labs 00-05)
- Week 4-7: Regression methods (Labs 06-13, multiple & logistic regression, cross-validation, LASSO)
- Week 9: Midterm exam (Oct 23)
- Week 10-13: Causal inference, tree-based methods, neural nets (Labs 14-15)
- Week 11: PS1 due, Mini-Project 1 due
- Week 13: Difference-in-differences
- Week 15: Regression discontinuity, Final project due
- Week 16: Final exam (Dec 12)

**Technology Stack:**
- R and RStudio (primary)
- ISLR textbook (Introduction to Statistical Learning with R)
- Cloud computing platforms (AWS, Google Cloud)
- Financial datasets (real market data)

**Synchronous Requirements:**
- Lecture/discussion (explaining complex statistical concepts)
- Lab guidance and troubleshooting
- Exam administration
- Final project feedback

---

### Online Conversion Strategy

#### Asynchronous Components ✅
- **Pre-recorded lectures** with statistics/ML concepts explained
- **RStudio walkthroughs** (recorded videos showing code execution)
- **Lab instructions** with detailed step-by-step guidance
- **ISLR chapter summaries** and reading guides
- **Solved lab examples** (previous semester solutions for reference)
- **Problem set** self-assessment tools

#### Synchronous Components 🎥
- **Weekly office hours** (1.5 hours, optional but highly encouraged)
  - R code troubleshooting
  - Statistics help (explaining causal inference, cross-validation, etc.)
  - Lab review and best practices
  - Final project check-ins
- **Lab review sessions** (recorded)
  - Common mistakes and how to avoid them
  - Conceptual foundations
- **Exam administration**
  - Midterm & final exams: Proctored online (Honorlock, Proctorio)
  - Alternative: Take-home exams with R coding components

#### Hands-On Challenges ⚠️
**R environment:**
- On-campus: Lab computers with pre-installed R + RStudio
- Online: Students install locally OR cloud-based RStudio Server
- **Recommended:** Provide cloud-based RStudio Server (RStudio Cloud or institutional server)
  - Benefits: Consistent environment, no setup hassles, easy TA access for help
  - Setup: Docker + cloud hosting (AWS EC2, DigitalOcean)

**Data access:**
- Financial datasets (real market data) may require API access or downloads
- **Solution:** Provide pre-loaded RStudio environment with datasets + code for pulling fresh data + API documentation

**Labs:**
- 15 labs is substantial + time-consuming
- Online delivery options:
  - **Option A:** Lab notebooks (Rmd) with detailed instructions and code scaffolding (students fill in blanks)
  - **Option B:** Video walkthroughs + independent lab completion
  - **Option C:** Hybrid - video walkthrough + lab exercise + lab report
  - **Recommended:** Hybrid approach

#### Exams
- **Midterm (week 9):** Proctored online R coding exam (2-3 hours)
  - Can use RStudio + packages (open-book style)
  - Focus on applying concepts to new datasets
- **Final Exam (week 16):** Similar to midterm OR capstone project (more meaningful)
  - **Alternative:** Replace final exam with final project emphasis

#### Final Project
- **Format:** R Markdown report + code + interpretive analysis
- **Focus:** End-to-end causal analysis or financial prediction
- **Scope:** 10-15 pages + code appendix

---

## Comparative Analysis: Synchronous Hours

| Course | On-Campus (hrs/week) | Online Sync (hrs/week) | Notes |
|--------|----------------------|------------------------|-------|
| BADM 554 | 4-5 | 1-2 | Most can be async; labs are challenge |
| BDI 513 | 4-5 | 1-2 | Storytelling benefits from discussion; presentations are live |
| BADM 557 | 3-4 | 1 | Case-based; mostly async-friendly |
| FIN 550 | 4-5 | 1.5-2 | Stats concepts need live help; labs are challenge |
| **Total** | **15-19** | **4.5-7** | **Flexibility achieved with careful design** |

---

## Assessment Redesign Summary

| Course | On-Campus | Online | Rationale |
|--------|-----------|--------|-----------|
| BADM 554 | 2 proctored exams | 1 proctored exam + capstone project | Project-based assessment is more practical, reduces cheating risk |
| BDI 513 | Live presentations | Live Zoom presentations (or recorded + peer feedback) | Maintains engagement and presentation skills practice |
| BADM 557 | Quiz + cases + projects | Quiz (take-home or proctored) + cases + projects | Flexible approach for self-paced learners |
| FIN 550 | Midterm + final exam + project | Proctored exams OR final project-based | Comprehensive causal analysis project as capstone |

---

## Technology Requirements Summary

| Technology | Purpose | Cost | Alternative |
|-----------|---------|------|-------------|
| **Cloud SQL/Database Hosting** | BADM 554 labs | ~$50-200/mo | Local installation |
| **RStudio Cloud/Server** | FIN 550 labs | ~$100-300/mo | Local R installation |
| **Wolfram Cloud** | BDI 513 analysis | Free (basic) | Local Mathematica license |
| **Tableau Public** | Visualization | Free | Tableau Desktop ($600+/seat) |
| **Proctoring Software** | Exam administration | ~$20-50/student | Instructor proctoring (Zoom) |
| **Canvas LMS** | Course management | Institutional | (Provided by university) |

---

## Cross-Course Opportunities (from on-campus analysis)

**MSBAi students benefit from same cross-course portfolio opportunities as on-campus:**

1. **Week 3-4:** Multi-tool visualization (Wolfram, R, Tableau)
2. **Week 5-6:** End-to-end regression analysis
3. **Week 7:** API dashboard project
4. **Week 8-10:** ML comparison (R vs Python)
5. **Week 9-11:** Company deep-dive with storytelling
6. **Week 12-13:** NLP/sentiment analysis pipeline
7. **Week 11-13:** Causal inference case study

**Online delivery benefits:** Asynchronous project collaboration enables global team formation + distributed peer learning

---

## Next Steps

1. **Create COURSE_ADAPTATIONS.md** - Detailed online design for each course
2. **Design COHORT_MODEL.md** - Synchronous session scheduling and community building
3. **Plan ELECTIVES_ROADMAP.md** - Map BADM syllabi to graduate electives
4. **Set up LMS_STRUCTURE.md** - Canvas course setup and navigation

---

*Last Updated: January 12, 2026*
