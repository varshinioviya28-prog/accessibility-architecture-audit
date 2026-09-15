# Accessibility & Repository Architecture Audit

## Website Audited

**My collection of Dummy sites – Practical testing for beginners**

URL: https://club.ministryoftesting.com/t/my-collection-of-dummy-sites-practical-testing-for-beginners/76939

## Project Purpose

This project audits the accessibility of a public-facing website using Google Lighthouse and keyboard-only navigation.

The project also provides a monorepo-style architecture with separate client, server, documentation, and test areas.

## Audit Method

- Google Lighthouse Accessibility Audit
- Keyboard navigation using Tab and Shift + Tab

## Repository Architecture

```text
accessibility-architecture-audit/
├── client/
├── server/
├── docs/
│   └── audit-report.md
├── tests/
└── README.md
