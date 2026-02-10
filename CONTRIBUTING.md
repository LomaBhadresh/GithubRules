# Contributing Guidelines – KKDollar iOS

## Branch Structure
We maintain three primary branches:
- main – Production
- SIT_KKDollar_iOS – SIT / QA testing
- Dev_KKDollar_iOS – Active development

All development work must start from Dev_KKDollar_iOS unless explicitly instructed.

---

## 1. Minor Bug Fixes (No Functional Impact)

### Branch Naming
Create a branch from Dev_KKDollar_iOS using the format:
Dev_KKDollar_iOS_<YourName>_<Date>

Example:
Dev_KKDollar_iOS_Bhadresh_Feb10

### Workflow
1. Create branch from Dev_KKDollar_iOS
2. Apply bug fix
3. Raise PR only to Dev_KKDollar_iOS
4. Merge after review

---

## 2. New Jira Tasks / Enhancements

### Branch Naming
Create a branch from Dev_KKDollar_iOS using:
<JIRA_TICKET>_<Short_Description>

Example:
KKRPROD-6187_Currency_Support

### Workflow
1. Create branch from Dev_KKDollar_iOS
2. Complete task
3. Commit only to your task branch
4. Raise PR only when instructed

---

## 3. Parallel / Separate Tasks

If working on a separate or long-running task:
- Do NOT raise PR to any branch
- Commit only to your task branch
- Create PR only after confirmation

---

## Git Flow Overview

main
  ↑
SIT_KKDollar_iOS
  ↑
Dev_KKDollar_iOS
  ├── Dev_KKDollar_iOS_Bhadresh_Feb10
  ├── KKRPROD-6187_Currency_Support
  ├── KKRPROD-6201_Login_UI

---

## Rules Summary
- Always branch from Dev_KKDollar_iOS
- Follow naming conventions strictly
- No direct commits to main, SIT_KKDollar_iOS, or Dev_KKDollar_iOS
- No PRs for unfinished or parallel tasks