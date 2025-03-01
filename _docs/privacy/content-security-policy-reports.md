---
title: DuckDuckGo Content Security Policy (CSP) Reports
nav_title: About CSP Reports
description: To protect our users and ensure a bug-free search experience, DuckDuckGo uses a security specification called a Content Security Policy.
category: Search Privacy
order: 550
---

At DuckDuckGo, we don’t track you, ever. That’s our [Privacy Policy](https://duckduckgo.com/privacy) in a nutshell. For example, we do not create unique cookies and, more generally, architect our product so that we do not even have the ability to create a search or browsing history for any individual — it’s privacy by design.

To protect you (our users) and ensure a bug-free search experience, we use a standardized computer security specification called a [Content Security Policy](https://en.wikipedia.org/wiki/Content_Security_Policy) or "CSP". Our CSP tells your browser which resources (for example, JavaScript code, images, etc.) it should trust, fetch, and execute on DuckDuckGo.com, helping us detect and block malicious third-party attacks, like [Cross-Site-Scripting](https://en.wikipedia.org/wiki/Cross-site_scripting) (XSS) attacks, [code injection attacks](https://en.wikipedia.org/wiki/Code_injection), [clickjacking](https://en.wikipedia.org/wiki/Clickjacking), and more.

When searching on DuckDuckGo, you may occasionally see an additional request made to `https://duckduckgo.com/csp_report.js` or `https://duckduckgo.com/csp_report_ed.js`. This request sends us a report listing any potential CSP violations automatically, like when a legitimate resource fails to load, and helps us validate CSP updates we deploy.

In line with our strict [Privacy Policy](https://duckduckgo.com/privacy), CSP reports contain no personal information — in other words, they're completely anonymous.
