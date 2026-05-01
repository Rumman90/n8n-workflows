# n8n Automation Workflows

This repository contains reusable n8n workflows for automation, integrations, and background jobs.

## Folder Structure
/workflows  
 ├── workflow-cron-http.json  
 ├── workflow-webhook-slack.json  
 ├── workflow-lead-summary.json  
 ├── workflow-transform-forward.json  
 ├── workflow-rss-to-slack.json  
 ├── workflow-form-to-google-sheets.json  
 ├── workflow-api-health-check.json  
 └── workflow-weekly-report-email.json  

## Included Workflows
- `workflow-cron-http.json` - runs a scheduled HTTP API request.
- `workflow-webhook-slack.json` - receives a webhook payload and sends a Slack notification.
- `workflow-lead-summary.json` - reads leads from Google Sheets and emails a daily summary.
- `workflow-transform-forward.json` - fetches JSON, transforms fields, and forwards it to another API.
- `workflow-rss-to-slack.json` - reads an RSS feed each morning and posts the latest items to Slack.
- `workflow-form-to-google-sheets.json` - captures contact form submissions, appends them to Google Sheets, and emails an admin.
- `workflow-api-health-check.json` - checks an API health endpoint every hour and sends an alert if it is unhealthy.
- `workflow-weekly-report-email.json` - reads metrics from Google Sheets and emails a weekly report.

## How to Use
1. Open n8n
2. Go to **Import Workflow**
3. Upload any JSON file from `/workflows`
4. Update credentials (API keys, Slack tokens, email settings)
5. Activate the workflow

## Requirements
- n8n (self-hosted or cloud)
- Working credentials (Slack, Google Sheet, Email, HTTP APIs)

## Contributions
Pull requests are welcome!
