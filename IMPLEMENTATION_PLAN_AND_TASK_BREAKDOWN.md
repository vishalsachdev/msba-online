# MSBAi Implementation Plan & Task Breakdown

**Version:** 1.0  
**Timeline:** January 2026 - August 2027  
**Status:** Ready for assignment to faculty/staff

---

## Executive Summary

MSBAi launch requires:
- **Content development:** 6 courses × 8 weeks = 48 weeks of course material
- **Synchronous infrastructure:** Studio sessions, discussions, office hours
- **Technology setup:** JupyterHub, AWS credits, GitHub org, Tableau licenses
- **Marketing & recruitment:** 50-75 first cohort by August 2026

**Critical path:** Content must be complete by June 1, 2026 to allow pilot + refinement before Fall 1 launch.

---

## Phase 1: Content Development (Jan 1 - June 1, 2026)

### 1.1 Course Syllabus Finalization

| Course | Rubric | Credits | Lead Faculty | Deadline | Status |
|--------|--------|---------|--------------|----------|--------|
| Data Foundations | BADM 554 or MSBAi554 | 4 | [TBD] | Mar 1 | [ ] |
| Data Storytelling (Part 1) | BDI 513 | 2 | [TBD] | Mar 1 | [ ] |
| Data Storytelling (Part 2) | BDI 513 | 2 | [TBD] | Mar 1 | [ ] |
| Analytics for Business | FIN 550 or MSBAi550 | 4 | [TBD] | Mar 1 | [ ] |
| Decision Intelligence with AI | BADM 557 or MSBAi557 | 4 | [TBD] | Mar 15 | [ ] |
| Generative AI for Analytics | [New] | 2 | [TBD] | Apr 1 | [ ] |
| Big Data Infrastructure | BADM 558 or MSBAi558 | 4 | [TBD] | Mar 15 | [ ] |
| Data Science & Machine Learning | BADM 576 or MSBAi576 | 4 | [TBD] | Mar 15 | [ ] |
| Quantum for Optimization | [New, TBD] | 2 | [TBD] | Apr 15 | [ ] |

**Deliverable per course:**
- [ ] Learning outcomes (L-C-E format, aligned to Bloom's)
- [ ] Week-by-week breakdown (topics, projects, assessments)
- [ ] Project specifications (3 templates: small, medium, large)
- [ ] Reading list + datasets
- [ ] AI tools integration points
- [ ] Studio session topics (which weeks focus on project work)

---

### 1.2 Jupyter Book Creation

**Scope:** 6 core courses need Jupyter Books (text + code + visualizations)

| Course | Chapters | Jupyter Notebooks | Lead Developer | Deadline |
|--------|----------|-------------------|-----------------|----------|
| BADM 554 | 8 | 12 code notebooks | [TBD] | Apr 15 |
| BDI 513 | 8 | 10 code notebooks | [TBD] | Apr 15 |
| FIN 550 | 8 | 12 code notebooks | [TBD] | May 1 |
| BADM 557 | 6 | 8 code notebooks | [TBD] | May 1 |
| BADM 558 | 8 | 10 code notebooks | [TBD] | May 15 |
| BADM 576 | 8 | 12 code notebooks | [TBD] | May 15 |

**Per course deliverable:**
- [ ] Jupyter Book template (title, chapters, navigation)
- [ ] 8+ chapters of narrative + code
- [ ] 10+ executable notebooks students can download
- [ ] GitHub repo with all source files + CI/CD for building book

---

### 1.3 Video Lecture Production

**Scope:** 60-80 short lectures (10-15 min each)

| Course | Lectures | Topics | Lead Producer | Deadline |
|--------|----------|--------|----------------|----------|
| BADM 554 | 12 | SQL, data modeling, APIs, NoSQL | [TBD] | Apr 15 |
| BDI 513 | 10 | Visualization, storytelling, narratives | [TBD] | Apr 15 |
| FIN 550 | 12 | Time series, ML, regression, classification | [TBD] | May 1 |
| BADM 557 | 8 | Analytics lifecycle, BI tools, dashboards | [TBD] | May 1 |
| BADM 558 | 10 | AWS, cloud architecture, data pipelines | [TBD] | May 15 |
| BADM 576 | 12 | ML fundamentals, algorithms, evaluation | [TBD] | May 15 |

**Per video:**
- [ ] Script (3-5 min read time)
- [ ] Screen recording + code walkthrough
- [ ] Closed captions (auto + manual review)
- [ ] YouTube + LMS hosting
- [ ] Associated Jupyter notebook for follow-along

---

### 1.4 Project Specification & Grading Rubrics

**Deliverable per course:** 3 major projects with detailed specs

| Course | Project 1 | Project 2 | Project 3 | Lead | Deadline |
|--------|-----------|-----------|-----------|------|----------|
| BADM 554 | ETL pipeline | Data model design | API integration | [TBD] | Mar 15 |
| BDI 513 | Viz design | Company analysis | Storytelling narrative | [TBD] | Mar 15 |
| FIN 550 | Exploratory analysis | Predictive model | Portfolio analysis | [TBD] | Apr 1 |
| BADM 557 | Case write-up | Classification model | BI dashboard | [TBD] | Apr 1 |
| BADM 558 | AWS setup | Data pipeline | Real-time processing | [TBD] | Apr 15 |
| BADM 576 | Data pipeline | ML model comparison | Capstone prediction | [TBD] | Apr 15 |

**Per project spec:**
- [ ] Problem statement + business context
- [ ] Dataset(s) + access instructions
- [ ] Deliverable requirements (GitHub repo, notebook, dashboard, etc.)
- [ ] Grading rubric (5 dimensions: technical, creativity, communication, code quality, impact)
- [ ] Sample solution (for instructor reference)

---

### 1.5 Studio Session Planning

**Scope:** Weekly project-focused tutorial sessions + monthly discussions

**Deliverables by Jan 31:**
- [ ] Studio session calendar (2026-2027 academic year)
- [ ] Studio session formats/templates (project-focused, discussion-focused)
- [ ] Guest speaker list (industry practitioners, alumni)
- [ ] Recording/hosting infrastructure

**Studio Session Types:**
1. **Project Studio (90 min, weekly)** — Hands-on project work
   - Instructor live-codes solution approach
   - AI tools demo (how to use Claude/ChatGPT/etc. to accelerate work)
   - Q&A and debugging
   - Breakout rooms for peer collaboration
   
2. **Analytics Conversation (60 min, bi-weekly)** — Current topics
   - Industry guest speakers
   - Case study discussions
   - Emerging tools + trends
   
3. **Office Hours (30-60 min, weekly)** — 1-on-1 support
   - One-on-one debugging
   - Career advice
   - Project feedback

---

### 1.6 GitHub Organization & Portfolio Setup

**Deliverables by Feb 15:**
- [ ] GitHub organization created (gies-msba or similar)
- [ ] Team structure defined (faculty, TAs, students)
- [ ] Template repos for each course (starter code, rubric, submission structure)
- [ ] Handbook: "How to use GitHub in MSBAi"
  - Clone, commit, push workflow
  - Naming conventions
  - README.md standards
  - Public portfolio guidelines
- [ ] Portfolio template (personal website or GitHub Pages for showcasing projects)

---

## Phase 2: Technology Infrastructure (Jan 15 - May 31, 2026)

### 2.1 Jupyter Environment Setup

**Deadline: Apr 1, 2026**

| Component | Status | Owner | Notes |
|-----------|--------|-------|-------|
| Google Colab integration | [ ] | [TBD] | Link to course datasets, auth |
| JupyterHub cloud hosting | [ ] | [TBD] | AWS EC2, optional premium tier |
| Python environment specs | [ ] | [TBD] | requirements.txt for all courses |
| Pre-loaded datasets | [ ] | [TBD] | S3 buckets, data access instructions |
| Notebook templates | [ ] | [TBD] | Standardized structure across courses |

**Deliverable:**
- [ ] "Getting Started Guide" (how to access Jupyter, upload files, save work)
- [ ] Troubleshooting documentation

---

### 2.2 AWS & Cloud Credits

**Deadline: May 1, 2026**

- [ ] AWS Educate program enrollment (free tier + $100+ per student)
- [ ] Cost estimation (EC2 for workshops, S3 for datasets, RDS for BADM 554)
- [ ] Student onboarding (how to claim credits, set up account)
- [ ] Monitoring/optimization (prevent runaway costs)
- [ ] Documentation: "AWS for MSBAi" guide

---

### 2.3 Tableau Licensing

**Deadline: Apr 15, 2026**

- [ ] Student academic licenses (Tableau Public free for all, Desktop academic for advanced)
- [ ] License management (track expiration dates, renewals)
- [ ] Onboarding: "Getting Started with Tableau Public"
- [ ] Sample dashboards + templates

---

### 2.4 Canvas LMS Configuration

**Deadline: May 1, 2026**

- [ ] Course shell templates (consistent layout, navigation)
- [ ] Content organization (lectures, labs, projects, discussions)
- [ ] Gradebook setup (auto-import project grades)
- [ ] Syllabus templates (consistent formatting)
- [ ] Integration with GitHub (maybe via webhooks for notifications)

---

### 2.5 Video Hosting & Delivery

**Deadline: Apr 1, 2026**

- [ ] YouTube channel + playlists (organized by course)
- [ ] Canvas module embeds
- [ ] Download options (for offline access)
- [ ] Closed caption management (accessibility)

---

## Phase 3: Marketing & Recruitment (Feb 1 - Aug 31, 2026)

### 3.1 Marketing Materials

**Deliverables by Apr 1:**
- [ ] Program overview (1-page summary + full description)
- [ ] Target personas (career pivoters, promotion seekers, executives)
- [ ] Marketing tagline: **"The AI-First MSBA"** or **"AI-First, Affordable, Flexible"**
- [ ] Key differentiators (vs. competitors):
  - Every student graduates AI-ready (not optional)
  - Project-focused learning with live studio sessions
  - 8-week modular format (work while you learn)
  - Stackable certificates (12-24-36 month options)
  - Affordability (20% cheaper than peer programs)
  - Applied capstones (real client projects)
- [ ] Testimonials/stories (from pilot cohort, if available)

---

### 3.2 Digital Marketing

**Budget: $30K | Timeline: May-Aug 2026**

- [ ] Website (Gies microsite or dedicated iMSBA site)
- [ ] Digital ads (LinkedIn, Google, Reddit — target working professionals)
- [ ] Email campaigns (B2B targeting, alumni networks)
- [ ] Webinars (live demos of courses, Q&A with faculty)
- [ ] Social media (LinkedIn posts, Twitter, TikTok for younger audience)
- [ ] Influencer partnerships (data science educators, podcasters)

---

### 3.3 Recruitment Events

**Budget: $20K | Timeline: May-Aug 2026**

- [ ] Virtual information sessions (4-6 events, different time zones)
- [ ] One-on-one recruitment calls (staff support for qualified prospects)
- [ ] Corporate partnerships (pitch to employers as professional development)
- [ ] Alumni network outreach (leverage 20,000+ Gies online learners)

---

### 3.4 Admissions & Enrollment

**Target: 50-75 students for Fall 1 cohort**

- [ ] Application process (simplified, 15 min online form)
- [ ] Prerequisites (none required; encourage any working professional)
- [ ] Start date cohorts (Fall 2026 start)
- [ ] Enrollment confirmation + onboarding

---

## Phase 4: Pilot & Refinement (May 1 - July 31, 2026)

### 4.1 Pilot Cohort (Internal)

**Scope:** 10-15 people (faculty, TAs, staff) test courses

**Timeline:** May 15 - June 30

| Course | Pilot Dates | Lead | Feedback Focus |
|--------|------------|------|-----------------|
| BADM 554 | May 15 - June 27 | [TBD] | Content clarity, project workload, timing |
| BDI 513 Part 1 | May 15 - June 15 | [TBD] | Visualization tools, storytelling structure |
| FIN 550 (condensed) | May 22 - June 29 | [TBD] | ML content depth, finance examples, pacing |

**Deliverable:**
- [ ] Feedback report per course (content, tools, timing, confusion points)
- [ ] Refinement roadmap (what needs fixing before Aug 1)

---

### 4.2 Content Refinement

**Timeline:** July 1-20

Based on pilot feedback:
- [ ] Update Jupyter Books (clarity, examples, datasets)
- [ ] Re-record videos that caused confusion
- [ ] Adjust project specs based on time estimates
- [ ] Fix technical issues (software conflicts, broken links, etc.)

---

### 4.3 Readiness Checklist

**By July 31:**
- [ ] All course syllabi finalized ✅
- [ ] All Jupyter Books complete + hosted ✅
- [ ] All videos uploaded + captioned ✅
- [ ] All project specs finalized with rubrics ✅
- [ ] Studio session schedule published ✅
- [ ] GitHub org + templates ready ✅
- [ ] JupyterHub + AWS setup tested ✅
- [ ] Canvas courses populated ✅
- [ ] Student onboarding materials ready ✅
- [ ] Marketing campaign live ✅
- [ ] 50+ applications received ✅

---

## Phase 5: Launch (Aug 1 - Oct 31, 2026)

### 5.1 Student Onboarding (Aug 1-24)

- [ ] Acceptance letters + enrollment confirmation
- [ ] Tech setup (GitHub, Jupyter, Tableau, Canvas)
- [ ] Community building (Discord/Slack, intro videos, welcome webinar)
- [ ] Orientation module (expectations, course structure, how to succeed)

---

### 5.2 Fall 1 Launch (Fall 2026)

**Courses:**
- BADM 554: Data Foundations (Weeks 1-8)
- BDI 513 Part 1: Data Storytelling (Weeks 1-8)

**Weekly Schedule:**
- Async lectures + assignments (self-paced, watch anytime)
- Weekly project studio (Tue 10am UTC, Thu 6pm UTC, Sat 2pm UTC)
- Weekly office hours (Mon 3pm UTC)
- Bi-weekly discussion (AI trends, guest speakers)

**Monitoring:**
- [ ] Student engagement (login rates, submission on-time %, forum participation)
- [ ] Course satisfaction (weekly pulse check, mid-course survey)
- [ ] Support requests (track common issues, refine help docs)

---

### 5.3 Fall 2 Launch (Fall 2026, Second Half)

**Courses:**
- FIN 550: Analytics for Business (Weeks 9-16)
- BDI 513 Part 2: Data Storytelling (Weeks 9-16)

**Timeline:**
- Weeks 1-8: Running Fall 1 + preparing Fall 2
- Oct 1 onwards: Fall 1 ends, Fall 2 begins

---

## Ongoing Operations (Fall 2026 - Fall 2027)

### Studio Session Schedule (Template)

**Weekly Pattern (example):**
- **Tue 10:00-11:30 UTC:** Project Studio (BADM 554 + BDI 513)
- **Wed 18:00-19:30 UTC:** Project Studio (FIN 550 + BADM 557)
- **Thu 14:00-15:30 UTC:** Office Hours (Drop-in, any course)
- **Fri 13:00-14:00 UTC:** Analytics Conversation (Guest speaker, discussion)

**All sessions recorded + uploaded to YouTube for async access**

---

### Monitoring & Iteration

**Monthly review (all staff):**
- Student engagement metrics
- Course satisfaction (NPS)
- Support ticket trends
- Content feedback
- Faculty workload assessment

**Quarterly strategic review:**
- Enrollment trajectory vs. goals
- Retention rates
- Job placement outcomes (post-grad surveys)
- Budget/cost analysis
- Adjustments to schedule, tools, electives

---

## Resource Requirements Summary

### Staffing (FTE)

| Role | Quantity | Timeline |
|------|----------|----------|
| **Instructional Designer** | 1 | Jan-Jun 2026 |
| **Video Producer/Editor** | 1 | Jan-Jun 2026 |
| **Course Developers (Faculty)** | 5-6 | Jan-Jun 2026 (reduced load) |
| **Tech Support / LMS Admin** | 1 | May 2026 - ongoing |
| **Teaching Assistants** | 3-5 | Aug 2026 - ongoing (per term) |
| **Program Manager** | 1 | Jan 2026 - ongoing |

### Budget Summary

| Category | Cost | Timeline |
|----------|------|----------|
| **Content Development** | $150K | Jan-Jun 2026 |
| **Technology Setup** | $50K | Jan-May 2026 |
| **Cloud Infrastructure** | $100K/yr | Jun 2026 - ongoing |
| **Marketing & Recruitment** | $50K | Feb-Aug 2026 |
| **Staff Salaries** | $200K (partial year 1) | Jan 2026 - ongoing |
| **TOTAL Year 1** | ~$550K | 2026 |

---

## Critical Milestones (Red Flags)

| Milestone | Deadline | Status | Owner | Notes |
|-----------|----------|--------|-------|-------|
| Syllabi finalized | Mar 1, 2026 | [ ] | Course leads | Delay = delay all downstream |
| Jupyter Books started | Feb 1, 2026 | [ ] | Dev team | Early start needed |
| Videos recorded | Apr 1, 2026 | [ ] | Producers | Tight timeline |
| Pilot cohort complete | Jun 30, 2026 | [ ] | Faculty | Must happen before refinement |
| Marketing live | May 1, 2026 | [ ] | Marketing | Need time for recruitment |
| JupyterHub tested | May 15, 2026 | [ ] | Tech | Must work before student onboarding |
| Enrollment target (50+) | Aug 1, 2026 | [ ] | Admissions | Conservative but achievable |
| Fall 1 ready | Aug 15, 2026 | [ ] | All | 10-day buffer before launch |

---

## Next Steps (Immediate Actions)

### By Jan 15, 2026
- [ ] Assign faculty leads to each course
- [ ] Assign instructional designer
- [ ] Schedule kickoff meeting (all stakeholders)
- [ ] Begin GitHub org setup
- [ ] Draft syllabus templates

### By Jan 31, 2026
- [ ] All course syllabi outlines completed
- [ ] Video production plan + schedule
- [ ] Jupyter Book infrastructure selected + tested
- [ ] Canvas template created
- [ ] Studio session calendar drafted

### By Feb 15, 2026
- [ ] GitHub org + repos ready
- [ ] Jupyter environment specs finalized
- [ ] AWS account setup + documentation
- [ ] Marketing strategy + messaging approved
- [ ] Video scripts drafted (courses 1-2)

---

## Success Metrics (End of Year 1)

### Must-Hit Targets
- ✅ 50+ students enrolled and started Fall 1
- ✅ 90%+ course completion rate (vs. industry 85%)
- ✅ All courses have 2-3 major projects
- ✅ All students use Python + Jupyter + GitHub
- ✅ Weekly studio sessions running with 70%+ attendance
- ✅ NPS >70 (student satisfaction)

### Nice-to-Hit Targets
- ✅ 70%+ job placement within 6 months
- ✅ Average $15K salary increase post-grad
- ✅ 200+ students on waitlist for Spring 1
- ✅ First cohort capstone projects with real clients
- ✅ Program mentioned in trade publications

---

## Appendix: Tool & Vendor List

**Required (No Alternatives):**
- Canvas LMS (institutional)
- GitHub (version control)
- Python 3.10+ (primary language)
- Jupyter Notebooks (computing environment)

**Recommended (Flexible):**
- Google Colab (free Jupyter hosting)
- JupyterHub (self-hosted option)
- AWS (cloud infrastructure; alternatives: Azure, GCP)
- Tableau Public (free visualization; paid: Tableau Desktop)
- AI tools (ChatGPT, Claude, Copilot, open-source; any/all supported)
- Discord/Slack (community, optional)

---

*Document prepared: January 12, 2026*  
*Next update: Feb 1, 2026 (after first faculty assignments)*
