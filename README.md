<img src="assets/banner.svg" alt="Mohsin, Senior Quality Engineer and SDET" width="100%" />

# Hi, I'm Mohsin

**Senior Quality Engineer & SDET.** I build end-to-end test suites, wire them into CI as quality gates, and contribute fixes back to the open-source testing tools I use.

Computer Science graduate · Portfolio, notes and free QA resources: **[mohsintl.is-a.dev](https://mohsintl.is-a.dev/)**

---

### Test automation projects

| Project | What it shows | Stack |
| :--- | :--- | :--- |
| **[automation-exercise-playwright](https://github.com/Mohsintl/automation-exercise-playwright)** | 24 tests, Page Object Model, smoke on every PR, nightly regression on Chromium, Firefox and WebKit, traces and videos on failure | Playwright · TypeScript · GitHub Actions |
| **[e2e-automation-exercise](https://github.com/Mohsintl/e2e-automation-exercise)** | The same journeys ported to the agentic e2e framework, with ad-network blocking for deterministic CI runs | e2e · TypeScript · GitHub Actions |
| **[qa-automation-resources](https://github.com/Mohsintl/qa-automation-resources)** | My portfolio site, tested with Playwright on desktop and mobile in CI before every deploy | React · Playwright · GitHub Pages |
| **[Omadeck](https://github.com/Mohsintl/omadeck)** | Phone-as-remote PWA and voice companion for Linux, 400+ tests in CI on Python 3.11 to 3.13 | Python · pytest · WebSockets |

### Open-source contributions

| Project | Pull request | Status |
| :--- | :--- | :--- |
| [tester-army/e2e](https://github.com/tester-army/e2e) · agentic E2E testing framework | [Fix date patterns in the replay cache](https://github.com/tester-army/e2e/pull/1511) | 🟢 Merged |
| | [JUnit failure screenshots as GitLab attachments](https://github.com/tester-army/e2e/pull/1526) | 🟡 In review |
| [dorny/test-reporter](https://github.com/dorny/test-reporter) · test results in GitHub Actions | [Document when `checks: write` is needed](https://github.com/dorny/test-reporter/pull/865) | 🟡 In review |
| [OpenRig](https://github.com/mvschwarz/openrig) · multi-agent orchestration CLI | [Warn on an unrecognized `--kind`](https://github.com/mvschwarz/openrig/pull/2365) | 🟢 Merged |
| | [Readable error when workspace validation refuses](https://github.com/mvschwarz/openrig/pull/2367) | 🟢 Merged |
| | [Refocus traces work in catalogued projects outside the workspace root](https://github.com/mvschwarz/openrig/pull/2717) | 🟢 Merged |
| [Sellbird](https://github.com/ethanplusai/sellbird) · sales reply agent | [Replies follow the configured offer and booking settings](https://github.com/ethanplusai/sellbird/pull/203) | 🔵 Co-authored |
| [Paperclip](https://github.com/paperclipai/paperclip) · agent management platform | [Reconcile stranded agents behind pending accounting](https://github.com/paperclipai/paperclip/pull/18590) | 🟡 In review |

### Tools I work with

- **Testing:** Playwright · e2e (agentic) · Selenium · Vitest · pytest · API testing
- **Languages:** TypeScript · JavaScript · Python
- **CI and tooling:** GitHub Actions · Docker · Node.js · Git

### What I care about

- Tests that fail for the right reason: deterministic suites, strict locators, and evidence (traces, screenshots, JUnit) that makes a CI failure quick to read.
- Quality gates in CI: fast smoke checks on pull requests, full cross-browser regression on main and nightly.
- Fixing the tools upstream instead of working around them.
