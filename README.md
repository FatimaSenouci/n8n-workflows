
# n8n Workflows

This repository contains exported workflows from **n8n**, an open-source workflow automation tool.  
The workflows automate tasks like sending emails, processing data, and integrating with other services.

## Workflow Files

- **daily-tasks-email.json**  
  Sends a daily summary of tasks via email.  
  - Extracts tasks from input data (e.g., Google Sheets)  
  - Formats tasks in a list  
  - Sends email using SMTP/Gmail  

## How to Use

1. **Import Workflow into n8n**
   - Open your n8n instance
   - Click **Workflow → Import**
   - Upload the desired JSON file (e.g., `daily-tasks-email.json`)

2. **Configure Credentials**
   - Email credentials (SMTP, Gmail, etc.)
   - Any API keys or service connections used in the workflow

3. **Activate Workflow**
   - Test the workflow manually first
   - Activate it to run automatically (via schedule or webhook)

## Contributing

Feel free to contribute by:

- Adding new workflows  
- Improving existing workflows  
- Reporting issues or suggestions
