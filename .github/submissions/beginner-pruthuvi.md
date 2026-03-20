# Beginner Badge Submission - Pruthuvi de Silva

**Date:** March 20, 2026  
**Status:** Submitted for Review

---

## ✅ Tasks Completed

- [x] Task 1: Run Your First Workflow
- [x] Task 2: Understand Workflow Triggers
- [x] Task 3: Build and Test Locally

---

## 📸 Evidence

### Task 1: Run Your First Workflow
**Objective:** Understand how workflows execute

✅ **Completed:** Successfully ran the "Hello World Workflow" manually from GitHub Actions tab.

**Evidence:**
- Navigated to repository Actions tab
- Found and clicked "Hello World Workflow"
- Clicked "Run workflow" button
- Workflow executed successfully
- Verified all echo outputs in the workflow logs
- Screenshots show successful workflow run with all outputs visible

---

### Task 2: Understand Workflow Triggers
**Objective:** Learn when workflows are triggered automatically

✅ **Completed:** Tested automatic push-triggered workflows.

**Evidence:**
- Edited `.github/workflows/hello-world.yml` (added learning comments)
- Committed changes: `feat: update hello-world workflow - testing automatic push triggers`
- Pushed changes to `main` branch
- Workflow ran automatically without manual trigger
- Verified workflow was triggered by `push` event (not manual)
- Confirmed branch: `main`
- Screenshots show automatic push-triggered workflow execution

---

### Task 3: Build and Test Locally
**Objective:** Run the sample app and tests locally

✅ **Completed:** Successfully built, tested, and ran the sample application.

**Evidence:**
- Navigated to `sample-app` directory
- Ran `npm install` - All dependencies installed successfully ✓
- Ran `npm test` - All 8 tests passed ✓
  - Test Suites: 1 passed
  - Tests: 8 passed, 8 total
  - Code Coverage: 82.75%
- Ran `npm start` / `node src/server.js` - Server started successfully on port 3000
- Visited `http://localhost:3000` in browser - Application loaded and working
- Screenshots show successful test run and app running in browser

---

## 🎯 What I Learned

✅ **Task 1:** How to manually trigger workflows from GitHub Actions UI and read execution logs

✅ **Task 2:** That push events automatically trigger workflows based on configuration in workflow YAML files

✅ **Task 3:** How to set up and run a Node.js application locally, run tests, and verify the app works

---

## 🎉 Completion Status

All beginner tasks (1-3) completed successfully with evidence provided.

**Ready for review!** ✅
