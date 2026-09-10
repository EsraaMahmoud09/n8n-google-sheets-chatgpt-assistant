# n8n-google-sheets-chatgpt-assistant

# Small ChatGPT by Google Sheet 

An automated n8n workflow that integrates **Google Sheets** with **Anthropic Claude (LLM)** to process and respond to queries seamlessly.

## Workflow Architecture
1. **Google Sheets Node**: Appends rows or triggers based on new data entries.
2. **Basic LLM Chain**: Connects the input text directly to the AI model.
3. **Anthropic Chat Model**: Generates intelligent contextual responses.

## Tech Stack & Tools
* **n8n** (Automation Platform)
* **Google Sheets API**
* **Anthropic Claude API**
