# Awesome-Accessibility-Testing-Platform

## Similar Projects to Accessibility Testing Platforms

**Accessibility Testing Platforms** help organizations audit websites and applications for compliance with WCAG, ADA, Section 508, EN 301 549, and other accessibility standards. They combine automated scanning, guided manual testing, reporting, and sometimes remediation. Leading commercial tools include Deque axe DevTools, Level Access, Siteimprove Accessibility, AudioEye, EqualWeb, UserWay, Silktide, accessiBe, Pope Tech, and Tenon.

Below is a **curated list** of notable platforms and their open-source equivalents. The open-source ecosystem is particularly strong in automated testing engines and CI/CD integration, with **axe-core** serving as the foundation for many commercial and free tools.

## 🏢 SaaS / Hosted Platforms

| Platform | Description | Pricing | Free Tier / Limits | Company Size (Est. ARR / Valuation) |
| :--- | :--- | :--- | :--- | :--- |
| **[Siteimprove Accessibility](https://www.siteimprove.com/)** | Part of a broader digital governance suite that includes accessibility scanning, reporting, and prioritization. | Custom enterprise quotes. | **No** | ~$100M+ ARR (Valued at ~$638M) |
| **[Level Access](https://www.levelaccess.com/)** | Enterprise accessibility platform offering testing, monitoring, and compliance management. | Custom enterprise quotes (typically $25,000 to $150,000+/year). | **No** (14-day trials or custom demos available). | ~$100M+ ARR (Acquired UserWay for ~$99M) |
| **[UserWay](https://userway.org/)** | Accessibility widget and testing platform focused on automated fixes and compliance. | Paid plans start at $490/year (approx. $49/month); custom enterprise quotes available. | **Yes** (Free basic widget for manual, user-triggered accessibility adjustments). | ~$99M Valuation (Acquired by Level Access in 2024) |
| **[accessiBe](https://accessibe.com/)** | AI-driven accessibility solution offering automated remediation and monitoring. | Paid plans start at ~$49/month (or $490/year) for Micro tier; custom enterprise quotes available. | **No** (Offers free website scan diagnostics and a 7-day free trial). | ~$51.3M ARR (Raised $58.5M) |
| **[Deque axe DevTools](https://www.deque.com/axe/)** | Industry-leading accessibility testing suite (browser extension, CI/CD, and enterprise monitoring) powered by the axe-core engine. | Paid plans (Pro) start at ~$60/user/month; custom enterprise quotes available. | **Yes** (Free browser extension for page-by-page automated testing; no intelligent guided tests or workflow integrations). | ~$35M–$52M ARR (Industry standard) |
| **[AudioEye](https://www.audioeye.com/)** | Accessibility platform combining automated testing with managed remediation services. | Paid plans start at ~$49/month; custom enterprise quotes available. | **No** (Offers free one-time website scan diagnostics and a 14-day free trial). | ~$42M ARR (Publicly traded, ~$80M Market Cap) |
| **[EqualWeb](https://www.equalweb.com/)** | AI-powered accessibility solution with scanning and remediation features. | Paid automated AI plans start at ~$39/month; custom enterprise quotes available. | **Yes** (Free accessibility widget with basic adjustment tools and free accessibility checker tool/Chrome extension). | ~$4M ARR (Raised $500K) |
| **[Silktide](https://silktide.com/)** | Digital accessibility and quality assurance platform with website scanning. | Custom quote-based pricing. | **No** (Offers free browser extension for page audits and a free 25-page sample scan). | ~$3M ARR (Bootstrapped) |
| **[Pope Tech](https://pope.tech/)** | Accessibility testing and monitoring platform, often used in higher education. | Paid plans start at $25/month (for a 50-page tier, billed annually). | **Yes** (Free forever plan for scanning up to 25 pages, 1 website, 2 users). | ~$750K ARR (Small/Independent) |
| **[Tenon](https://tenon.io/)** | API-first accessibility testing service for developers and enterprises. | *Discontinued* (Acquired by Level Access in 2021; service retired in August 2023). | *Discontinued* (Service retired). | Discontinued (Acquired by Level Access) |

## 🔓 Open-Source Software

### 🌟 Open-Source Repositories (Sorted by GitHub Stars)
- **[Lighthouse](https://github.com/GoogleChrome/lighthouse)** [![GitHub stars](https://img.shields.io/github/stars/GoogleChrome/lighthouse?style=social&color=white)](https://github.com/GoogleChrome/lighthouse/stargazers) — Google’s open-source auditing tool (built into Chrome DevTools). Includes a solid accessibility audit alongside performance, SEO, and best practices. Fully scriptable via Lighthouse CI.
- **[axe-core](https://github.com/dequelabs/axe-core)** [![GitHub stars](https://img.shields.io/github/stars/dequelabs/axe-core?style=social&color=white)](https://github.com/dequelabs/axe-core/stargazers) — The most widely used open-source accessibility testing engine (Mozilla Public License). Powers Deque’s commercial tools as well as many free and open-source projects. Highly accurate with low false positives; supports WCAG 2.0–2.2 and best practices.
- **[Pa11y](https://github.com/pa11y/pa11y)** [![GitHub stars](https://img.shields.io/github/stars/pa11y/pa11y?style=social&color=white)](https://github.com/pa11y/pa11y/stargazers) — Popular open-source command-line tool for automated accessibility testing. Can use axe-core or HTML CodeSniffer as the underlying engine. Excellent for CI/CD pipelines.
- **[HTML_CodeSniffer](https://github.com/squizlabs/HTML_CodeSniffer)** [![GitHub stars](https://img.shields.io/github/stars/squizlabs/HTML_CodeSniffer?style=social&color=white)](https://github.com/squizlabs/HTML_CodeSniffer/stargazers) — Open-source JavaScript library that checks HTML for accessibility issues against WCAG standards. Can be used as a bookmarklet or integrated into other tools.
- **[Accessibility Insights](https://accessibilityinsights.io/)** [![GitHub stars](https://img.shields.io/github/stars/microsoft/accessibility-insights-web?style=social&color=white)](https://github.com/microsoft/accessibility-insights-web/stargazers) (Microsoft) — Free and open-source tools (browser extension + Windows app) for automated checks and guided manual testing. Built on axe-core.
- **[IBM Equal Access Accessibility Checker](https://github.com/IBMAccessibility/equal-access)** [![GitHub stars](https://img.shields.io/github/stars/IBMAccessibility/equal-access?style=social&color=white)](https://github.com/IBMAccessibility/equal-access/stargazers) — Open-source browser extension and Node.js package for accessibility testing.
- **[Guidepup](https://github.com/guidepup/guidepup)** [![GitHub stars](https://img.shields.io/github/stars/guidepup/guidepup?style=social&color=white)](https://github.com/guidepup/guidepup/stargazers) — Open-source library for automating screen reader testing (VoiceOver, NVDA) with Playwright and other tools.
- **[AccessLint](https://github.com/accesslint)** [![GitHub stars](https://img.shields.io/github/stars/accesslint/accesslint?style=social&color=white)](https://github.com/accesslint/accesslint/stargazers) — GitHub App and related tools that comment on pull requests with accessibility issues.

### 🛠️ Framework Integrations & Other Free Tools
- **WAVE** (WebAIM) — Widely used free browser extension for visual accessibility evaluation (not fully open-source, but free and highly trusted).
- **cypress-axe**, **jest-axe**, **vitest-axe**, and similar integrations — Open-source packages that bring axe-core into popular testing frameworks.
- Various community extensions and bookmarklets built on axe-core or HTML_CodeSniffer.
- Emerging full-site scanners and audit platforms (e.g., community WCAG crawlers and projects like Look-see) that combine crawling with axe-core or similar engines.

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
