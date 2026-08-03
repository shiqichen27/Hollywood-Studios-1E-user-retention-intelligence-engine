---

> ## Challenge Advisor: Update & Finalize Your Project Overview
>
> > 💡 **These grey text instructions are just for you, the team's Challenge Advisor; please delete them once you have completed the steps below.**
>
> We've pre-populated this Challenge Project Overview page — which is what will be shared with your Break Through Tech student team in August — using the details from your submission form. You should have received an email inviting you to join this repo as a Collaborator, enabling you to add files and make edits.
> 
> In order for your project to be finalized and assigned to a team, please:
> 1. **Review all sections below** and update or expand any content as needed, making sure to address the SME Feedback in the section immediately below. Look for square brackets to find the places below that require additional inputs from you (e.g., "About [Company / Org Name]").
> 2. **Add your dataset** to the [data folder](data) in this repo.
> 3. **Close the Issue assigned to you in this repo** to let us know that you have made your edits and the overview page is ready for final review. You can do this by going to the _Issues_ tab in the top left section of the menu above, add a comment that says "CA review complete", and click the button to Close the Issue. 
>
> If you're unfamiliar with how to edit a page like this in GitHub, check out [this tutorial](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/handson/edit-readme.html) for a quick overview (start with step 2 and only edit this page), and [this guide](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/markdown.html) on how to use Markdown to compose text.
>
>
> ❌ Remember that this is a public repo. Do NOT include: Proprietary data, PII, API keys, credentials, or anything confidential.

---

## 📋 BTT Internal Evaluation Notes
*(This section is for BTT staff and CAs only — remove before sharing with students)*

### Technical Vetting
| Check | Status | Notes |
| :--- | :--- | :--- |
| Python Compatibility | 🟢 | The project uses Python-based ML techniques and libraries, making it well-suited to students' skill sets. |
| Data Readiness | 🟡 | While the estimated data size is manageable, there may be concerns regarding the accessibility and cleaning of proprietary and hybrid datasets, which could complicate the initial stages. |
| Resource Check | 🟡 | The Google Colab free tier can accommodate initial work, but reliance on additional compute resources and API keys may pose access challenges for all students. |

### Internal Scores
- **Student Fit Score:** 7/10
- **Technical Depth Score:** 8/10
- **Overall Recommendation:** REVISE

### Advisor Feedback Draft
The project presents a compelling intersection of creative arts and AI technology, showcasing innovative applications in intellectual property management. Students should ensure they fully understand the nuances of both the data they are working with and the ML models they intend to implement. Additionally, I recommend focusing on concrete examples during prototype development to align expectations with deliverables, especially in terms of the prediction module.

---

# Hollywood Studios Secure AI and Chain of Title

**Company / Org:** Chambers Capital Ventures  
**Challenge Advisor:** Chris Chambers, chrisc@theeinsteinbridge.com  
**Program:** Break Through Tech AI Studio - Fall 2026  

---

## 🏢 About Chambers Capital Ventures
Chambers Capital Ventures is an investment and development firm operating at the intersection of media, finance, and advanced technology. The team focuses on optimizing creative workflows and protecting intellectual property within the entertainment industry through the implementation of secure AI governance systems.

---

## 🎯 The Challenge
### Project Summary
This project aims to build the Vault™ governance engine and integrate it with CreativeOS™ to facilitate secure, AI-driven creative workflows. By utilizing proprietary provenance logs, structured IP records, and public market demand datasets, the team will develop a hybrid ML architecture to track intellectual property rights and predict commercial streaming licensing outcomes.

### Success Criteria
Delivery of a functional prototype of the Vault™ + CreativeOS™ secure AI ecosystem with a working proof-of-concept demonstrating secure asset upload, AI-governed interaction logging, provenance tracking, and chain-of-title maintenance. A functional Streaming Deals Prediction module that accurately projects licensing terms. Positive evaluation on technical quality, innovation, IP protection, and usability.

### Project Milestones
Use these milestones to guide your work. Your team will create a GitHub Projects board to track tasks within each milestone.
| Month | Milestone | Key Activities |
|-------|-----------|----------------|
| **September** | Data Exploration & Preprocessing | Standardizing hybrid CSV/JSON/SQL schemas and building robust cleaning pipelines for disparate IP and box office records. |
| **October** | Feature Engineering & Baseline Modeling | Developing time-series features for market demand and applying NLP techniques to extract metadata from creative assets. |
| **November** | Model Optimization & Evaluation | Performing hyperparameter tuning on predictive models and conducting rigorous validation against historical chain-of-title logs. |
| **December** | Insights, Deliverables & Presentation | Finalizing the UI/UX for the proof-of-concept prototype and preparing executive reports on licensing value projections. |

> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset
**Name and Source:** Chambers Capital IP Provenance & Industry Market Data  
**Format:** CSV, TSV, JSON, SQL, PNG/JPG  
**Size:** 1gb to 5gb  
**Location:** Secure S3 bucket and encrypted database exports provided at project kickoff.  

### Key Details
- Proprietary provenance and interaction log data, public entertainment performance datasets (box office, audience demand signals), creative asset metadata, provenance logs, interaction metadata, and hybrid structured/unstructured IP records. Formats include CSV/TSV, JSON, Image files (.png, .jpg), and database exports (SQL dump).
- Teams must implement strict deduplication for hybrid data sources and perform categorical encoding for unstructured IP metadata fields to ensure consistency across the prediction engine.

---

## 🛠️ Suggested Approach
**ML Problem Type:** Classification, Regression, Time Series, NLP & RAG, Multi-Agent Systems  
**Recommended Libraries:**
- Natural language processing (NLP)
- classification models
- time-series analysis
- hybrid inference techniques
- regression
- Large Language Models (LLMs)/Generative AI
- and Transfer Learning / Pre-trained Models.
**Evaluation Metrics:** Precision and recall for IP provenance tracking; Mean Absolute Percentage Error (MAPE) for streaming deal predictions; system latency and security audit compliance scores.

---

## 📚 Resources to Get Started
The following resources will help your team understand the problem space and potential technical approaches for this project:
**Background Reading:**
- Industry standards on Digital Asset Management (DAM) and blockchain-based provenance tracking.
**Technical Tutorials:**
- Documentation on RAG (Retrieval-Augmented Generation) frameworks for secure data retrieval.
**Code Examples:**
- Boilerplate repository for secure API integration and time-series forecasting models provided by internal partners.

---

## 🤝 How We'll Work Together
**Check-ins:** During our biweekly 60-min AI Studio Lab Section meeting block (2nd and 4th week of every month)  
**Communication:** Slack and Corporate Email  
**Response time:** 24-48 business hours  
**Recommended Tools:**
- **Coding:** Google Colab Free Tier  
- **Collaboration:** GitHub, Notion  
- **Virtual Meetings:** Zoom, Google Meet  

---

## 🚀 Getting Started
1. **Review this overview document** and note any questions for our first meeting.
2. **Begin reviewing the dataset** using the link provided in the Dataset section.
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects).

I'm excited to work with you!

---

## ❓ Questions?
Please bring any questions to our first meeting during the week of August 24th (Break Through Tech's Bridge to Studio - Session B).
