
# Document Change Log

|Version|Date|Description of Changes|Author|Related documents|
|---|---|---|---|---|
|1.0|YYYY-MM-DD|Initial creation of the document.|[Author Name]|[RFC-1], [ADR-1]|
|1.1|YYYY-MM-DD|Added web NFRs.|[Author Name]|[RFC-2], [ADR-2]|
|...|...|...|...||

---

# Document Overview

## Purpose

This document outlines the non-functional requirements crucial for our technology stack's long-standing success. These requirements ensure that the system's performance, usability, security, and other quality attributes meet the stakeholders' expectations and the end users' needs.

## Scope

The document covers non-functional requirements for the backend, frontend, and mobile components.

---

# NFRs

## Backend NFRs

### Performance

- **Requirement:** Response time for APIs should not exceed 2 seconds under normal load conditions.
- **Measurement:** Use Grafana dashboards to monitor response times.
- **Target:** 95% of requests within 2 seconds.

### Scalability

- **Requirement:** The system should automatically scale to handle a 10x increase in user traffic.
- **Measurement:** Simulate increased loads using Gatling testing.
- **Target:** Automatic scaling without human intervention.

### Security

- **Requirement:** Implement OAuth 2.0 for authentication and ensure data encryption.
- **Measurement:** Security audit reports.
- **Target:** No critical vulnerabilities reported.

---

## Frontend NFRs

### Usability

- **Requirement:** Website should comply with WCAG 2.1 AA standards.
- **Measurement:** Accessibility audit using Accessibility Checker.
- **Target:** 100% compliance.

### Performance

- **Requirement:** First Contentful Paint (FCP) within 1.5 seconds.
- **Measurement:** Use Lighthouse for performance metrics.
- **Target:** 75% of page loads within the target time.

---

## Mobile NFRs

### Battery Usage

- **Requirement:** The app does not consume more than 2% battery for 1 hour of active use.
- **Measurement:** Battery usage monitoring tools.
- **Target:** Less than 2% battery usage.

### Offline Functionality

- **Requirement:** Essential features available offline.
- **Measurement:** Manual and automated testing ensures data is presented as expected after the device goes offline.
- **Target:** Core functionalities operable without internet connection.

---

# Review and Updates

**Review Frequency:** Bi-annually.

**Next Review Date:** YYYY-MM-DD.

**Responsible Party:** [Name/Role].

---
NFR Template.md
Displaying NFR Template.md.