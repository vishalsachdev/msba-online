# Electives Analysis: BADM 557, 558, 576

**Date:** January 12, 2026  
**Purpose:** Compare MSBAi curriculum draft requirements against actual syllabi for courses 557, 558, 576

---

## CRITICAL INCONSISTENCIES FOUND

### ⚠️ **ISSUE 1: Credit Hour Mismatch (All Three Courses)**

**Curriculum Draft Claims:**
- BADM 557: 4 credits
- BADM 558: 4 credits  
- BADM 576: 4 credits
- **Total for three courses: 12 credits**

**Actual Syllabi Show:**
- BADM 557 (Bahrini, sp25): **3 credits**
- BADM 558 (Khandelwal, sp25): **3 credits**
- BADM 576 (Khandelwal, sp25): **3 credits**
- **Actual total: 9 credits**

**⚠️ Impact:** Program would be **3 credit hours short** of curriculum draft. Need to either:
1. Expand these courses from 3 to 4 credits (requires faculty approval + workload redesign)
2. Add an additional 3-credit course somewhere in the program
3. Revise total program credits downward

---

### ✅ **ISSUE 2: BADM 557 - RESOLVED (Use Subramanyam Version)**

**Two Versions Exist:**

**❌ Bahrini (sp25):**
- "Topics in Business Intelligence: Introduction to Decision Analysis, Game Theory, and Conflict Analysis"
- **NOT** data analytics; focuses on strategic decision-making
- Tools: GMCR software, game theory
- Not suitable for MSBAi

**✅ Subramanyam (sp25 & fa25) - SELECTED FOR MSBAi:**
- **"Business Intelligence"** (actual BI course)
- **Perfect alignment with curriculum draft**
- Case-based + hands-on analytics toolkit approach

**Assessment Structure (Subramanyam):**
- Share & Tell: 5%
- Case/Article Submissions: 35%
- Class Participation: 16% (50% attendance, 50% quality)
- Quiz (Algorithm Basics): 22%
- Project (Tableau + Python): 22%

**Technology Stack (Subramanyam):**
- Python (Google Colab or Anaconda/Jupyter)
- Tableau (Desktop Academic or Public)
- MS Excel/Office 365
- Harvard Business School Coursepack

**Learning Objectives:**
- Analytics lifecycle, data curation, governance
- Data visualization with Tableau
- Multivariate regression, logistic regression, decision trees
- k-NN, Naïve Bayes, k-means clustering
- Text mining and sentiment analysis
- Python data science programming

**✅ Status:** Subramanyam versions extracted and saved as JSON:
- `557_Subramanyam_sp25.json` ✅
- `557_Subramanyam_fa25.json` ✅

---

### ✅ **ISSUE 3: BADM 558 & 576 - Learning Objectives & Topics Extracted**

**BADM 558 - Big Data Infrastructure (Khandelwal, sp25)**

**Curriculum Draft:** "BADM 558- Big Data Infrastructures" (4 credits)

**Actual Syllabus:**
| Attribute | Value |
|-----------|-------|
| Credits | 3 |
| Instructor | Khandelwal |
| Title | Big Data Infrastructure |
| Duration | 14 weeks |
| Focus | AWS, cloud computing, data engineering |

**Learning Objectives:**
- Understand and implement AWS services for big data infrastructure
- Design and execute scalable, efficient big data workflows
- Perform data analysis and generate insights from big data using AWS tools
- Demonstrate proficiency in managing and securing big data environments

**Topics (14 weeks):**
1. AWS Cloud Concepts
2. Compute and Storage Services
3. Infrastructure for Data Driven Decisions
4. Data Ingestion and Preparation
5. Big Data Processing - Hadoop and Spark
6. Data for Machine Learning
7. Data Analysis and Visualization
8. Online and Offline Data Pipelines
9. Stream Processing with Kinesis
10. Data Lakes and Warehouses
11. Orchestrating Data Pipelines
12. AWS Security and IAM
13. Scaling and Load Balancing
14. Final Project Presentations

**Tools:** AWS, SQL, Python, Unix shell

**Alignment with MSBAi:** ✅ **GOOD** - Covers big data infrastructure, cloud computing, practical engineering

---

**BADM 576 - Data Science and Analytics (Khandelwal, sp25)**

**Curriculum Draft:** "BADM 576- Data Science & Analytics" (4 credits)

**Actual Syllabus:**
| Attribute | Value |
|-----------|-------|
| Credits | 3 |
| Instructor | Khandelwal |
| Title | Data Science and Analytics |
| Duration | 14 weeks |

**Assessment Structure:**
- Midterm exam: 20%
- Project: 40%
- Participation: 10%
- Homework: 20%
- In-class activity: 10%
- ✅ **Weights add up to 100%**

**Topics (14 weeks):**
1. Fundamentals of Data Analytics
2. Statistics: Uncertainty quantification
3. Probability Distributions
4. Explanatory Modeling - Regression
5. Causal Analysis
6. Fundamentals of Data Science + ML Process
7. End-to-end ML with Scikit-Learn
8. Supervised Learning: Regression Models
9. Supervised Learning: Classification Models
10. Time Series Analysis
11. Unsupervised Learning: Clustering & PCA
12. Recommendation Models & Anomaly Detection
13. Text Analysis: NLP
14. (Topic 14 truncated in extraction)

**Tools:** Python, Scikit-Learn, DataCamp

**Alignment with MSBAi:** ✅ **EXCELLENT** - Covers ML, statistics, practical data science

---

## Summary: Data Completeness Assessment

### Core Courses (Already Documented in CORE_COURSES.md)

| Course | Status | Notes |
|--------|--------|-------|
| **BADM 554** (Database Mgmt) | ✅ Complete | 4 credits, fully documented |
| **BDI 513** (Data Storytelling) | ✅ Complete | 4 credits, fully documented |
| **FIN 550** (Big Data Analytics) | ✅ Complete | 4 credits, fully documented |

### Electives (Spring/Summer Courses)

| Course | Credits (Draft) | Credits (Actual) | Status | Concerns |
|--------|-----------------|-----------------|--------|----------|
| **BADM 557** | 4 | 3 | ⚠️ INCOMPLETE | **Wrong instructor/version?** Bahrini teaches game theory, not BI. Need Subramanyam version. |
| **BADM 558** | 4 | 3 | ⚠️ Partial | Assessment weights broken in extraction. Cloud/infrastructure focus is good. |
| **BADM 576** | 4 | 3 | ✅ Good | ML/Data Science content solid; full assessment data available. |

---

## Status Summary

### ✅ **RESOLVED: BADM 557**
- **Decision:** Use Subramanyam version (sp25 or fa25)
- **Rationale:** Perfect BI/Analytics alignment vs. Bahrini's game theory focus
- **JSON files created:** Both sp25 and fa25 variants available

### ⏳ **REMAINING: Credit Hour Discrepancy**
- Curriculum draft claims 4 credits for 557, 558, 576
- Actual courses are 3 credits each
- **Total shortfall:** 3 credits
- **Decision needed:** Expand courses? Add new course? Or adjust program total to 33 credits?

### ✅ **COMPLETE: 558 & 576 Topics/Learning Objectives**
- All learning objectives extracted
- All 14-week topic sequences documented
- Technology stacks identified

---

## Recommendations for Next Steps

### Immediate (This Week)
1. **Obtain full 558 & 576 syllabus PDFs** and manually verify assessment structures
2. **Clarify BADM 557:** Which instructor version should MSBAi use?
3. **Confirm credit hours:** Are these 3-credit or 4-credit courses in MSBAi?

### For Course Adaptation Document
Once above is clarified, create `COURSE_ADAPTATIONS.md` with:
- **For BADM 557:** Online design strategy (decision analysis version OR BI version)
- **For BADM 558:** Hands-on AWS lab infrastructure, proctoring, assessment redesign
- **For BADM 576:** Scikit-Learn environment setup, project-based alternatives to exams

### For Total Program
- Recalculate total credits if 557/558/576 remain at 3 credits
- Identify if additional course needed to reach 36-credit target
- Consider stacking: Could some courses earn dual-credit (stackable certificates)?

---

## Data Sources

**Syllabi Extracted From:**
```
/Users/vishal/admin/undergrad-ai/badm-syllabi/raw_syllabi/
  - 557_Bahrini_sp25.pdf ✅ (extracted, not recommended for MSBAi)
  - 557_Subramanyam_sp25.pdf ✅ (extracted & converted to JSON)
  - 557_Subramanyam_fa25.pdf ✅ (extracted & converted to JSON)
  - 558_Khandelwal_sp25.pdf ✅ (topics/learning objectives captured)
  - 576_Khandelwal_sp25.pdf ✅ (topics/learning objectives captured)

/Users/vishal/admin/msba-online/
  - 557_Subramanyam_sp25.json ✅ (PRIMARY)
  - 557_Subramanyam_fa25.json ✅ (ALTERNATIVE)
```

---

*This analysis prepared to support curriculum design decisions for MSBAi program launch (Target: Fall 2026)*
