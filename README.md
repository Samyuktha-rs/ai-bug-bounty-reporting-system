# AI-Powered Automated Bug Bounty Reporting System

## Project Overview
This project automates bug bounty report generation using n8n, Telegram, and Google Gemini AI.

It receives vulnerability details through Telegram, checks for duplicate findings, generates a structured report, saves the report, and sends it back through Telegram.

## Technologies Used
- n8n – Workflow automation
- Telegram Bot – Receives findings and sends reports
- Google Gemini AI – AI-based report generation
- Data Tables – Report storage and duplicate checking
- JavaScript – Data processing and report formatting

## Workflow
1. Receive vulnerability details from Telegram.
2. Clean and process the input.
3. Check for duplicate findings.
4. Identify new vulnerabilities.
5. Count or retrieve existing reports.
6. Generate a report using Google Gemini AI.
7. Format the report.
8. Save the report in a data table.
9. Send the report through Telegram.

## Applications
- Bug bounty reporting
- Vulnerability documentation
- Penetration testing
- Security finding management
- Web application security testing

## Security
- Test only authorized applications.
- Never publish API keys, Telegram bot tokens, passwords, or confidential findings.

## Project Status
Workflow implementation and testing in progress.
