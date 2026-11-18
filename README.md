<img src="assets/banner.svg" alt="Mohsin, Senior Quality Engineer Analyst and SDET" width="100%" />

# Hi, I'm Mohsin

**I break software before your users do, then automate the test so the bug never comes back.**

Senior Quality Engineer Analyst and SDET. My Playwright, Selenium, pytest and e2e tests are merged into Eclipse Open VSX, Selenium and the e2e framework, and run in CI on every pull request.

Portfolio, notes and free QA resources: **[mohsintl.is-a.dev](https://mohsintl.is-a.dev/)**

## Tests for other products

End-to-end tests I wrote for open-source products, so their bugs get caught in CI.

- **[Eclipse Open VSX](https://github.com/eclipse-openvsx/openvsx)**, the extension registry behind VS Code forks: a [Playwright test for switching an extension to an older version and back](https://github.com/eclipse-openvsx/openvsx/pull/2462). In review: [tests for the changelog and reviews tabs and the namespace link](https://github.com/eclipse-openvsx/openvsx/pull/2463).
- **In review:** [phone and tablet Playwright tests for Tabularis](https://github.com/TabularisDB/tabularis/pull/1612), a database client.

## Fixes in testing tools

Bugs I fixed inside the tools testers rely on.

- **[e2e](https://github.com/e2e-inc/e2e)**, the next-generation agentic e2e framework for web and mobile (14k★): [date patterns in the replay cache](https://github.com/e2e-inc/e2e/pull/1511), and [failure screenshots as GitLab attachments in JUnit](https://github.com/e2e-inc/e2e/pull/1526).
- **[Selenium](https://github.com/SeleniumHQ/selenium)** (Python bindings): [`Select` escapes trailing double quotes correctly](https://github.com/SeleniumHQ/selenium/pull/18292), and [`Select` finds options by value with XPath](https://github.com/SeleniumHQ/selenium/pull/18305). In review: [keep waiting when an element goes stale](https://github.com/SeleniumHQ/selenium/pull/18319).
- **In review:** [test-reporter docs](https://github.com/dorny/test-reporter/pull/865).

## Community examples

Test suites that a testing project shows to its users as reference examples.

- **[OmaDeck on e2e](https://e2e.com/examples/omadeck)**: phone-deck tests against a fake desktop.
- **[Automation Exercise on e2e](https://e2e.com/examples/automation-exercise)**: a full shop journey suite, with ad networks blocked for stable CI runs.
- **In review:** [Selenium's Listeners docs](https://github.com/SeleniumHQ/seleniumhq.github.io/pull/3000), tested Java and Python examples on selenium.dev.

## My own projects

- **[OmaDeck](https://github.com/Mohsintl/omadeck)** turns your phone into a Stream Deck and voice remote for Omarchy and Hyprland Linux. It's Python, with 500+ unit tests and e2e tests in CI. ⭐ [Star it](https://github.com/Mohsintl/omadeck) if it's useful · [site](https://mohsintl.is-a.dev/omadeck/)
- **[automation-exercise-playwright](https://github.com/Mohsintl/automation-exercise-playwright)**: 24 Playwright tests in TypeScript with page objects. A smoke run checks every PR, and a nightly regression runs on Chromium, Firefox and WebKit.
- **[e2e-automation-exercise](https://github.com/Mohsintl/e2e-automation-exercise)**: the same journeys on e2e, so the two frameworks can be compared side by side.
- **[My portfolio](https://github.com/Mohsintl/Mohsintl.github.io)**: React, gated by Playwright tests on desktop and mobile before every deploy.

## Other open source

- **[omarchy-widgets](https://github.com/SimonSchubert/omarchy-widgets):** a [pressure widget](https://github.com/SimonSchubert/omarchy-widgets/pull/463), [lighter polling](https://github.com/SimonSchubert/omarchy-widgets/pull/471), and the [capture widget](https://github.com/SimonSchubert/omarchy-widgets/pull/474) with [its 1.1 update](https://github.com/SimonSchubert/omarchy-widgets/pull/488).
- **[OpenRig](https://github.com/mvschwarz/openrig):** [three CLI and daemon fixes](https://github.com/mvschwarz/openrig/pulls?q=is%3Amerged+author%3AMohsintl).
- **[brag](https://github.com/latent-spaces/brag/pull/72)** CI, **[Sellbird](https://github.com/ethanplusai/sellbird/pull/203)** (co-authored), and OmaDeck listed on [awesome-omarchy](https://github.com/aorumbayev/awesome-omarchy/pull/93).
- **In review:** [Paperclip](https://github.com/paperclipai/paperclip/pull/18590), and [two for omalauncher](https://github.com/SimonSchubert/omalauncher/pulls?q=author%3AMohsintl).

## What I use

Playwright, e2e, Selenium, Vitest and pytest. TypeScript, JavaScript, Python and Java. GitHub Actions, Docker and Git.
