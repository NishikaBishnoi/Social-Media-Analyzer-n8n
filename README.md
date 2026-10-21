# Social Media Analyzer — AI Automation with n8n

An AI-powered YouTube data analysis workflow built with n8n, the YouTube Data API, Google Gemini, Google Sheets, and Gmail.

## Project Overview

This project automates the process of collecting YouTube data, processing API responses, extracting relevant information, generating analysis with AI, and delivering results through email.

It demonstrates how API integration, workflow automation, data transformation, and generative AI can work together in a single workflow.

## Workflow Architecture

1. **Workflow Trigger:** Starts the automation using the configured trigger.
2. **YouTube API Integration:** HTTP Request nodes retrieve data from the YouTube Data API.
3. **Data Processing:** JavaScript code nodes transform and prepare the retrieved information.
4. **Conditional Routing:** An IF node determines which path the workflow follows.
5. **Data Extraction:** A Split Out node separates selected data into individual items.
6. **Data Transformation:** Edit Fields nodes prepare essential information and structure the data for downstream steps.
7. **Google Sheets Integration:** The workflow saves the configured data to Google Sheets.
8. **Analysis Preparation:** A JavaScript code node prepares the analysis input.
9. **AI Analysis:** An AI Agent connected to Google Gemini processes the prepared information and generates insights.
10. **Email Reporting:** Gmail sends the configured analysis or report.

## Technology Stack

- n8n — Workflow automation
- YouTube Data API — YouTube data retrieval
- HTTP Request — API integration
- JavaScript — Data transformation and processing
- IF and Split Out — Conditional routing and item processing
- Edit Fields — Data mapping and preparation
- Google Gemini — AI-generated analysis
- Google Sheets — Data storage
- Gmail — Automated reporting

## Setup Requirements

- A running n8n instance
- Access to the YouTube Data API
- Google Gemini API access
- Google Sheets and Gmail credentials configured in n8n

## Setup Instructions

1. Download the workflow JSON from this repository.
2. Import the workflow into your n8n instance.
3. Configure your own API credentials and connected accounts.
4. Review the HTTP Request nodes and YouTube API parameters.
5. Verify the Google Sheets mappings and Gmail recipient configuration.
6. Test the workflow with a small, appropriate dataset before using it regularly.

## Security

Never publish API keys, access tokens, passwords, private webhook URLs, or confidential data. Configure credentials securely in n8n.

## Author

Nishika Bishnoi

AI Automation | API Integration | Data Processing | Generative AI


