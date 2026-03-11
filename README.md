# FUTURE_CS_01 - Vulnerability Assessment Report 

## Overview
This repository contains a vulnerability assessment report conducted as part of the **Future Intern Cyber Security Internship Program for task one**.

The objective of this project was to identify potential security weaknesses in a web application using passive and non-intrusive security testing techniques.

## Target Website
http://bwapp.hakhub.net

The tested application is **bWAPP (Buggy Web Application)**, an intentionally vulnerable web application designed for cybersecurity training and vulnerability testing.

## Scope of Assessment
The scope of this assessment was limited to **passive reconnaissance and configuration analysis**.  
No active exploitation or attacks were performed during the testing process.

The assessment focused on identifying common web security weaknesses including:
- exposed network services
- server information disclosure
- missing security headers
- insecure session cookie configuration

## Tools Used & Purpose: 
1. Nmap -  For network scanning and service discovery. 
2. OWASP ZAP - For passive vulnerability scanning.  
3. Browser Developer Tools- For inspecting HTTP headers and cookies.
4. SecurityHeaders.com -  For security header analysis. 

## Key Findings
The assessment identified **four Medium-risk vulnerabilities**:
1. Open Ports and Services Identified
2. Server Information Disclosure
3. Missing Security Headers
4. Insecure Session Cookie Configuration  

## Repository Contents
1. Vulnerability_Assessment_Report.pdf – Full professional report.
2. Evidence/ – Supporting screenshots and tool outputs. 

## Purpose of This Project
This project demonstrates the process of conducting a basic vulnerability assessment and documenting findings using industry-style reporting methods.


