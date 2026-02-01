![Workflow thumbnail](assets/thumbnail.webp)

![Workflow thumbnail](assets/thumbnail.svg)

![Workflow thumbnail](assets/thumbnail.svg)

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Evaluate AI workflows using Google Sheets, Gemini, Claude, GPT, and Perplexity

Advanced n8n automation for Evaluate AI workflows using Google Sheets, Gemini, Claude, GPT, and Perplexity.

## Overview
- Category: Engineering, AI Summarization
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Learn 5 n8n evaluation methodscategorization, correctness, tools, string similarity & helpfulnessplus Sheets setup, tracking, and best practices.

## Included Files
- `workflow.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.chainSummarization`
- `@n8n/n8n-nodes-langchain.informationExtractor`
- `@n8n/n8n-nodes-langchain.lmChatAnthropic`
- `@n8n/n8n-nodes-langchain.lmChatGoogleGemini`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `n8n-nodes-base.evaluation`
- `n8n-nodes-base.evaluationTrigger`
- `n8n-nodes-base.extractFromFile`
- `n8n-nodes-base.gmail`
- `n8n-nodes-base.gmailTrigger`
- `n8n-nodes-base.if`
- `n8n-nodes-base.perplexityTool`
- `n8n-nodes-base.stickyNote`

## Author

Murtaza Baig

## Screenshots

![Screenshot](assets/10025-automate-interior-design-lead-qualification-with-ai---human-approval-to-notion.webp)
![Screenshot](assets/10376-sync-events-from-excel-to-google-calendar-with-gpt-4o-mini-smart-summaries.webp)
![Screenshot](assets/5966-analyze---target-high-value-customers-with-gpt-4-and-bright-data-mcp.webp)
![Screenshot](assets/image_c8e1990a84.png)
![Screenshot](assets/n8nworfklows.webp)
![Screenshot](assets/thumbnail.webp)

## License
MIT License. See `LICENSE`.