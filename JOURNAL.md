## Week 7 — Issue selection

**Issue link:** https://github.com/ascherj/pathreview/issues/50

**Issue title:** Add a has_tests boolean to the repo analysis output

**Tier:** [x] Tier 1  [ ] Tier 2  [ ] Tier 3

**Problem summary:**
Test coverage is important, adding detection logic to check if a repo has test files/folders or a pytest.ini,etc. A successful fix would give a boolean output - true or false for the test checks. Relevant files for the implementation would be agent/tools/github_tool.py and agent/tools/repo_analyzer.py

**Branch name:** test/50-add-boolean-for-test

**Setup confirmation:** [x] App runs locally at localhost:5173

**Cohort ledger:** [x] Issue added to cohort ledger

**Issue selection reasoning:**
1. Can I explain what this issue is asking for in my own words?
        [x] *I can explain the problem and the expected behavior in 2–3 sentences without reading the issue*

2. Do I understand which part of the app is affected?
        [x] *I've located the relevant files and confirmed they exist in the codebase*

3. Do I understand what "done" looks like?
        [x] *I can describe a concrete before-and-after: what the user sees before the fix and what they see after.*
    
4. Is the tier a realistic match for where I am right now?
    *This is my first open source contribution, therefore I am choosing tier-1 for starters*




## Week 8 — Reproduction & solution planning

**Reproduction commit link:** [link to commit documenting the reproduced issue]

**Reproduction summary:**
Setup the whole project in docker and ran the project using "make run" and it did not run the project as intended at first. Then had to troubleshoot for a bit and got it to run. There was no detection logic for the project to find test/ or tests/ folder.

**PLAN.md link:** [link to PLAN.md in your fork]

**Walkthrough video (recommended):** No video was recorded

**Blockers or open questions:**
The issue calls for two relevant files:
agent/tools/github_tool.py
agent/tools/repo_analyzer.py

but the project only has the first one and not the repo_analyzer.py