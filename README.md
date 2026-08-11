# n8n Google Sheets to Gmail Automation

An automated workflow built with **n8n**, **Google Sheets**, **JavaScript**, and **Gmail**.

This workflow reads rows from a Google Sheet, combines the data into a structured email summary, and sends the result through Gmail automatically.

This project was created as part of the **Gen AI Architect Program – Assignment 9: n8n Automation: Google Sheets to Gmail**.

## Workflow Overview

The workflow follows this structure:

```text
Manual Trigger
      ↓
Google Sheets - Get Row(s)
      ↓
IF
      ↓
Code in JavaScript
      ↓
Gmail - Send Message
