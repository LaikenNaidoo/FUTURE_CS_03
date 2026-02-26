# FUTURE_CS_03  
## API Security Risk Analysis – Task 3 (Future Interns 2026)

---

## Overview

This repository contains a structured API Security Risk Analysis conducted as part of the Future Interns Cyber Security track.

The objective of this assessment was to perform a read-only security evaluation of a public REST API, identify common API security weaknesses, classify risks by severity, and provide business-oriented remediation recommendations — similar to a real-world SaaS security engagement.

---

## API Tested

**API Name:** JSONPlaceholder  
**Base URL:** https://jsonplaceholder.typicode.com  
**API Type:** Public Demo REST API  

This API was selected because it is intentionally designed for safe educational testing.

---

## Tools Used

- Postman – API request execution and response inspection  
- Browser Developer Tools – Header and response analysis  
- Microsoft Word / PDF – Report documentation  
- GitHub – Version control and structured submission  

---

## Scope of Testing

The assessment was limited to:

- Public endpoints only  
- Read-only GET requests  
- Safe POST request (demo endpoint)  
- Authentication requirement analysis  
- Authorization behavior observation  
- Response and header inspection  

The following were **not performed**:

- Exploitation attempts  
- Authentication bypass attempts  
- Denial-of-Service (DoS) testing  
- Attacks on private or production systems  

This assessment strictly followed ethical testing guidelines.

---

## Endpoints Tested

- `GET /posts`  
- `GET /posts/1`  
- `GET /comments`  
- `POST /posts` (safe test request)  

Supporting Postman screenshots are available in the `/screenshots` directory.

---

## Key Security Findings Summary

The full analysis is documented in the attached PDF report.

Summary of identified risks:

- Lack of authentication enforcement (High)
- Broken authorization controls (High)
- Excessive data exposure (Medium)
- Absence of rate limiting (Medium)
- Missing security headers (Low–Medium)

Each risk was classified based on potential business impact in a real-world SaaS environment.

---

## Deliverables

- API Security Risk Analysis Report (PDF)
- Postman request screenshots
- Structured GitHub documentation
- Clearly defined scope, tools, and methodology

---

## Disclaimer

This repository is created for educational purposes only.  
All testing was conducted against a public demo API designed for safe learning.
