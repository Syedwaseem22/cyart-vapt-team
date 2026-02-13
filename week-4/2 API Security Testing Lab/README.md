# API Security Testing Lab

## Practical Application
This lab focuses on identifying and exploiting API vulnerabilities aligned with the OWASP API Top 10.

---

## Objectives
- Enumerate API endpoints.
- Identify authorization and injection flaws.
- Manipulate tokens and parameters.
- Produce professional security documentation.

---

## Tools Used
- Burp Suite
- Postman
- sqlmap

---

## Test Environment
Target: DVWA API

---

## Activity Log

| Test ID | Vulnerability      | Severity | Target Endpoint |
|--------:|-------------------|----------|-----------------|
| 008     | BOLA              | Critical | /api/users      |
| 009     | GraphQL Injection | High     | /graphql        |

---

## Manual Testing

Burp Suite was used to intercept requests and replay them with modified object identifiers and tokens. Unauthorized data access confirmed missing access control validation on multiple endpoints.

---

## Testing Checklist
- Enumerate API endpoints  
- Test for BOLA  
- Fuzz GraphQL queries  
- Validate authentication & authorization  
- Attempt injection attacks  

---

## API Test Summary (50 words)

The assessment revealed broken object-level authorization and improper input validation. Attackers could enumerate user records and manipulate queries. Strong authentication enforcement, schema validation, and centralized authorization checks are required to prevent privilege abuse.

---

## Skills Demonstrated
- API enumeration
- Access control testing
- Token manipulation
- Structured reporting

---

## Author
Syed Waseem
