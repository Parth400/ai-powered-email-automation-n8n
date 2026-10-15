# AI-Powered Email Automation using n8n

## Overview
This project demonstrates an AI-powered workflow built using n8n to automate form submission processing and email communication. It integrates an AI Agent with the OpenAI Chat Model and Gmail to create an automated workflow.

## Technologies Used
- **n8n:** Workflow automation and orchestration
- **OpenAI Chat Model:** AI-powered text processing and responses
- **AI Agent:** Coordinates the workflow's AI processing
- **Gmail Integration:** Email communication and delivery

## Workflow
1. Trigger the workflow when a form is submitted.
2. Process the submission using an AI Agent connected to an OpenAI Chat Model.
3. Use Gmail integration to send an email as part of the automated workflow.

## Project Files
- `workflow.json` — Exported n8n workflow configuration.

## Setup
1. Import `workflow.json` into an n8n instance.
2. Configure the required OpenAI and Gmail credentials.
3. Verify the node settings and email configuration.
4. Test the workflow with a sample form submission before activating it.

## Note
The workflow was developed in n8n. The exported JSON provides the workflow configuration; API credentials and account-specific settings must be configured separately.

## Purpose
To demonstrate practical applications of AI agents, language models, and workflow automation for reducing manual effort in business communication.
