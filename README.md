## Hi there 👋

## 🌍 Open Source Contributions

I contribute to open-source projects through testing, bug fixes, code quality improvements, and developer tooling.

### ✅ CPython — Python Core

**Project:** [python/cpython](https://github.com/python/cpython)

- **Pull Request:** [#160086 — Simplify datetime awareness docs](https://github.com/python/cpython/pull/160086) · Merged

**What I contributed**

- Simplified documentation explaining how to determine whether `datetime` and `time` objects are timezone-aware or naive.
- Replaced verbose awareness criteria with a simpler check using the `utcoffset()` method.
- Validated the documentation change with documentation checks and datetime tests.

**Tech:** Python · Technical Documentation · pytest · Git · GitHub Pull Requests

### ✅ Critique — Fix Project Response Counts

**Project:** [BistaDinesh03/critique](https://github.com/BistaDinesh03/critique)

- **Pull Request:** [#127 — Fix project-list response counts](https://github.com/BistaDinesh03/critique/pull/127) · Merged

**What I contributed**

- Fixed incorrect response counts caused by joining question IDs directly to project IDs.
- Corrected response aggregation for both Discover and My Projects endpoints.
- Added regression tests for mismatched project and question IDs.
- Preserved single-query behavior and impression batching to avoid N+1 queries.

**Tech:** Python · SQLAlchemy · pytest · Backend Testing · GitHub Pull Requests

### ✅ FleetPilot — Repository Test Organization

**Project:** [ChristianHandy/FleetPilot](https://github.com/ChristianHandy/FleetPilot)

- **Pull Request:** [#208 — Repo cleanup: move the tests into tests/ (#171)](https://github.com/ChristianHandy/FleetPilot/pull/208) · Merged

**What I contributed**

- Organized the repository's tests by moving test files from the repository root into the `tests/` directory.
- Updated the project structure to improve test discoverability and maintainability.
- Added a changelog entry documenting the test reorganization.

**Tech:** Python · pytest · Repository Maintenance · Git · GitHub Pull Requests

### ✅ Critique — Relative Markdown Link Checker

**Project:** [BistaDinesh03/critique](https://github.com/BistaDinesh03/critique)

- **Pull Request:** [#100 — Add relative Markdown link checker](https://github.com/Milan-CSE/critique/pull/100) · Merged

**What I contributed**

- Added automated tests for relative Markdown links in project documentation.
- Covered broken links, external URLs, fragments, URL-encoded paths, and fenced code blocks.
- Verified that the checker detects broken links and passes when the referenced files are restored.

**Tech:** Python · pytest · Ruff · GitHub Pull Requests

### ✅ arda-suite — Shared Memory Smoke Test Documentation

**Project:** [yunusarda-sudo/arda-suite](https://github.com/yunusarda-sudo/arda-suite)

- **Pull Request:** [#19 — Document shared memory smoke test](https://github.com/yunusarda-sudo/arda-suite/pull/19) · Merged

**What I contributed**

- Documented the local smoke-test workflow for the shared memory service.
- Updated the shared memory README and installation documentation.
- Improved instructions for developers setting up and validating the service locally.

**Tech:** Documentation · Developer Tooling · GitHub Pull Requests

### ✅ FleetPilot — Contributor Documentation

**Project:** [ChristianHandy/FleetPilot](https://github.com/ChristianHandy/FleetPilot)

- **Pull Request:** [#142 — View merged contribution](https://github.com/ChristianHandy/FleetPilot/pull/142) · Merged

**What I contributed**

- Improved the project's `CONTRIBUTING.md` documentation with an additional explanatory paragraph.
- Helped clarify contributor guidance for people working on the project.
- Passed the reported 9 automated checks.

**Tech:** Technical Documentation · Open-Source Collaboration · GitHub Pull Requests

<!--
**Milan-CSE/Milan-CSE** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
