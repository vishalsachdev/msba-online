# Course Adaptations: 8-Week Online Format

**Version:** 1.0
**Last Updated:** January 12, 2026
**Status:** Ready for faculty course development

---

## Document Purpose

This document provides detailed, week-by-week syllabus specifications for all MSBAi core courses adapted to the 8-week online format. Each course specification includes:

- **Learning Outcomes** (L-C-E format aligned to Bloom's Taxonomy)
- **Week-by-week breakdown** (topics, activities, assessments)
- **Major projects** (3 per course with detailed specs)
- **AI tools integration** (how AI accelerates learning)
- **Studio session schedule** (live project-focused sessions)
- **Assessment rubric** (project-based, no traditional exams)
- **Technology requirements** (Python, Jupyter, tools)

**Design Principle:** Python + Jupyter Notebooks as computational backbone; projects as primary learning vehicle; weekly studio sessions for hands-on project work + AI-augmented analysis demos.

---

## Part 1: BADM 554 - Data Foundations

**Credits:** 4 | **Term:** Fall 1 (Weeks 1-8) | **Status:** ✅ Ready for Fall 2026 launch

### Course Vision

Students master SQL, relational data modeling, and Python data wrangling to become proficient at designing, querying, and maintaining data systems. By course end, students build a complete ETL pipeline using Python, design a normalized database schema, and understand cloud data infrastructure basics.

### Learning Outcomes (L-C-E Framework)

#### Literacy (Foundational Awareness)
- **L1:** Understand relational database concepts (tables, keys, relationships) and explain why normalization matters
- **L2:** Read and interpret SQL queries to identify what data they retrieve
- **L3:** Recognize when data needs cleaning and describe common data quality issues

#### Competency (Applied Skills)
- **C1:** Write SQL queries to extract, transform, and aggregate data from relational databases
- **C2:** Design a normalized database schema (3NF) for a given business problem
- **C3:** Use Python (pandas, sqlalchemy) to build a complete ETL pipeline
- **C4:** Connect to cloud databases and run queries in browser-based SQL environments

#### Expertise (Advanced Application)
- **E1:** Evaluate design trade-offs (normalization vs. denormalization) for specific use cases
- **E2:** Optimize queries for performance and design effective indexes
- **E3:** Build a production-ready data pipeline with error handling and logging

### Week-by-Week Breakdown

| Week | Topic | Lectures | Project Work | Studio Session | Assessment |
|------|-------|----------|--------------|----------------|------------|
| **1** | Relational databases + SQL SELECT fundamentals | 3 videos (30 min each) | Project 1A: Design database for case | *Project kickoff* - database design walkthrough | Quiz (L1-L2) |
| **2** | JOINs, subqueries, aggregations | 3 videos | Project 1 work: Write queries | *SQL deep-dive* - JOIN patterns + common mistakes | Quiz (C1) |
| **3** | Data modeling + Entity-Relationship diagrams | 2 videos + Jupyter notebook | Project 1 work: Refine schema | *ER diagram workshop* - using Lucidchart/DrawIO | Project 1 due |
| **4** | Python fundamentals + pandas intro | 3 videos | Project 2A: Data wrangling | *Pandas fundamentals* - DataFrame operations in Jupyter | DataCamp assignment |
| **5** | ETL pipelines + Python (pandas, sqlalchemy) | 3 videos | Project 2 work: Build ETL | *ETL pipeline workshop* - error handling, logging | Code review (peer) |
| **6** | NoSQL basics (MongoDB) + API data ingestion | 2 videos | Project 2 work: Complete ETL | *MongoDB + APIs* - document databases, Yelp/weather API | Mid-course checkpoint |
| **7** | Indexing, optimization, cloud databases | 2 videos | Project 3A: Cloud database setup | *AWS RDS setup* - cloud database hands-on | AWS setup quiz |
| **8** | Data quality, governance, synthesis | 1 video + review | Project 3 complete + portfolio reflection | *Final presentations* - each student demos pipeline | Projects 2 & 3 due |

### Projects (3 per course)

#### Project 1: Relational Database Design (Weeks 1-3, Individual, 20% of grade)

**Problem Statement:** You've been hired by a local e-commerce startup to design their database. They currently track customers, orders, products, and reviews in spreadsheets. Your task: design a normalized relational schema.

**Deliverables:**
- Entity-Relationship diagram (ERD) showing tables, keys, relationships
- SQL schema definition (CREATE TABLE statements)
- Normalization analysis (identify 3NF violations in original data)
- 5 sample SQL queries demonstrating the schema works
- GitHub repo with schema documentation

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Schema Design** | 3NF normalized, handles all requirements | Mostly 3NF with 1-2 denormalization choices | Normalization issues present |
| **SQL Queries** | All queries correct + efficient | 4/5 queries correct | 3+ query errors |
| **Documentation** | Clear ERD + written justification | Basic ERD, minimal explanation | Incomplete ERD |
| **Code Quality** | Well-organized GitHub repo, clear comments | Adequate organization | Messy file structure |
| **Business Understanding** | Explains why design serves business needs | Mentions business context | No business rationale |

#### Project 2: ETL Pipeline in Python (Weeks 4-6, Individual, 30% of grade)

**Problem Statement:** Build a complete Extract-Transform-Load pipeline in Python. You'll fetch data from multiple sources (CSV, API, database), clean and standardize it, then load into a normalized database.

**Datasets Available:**
- Option A: Yelp API (business, review, user data)
- Option B: US Census Bureau API (demographic data by region)
- Option C: Stock market data (Yahoo Finance API)
- Option D: Weather + transportation data (public APIs)

**Deliverables:**
- Python script (pandas + sqlalchemy) that runs end-to-end
- Jupyter notebook explaining each step
- README with setup instructions (dependencies, API keys, credentials)
- Error handling documentation (what happens if API fails?)
- GitHub repo with all code + test datasets

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Code Quality** | Modular, documented, type hints | Good structure, minimal comments | Spaghetti code |
| **Data Handling** | Robust error handling, validates data | Handles happy path, basic validation | Fails on edge cases |
| **Python Fluency** | Efficient pandas/sqlalchemy usage | Standard approach, minor inefficiencies | Verbose or incorrect usage |
| **Testing** | Unit tests present, test data included | Manual testing documented | No testing shown |
| **Documentation** | Clear setup guide + code comments | Basic README | Minimal documentation |

#### Project 3: Cloud Database + Optimization (Weeks 7-8, Individual, 25% of grade)

**Problem Statement:** Deploy your ETL pipeline to AWS RDS (cloud database). Optimize it for performance. Build an automated job that runs nightly to update the database with fresh data.

**Deliverables:**
- AWS RDS database live and accessible
- Python script that updates data nightly (cron job or AWS Lambda)
- Performance analysis (query times before/after optimization)
- Indexes designed to improve 3 key queries
- Architecture diagram (data flow, storage, compute)
- GitHub repo with all code + AWS setup guide

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **AWS Implementation** | RDS properly configured, secure, monitored | RDS works, basic configuration | Connection/setup issues |
| **Optimization** | 30%+ performance gain, indexes chosen strategically | 10-20% improvement, reasonable indexes | Minimal or no optimization |
| **Automation** | Scheduled job runs reliably, logs captured | Job works manually, needs refinement | Automation incomplete |
| **Costs** | Careful cost optimization, documented | Aware of costs but not optimized | Unexpected high costs |
| **Documentation** | Complete architecture diagram + setup guide | Basic documentation | Incomplete instructions |

### AI Tools Integration

**Where AI Accelerates Learning:**

1. **Week 1 (SQL Fundamentals):** Use Claude/ChatGPT to:
   - Explain SQL errors ("Why does this JOIN return NULL?")
   - Generate sample SQL queries for practice
   - Validate your schema design
   - Suggest refactoring for clarity

2. **Week 4-5 (Python ETL):** Use AI to:
   - Debug pandas errors ("How do I reshape this DataFrame?")
   - Optimize code performance ("How do I vectorize this loop?")
   - Generate error handling patterns
   - Suggest pandas functions for complex transformations

3. **Week 7-8 (Cloud & Optimization):** Use AI to:
   - Troubleshoot AWS configuration issues
   - Suggest index strategies for slow queries
   - Review security practices
   - Generate Lambda function code for automation

**Studio Session Topics:**
- Week 1: ER diagram design walkthrough + SQL SELECT fundamentals
- Week 2: Advanced SQL patterns (window functions, CTEs, complex JOINs)
- Week 3: Database normalization decisions + denormalization trade-offs
- Week 4: Pandas vs. SQL + when to use each
- Week 5: Error handling patterns in Python + logging best practices
- Week 6: API authentication + managing credentials safely
- Week 7: Query optimization + index strategies
- Week 8: Final presentations + portfolio feedback

### Assessment Summary

| Component | Weight | Notes |
|-----------|--------|-------|
| Project 1 (Database Design) | 20% | Individual, schema-focused |
| Project 2 (ETL Pipeline) | 30% | Individual, Python-focused |
| Project 3 (Cloud + Optimization) | 25% | Individual, AWS-focused |
| Quizzes + DataCamp | 15% | Formative, spread across weeks |
| Studio participation + peer review | 10% | Weekly attendance, code review |

**No traditional exam.** All assessment is project-based + participation.

### Technology Stack

- **Database:** SQLFiddle (learning), MySQL/PostgreSQL locally or AWS RDS (projects)
- **Python Libraries:** pandas, sqlalchemy, requests, logging
- **Cloud:** AWS RDS (relational), AWS Free Tier or student credits
- **Tools:** Jupyter Notebooks, GitHub, Lucidchart/DrawIO for ERDs
- **Data Sources:** Yelp API, Census Bureau, Yahoo Finance, public datasets

### Prerequisites & Assumptions

- No SQL experience required
- Python fundamentals helpful (loops, functions, data types)
- Comfortable installing software + troubleshooting

---

## Part 2: BDI 513 - Data Storytelling with AI

**Credits:** 4 (Split: 2 credits Fall 1, 2 credits Fall 2) | **Status:** ✅ Ready for Fall 2026 launch

### Course Vision

Students master data visualization and narrative storytelling to communicate insights from financial, business, and public datasets. Students learn to ask questions of data, explore answers, and craft compelling narratives that drive decision-making.

### Learning Outcomes (L-C-E Framework)

#### Literacy (Foundational Awareness)
- **L1:** Understand visualization principles (Tufte, pre-attentive processing) and explain why certain charts work better than others
- **L2:** Identify the story in a dataset (trends, anomalies, comparisons)
- **L3:** Recognize when storytelling is effective vs. misleading

#### Competency (Applied Skills)
- **C1:** Create effective visualizations (bar charts, line charts, scatter plots, heatmaps) using Python and Tableau
- **C2:** Explore a dataset systematically, asking and answering questions
- **C3:** Craft a narrative arc that connects data insights to business action
- **C4:** Present findings to a live audience with clear explanations and compelling visuals

#### Expertise (Advanced Application)
- **E1:** Design a multi-part data story with sub-narratives that reinforce main message
- **E2:** Critique visualization choices in published reports and suggest improvements
- **E3:** Use advanced Tableau features (calculated fields, parameters, interactive dashboards)

### Part 1: Fall 1 (Weeks 1-8) - Foundation

| Week | Topic | Lectures | Project Work | Studio Session | Assessment |
|------|-------|----------|--------------|----------------|------------|
| **1** | Storytelling principles + Tufte | 2 videos | Project 1A: Case analysis | *Storytelling fundamentals* - effective charts | Case reading quiz |
| **2** | Exploratory analysis + Python viz | 3 videos | Project 1 work: Explore dataset | *Exploratory data analysis in pandas* | Notebook submission |
| **3** | Tableau intro + interactivity | 2 videos | Project 1 work: Build dashboard | *Tableau Public workshop* - drag/drop interface | Tableau dashboard due |
| **4** | Color, design, accessibility | 2 videos | Project 2A: Financial deep-dive | *Visualization accessibility* - colorblind-friendly palettes | Design critique |
| **5** | Narrative structure + business context | 2 videos | Project 2 work: Analysis + draft narrative | *Narrative workshop* - story arc, key insights | Draft write-up |
| **6** | Exploring financial data + APIs | 2 videos | Project 2 work: Company analysis in depth | *Financial APIs* - pulling stock, earnings, news data | Data gathering checkpoint |
| **7** | Advanced Python visualization | 2 videos | Project 2 work: Finalize analysis | *Matplotlib + seaborn advanced* - custom charts | Notebook review |
| **8** | Synthesis + peer feedback | 1 video | Final prep for Part 1 submission | *Peer feedback circles* - giving/receiving critique | Part 1 submission |

### Part 2: Fall 2 (Weeks 9-16) - Deepening

| Week | Topic | Lectures | Project Work | Studio Session | Assessment |
|------|-------|----------|--------------|----------------|------------|
| **9** | Storytelling in practice + case studies | 2 videos | Project 2 refine: Integrate feedback | *Case study analysis* - how do companies tell data stories | Case worksheet |
| **10** | Time series storytelling | 2 videos | Project 2 work: Add time-series analysis | *Time series visualization* - line charts, trend analysis | Visualization critiques |
| **11** | Cluster analysis + segmentation | 2 videos | Project 2 work: Customer/market segmentation | *Segmentation storytelling* - how to explain clusters | Segment narratives |
| **12** | Dashboard design + interactivity | 2 videos | Project 3A: Final dashboard design | *Advanced Tableau* - parameters, filters, drill-down | Dashboard mockup |
| **13** | Presenting to stakeholders | 1 video | Project 3 work: Build final dashboard | *Presentation skills workshop* - live practice | Practice presentation |
| **14** | Current events + trending stories | 2 videos | Project 3 work: Complete analysis | *Current data stories* - analyzing trending topics | News analysis write-up |
| **15** | Final presentations (live) | — | Final prep | *Live presentations* - 15 min + Q&A, peer evaluation | Presentation (graded) |
| **16** | Reflection + portfolio curation | — | Portfolio assembly + final write-up | *Portfolio feedback* - 1-on-1 review | Final submission |

### Projects (3 across both parts)

#### Project 1: Case Study Analysis (Fall 1, Weeks 1-3, Individual, 15% of grade)

**Problem Statement:** Analyze a published report or dataset visualization. Critique what works, what doesn't, and redesign one visualization to tell the story better.

**Options:**
- FT Visual Storytelling pieces (Financial Times)
- Harvard Business Review data articles
- Our World in Data datasets
- ProPublica investigations
- Kaggle dataset + published analysis

**Deliverables:**
- 2-page written critique (what's effective, what's confusing)
- Redesigned visualization in Tableau Public
- Explanation of design choices
- Jupyter notebook with data loaded + analysis

**Rubric:**

| Dimension | Excellent | Proficient | Developing |
|-----------|-----------|-----------|-----------|
| **Critique** | Insightful analysis with specific examples | Identifies strengths + weaknesses | Superficial critique |
| **Redesign** | New visualization more effective | Improves on original | Similar to original |
| **Written explanation** | Clear rationale, references design principles | Explains choices | Minimal explanation |
| **Technical execution** | Clean code, well-organized notebook | Works, some messiness | Errors or incomplete |

#### Project 2: Financial Deep-Dive Analysis (Weeks 4-8 Fall 1, Weeks 9-14 Fall 2, Individual, 50% of grade)

**Problem Statement:** Select a publicly-traded company. Analyze financial performance, market trends, and competitive position over 5-10 years. Tell the story of what happened.

**Company Options:**
- Tech giants (Apple, Microsoft, Google, Tesla)
- Finance/Banking (JPMorgan, Wells Fargo, crypto companies)
- Retail/Consumer (Walmart, Amazon, Nike)
- Healthcare/Biotech
- Energy/Utilities
- Student's choice (approved by instructor)

**Data Sources:**
- SEC 10-K filings (use Edgar API or preprocessed data)
- Yahoo Finance (stock prices, fundamentals)
- Company earnings calls (earnings transcript + guidance)
- News articles (LLM-powered sentiment analysis)
- Competitor data (industry benchmarks)

**Deliverables (Progressive):**
- **Weeks 4-5:** Data exploration notebook + 3-5 initial visualizations
- **Weeks 6-7:** Preliminary write-up (3-5 pages) + 8-10 polished visualizations + Tableau dashboard (5-8 charts)
- **Weeks 9-14:** Refined narrative + advanced analysis (segmentation, causality exploration, prediction) + interactive dashboard
- **Week 15:** Live presentation (15 min) + investor-ready deck (10 slides)
- **Week 16:** Final GitHub repo with all code, data, dashboards, presentation deck

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Data Exploration** | Systematic, creative questions, insights | Explores key areas, some surface | Shallow exploration |
| **Visualizations** | Compelling, precise, story-driven | Clear and correct | Confusing or cluttered |
| **Narrative Arc** | Coherent story with beginning/middle/end | Logical flow, some disconnects | Disjointed or missing context |
| **Financial Understanding** | Explains drivers of performance, competitive position | Shows understanding | Superficial understanding |
| **Presentation** | Clear, confident, handles questions well | Adequate, minor stumbles | Unclear or unprepared |

#### Project 3: Capstone Dashboard + Pitch (Fall 2, Weeks 12-16, Individual, 35% of grade)

**Problem Statement:** Create a professional, interactive dashboard that tells the complete story of your company analysis. Practice pitching your findings to investors/stakeholders.

**Deliverables:**
- Interactive Tableau dashboard (public, embedded in portfolio)
  - 5-8 key charts telling the story
  - Filters + parameters for interactivity
  - Clear titles, labels, annotations
  - Export to PDF for presentations
- Investor-ready deck (10 slides, 2 min narration)
- Executive summary (1-page)
- 15-minute live presentation to class + Q&A
- Recorded pitch (3 min, for portfolio)
- GitHub repo with final analysis code + narrative

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Dashboard Design** | Professional, intuitive, story-focused | Functional, mostly clear | Cluttered or confusing |
| **Interactivity** | Meaningful filters, enables exploration | Some interactive elements | Static or irrelevant filters |
| **Presentation Skills** | Confident, clear, engages audience | Adequate delivery | Unclear or unprepared |
| **Business Insight** | Actionable recommendations, strategic insight | Identifies opportunities | Surface-level observations |
| **Polish** | Publication-ready, no errors | Minor typos/issues | Needs polish |

### AI Tools Integration

**Fall 1 (Weeks 1-8):**
1. Use Claude/ChatGPT to:
   - Suggest visualization types for different data
   - Debug Python visualization code
   - Generate narrative outlines ("What's the story in this financial data?")
   - Critique your draft visualizations

2. Use AI for:
   - Extracting text from PDFs (annual reports, earnings calls)
   - Summarizing long financial documents
   - Suggesting analytical questions to ask of data

**Fall 2 (Weeks 9-16):**
1. Use AI to:
   - Analyze financial statements (what do these metrics mean?)
   - Generate dashboard design suggestions
   - Practice pitch feedback ("How would investors react?")
   - Refine narrative language for clarity

2. Advanced applications:
   - Sentiment analysis of earnings call transcripts (Claude API)
   - Market sentiment from news (use AI to score articles)
   - Competitive intelligence (summarize competitor reports)

**Studio Session Topics:**
- Week 1: Storytelling fundamentals + effective visualization principles
- Week 2: Exploratory data analysis workflows
- Week 3: Tableau Public workshop + dashboard design
- Week 4: Color theory + accessibility in visualization
- Week 5: Writing compelling narratives + business context
- Week 6: Financial APIs + data gathering
- Week 7: Advanced Python visualization + custom charts
- Week 8: Peer feedback workshop + revision strategies
- Week 9: Case study analysis + how companies tell stories
- Week 10: Time series storytelling + trend analysis
- Week 11: Segmentation + cluster storytelling
- Week 12: Advanced Tableau + dashboard interactivity
- Week 13: Presentation skills + handling Q&A
- Week 14: Current events + trending data stories
- Week 15: Live presentations + peer evaluation
- Week 16: Portfolio curation + reflective writing

### Assessment Summary

| Component | Weight | Notes |
|-----------|--------|-------|
| Project 1 (Case Study) | 15% | Analysis + redesign, weeks 1-3 |
| Project 2 (Deep-Dive) | 50% | Semester-long, progressive submissions |
| Project 3 (Capstone) | 25% | Dashboard + presentation, weeks 12-16 |
| Studio participation | 10% | Weekly attendance + peer feedback |

**No traditional exam.** Semester-long project with progressively refined outputs.

### Technology Stack

- **Visualization:** Python (matplotlib, seaborn, plotly), Tableau Public
- **Data:** pandas, numpy for exploration
- **APIs:** yfinance, edgar-online (for SEC filings), newsapi, Twitter API
- **Notebook:** Jupyter, Google Colab
- **Presentation:** Tableau dashboards, Google Slides or PowerPoint

### Prerequisites

- Comfortable with Python (or willing to learn alongside course)
- Interest in business/finance (no finance expertise required)
- Comfortable public speaking

---

## Part 3: FIN 550 / MSBAi550 - Analytics for Business

**Credits:** 4 | **Term:** Fall 2 (Weeks 9-16) | **Status:** ✅ Ready for Fall 2026 launch

### Course Vision

Students learn machine learning fundamentals applied to business problems. Unlike on-campus version, we skip causal inference details and focus on prediction, classification, and clustering. Real finance-oriented projects keep students engaged. AI tools demonstrate how LLMs accelerate model building.

### Learning Outcomes (L-C-E Framework)

#### Literacy (Foundational Awareness)
- **L1:** Understand supervised vs. unsupervised learning and explain when each applies
- **L2:** Recognize overfitting and describe train/test/validation splits
- **L3:** Explain what accuracy, precision, recall mean and why they matter for different problems

#### Competency (Applied Skills)
- **C1:** Build regression models (linear, logistic) using scikit-learn for prediction
- **C2:** Build classification models (decision trees, random forests) for categorical outcomes
- **C3:** Evaluate models rigorously (cross-validation, ROC curves, confusion matrices)
- **C4:** Communicate model performance to non-technical stakeholders

#### Expertise (Advanced Application)
- **E1:** Compare multiple model types and choose the best based on business criteria
- **E2:** Engineer features from raw business data to improve model performance
- **E3:** Deploy a simple model to production (containerized or API)

### Week-by-Week Breakdown

| Week | Topic | Lectures | Project Work | Studio Session | Assessment |
|------|-------|----------|--------------|----------------|------------|
| **9** | Intro to ML + supervised learning | 3 videos | Project 1A: Regression problem setup | *ML fundamentals* - supervised vs. unsupervised | Quiz (L1-L2) |
| **10** | Linear regression + evaluation | 3 videos | Project 1 work: Build baseline model | *Regression workshop* - sklearn patterns, evaluation metrics | Code review |
| **11** | Logistic regression + classification | 3 videos | Project 1 work: Classification model | *Classification deep-dive* - logistic, decision boundaries | Project 1 due |
| **12** | Tree-based models + ensembles | 3 videos | Project 2A: Feature engineering | *Random forests workshop* - why ensembles work | DataCamp assignment |
| **13** | Feature engineering + selection | 2 videos | Project 2 work: Complex model building | *Feature engineering tactics* - domain knowledge + data-driven | Mid-course checkpoint |
| **14** | Clustering + dimensionality reduction | 2 videos | Project 2 work: Clustering analysis | *Unsupervised learning* - K-means, UMAP visualization | Clustering assignment |
| **15** | Time series basics + model deployment | 2 videos | Project 3A: Deploy simple model | *Model serving* - REST API, Docker basics | Deployment demo |
| **16** | Synthesis + business recommendations | 1 video | Project 3 complete | *Final presentations* - sharing insights with stakeholders | Projects 2 & 3 due |

### Projects (3 per course)

#### Project 1: Supervised Learning End-to-End (Weeks 9-11, Individual, 25% of grade)

**Problem Statement:** Predict a business outcome using supervised learning. Choose regression (continuous target) or classification (binary/multiclass). Real financial data preferred.

**Options:**
- **Regression:** Predict stock price tomorrow, house prices, customer lifetime value
- **Classification:** Predict loan default (yes/no), customer churn (yes/no), credit card fraud (yes/no)

**Datasets Available:**
- US housing prices (Kaggle)
- Stock prices (Yahoo Finance API)
- Loan defaults (LendingClub)
- Credit card fraud (Kaggle)
- Student choice (approved)

**Deliverables:**
- Jupyter notebook with exploratory analysis
- Clean, documented code (functions, classes)
- Train/test split + cross-validation
- 2-3 model comparisons (at least one baseline)
- Evaluation metrics (MSE/RMSE for regression, F1/AUC for classification)
- 2-page write-up explaining model choice + business implications
- GitHub repo with all code

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Problem Understanding** | Clear definition, appropriate metric chosen | Understands core problem | Vague problem statement |
| **Data Handling** | Thoughtful train/test/validation split, cross-validation | Train/test present | Data leakage or poor split |
| **Model Building** | 2-3 diverse models with justification | 2 models, basic comparison | Single model or poor comparison |
| **Evaluation** | Rigorous evaluation, explains metrics | Computes metrics, interpretation okay | Weak evaluation |
| **Writeup** | Clear explanation, connects to business | Adequate explanation | Minimal writeup |

#### Project 2: Feature Engineering + Advanced Models (Weeks 12-14, Individual, 35% of grade)

**Problem Statement:** Improve your Project 1 model using feature engineering, ensembles, and hyperparameter tuning. Compete on leaderboard (if using Kaggle) or optimize business metric.

**Deliverables:**
- Feature engineering notebook (create 5-10 new features with justification)
- Model comparison (gradient boosting, XGBoost, or neural net vs. baseline)
- Hyperparameter tuning results (grid search or random search)
- Feature importance analysis (which features matter most?)
- Evaluation metrics showing improvement over Project 1
- Learning curves (showing where you have bias vs. variance)
- 3-page write-up explaining improvements
- GitHub repo with final code + model artifacts

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Feature Engineering** | Creative features with domain insight | Standard feature creation | Minimal feature work |
| **Model Selection** | Advanced models well-justified | Good model choices | Limited exploration |
| **Hyperparameter Tuning** | Systematic grid/random search with analysis | Some tuning attempted | Minimal tuning |
| **Results** | Significant improvement with clear wins | Modest improvement | Little/no improvement |
| **Analysis** | Explains why improvements worked | Describes metrics | Minimal analysis |

#### Project 3: Model Deployment + Business Case (Weeks 15-16, Individual, 30% of grade)

**Problem Statement:** Deploy your model to production. Build a simple API or web interface. Write a business case for stakeholders.

**Deliverables:**
- Dockerized model or cloud-deployed API (AWS Lambda, Heroku, or similar)
- REST API endpoint that accepts input and returns predictions
- Unit tests for critical functions
- API documentation (how to use it)
- Business case document (5 pages):
  - Executive summary
  - Model performance + baseline comparison
  - Recommended business action
  - Limitations + risks
  - ROI calculation (if applicable)
- Live demo (either API call or web interface)
- GitHub repo with all code + deployment instructions

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Deployment** | Model properly containerized + accessible | Runs on cloud platform | Local only or fragile |
| **Testing** | Unit tests + integration tests | Some tests present | Minimal testing |
| **API Design** | Clear, well-documented, handles errors | Functional, basic docs | Hard to use |
| **Business Case** | Compelling, data-driven, actionable | Addresses most points | Incomplete or unclear |
| **ROI Calculation** | Thoughtful cost-benefit analysis | Estimates provided | Missing or speculative |

### AI Tools Integration

**Week 9-11 (Supervised Learning):**
1. Use Claude/ChatGPT to:
   - Explain model selection for your problem
   - Debug scikit-learn errors
   - Suggest evaluation metrics
   - Interpret model results

2. Use AI to:
   - Generate feature engineering ideas
   - Review code for pythonic style
   - Suggest sklearn documentation links

**Week 12-14 (Advanced Models):**
1. Use AI to:
   - Explain hyperparameter tuning strategies
   - Debug XGBoost/gradient boosting issues
   - Generate feature combinations
   - Suggest regularization approaches

**Week 15-16 (Deployment):**
1. Use AI to:
   - Write Docker configuration
   - Build Flask/FastAPI endpoints
   - Generate unit test templates
   - Review API design

**Studio Session Topics:**
- Week 9: Supervised learning overview + sklearn workflow
- Week 10: Train/test/validation splits + cross-validation
- Week 11: Classification metrics deep-dive (precision, recall, F1, ROC)
- Week 12: Feature engineering tactics + domain knowledge
- Week 13: Ensemble methods + gradient boosting
- Week 14: Hyperparameter tuning + computational costs
- Week 15: Model deployment + containerization (Docker basics)
- Week 16: Final presentations + business case review

### Assessment Summary

| Component | Weight | Notes |
|-----------|--------|-------|
| Project 1 (Supervised Learning) | 25% | Weeks 9-11, regression or classification |
| Project 2 (Feature Engineering) | 35% | Weeks 12-14, improvements over baseline |
| Project 3 (Deployment) | 30% | Weeks 15-16, production-ready + business case |
| Studio participation + DataCamp | 10% | Spread throughout course |

**No traditional exam.** Project-based with progressive complexity.

### Technology Stack

- **ML Library:** scikit-learn, XGBoost, LightGBM
- **Data:** pandas, numpy
- **Visualization:** matplotlib, seaborn, Plotly
- **Deployment:** Docker, Flask/FastAPI, AWS Lambda or Heroku
- **Notebook:** Jupyter, Google Colab
- **APIs:** yfinance, Kaggle API

### Prerequisites

- Python programming (from BADM 554 or equivalent)
- Basic statistics helpful but not required

---

## Part 4: BADM 557 - Business Intelligence with AI

**Credits:** 4 | **Term:** Spring 1 (Weeks 17-24) | **Status:** ✅ Ready for Spring 2027 launch

### Course Vision

Students master business intelligence—combining data analysis, visualization, and business intuition to solve real problems. Using cases from Harvard Business School + modern AI tools, students learn to ask business questions, find answers in data, and present insights clearly.

### Learning Outcomes (L-C-E Framework)

#### Literacy (Foundational Awareness)
- **L1:** Explain what business intelligence is and distinguish BI from analytics
- **L2:** Identify stakeholder questions that data can answer
- **L3:** Recognize ethical issues in data analysis (bias, privacy, misrepresentation)

#### Competency (Applied Skills)
- **C1:** Use data to answer business questions (find root causes, forecast, segment)
- **C2:** Build a BI dashboard that executives would actually use
- **C3:** Explain analytical findings to non-technical stakeholders
- **C4:** Apply classifiers and clustering to business decisions

#### Expertise (Advanced Application)
- **E1:** Design an end-to-end BI solution for a business problem
- **E2:** Combine multiple data sources into coherent insights
- **E3:** Recommend business actions based on analytical findings

### Week-by-Week Breakdown

| Week | Topic | Lectures | Project Work | Studio Session | Assessment |
|------|-------|----------|--------------|----------------|------------|
| **17** | BI fundamentals + case analysis | 2 videos | Project 1A: Case read + questions | *BI principles* - what questions can data answer | Case quiz |
| **18** | Analytics lifecycle + hypothesis testing | 2 videos | Project 1 work: Data exploration | *Hypothesis testing workshop* - A/B test, significance | Case write-up |
| **19** | Classification + decision-making | 2 videos | Project 1 work: Build classifier | *Classification in practice* - how to interpret for decisions | Project 1 due |
| **20** | Dashboard design + Tableau deep-dive | 2 videos | Project 2A: Tableau setup + design | *Tableau for executives* - what dashboards should show | Dashboard mockup |
| **21** | Real-world BI challenges | 2 videos | Project 2 work: Build dashboard | *Data quality + governance* - what goes wrong in practice | Quality assessment |
| **22** | Clustering + segmentation | 2 videos | Project 2 work: Segmentation analysis | *Customer segmentation* - clustering for business decisions | Segment memo |
| **23** | Business communication + storytelling | 1 video | Project 3A: Present findings | *Executive communication* - clear, concise, actionable | Draft presentation |
| **24** | Synthesis + case presentations | — | Final prep + reflection | *Live case presentations* - peer Q&A | Final presentations |

### Projects (3 per course)

#### Project 1: Case Analysis + Classifier (Weeks 17-19, Individual, 25% of grade)

**Problem Statement:** Analyze a Harvard Business School case. Use data to make the decision the protagonist faced. Build a classifier if applicable.

**Cases Available:**
- **Retailers (with sales data):** Optimize inventory or staffing
- **Financial (with market data):** Predict credit risk or fraud
- **Operations (with process data):** Optimize supply chain or workflows
- **Marketing (with campaign data):** Predict customer response or churn
- **Instructor-provided real data:** Use current business problem

**Deliverables:**
- Case read + 2-page summary of business problem
- Data exploration notebook (visualizations, patterns, hypotheses)
- Classifier or regression model (if applicable to case)
- Memorandum (2-3 pages) with recommendation
- GitHub repo with analysis code

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Case Understanding** | Deep understanding of context + constraints | Good understanding | Surface-level reading |
| **Data Analysis** | Systematic exploration, clear insights | Adequate exploration | Shallow analysis |
| **Recommendation** | Well-justified, considers trade-offs | Defensible | Unclear rationale |
| **Model Quality** | Rigorous approach if classifier built | Functional model | Model issues |
| **Written Communication** | Professional memo, clear recommendation | Adequate write-up | Unclear or incomplete |

#### Project 2: BI Dashboard + Segmentation (Weeks 20-22, Individual, 35% of grade)

**Problem Statement:** Design a comprehensive BI dashboard for a business problem. Include segmentation analysis to understand customer/market groups.

**Problem Options:**
- **E-commerce:** Customer segmentation + churn dashboard
- **Finance:** Portfolio analytics + risk dashboard
- **Healthcare:** Patient segmentation + outcomes dashboard
- **Retail:** Sales analytics + inventory dashboard
- **Student choice (approved)**

**Deliverables:**
- Problem definition (1 page: business context, key questions)
- Data exploration notebook (understand data quality, distributions)
- Tableau dashboard (5-8 visualizations showing KPIs, trends, segments)
- Segmentation analysis:
  - Clustering (K-means or hierarchical) on customer/entity data
  - Segment profiles (size, characteristics, behavior)
  - Business implications of each segment
- 3-page analysis document:
  - Dashboard overview + how to use it
  - Segment descriptions + recommendations
  - Technical approach + limitations
- GitHub repo with code + data

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Dashboard Design** | Professional, intuitive, actionable insights | Clear layout, good coverage | Cluttered or confusing |
| **Segmentation** | Meaningful clusters, clear business implications | Clusters identified | Limited insight |
| **Tableau Proficiency** | Advanced features (parameters, calculated fields) | Standard features used well | Basic functionality |
| **Analysis Depth** | Explores "why" behind segments and trends | Describes what | Surface observations |
| **Documentation** | Clear guide for stakeholders | Adequate explanation | Minimal docs |

#### Project 3: Capstone BI Project + Presentation (Weeks 23-24, Individual, 30% of grade)

**Problem Statement:** Design and execute an end-to-end BI solution. Present recommendations to a mock leadership team.

**Deliverables:**
- Refined dashboard (5-8 interactive visualizations)
- Executive brief (1 page: situation, 3 key findings, recommendation)
- Detailed analysis (5-7 pages):
  - Problem statement + business context
  - Segmentation findings
  - Key insights + root causes
  - Recommended actions + expected impact
  - Limitations + risks
  - Implementation roadmap
- Live presentation (15 min) to mock leadership team + Q&A
- GitHub repo with all code + dashboards

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Dashboard** | Executive-ready, clear story, interactive | Functional, mostly clear | Needs polish |
| **Analysis** | Deep insights, data-driven recommendations | Good analysis | Shallow or missing insights |
| **Presentation** | Confident, clear, handles questions well | Adequate delivery | Unclear or unprepared |
| **Business Acumen** | Understands constraints, realistic recommendations | Shows business sense | Generic or impractical |
| **Completeness** | All components polished + integrated | Components present | Incomplete |

### AI Tools Integration

**Weeks 17-19 (Case Analysis):**
1. Use Claude/ChatGPT to:
   - Explain business context from case
   - Suggest features for classification model
   - Interpret classifier results
   - Generate memo structure + language

**Weeks 20-22 (Dashboard):**
1. Use AI to:
   - Suggest dashboard design (what charts for what questions)
   - Generate Tableau calculation syntax
   - Create segment profiles and narratives
   - Review dashboard usability

**Weeks 23-24 (Capstone):**
1. Use AI to:
   - Refine recommendations for clarity
   - Draft executive brief language
   - Generate presentation slides
   - Practice Q&A scenarios

**Studio Session Topics:**
- Week 17: BI principles + analytics lifecycle
- Week 18: Case analysis strategy + asking the right questions
- Week 19: Classification for business decisions
- Week 20: Dashboard design best practices + Tableau architecture
- Week 21: Real-world BI challenges + data quality issues
- Week 22: Customer segmentation + actionable clusters
- Week 23: Executive communication + presenting to leadership
- Week 24: Live presentations + peer feedback

### Assessment Summary

| Component | Weight | Notes |
|-----------|--------|-------|
| Project 1 (Case Analysis) | 25% | Weeks 17-19, individual, case-driven |
| Project 2 (Dashboard) | 35% | Weeks 20-22, dashboard + segmentation |
| Project 3 (Capstone BI) | 30% | Weeks 23-24, end-to-end + presentation |
| Studio participation | 10% | Weekly attendance + peer feedback |

**No traditional exam.** Project-based with business focus.

### Technology Stack

- **BI Tool:** Tableau Public or Desktop (academic license)
- **Analytics:** Python (scikit-learn, pandas, seaborn)
- **Data:** HBS cases datasets + public business data
- **Clustering:** scikit-learn (K-means, hierarchical)
- **Notebook:** Jupyter, Google Colab
- **Tools:** GitHub for version control

### Prerequisites

- Completion of BADM 554, BDI 513, FIN 550 (or equivalent)
- Comfortable with Python + data exploration

---

## Part 5: BADM 558 - Big Data Infrastructure

**Credits:** 4 | **Term:** Spring 2 (Weeks 25-32) | **Status:** ✅ Ready for Spring 2027 launch

### Course Vision

Students master cloud-based big data infrastructure. Using AWS services, students build scalable data pipelines, work with cloud storage (S3), distributed processing (Spark), and data warehouses. By course end, students understand how to architect data systems for large-scale applications.

### Learning Outcomes (L-C-E Framework)

#### Literacy (Foundational Awareness)
- **L1:** Explain cloud computing benefits (scalability, cost, flexibility) and describe major cloud providers
- **L2:** Understand when big data infrastructure is needed vs. traditional databases
- **L3:** Recognize AWS service categories (compute, storage, database, analytics)

#### Competency (Applied Skills)
- **C1:** Build data pipelines using AWS (S3, EC2, Lambda)
- **C2:** Use Apache Spark for distributed processing of large datasets
- **C3:** Design and query data warehouses (Redshift or similar)
- **C4:** Implement basic data security and IAM practices

#### Expertise (Advanced Application)
- **E1:** Architect an end-to-end big data solution (ingest → store → process → analyze)
- **E2:** Optimize data pipelines for cost and performance
- **E3:** Implement monitoring, logging, and error handling for production systems

### Week-by-Week Breakdown

| Week | Topic | Lectures | Project Work | Studio Session | Assessment |
|------|-------|----------|--------------|----------------|------------|
| **25** | Cloud fundamentals + AWS overview | 3 videos | Project 1A: AWS account setup | *AWS fundamentals* - regions, services, free tier | AWS setup quiz |
| **26** | S3 + data lakes | 2 videos | Project 1 work: Upload data to S3 | *S3 workshop* - buckets, prefixes, permissions | Data upload |
| **27** | EC2 + compute instances | 2 videos | Project 1 work: Spin up instances | *EC2 deep-dive* - instance types, security groups | Instance launch |
| **28** | Spark fundamentals + RDD/DataFrames | 3 videos | Project 2A: Spark cluster setup | *Spark basics* - distributed processing, lazy evaluation | Spark job submission |
| **29** | Spark SQL + data processing | 3 videos | Project 2 work: Process large dataset | *Spark SQL* - DataFrame operations at scale | Code review |
| **30** | Data warehousing + Redshift intro | 2 videos | Project 2 work: Load warehouse | *Redshift* - columnar storage, SQL queries | Warehouse query |
| **31** | Data pipelines + orchestration | 2 videos | Project 3A: Build end-to-end pipeline | *Lambda + Step Functions* - serverless automation | Mid-course checkpoint |
| **32** | Security, monitoring, synthesis | 1 video | Project 3 complete + reflection | *AWS security + monitoring* - logging, alerts, cost | Final presentations |

### Projects (3 per course)

#### Project 1: Cloud Data Lake Setup (Weeks 25-27, Individual, 20% of grade)

**Problem Statement:** Build a cloud data lake on AWS. Ingest data from multiple sources (public datasets, APIs, local files) into S3. Organize with proper naming conventions, partitioning, and metadata.

**Deliverables:**
- AWS S3 bucket created with proper structure (raw, processed, output folders)
- At least 2 data sources ingested:
  - Public dataset (Kaggle, government data, etc.)
  - API data (weather, stocks, social media, etc.)
- Data organization with clear naming conventions
- Metadata documentation (what data, when updated, definitions)
- Basic access control (IAM roles, bucket policies)
- Cost estimation document
- GitHub repo with infrastructure code (CloudFormation or Terraform templates, if desired)

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **S3 Organization** | Well-structured with clear partitioning | Organized, some redundancy | Messy or hard to navigate |
| **Data Ingestion** | Multiple sources, automated process | 2 sources, some manual steps | Limited sources or manual only |
| **Documentation** | Clear metadata, data dictionary | Adequate documentation | Minimal docs |
| **Security** | Proper IAM roles, bucket policies | Basic security | Missing security |
| **Cost Awareness** | Monitored costs, optimized | Aware of costs | No cost tracking |

#### Project 2: Spark Data Processing (Weeks 28-30, Individual, 35% of grade)

**Problem Statement:** Process a large dataset using Apache Spark. Clean, transform, and aggregate data. Load results into a data warehouse or new S3 location.

**Dataset Options:**
- 1GB+ public dataset (Wikipedia, Amazon reviews, GitHub, Twitter, etc.)
- User's own data (CSV, Parquet, JSON)
- Synthetic/generated big data

**Deliverables:**
- PySpark application (Python + Spark DataFrame API)
- Data cleaning + transformation logic
- Aggregations and analytical queries
- Output saved to S3 or Redshift
- Performance analysis:
  - Execution time with different cluster sizes
  - Cost estimates for 1-node, 5-node, 10-node clusters
  - Optimization recommendations
- Jupyter notebook explaining approach + results
- GitHub repo with PySpark code + data schema

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Spark Code** | Efficient transformations, proper caching | Functional code | Inefficient or problematic |
| **Data Quality** | Handles missing values, edge cases | Handles common cases | Errors or data loss |
| **Performance** | Optimized partitioning, justifies choices | Adequate performance | Unoptimized or slow |
| **Documentation** | Clear explanation of transformations | Adequate explanation | Minimal docs |
| **Cost Analysis** | Detailed estimates, optimization ideas | Basic estimates | Missing analysis |

#### Project 3: End-to-End Data Pipeline (Weeks 31-32, Individual, 35% of grade)

**Problem Statement:** Design and implement a complete big data pipeline. Automate daily/weekly data ingestion, processing, and loading. Build a simple dashboard or reporting layer.

**Pipeline Components:**
1. **Ingestion:** Scheduled data pull (S3 from API, CloudWatch logs, or other source)
2. **Processing:** Spark job cleaning + transforming data
3. **Storage:** Results stored in data lake (S3) or warehouse (Redshift)
4. **Reporting:** Simple dashboard or SQL queries showing results

**Deliverables:**
- AWS Lambda function(s) for scheduled ingestion
- Spark job for data processing
- AWS Step Functions workflow orchestrating the pipeline
- CloudWatch monitoring + alarms
- Cost estimation (monthly running cost)
- Architecture diagram
- Operational runbook (how to monitor + troubleshoot)
- GitHub repo with all code + infrastructure templates
- Live demo of pipeline in action (or scheduled run with logs)

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Pipeline Architecture** | Well-designed, scalable, modular | Functional, some inefficiency | Basic or problematic design |
| **Automation** | Fully automated, scheduled correctly | Mostly automated | Manual steps remaining |
| **Monitoring** | Comprehensive logging + alerts | Basic monitoring | Minimal visibility |
| **Documentation** | Clear runbook + architecture diagram | Adequate documentation | Minimal docs |
| **Production Readiness** | Error handling, rollback plan, tested | Mostly robust | Lacks error handling |

### AI Tools Integration

**Weeks 25-27 (Cloud Setup):**
1. Use Claude/ChatGPT to:
   - Explain AWS services + when to use each
   - Debug IAM permission issues
   - Generate S3 naming conventions
   - Review bucket policies

**Weeks 28-30 (Spark Processing):**
1. Use AI to:
   - Suggest Spark DataFrame transformations
   - Debug PySpark errors
   - Optimize partitioning strategy
   - Generate cost calculations

**Weeks 31-32 (Pipeline):**
1. Use AI to:
   - Generate Lambda function code
   - Debug Step Functions workflows
   - Suggest monitoring strategies
   - Review error handling patterns

**Studio Session Topics:**
- Week 25: Cloud fundamentals + AWS services overview
- Week 26: S3 workshop + data lake organization
- Week 27: EC2 + security groups + SSH basics
- Week 28: Spark architecture + RDD/DataFrame concepts
- Week 29: Spark SQL optimization + cost implications
- Week 30: Data warehouse design + Redshift queries
- Week 31: Orchestration + scheduling (Lambda, Step Functions, Airflow)
- Week 32: Monitoring + operational best practices

### Assessment Summary

| Component | Weight | Notes |
|-----------|--------|-------|
| Project 1 (Data Lake) | 20% | Weeks 25-27, S3 setup |
| Project 2 (Spark Processing) | 35% | Weeks 28-30, distributed computing |
| Project 3 (End-to-End Pipeline) | 35% | Weeks 31-32, production-like system |
| Studio participation | 10% | Weekly attendance |

**No traditional exam.** Project-based with infrastructure focus.

### Technology Stack

- **Cloud:** AWS (S3, EC2, Lambda, RDS, Redshift, Step Functions)
- **Processing:** Apache Spark (PySpark), Python
- **Languages:** Python, SQL
- **Infrastructure:** CloudFormation or Terraform (optional)
- **Monitoring:** CloudWatch, X-Ray
- **Notebook:** Jupyter with Spark kernel

### Prerequisites

- Completion of BADM 554 (SQL) + FIN 550 (Python) (or equivalent)
- Comfortable with Linux command line (SSH, file operations)

---

## Part 6: BADM 576 - Data Science & Machine Learning

**Credits:** 4 | **Term:** Summer (Weeks 33-40) | **Status:** ✅ Ready for Summer 2027 launch

### Course Vision

Students master the full machine learning lifecycle—from problem definition through model deployment. This course is the capstone of analytics skill-building, combining stats, algorithms, feature engineering, and business acumen into a comprehensive data science approach.

### Learning Outcomes (L-C-E Framework)

#### Literacy (Foundational Awareness)
- **L1:** Understand the ML lifecycle (problem definition, data collection, feature engineering, modeling, evaluation, deployment)
- **L2:** Explain different ML paradigms (supervised, unsupervised, reinforcement learning)
- **L3:** Recognize ethical issues in ML (bias, fairness, transparency)

#### Competency (Applied Skills)
- **C1:** Build an end-to-end ML system from raw data to predictions
- **C2:** Engineer features from domain knowledge + data-driven approaches
- **C3:** Compare multiple ML algorithms and choose the best for your problem
- **C4:** Evaluate models rigorously and communicate uncertainties

#### Expertise (Advanced Application)
- **E1:** Diagnose and fix model problems (underfitting, overfitting, data drift)
- **E2:** Deploy and monitor models in production
- **E3:** Build ML systems that fairness and bias

### Week-by-Week Breakdown

| Week | Topic | Lectures | Project Work | Studio Session | Assessment |
|------|-------|----------|--------------|----------------|------------|
| **33** | ML lifecycle + problem definition | 2 videos | Project 1A: Problem framing | *Defining ML problems* - how to know if ML is right | Problem worksheet |
| **34** | Exploratory data analysis + feature engineering | 3 videos | Project 1 work: Data exploration + features | *Feature engineering tactics* - domain knowledge + data-driven | EDA notebook |
| **35** | Regression + regularization | 2 videos | Project 1 work: Regression baseline | *Regularization deep-dive* - L1/L2, elastic net | Model comparison |
| **36** | Classification + decision trees | 3 videos | Project 2A: Classification models | *Tree models workshop* - decision trees, ensembles | Code review |
| **37** | Ensemble methods + neural nets intro | 2 videos | Project 2 work: Ensemble + deep learning | *Boosting + bagging* - why ensembles work | Model evaluation |
| **38** | Text + time series ML | 2 videos | Project 2 work: NLP or time series | *NLP with scikit-learn* - TF-IDF, word embeddings | Text/time analysis |
| **39** | Model deployment + ML operations | 2 videos | Project 3A: Deploy model | *ML in production* - monitoring, retraining, A/B testing | Deployment demo |
| **40** | Ethics + synthesis | 1 video | Project 3 complete + reflection | *Ethics in ML* - bias, fairness, transparency | Final presentations |

### Projects (3 per course)

#### Project 1: Regression + Feature Engineering (Weeks 33-35, Individual, 25% of grade)

**Problem Statement:** Build a regression model to predict a continuous target. Focus on feature engineering and model selection.

**Problem Options:**
- Predict house prices (Kaggle)
- Predict stock returns (financial data)
- Predict customer spending (e-commerce data)
- Predict healthcare outcomes (medical data, anonymized)
- Student choice (approved)

**Deliverables:**
- Exploratory data analysis notebook (distributions, correlations, missing values)
- Feature engineering notebook:
  - Create 5-10 new features with justification
  - Handle categorical variables (one-hot, ordinal, embedding)
  - Scale features appropriately
- Model comparison (linear regression, regularized regression, robust regression)
- Cross-validation results + learning curves
- Feature importance analysis
- Error analysis (where does model struggle?)
- 2-page write-up explaining approach
- GitHub repo with all code

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Feature Engineering** | Creative features with domain insight | Standard feature creation | Minimal feature engineering |
| **EDA** | Systematic exploration with insights | Covers main aspects | Superficial analysis |
| **Model Selection** | Justified choices, multiple models compared | 2-3 models compared | Single model |
| **Evaluation** | Rigorous cross-validation + error analysis | Standard evaluation | Weak evaluation |
| **Documentation** | Clear explanation + code comments | Adequate explanation | Minimal docs |

#### Project 2: Classification + Ensemble Methods (Weeks 36-38, Individual, 35% of grade)

**Problem Statement:** Build a classification model using ensemble methods. Predict a binary or multiclass target. Compare with simpler baselines.

**Problem Options:**
- Customer churn prediction (telecom data)
- Credit card fraud detection (financial data)
- Email spam classification
- Disease diagnosis (medical data)
- Student choice (approved)

**Deliverables:**
- Problem definition + baseline model (simple classifier)
- Class imbalance analysis (if applicable)
- Model comparison:
  - Logistic regression (baseline)
  - Decision tree
  - Random forest
  - Gradient boosting (XGBoost or LightGBM)
  - Optional: neural network
- Evaluation metrics (accuracy, precision, recall, F1, AUC-ROC)
- Feature importance analysis
- Threshold optimization (choosing decision boundary for business context)
- 3-page write-up explaining models + business implications
- GitHub repo with code + model artifacts

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Model Diversity** | 4-5 diverse algorithms, justified | 3+ models | 2 or fewer |
| **Imbalance Handling** | Addresses class imbalance thoughtfully | Mentions imbalance | Ignores imbalance |
| **Evaluation** | Multiple metrics, threshold analysis | Standard metrics | Limited evaluation |
| **Feature Importance** | Explains what features matter + why | Identifies top features | Missing analysis |
| **Business Context** | Explains implications (precision vs. recall) | Mentions business | Only technical focus |

#### Project 3: Full ML System + Deployment (Weeks 39-40, Individual, 30% of grade)

**Problem Statement:** Build a production-ready ML system. Deploy your best model from Projects 1 or 2. Monitor performance + prepare for retraining.

**Deliverables:**
- **Model Documentation:**
  - Model card (what it does, performance, limitations, ethical considerations)
  - Data sheet (dataset provenance, bias analysis)
  - System design document (inputs, outputs, dependencies)

- **Deployment:**
  - Containerized model (Docker)
  - REST API (Flask/FastAPI)
  - Cloud deployment (AWS Lambda, Heroku, or similar)

- **Monitoring + Operations:**
  - Unit tests + integration tests
  - Performance monitoring (track model accuracy over time)
  - Data drift detection (alert if input distribution changes)
  - Retraining strategy (how often to retrain?)

- **Fairness + Ethics Analysis:**
  - Evaluate model for bias (across demographic groups if applicable)
  - Document limitations + intended use cases
  - Identify risks + mitigation strategies

- **Operational Runbook:**
  - How to deploy
  - How to monitor
  - How to troubleshoot
  - How to retrain

- **GitHub repo with:**
  - All code + tests
  - Model artifacts
  - Docker file + deployment instructions
  - Documentation

**Rubric (5 dimensions):**

| Dimension | Excellent (A) | Proficient (B) | Developing (C) |
|-----------|---------------|----------------|----------------|
| **Deployment** | Production-ready, containerized, accessible | Works on cloud | Local only |
| **Testing** | Comprehensive unit + integration tests | Some tests | Minimal testing |
| **Monitoring** | Performance + data drift monitoring | Basic tracking | No monitoring |
| **Fairness Analysis** | Thoughtful bias evaluation + mitigation | Addresses fairness | Ignores fairness |
| **Documentation** | Model card + system design complete | Adequate docs | Minimal documentation |

### AI Tools Integration

**Weeks 33-35 (Regression):**
1. Use Claude/ChatGPT to:
   - Suggest features for your domain
   - Debug scikit-learn errors
   - Explain regularization trade-offs
   - Generate feature engineering code

**Weeks 36-38 (Classification):**
1. Use AI to:
   - Explain classifier selection for your problem
   - Debug ensemble model issues
   - Suggest class imbalance solutions
   - Generate test code

**Weeks 39-40 (Deployment):**
1. Use AI to:
   - Write Docker/API code
   - Generate monitoring code
   - Create bias evaluation scripts
   - Review design for production readiness

**Studio Session Topics:**
- Week 33: ML lifecycle overview + problem framing
- Week 34: Exploratory data analysis + feature brainstorming
- Week 35: Regularization + overfitting diagnosis
- Week 36: Decision trees + interpretability
- Week 37: Ensemble methods + boosting
- Week 38: NLP + text feature engineering
- Week 39: Model deployment + containerization
- Week 40: ML ethics + fairness + responsible AI

### Assessment Summary

| Component | Weight | Notes |
|-----------|--------|-------|
| Project 1 (Regression) | 25% | Weeks 33-35, feature engineering focus |
| Project 2 (Classification) | 35% | Weeks 36-38, ensemble methods |
| Project 3 (Deployment) | 30% | Weeks 39-40, production-ready system |
| Studio participation | 10% | Weekly attendance + peer feedback |

**No traditional exam.** Project-based with production focus.

### Technology Stack

- **ML Libraries:** scikit-learn, XGBoost, LightGBM, keras/tensorflow
- **Data:** pandas, numpy, feature-engine
- **Text:** scikit-learn (TF-IDF), gensim, spacy (optional)
- **Time Series:** statsmodels, prophet
- **Deployment:** Docker, Flask/FastAPI, AWS Lambda
- **Monitoring:** evidently (for ML monitoring), custom scripts
- **Testing:** pytest, unittest
- **Notebook:** Jupyter

### Prerequisites

- Completion of FIN 550 (Python + ML basics) + BADM 558 (cloud infrastructure)
- Comfortable with Python programming + SQL

---

## Cross-Course Convergence & Integration

**Weeks Where Multiple Courses Align:**

### Visual Analytics Cluster (Weeks 3-4 across Fall 1 courses)
- **BADM 554:** SQL visualization + exploratory analysis
- **BDI 513:** Tableau + storytelling foundations
- **Studio:** Cross-course visualization workshop

### Regression Deep-Dive (Weeks 5-6)
- **BDI 513:** Financial regression + exploratory analysis
- **FIN 550:** Linear + logistic regression (when launched)
- **Studio:** Regression theory + applications across domains

### Classification & Clustering (Weeks 7-8)
- **FIN 550:** Classification + time series
- **BADM 557:** Classification for BI decisions
- **Studio:** When to use supervised vs. unsupervised learning

---

## Final Notes for Faculty

1. **Python + Jupyter Are Non-Negotiable:** Every project should include Jupyter notebooks as primary deliverables.

2. **Studio Sessions Are Key:** These are distinct from lectures. Use them to demonstrate tools, show AI-augmented workflows, and help students debug.

3. **AI Tools Throughout:** Integrate Claude/ChatGPT naturally. Show how AI accelerates work (code generation, debugging, ideation).

4. **GitHub-First:** All students should submit via GitHub. Make this a career-building habit.

5. **No Traditional Exams:** Assessment is entirely project-based. Projects demonstrate competency better than exams.

6. **Flexibility in Tool Choices:** Students can use R, other cloud platforms, etc., but Python + cloud are defaults.

---

*Document prepared: January 12, 2026*
*Next updates: As course development begins (faculty will refine week-by-week details)*
