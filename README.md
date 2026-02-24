# Task-2-FUTURE_CS_03
# API Security Risk Analysis – Task 3 (Future Interns 2026)

## Overview

This repository contains my submission for **Cyber Security Task 3 (API Security Risk Analysis)**.

The objective of this task was to perform a read-only security assessment of a public API, identify potential security risks, classify their severity, and provide remediation recommendations — similar to how SaaS security consultants perform API audits.

---

## API Tested

**API Name:** JSONPlaceholder  
**Base URL:** https://jsonplaceholder.typicode.com  
**Type:** Public Demo REST API  

This API was selected because it is specifically designed for safe testing and learning.

---

## Tools Used

- **Postman** – API request testing and response inspection
- **GitHub** – Version control and submission repository
- **Microsoft Word / PDF** – Report documentation
- **Browser Developer Tools** – Header and response inspection

---

## Scope of Testing

The assessment was limited to:

- Public endpoints only
- Read-only GET requests
- Safe POST request (demo endpoint)
- Header inspection
- Response data inspection
- Authentication requirement analysis

The following were **NOT performed**:

- Exploitation attempts
- Authentication bypass attempts
- Denial of Service (DoS) testing
- Attacks on private or production systems

This assessment strictly followed ethical testing guidelines.

---

## Endpoints Tested

- `GET /posts`
- `GET /posts/1`
- `GET /comments`
- `POST /posts` (safe test request)

Screenshots of all Postman requests are available in the `/screenshots` folder.

---

## Key Security Findings

The full analysis is documented in the attached PDF report.  
Summary of identified risks includes:

- Open / unauthenticated endpoints
- Excessive data exposure
- Lack of rate limiting
- No authentication enforcement
- Missing security headers

Each risk has been classified as Low, Medium, or High based on business impact.

---

## Deliverables Included

- API Security Risk Analysis Report (PDF)
- Postman request screenshots
- Structured GitHub repository
- Clear documentation of tools, methodology, and scope

---

## Author

Laiken Naidoo  
Future Interns – Cyber Security Task 3  
February 2026
