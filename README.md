<h1>
  SAP Business One Sales Automation
  <img align="right" width="260" src="https://github.com/user-attachments/assets/23de988a-1c18-4938-8951-15715c6b1da4">
</h1>

Intelligent sales automation for SAP Business One that connects ERP data with AI models to generate actionable insights with n8n, automated reports in Google Sheets, and real-time notifications via Telegram.

[![SAP B1](https://img.shields.io/badge/SAP-Business%20One-0FAAFF)](https://github.com/atonekaboni/SBO)
[![n8n](https://img.shields.io/badge/n8n-Code-EA4B71)](https://gist.github.com/atonekaboni)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Post-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/posts/tonekaboni_automating-sap-business-one-with-n8n-activity-7338469577615421440-7kD7)
[![Guide](https://img.shields.io/badge/Full%20Guide-PDF-EC1C24?logo=adobeacrobatreader&logoColor=white)](https://github.com/user-attachments/files/22624398/4_SAPB1_SALES_AI_n8n.pdf)

## Overview

This n8n workflow connects SAP Business One with Google Sheets, Telegram, and Google's Gemma AI to automate sales reporting. The workflow extracts sales orders from SAP Service Layer, syncs them to Google Sheets for tracking, and uses AI to analyze daily performance trends. Sales summaries with key metrics and insights are automatically sent via Telegram each day. This setup eliminates manual data entry and report generation, helping small to midsize businesses reduce errors and make faster decisions based on real-time sales data.

<a href="https://github.com/user-attachments/files/22624398/4_SAPB1_SALES_AI_n8n.pdf">
  <img width="1473" alt="n8n workflow - Click to view full documentation" src="https://github.com/user-attachments/assets/97cda987-0214-4340-927e-7496b21c593f" />
</a><br>
<br>

**Key capabilities:**
- Real-time sales order extraction via Service Layer API
- AI-powered trend detection and recommendations
- Automated Google Sheets synchronization
- Daily Telegram summaries with key metrics
  <br>

## Technology Stack
- **n8n** - Workflow orchestration (Docker deployment)
- **SAP Business One 10+** - ERP system with Service Layer
- **Google Gemma AI** - Open source Natural language analysis
- **Google Sheets API** - Data storage and reporting
- **Telegram Bot API** - Notification delivery

## Prerequisites

To implement this automation, you need:

- **SAP Business One Access**: Valid database (e.g., SBODemoUS) with authorized username, password, and active Service Layer
- **Docker Experience**: Familiarity with installing and running Docker Desktop to deploy n8n
- **Google Account**: Access to Google Sheets and Google Cloud Platform for API setup (OAuth2 authentication)
- **Telegram Account**: To create a bot and obtain user ID for notifications
- **n8n Account**: Free or trial account at n8n.io, or self-hosted instance via Docker
- **Basic JavaScript Knowledge**: Understanding of JavaScript syntax to customize code snippets in workflow nodes

## Quick Start

1. Create a new workflow in n8n
2. Configure SAP Service Layer credentials
3. Set up Google Sheets and Gemma AI credentials
4. Create Telegram bot and add token
5. Add Code nodes and paste JavaScript codes
6. Connect nodes and activate workflow

For detailed setup instructions including Docker deployment, API configuration, and troubleshooting, see the [complete documentation](https://github.com/user-attachments/files/22624398/4_SAPB1_SALES_AI_n8n.pdf).

## Code Examples and Sample Output
The workflow uses JavaScript Code nodes for data processing and AI prompt generation:

- [Sales Data Processor](https://gist.github.com/atonekaboni/0aadc0af7e62539f28cf142238977e84) - Filters sales by date, calculates metrics, generates structured AI prompts
- [Additional Processing](https://gist.github.com/atonekaboni/5e316ad81d4d49091d3498b1e19bc32f) - Supporting workflow operations

<p align="right">
  <a href="https://github.com/atonekaboni/SBO_Sales_AI_Automation/">
    <img width="35%" src="https://github.com/user-attachments/assets/e4302810-3bcb-4008-ac9e-0cdb35273dce">
  </a>
</p>

## Why This Project?

This workflow can save hours of manual work and bring real-time visibility into sales performance. Once running, it delivers daily reports to Telegram without manual input, while the AI analysis identifies patterns that manual reviews might miss.

The initial setup takes a few hours, but the time investment pays off quickly. If you have Docker running and basic JavaScript knowledge, implementation is straightforward. Beyond sales reporting, this same approach extends to other SAP B1 modules like purchasing or inventory management, making it a cost-effective alternative to enterprise automation platforms with more control over what gets reported.

## Documentation

- [Full Tutorial (PDF)](https://github.com/user-attachments/files/22624398/4_SAPB1_SALES_AI_n8n.pdf) - Complete implementation guide with screenshots
- [LinkedIn Post](https://www.linkedin.com/posts/tonekaboni_automating-sap-business-one-with-n8n-activity-7338469577615421440-7kD7) - Project overview and business impact
- [Code Gists](https://gist.github.com/atonekaboni) - JavaScript snippets for Code nodes

## Related Projects

Additional SAP Business One Developed Solutions:

- [Advanced ATP and Delivery Schedule Management](https://github.com/atonekaboni/SBO_Inventory/)
- [Hidden Sales Insights](https://github.com/atonekaboni/SBO_Marketing)
- [Business Partner Management Enhancement](https://github.com/atonekaboni/SBO_ConnectedBP)
- [Sales Restriction](https://community.sap.com/t5/enterprise-resource-planning-blog-posts-by-members/custom-sales-blocklist-in-sap-business-one/ba-p/14164922)

View all projects: [GitHub Repository](https://github.com/atonekaboni/SBO)

## Contact

<p align="center">
  <a href="https://www.linkedin.com/in/tonekaboni/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  &nbsp;&nbsp;
  <a href="https://github.com/atonekaboni/" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  &nbsp;&nbsp;
  <a href="https://atonekaboni.github.io/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-D14836?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
</p>
