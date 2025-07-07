# TA Automation Reports

[![GitHub Pages](https://img.shields.io/badge/Playwright--Reports-LIVE-green?style=flat&logo=github)](https://nitolkinetik.github.io/ta-automation-reports/)

Welcome to the **Test Automation Reports** dashboard!  
This repository serves as the public home for Playwright HTML test reports, automatically published after every successful pipeline run from our Bitbucket CI.

---

## 📊 **Latest Playwright Test Report**

- 👉 **[View the Latest Report](https://nitolkinetik.github.io/ta-automation-reports/)**  
  (Opens the latest Playwright HTML report)

---

## 🛠️ **How Does This Work?**

- Tests are run using [Playwright](https://playwright.dev/) in our Bitbucket Pipelines.
- After each test run, a beautiful, detailed HTML report is generated.
- The latest report is automatically **published here** using a pipeline step that pushes all report files to the `main` branch of this repo, which is configured with GitHub Pages.
- **No manual uploads!** Just trigger the pipeline.

---

## 🚀 **How to Publish a New Report**

1. **Trigger a pipeline** in Bitbucket (`manual-main-stage` or `manual-environment-selection`).
2. After the tests pass, the pipeline pushes the updated report here.
3. Wait 1-2 minutes, then refresh [the live report](https://nitolkinetik.github.io/ta-automation-reports/).

---

## 🗂️ **Finding Old Reports**

- By default, only the **latest report** is available.
- Want to keep a history of all runs?  
  Ask the devs to enable report archiving (see below)!

---

## 📝 **About**

- Repo owner: [nitolkinetik](https://github.com/nitolkinetik)
- Playwright Version: v1.52.0
- HTML reports generated automatically via CI

---

## 🗣️ **Need Archiving or Extra Features?**

Want to keep an archive of past reports (by date or build number)?  
Open an [issue](https://github.com/nitolkinetik/ta-automation-reports/issues) or ping [Nitol](mailto:narayan@kinetik.care) for advanced publishing options!

---

<sub>Powered by Bitbucket Pipelines & GitHub Pages.  
README last updated: 2025-07-07</sub>
