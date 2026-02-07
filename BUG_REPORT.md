# 🐞 Bug Report - Dainik Coxsbazar News Portal

This report contains a detailed list of bugs and feature improvements identified during the manual E2E testing phase of the **Dainik Coxsbazar News Portal**. All issues were logged and managed using **Jira**.

## 📊 Testing Summary
- **Total Issues Found:** 11
- **Critical/High Priority:** 2
- **Medium Priority:** 8
- **Low Priority:** 1

---

## 🛠 Detailed Bug List

### 1. Social Media Share Icon (Feature Request)
- **Issue Key:** `KAN-11`
- **Priority:** 🔥 High
- **Type:** Feature
- **Requirement:** Social media sharing icons (Facebook, WhatsApp, etc.) are missing from news article pages.
- **Expected:** Icons should be visible at the top or bottom of every news article for easy sharing.

### 2. Comment Section Functionality
- **Issue Key:** `KAN-14`
- **Priority:** Medium
- **Status:** In Progress
- **Description:** Verifying if users can type and submit comments in the comment section.
- **Expected:** The comment box should accept text input and a 'Submit' button should save the data.

### 3. Author Name & Date Format Issue
- **Issue Key:** `KAN-13`
- **Priority:** Medium
- **Status:** In Progress
- **Description:** Checking if the author's name and publish date are visible and formatted correctly.
- **Actual Result:** Formatting inconsistencies found in the date display.
- **Expected:** Standard date format (e.g., DD/MM/YYYY) should be maintained.

### 4. Banglish Search: Case Sensitivity
- **Issue Key:** `KAN-9`
- **Priority:** Medium
- **Status:** In Progress
- **Description:** Testing if search results differ for uppercase vs lowercase Banglish input (e.g., "Coxsbazar" vs "coxsbazar").
- **Expected:** Search results should be identical regardless of case.

### 5. Banglish Search: Mixed Language Input
- **Issue Key:** `KAN-8`
- **Priority:** Medium
- **Status:** In Progress
- **Description:** Using a mix of Bangla and English characters in the search bar.
- **Result:** System handles mixed input but needs verification for relevance accuracy.

### 6. Empty Search Input
- **Issue Key:** `KAN-4`
- **Priority:** Low
- **Status:** In Progress
- **Description:** Testing system behavior when the search button is clicked without entering any text.
- **Expected:** A validation message or no action should occur instead of a page reload/error.

### 7. Other Modules Tested
- **KAN-7:** Search Results Verification (Relevant articles displayed).
- **KAN-10:** Verify 'All News' categories list.
- **KAN-12:** News detail page category/tag visibility.

---

## 📸 Proof of Testing (Jira Tracking)
All bugs listed above have been tracked in a private Jira Kanban board. Each issue includes:
- Reproducible steps.
- Screenshots of the actual result.
- Severity and Priority labels.

## 💻 Environment
- **Browsers:** Google Chrome, Mozilla Firefox.
- **Device:** Windows 11 Desktop, Android (Mobile View).
- **Tool:** Jira (Software Management).

---
*Reported by: MD. Rezwanul Islam Rimel*
