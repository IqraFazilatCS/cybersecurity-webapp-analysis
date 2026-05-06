# MERN Stack Cybersecurity Assessment

## Overview
This project presents a security analysis of a MERN Stack User Management System.  
The goal was to identify vulnerabilities and apply security improvements.

## Technologies Used
- MongoDB
- Express.js
- React.js
- Node.js

## Tools Used
- OWASP ZAP
- Browser Developer Tools

## Vulnerabilities Identified
- Missing Content Security Policy (CSP)
- Missing X-Frame-Options (Clickjacking risk)
- Missing X-Content-Type-Options
- Server Information Disclosure
- No HTTPS implementation

## Security Improvements
- Added security headers
- Disabled server information leakage
- Input validation & sanitization
- Recommendation for HTTPS

## Screenshots
(Add your screenshots here)

##  How to Run
```bash
npm install
npm start
```

## Report
See full report in:
`Cybersecurity_Assessment_Report.docx`
