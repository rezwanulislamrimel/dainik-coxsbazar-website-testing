# <p align="center">📰 Dainik Coxsbazar News Portal: Full QA Lifecycle</p>

<p align="center">
  <img src="https://img.shields.io/badge/Testing-Manual%20E2E-blue?style=for-the-badge&logo=checkmarx" />
  <img src="https://img.shields.io/badge/Jira-Bug%20Tracking-0052CC?style=for-the-badge&logo=jira" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
</p>

---

### 📖 Project Overview
> [!IMPORTANT]
> This repository showcases the **Comprehensive Manual Testing** and QA Documentation for the **Dainik Coxsbazar News Portal**. The primary focus was ensuring a stable, user-friendly, and high-performance experience for a high-traffic news platform.

---

## 🎯 Testing Scope & Strategy

I followed a structured **STLC (Software Testing Life Cycle)** to cover all critical aspects of the portal:

#### 🟦 **Functional Testing**
* **Search Logic:** Validating keyword matching (including **Banglish** search).
* **Content Management:** News upload workflow, category mapping, and archive retrieval.

#### 🟧 **UI/UX & Compatibility**
* **Font Rendering:** Ensuring Bengali fonts (Unicode) display correctly across devices.
* **Ad Placement:** Verifying that advertisements do not overlap with news content.
* **Responsiveness:** Fluid layout checks on `Chrome`, `Firefox`, and `Android` mobile devices.

#### 🟩 **Social & SEO**
* **Metadata Validation:** Checking Open Graph tags for correct social media previews.
* **Social Integration:** Verification of social share icon functionality.

---

## 📊 Test Execution Summary

| 📈 Metric | 📋 Performance Details |
| :--- | :--- |
| **Total Issues Logged** | <kbd>11 Defects</kbd> |
| **Critical/High Priority** | 🔥 **02 (Social Share & Formatting)** |
| **Platform Coverage** | Windows 11, Android 12+ |
| **Tracking Tool** | `Jira (Kanban Board)` |

---

## 🐞 Bug Reporting & Tracking

> [!NOTE]
> All defects were managed via **Jira** to maintain a transparent and traceable bug life cycle.

| Severity | Defect Description | Status |
| :--- | :--- | :--- |
| <code style="color:red">🔴 Critical</code> | **Social Share Icons** - Failing to fetch correct metadata. | 🛠️ Logged |
| <code style="color:orange">🟡 High</code> | **Author Formatting** - UI alignment issues on mobile view. | 🛠️ Logged |
| <code style="color:blue">🔵 Medium</code> | **Ad Placement** - Minor overlap on tablet resolution. | ✅ Fixed |

---

## 📄 QA Artifacts (Repository Contents)

* 📂 **[Test Scenarios](./Test_Scenarios):** Comprehensive test cases for all modules.
* 📂 **[Test Plan](./Dainik_Coxsbazar_Test_Plan.pdf):** Official testing strategy and scope.
* 📂 **[Detailed Bug Report](./BUG_REPORT.md):** Full breakdown of issues exported from Jira.

---

## 🛠️ Environment & Tools
* **Management:** `Jira`, `MS Excel`.
* **Browsers:** `Google Chrome`, `Mozilla Firefox`.
* **Operating Systems:** `Windows 11`, `Android 12+`.

---

## 📂 Repository Structure

```text
├── 📂 Test_Scenarios
│   └── 📊 Functional_Test_Cases.xlsx
├── 📂 Docs
│   └── 📄 Dainik_Coxsbazar_Test_Plan.pdf
├── 🐞 BUG_REPORT.md
└── 📄 README.md
```

---

# 👤 Author

**Rezwanul Islam**
*SQA Engineer | Manual & Automation Specialist*

<p align="left">
<a href="https://www.linkedin.com/in/rezwanulrimel/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/rezwanulislamrimel"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

---
<p align="center"><i>Maintained by Rezwanul Rimel © 2026</i></p>
