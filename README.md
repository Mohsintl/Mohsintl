<img src="assets/banner.svg" alt="Mohsin, Senior Quality Engineer Analyst and SDET" width="100%" />

# Hi, I'm Mohsin

I'm a Senior Quality Engineer Analyst and SDET. I write end-to-end tests, run them in CI so a broken build gets caught before it ships, and when a testing tool I use has a bug, I try to fix it upstream.

My portfolio, notes and free QA resources are at **[mohsintl.is-a.dev](https://mohsintl.is-a.dev/)**.

## Things I've built

- **[OmaDeck](https://github.com/Mohsintl/omadeck)** turns my phone into a Stream Deck and voice remote for my Linux desktop (Omarchy and Hyprland). It's Python, with 500+ unit tests and phone-deck tests that run against a fake desktop. Those tests are a [community example on e2e](https://e2e.com/examples/omadeck).
- **[automation-exercise-playwright](https://github.com/Mohsintl/automation-exercise-playwright)** is 24 Playwright tests in TypeScript using page objects. A smoke run checks every pull request, and a nightly run covers Chromium, Firefox and WebKit, with traces and videos when something fails.
- **[e2e-automation-exercise](https://github.com/Mohsintl/e2e-automation-exercise)** ports the same tests to the e2e framework and blocks ad networks so CI runs stay stable. It's also a [community example on e2e](https://e2e.com/examples/automation-exercise).
- **[My portfolio](https://github.com/Mohsintl/Mohsintl.github.io)** is React, tested with Playwright on desktop and mobile before every deploy.

## Merged pull requests

- **Selenium** (Python bindings): [`Select` escapes trailing double quotes correctly](https://github.com/SeleniumHQ/selenium/pull/18292), and [`Select` finds options by value with XPath](https://github.com/SeleniumHQ/selenium/pull/18305).
- **e2e:** [date patterns in the replay cache](https://github.com/e2e-inc/e2e/pull/1511), [failure screenshots as GitLab attachments in JUnit](https://github.com/e2e-inc/e2e/pull/1526), and two community examples ([Automation Exercise](https://github.com/e2e-inc/e2e/pull/1512), [OmaDeck](https://github.com/e2e-inc/e2e/pull/1707)).
- **omarchy-widgets:** a [pressure widget](https://github.com/SimonSchubert/omarchy-widgets/pull/463) showing free RAM the way the kernel sees it, [lighter polling](https://github.com/SimonSchubert/omarchy-widgets/pull/471) for it, and a [capture widget](https://github.com/SimonSchubert/omarchy-widgets/pull/474) that saves a dictated thought to `~/inbox.md`.
- **OpenRig:** [a warning for an unknown `--kind`](https://github.com/mvschwarz/openrig/pull/2365), [a readable error when workspace validation refuses](https://github.com/mvschwarz/openrig/pull/2367), and [refocus tracing work outside the workspace root](https://github.com/mvschwarz/openrig/pull/2717).
- **Sellbird:** [replies follow the configured offer and booking settings](https://github.com/ethanplusai/sellbird/pull/203), co-authored.

Still in review: [test-reporter docs](https://github.com/dorny/test-reporter/pull/865), [Paperclip](https://github.com/paperclipai/paperclip/pull/18590), and two for [omalauncher](https://github.com/SimonSchubert/omalauncher/pulls?q=author%3AMohsintl).

## What I use

Playwright, e2e, Selenium, Vitest and pytest. TypeScript, JavaScript and Python. GitHub Actions, Docker and Git.
