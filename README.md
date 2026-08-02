# Awesome-Accessibility-Testing-Platform

## Similar Projects to Accessibility Testing Platforms

**Accessibility Testing Platforms** help organizations audit websites and applications for compliance with WCAG, ADA, Section 508, EN 301 549, and other accessibility standards. They combine automated scanning, guided manual testing, reporting, and sometimes remediation. Leading commercial tools include Deque axe DevTools, Level Access, Siteimprove Accessibility, AudioEye, EqualWeb, UserWay, Silktide, accessiBe, Pope Tech, and Tenon.

Below is a **curated list** of notable platforms and their open-source equivalents. The open-source ecosystem is particularly strong in automated testing engines and CI/CD integration, with **axe-core** serving as the foundation for many commercial and free tools.

## 🏢 SaaS / Hosted Platforms

- **[Deque axe DevTools](https://www.deque.com/axe/)** — Industry-leading accessibility testing suite (browser extension, CI/CD, and enterprise monitoring) powered by the axe-core engine.
- **[Level Access](https://www.levelaccess.com/)** — Enterprise accessibility platform offering testing, monitoring, and compliance management.
- **[Siteimprove Accessibility](https://www.siteimprove.com/)** — Part of a broader digital governance suite that includes accessibility scanning, reporting, and prioritization.
- **[AudioEye](https://www.audioeye.com/)** — Accessibility platform combining automated testing with managed remediation services.
- **[EqualWeb](https://www.equalweb.com/)** — AI-powered accessibility solution with scanning and remediation features.
- **[UserWay](https://userway.org/)** — Accessibility widget and testing platform focused on automated fixes and compliance.
- **[Silktide](https://silktide.com/)** — Digital accessibility and quality assurance platform with website scanning.
- **[accessiBe](https://accessibe.com/)** — AI-driven accessibility solution offering automated remediation and monitoring.
- **[Pope Tech](https://pope.tech/)** — Accessibility testing and monitoring platform, often used in higher education.
- **[Tenon](https://tenon.io/)** — API-first accessibility testing service for developers and enterprises.

## 🔓 Open-Source Software

### Core Engines & Leading Tools
- **[axe-core](https://github.com/dequelabs/axe-core)** — The most widely used open-source accessibility testing engine (Mozilla Public License). Powers Deque’s commercial tools as well as many free and open-source projects. Highly accurate with low false positives; supports WCAG 2.0–2.2 and best practices.
- **[Pa11y](https://github.com/pa11y/pa11y)** — Popular open-source command-line tool for automated accessibility testing. Can use axe-core or HTML CodeSniffer as the underlying engine. Excellent for CI/CD pipelines.
- **[Lighthouse](https://github.com/GoogleChrome/lighthouse)** — Google’s open-source auditing tool (built into Chrome DevTools). Includes a solid accessibility audit alongside performance, SEO, and best practices. Fully scriptable via Lighthouse CI.
- **[Accessibility Insights](https://accessibilityinsights.io/)** (Microsoft) — Free and open-source tools (browser extension + Windows app) for automated checks and guided manual testing. Built on axe-core.
- **[HTML_CodeSniffer](https://github.com/squizlabs/HTML_CodeSniffer)** — Open-source JavaScript library that checks HTML for accessibility issues against WCAG standards. Can be used as a bookmarklet or integrated into other tools.

### Browser Extensions & Developer Tools
- **WAVE** (WebAIM) — Widely used free browser extension for visual accessibility evaluation (not fully open-source, but free and highly trusted).
- **IBM Equal Access Accessibility Checker** — Open-source browser extension and Node.js package for accessibility testing.
- Various community extensions and bookmarklets built on axe-core or HTML_CodeSniffer.

### CI/CD & Automation Focused
- **[AccessLint](https://github.com/accesslint)** — GitHub App and related tools that comment on pull requests with accessibility issues.
- **cypress-axe**, **jest-axe**, **vitest-axe**, and similar integrations — Open-source packages that bring axe-core into popular testing frameworks.
- **[Guidepup](https://github.com/guidepup/guidepup)** — Open-source library for automating screen reader testing (VoiceOver, NVDA) with Playwright and other tools.
- Emerging full-site scanners and audit platforms (e.g., community WCAG crawlers and projects like Look-see) that combine crawling with axe-core or similar engines.

### Supporting Libraries & Utilities
- Color contrast checkers, focus management utilities, and ARIA validation libraries available across the open-source ecosystem.
- Screen reader testing helpers and virtual screen reader projects for automated verification.

### Typical Open-Source Stack
1. **Automated scanning** — axe-core (via browser extension, Pa11y, or testing framework integrations)
2. **CI/CD gates** — Pa11y, Lighthouse CI, or jest-axe / cypress-axe
3. **Guided manual testing** — Accessibility Insights or WAVE
4. **Screen reader validation** — Guidepup or manual testing with NVDA/Orca/VoiceOver

This combination covers the majority of automated accessibility issues and integrates cleanly into modern development workflows, while commercial platforms typically add enterprise reporting, continuous monitoring, and managed remediation.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects related to accessibility testing, WCAG auditing, or assistive technology automation.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open-source accessibility tooling makes the web more inclusive for everyone! ♿
