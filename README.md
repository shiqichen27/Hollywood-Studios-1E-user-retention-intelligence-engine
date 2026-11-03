# Hollywood Studios: User Retention Intelligence Engine

---

### 👥 **Team Members**

| Name              | GitHub Handle | Contribution                                                             |
|-------------------|---------------|--------------------------------------------------------------------------|
| Jolaoluwa Amodu   | @the-jola-amodu    | Measure and track user interaction, created local testing                                                  |
| Imara Zepeda   | @[handle2]    |                                                   |
| Shiqi Chen   | @[handle3]    |                                                   |
| Adam Walid   | @[handle4]    |                                                   |
| Lina Romero-Fabian   | @[handle5]    |                                                   |
| Tamara Landman   | @[handle6]    |                                                   |

---

## 🎯 **Project Highlights**

- Built an in-memory, disposable PostgreSQL-compatible database testing workflow and Neon SQL adapter layer for fast, isolated development without risking production data.
- Implemented robust server-side authorization for the Retention Intelligence Engine, featuring session validation, strict admin allowlists, fail-closed default-deny access, and generic unauthorized UI states.
- Enhanced admin UX with a real-time searchable member directory and direct sidebar navigation under Settings for seamless report lookup.
- Integrated a seeded local session flow across admin, member, and peer roles, verified through API-level integration tests and browser-driven end-to-end checks.
- Developed the foundation for user retention prediction (7/30/60/90-day active probability, churn detection, lifetime estimation) integrated within the existing Hollywood Studios application fork.

---

## 👩🏽‍💻 **Setup and Installation**

### Prerequisites
- Node.js (v18+ recommended)
- Git

### Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/maherhasannn/hsi/tree/retention-engine
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Environment Setup:**
   Create a `.env.local` file in the root directory and configure local session and database settings.

4. **Run Local Disposable Database & Application:**
   Start the application in local test mode against the in-memory database:
   ```bash
   npm run dev
   ```

5. **Run Integration & Verification Tests:**
   Validate local database adapter, authorization rules, and UI access layers:
   ```bash
   npm run test
   ```

---

## 🏗️ **Project Overview**

- **Program Connection:** Developed as part of the Break Through Tech AI Program AI Studio Challenge.
- **Host Company & Objective:** Partnered with Hollywood Studios to build a User Retention Intelligence Engine integrated into the existing application fork. The system shifts engagement analytics from static tracking to predictive modeling that forecasts user activity over 7, 30, 60, and 90 days.
- **Real-World Impact:** Identifying early warning signs of disengagement enables targeted interventions (e.g., connection recommendations, project suggestions) that extend active user lifetime and optimize platform retention strategies.

---

## 📊 **Data Exploration**

- **Dataset & Interactions:** The platform tracks behavioral events across rolling time windows (7-, 14-, 30-day metrics), covering:
  - **Platform Activity:** Login frequency, session durations, inactivity intervals.
  - **Networking:** Profile views, search queries, connections established, messaging volume.
  - **Engagement:** Content interactions, projects created/joined, feature usage.
  - **Referrals:** Outbound invites, conversion rates, and subsequent invitee retention.
- **Preprocessing & Aggregation:** Calculated behavioral recency, frequency, and changes in activity trends over time.
- **Challenges:** Managing non-production testing without leaking sensitive metadata led to building an isolated in-memory PostgreSQL emulator handling nested SQL fragments and dynamic parameterization.

---

## 🧠 **Model Development**

- **Target Capabilities:**
  1. **Behavioral Classification:** Categorizing users (e.g., frequent networkers, passive browsers, collaborators).
  2. **Retention Prediction:** Supervised modeling for 7-, 30-, 60-, and 90-day active probabilities.
  3. **Lifetime Estimation:** Survival analysis / time-to-event modeling to estimate remaining active days.
  4. **Churn Detection:** Identifying trajectory drops (e.g., declining messaging frequency).
- **Inference & Explainability Strategy:** Quantifying relative feature contributions to highlight key behaviors driving retention, powering actionable, personalized interventions.

---

## 📈 **Results & Key Findings**

- **Infrastructure & Test Safety:** Successfully deployed a fully functional local development pipeline allowing offline API testing and UI validation without impacting production data.
- **Access Control & Privacy:** Server-side authorization prevents unauthorized access and completely hides engagement data and page metadata from non-admin accounts.
- **Admin Workflow Efficiency:** Replaced manual user handle lookups with a searchable, live-filtered member directory for engagement report viewing.
- **Validation Pipeline:** Clean build execution with 100% pass rate across role-based access tests, public data safety checks, and metric rendering integration tests.

---

## 🚀 **Next Steps**

- **Model Training & Deployment:** Transition from preliminary baseline models to full supervised training and survival models as historical behavioral event volume increases.
- **Intervention Engine:** Automate personalized in-app recommendations (relevant connections, projects, feature onboarding) based on retention model outputs.
- **Expanded Route Coverage:** Extend the local disposable database and testing workflow to additional application routes beyond retention reporting.
- **Automated E2E Testing:** Implement automated visual regression testing scripts (e.g., Playwright/Cypress) in the CI/CD pipeline for permission state verification.

---

## 📝 **License**

This project is licensed under the MIT License.

---

## 📄 **References**

- Hollywood Studios Project Guidance & Specifications
- Neon SQL & PostgreSQL In-Memory Database Emulation Patterns
- Survival Analysis for User Lifetime & Churn Prediction Literature

---

## 🙏 **Acknowledgements**

Thank you to our Challenge Advisor, host company representatives from Hollywood Studios, TAs, and the Break Through Tech AI team for their guidance and support throughout this project.
