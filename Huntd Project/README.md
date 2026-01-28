# Huntd – QA Testing Project (Web & Mobile)

## 📌 Project Overview
**Huntd** is a Web3-focused recruitment platform connecting candidates with recruiters through candidate discovery, job listings, and secure chat-based communication.

This repository presents a **complete QA testing project**, covering both:
- **Web application** (desktop & mobile browsers)
- **Mobile application (MVP)** – Android / iOS

The project was executed as an end-to-end manual QA practice, including test planning, test design, execution, and bug reporting.

---

## 🎯 Testing Objectives
- Validate core business flows for **Candidates** and **Recruiters**
- Verify **permissions & access control** for different user roles
- Ensure consistency between **web and mobile** implementations
- Identify functional, UX, and security-related issues
- Deliver clear documentation and traceability between requirements, test cases, and defects

---

## 👥 User Roles Covered
- **Guest (not logged-in user)**
- **Candidate**
- **Recruiter**

Each role was tested against defined permissions and expected behavior using a dedicated **Permission Access Testing Table** :contentReference[oaicite:0]{index=0}.

---

## 🧩 Scope of Testing

### ✅ In Scope
**Web Application**
- Main pages: *For Engineers* / *For Companies*
- Candidate list & advanced filters
- Candidate profile & contact visibility logic
- Sign Up / Sign In (email + social login)
- Chats (contact sharing, offer/reject, archive, favourite)
- Profile management & role switching
- Web3 Companies & Jobs (job posting, 1-click apply)
- Footer content & links
- Responsive behavior

**Mobile Application (MVP)**
- Authentication
- Chat (real-time messaging, contact sharing)
- Profile preview & settings
- Basic navigation and stability

Full scope definition and exclusions are described in the Test Plan :contentReference[oaicite:1]{index=1}.

---

## ❌ Out of Scope
- Admin panel
- Feedback / question forms
- Mobile features not implemented in MVP

---

## 🧪 Testing Artifacts Included

### 📄 Test Documentation
- **Test Plan (Web + Mobile)** – strategy, scope, risks, schedule :contentReference[oaicite:2]{index=2}
- **Priority Plan (P0–P3)** – feature risk-based prioritization :contentReference[oaicite:3]{index=3}
- **Permission Access Testing Table** – role-based access matrix :contentReference[oaicite:4]{index=4}
- **RTM (Requirements Traceability Matrix)** – mapping requirements to test cases :contentReference[oaicite:5]{index=5}

### 🧠 Test Design
- Functional decomposition per module
- Positive & negative test cases
- Role-based and edge-case scenarios
- Separate coverage for Web and Mobile

---

## 🐞 Bug Tracking & Results
All identified issues were reported and tracked in **Jira**, covering both Web and Mobile applications.

### Bug Highlights:
- Authentication & password validation gaps
- Chat synchronization and notification issues
- Missing permission restrictions
- UX inconsistencies between desktop and mobile
- Validation and error-handling problems

The Jira export contains:
- **Epics, Stories, and Bugs**
- Clear priorities (Highest → Lowest)
- Status tracking and timestamps :contentReference[oaicite:6]{index=6}

---

## 🔧 Tools Used
- **Jira** – bug tracking & test management
- **TestRail** – test cases & test runs
- **Browser DevTools**
- **Android device** (real device testing)
- **Responsive & cross-browser testing**

---

## ⏱️ Effort & Timeline
- Total estimated effort: **~40 hours**
- Activities included:
  - Product analysis
  - Test documentation
  - Test case design
  - Test execution
  - Bug reporting
  - Final test summary

Detailed breakdown available in the Test Plan :contentReference[oaicite:7]{index=7}.

---

## 📊 Key QA Takeaways
- Strong focus on **business-critical flows (P0/P1)**
- Emphasis on **permissions & security**
- Real-life bug patterns typical for production systems
- Clear separation between Web and Mobile testing scopes
- Full traceability from requirements → test cases → bugs

---

## 👤 Author
**Bartosz Dąbek**  
Manual QA Engineer  
Focus: Functional Testing · Web & Mobile · Jira · TestRail · Test Design

---

## 📎 Notes
This repository is intended as a **portfolio QA project**, demonstrating real-world testing approach rather than automated solutions.

Jeśli chcesz, w kolejnym kroku mogę:

✂️ skrócić README pod jedną stronę A4 (super pod rekrutera),

🔥 dopasować je stricte pod Junior / Regular QA,

📂 rozpisać strukturę repo (folders + naming),

🧲 albo dorobić sekcję “What problems I solved as QA” – bardzo dobrze działa na rozmowach.

Daj znać, co robimy dalej 💪


Źródła





Powiedziałeś(-aś):
trzeba powyrzucać contentReference bo to nic nie da


ChatGPT powiedział:
Masz rację 👍
contentReference / cite’y do plików nie mają żadnej wartości na GitHubie – to jest tylko mechanika tego czata. Na repo README powinno być czyste, samodzielne i czytelne.

Poniżej masz oczyszczoną wersję README.md, bez żadnych contentReference, gotową do wrzucenia na GitHuba.

md
Skopiuj kod
# Huntd – QA Testing Project (Web & Mobile)

## 📌 Project Overview
**Huntd** is a Web3-focused recruitment platform connecting candidates with recruiters through candidate discovery, job listings, and secure chat-based communication.

This repository presents a **complete manual QA testing project**, covering both:
- **Web application** (desktop & mobile browsers)
- **Mobile application (MVP)** – Android / iOS

The project was executed end-to-end, including test planning, test design, execution, and bug reporting.

---

## 🎯 Testing Objectives
- Validate core business flows for **Candidates** and **Recruiters**
- Verify **permissions & access control** for different user roles
- Ensure consistency between **web and mobile** implementations
- Identify functional, UX, and security-related issues
- Provide full traceability between requirements, test cases, and defects

---

## 👥 User Roles Covered
- **Guest (not logged-in user)**
- **Candidate**
- **Recruiter**

Each role was tested against defined permissions and expected behavior using a dedicated permission access matrix.

---

## 🧩 Scope of Testing

### ✅ In Scope

#### Web Application
- Main pages: *For Engineers* / *For Companies*
- Candidate list with advanced filters
- Candidate profile & contact visibility logic
- Sign Up / Sign In (email + social login)
- Chats (contact sharing, offer/reject, archive, favourite)
- Profile management & role switching
- Web3 Companies & Jobs (job posting, 1-click apply)
- Footer content & links
- Responsive design

#### Mobile Application (MVP)
- Authentication
- Chat (real-time messaging, contact sharing)
- Profile preview & settings
- Basic navigation and stability

---

## ❌ Out of Scope
- Admin panel
- Feedback / question forms
- Mobile features not implemented in MVP

---

## 🧪 Testing Artifacts Included

### 📄 Test Documentation
- Test Plan (Web + Mobile)
- Priority Plan (P0–P3)
- Permission Access Testing Table
- Requirements Traceability Matrix (RTM)

### 🧠 Test Design
- Functional decomposition per module
- Positive and negative test cases
- Role-based and edge-case scenarios
- Separate coverage for Web and Mobile

---

## 🐞 Bug Tracking & Results
All issues were reported and tracked in **Jira**, covering both Web and Mobile applications.

### Bug coverage included:
- Authentication and password validation issues
- Chat synchronization and notification problems
- Missing or incorrect permission restrictions
- UX inconsistencies between desktop and mobile
- Validation and error-handling gaps

The Jira backlog contains epics, stories, and bugs with defined priorities and statuses.

---

## 🔧 Tools Used
- **Jira** – bug tracking and test management
- **TestRail** – test cases and test runs
- **Browser DevTools**
- **Android real device**
- **Responsive & cross-browser testing**

---

## ⏱️ Effort & Timeline
- Total effort: **~40 hours**

Activities included:
- Product analysis
- Test documentation
- Test case design
- Test execution
- Bug reporting
- Final test summary

---

## 📊 Key QA Takeaways
- Focus on **business-critical flows (P0/P1)**
- Strong emphasis on **permissions & security**
- Real-life bug patterns typical for production systems
- Clear separation between Web and Mobile testing
- Full traceability from requirements to defects

---

## 👤 Author
**Bartosz Dąbek**  
Manual QA Engineer  

Focus areas:
- Functional Testing
- Web & Mobile Applications
- Test Design
- Jira & TestRail

---

## 📎 Notes
This repository is intended as a **portfolio QA project**, demonstrating a real-world testing approach rather than automation.
