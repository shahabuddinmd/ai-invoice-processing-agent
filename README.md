# 🤖 AI Invoice Processing Agent

An automated end-to-end AI Agent built using **n8n**, **OpenAI API**, and **Google Sheets** to process PDF/Image invoices and automatically extract structured data into a centralized spreadsheet.

---

## 🚀 Overview & Workflow

1. **Trigger:** Receives invoice documents (PDFs/Images) uploaded via a Webform/Webhook.
2. **AI Data Extraction:** Utilizes OpenAI Vision/LLM to extract key details in structured JSON format.
3. **Automated Storage:** Parses and maps the extracted attributes (`Invoice Number`, `Date`, `Vendor Name`, `Total Amount`) directly into Google Sheets.

---

## 🛠️ Tech Stack

- **Workflow Engine:** n8n
- **AI Processing:** OpenAI API
- **Data Storage:** Google Sheets
- **Language/Regex:** JavaScript Data Mapping (`split`/Regex)

---

## 📦 How to Import

1. Download the `ai-invoice-processing-agent.json` file from this repository.
2. Open your **n8n** dashboard.
3. Go to **Workflows > Import from File** and upload the JSON.
4. Configure your **OpenAI Credentials** and **Google Sheets OAuth**.
5. Activate the workflow!
