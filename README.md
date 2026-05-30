## Overview

This assessment involved a read-only security review of the publicly accessible ReqRes API to evaluate the implementation of fundamental API security controls and identify potential security risks. The review focused on authentication requirements, access control mechanisms, HTTP response headers, information disclosure, and Cross-Origin Resource Sharing (CORS) configurations.

Testing activities were performed using Insomnia and Browser Developer Tools to inspect API requests, responses, headers, status codes, and publicly exposed information. The assessment followed a passive testing methodology and did not involve exploitation attempts, authentication bypass techniques, denial-of-service testing, or any actions that could impact the availability or integrity of the target system.

The objective of the assessment was to identify security observations, evaluate the effectiveness of implemented controls, and provide recommendations aligned with OWASP API Security best practices. Based on the observations identified, the API demonstrated a generally secure configuration with no evidence of critical vulnerabilities or unauthorised access.

## Tools Used

| Tool | Purpose |
|------|---------|
| Insomnia | API request testing, response analysis, authentication validation, and header inspection |
| Browser Developer Tools (Chrome DevTools) | Inspection of HTTP requests, response headers, status codes, and browser security configurations |

## Scope 

The scope of this assessment was limited to the publicly accessible ReqRes API and focused on evaluating fundamental API security controls through passive and read-only testing techniques. The assessment included review and analysis of publicly available endpoints, authentication requirements, HTTP response headers, status codes, response data, access control mechanisms, and Cross-Origin Resource Sharing (CORS) configurations.

The assessment specifically covered:

-Authentication enforcement mechanisms
-Access control validation
-HTTP security header implementation
-Information disclosure through API responses
-Cross-Origin Resource Sharing (CORS) settings
-General API security configuration observations

The assessment did not include exploitation attempts, authentication bypass testing, denial-of-service activities, vulnerability exploitation, source code review, infrastructure testing, or any actions that could impact the confidentiality, integrity, or availability of the target system. All activities were conducted within ethical and legal boundaries using publicly accessible functionality only.

## Methodology

The assessment was conducted using a structured passive testing methodology. Public API documentation was first reviewed to understand available endpoints, request methods, and authentication requirements. API requests were then performed using Insomnia, while Browser Developer Tools were used to inspect HTTP responses, response headers, status codes, and browser security configurations.

The collected information was evaluated against common API security risks, including authentication weaknesses, access control issues, information disclosure, insecure configurations, missing security controls, and Cross-Origin Resource Sharing (CORS) settings. Particular attention was given to authentication enforcement, exposed response data, HTTP security headers, and access restrictions implemented by the API.

All testing activities were limited to read-only interactions and safe requests permitted by the platform. No exploitation attempts, authentication bypass techniques, denial-of-service testing, or actions that could affect the availability, integrity, or confidentiality of the target system were performed. The assessment was conducted within ethical and legal boundaries and aligned with OWASP API Security best practices.
