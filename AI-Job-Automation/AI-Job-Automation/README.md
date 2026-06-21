# AI Job Automation using n8n

## Overview

This project automatically fetches AI/ML, Python, Data Science and Software Engineering jobs from Job APIs and sends a beautiful HTML email every day.

## Features

- Daily scheduled automation
- Fetches latest jobs
- HTML email formatting
- Apply Now button
- Gmail integration
- JavaScript processing
- REST API integration

## Workflow

Schedule Trigger

↓

HTTP Request (Job API)

↓

JavaScript

↓

Gmail

## Technologies

- n8n
- JavaScript
- REST API
- Gmail API
- JSON
- HTTP Request

## Screenshots

### Workflow

![Workflow](screenshots/workflow.png)

### Email

![Email](screenshots/email-output.png)

## Project Structure

```
AI-Job-Automation/
├── workflow.json
├── README.md
├── screenshots/
├── sample-output/
└── docs/
```

## Future Improvements

- LinkedIn Jobs
- Wellfound Jobs
- Resume Matching
- ATS Score
- Slack Notifications
- Telegram Notifications
