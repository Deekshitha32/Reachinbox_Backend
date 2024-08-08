## Description

This project is an email management tool that integrates with Gmail and Outlook. It uses OpenAI to categorize and generate responses to emails. The tool is built using Node.js, TypeScript, and utilizes OAuth for authentication.

## Features

- **OAuth Authentication**: Supports Gmail and Outlook authentication.
- **Email Categorization**: Categorizes emails into 'Action Required', 'Information', or 'Follow-up Needed' using OpenAI.
- **Automated Responses**: Generates appropriate responses to emails based on their category.
- **Scheduled Processing**: Processes emails from both Gmail and Outlook every 5 minutes using cron jobs.

## Installation

```bash
# Clone the repository
git clone https://github.com/username/repository.git
cd repository

## Install dependencies
npm install

 Configure Environment Variables
 Create a .env file in the root directory and add the following environment variables:
 GMAIL_CLIENT_ID=your_gmail_client_id
 GMAIL_CLIENT_SECRET=your_gmail_client_secret
 GMAIL_REDIRECT_URI=your_gmail_redirect_uri
 OUTLOOK_CLIENT_ID=your_outlook_client_id
 OUTLOOK_CLIENT_SECRET=your_outlook_client_secret
 OUTLOOK_REDIRECT_URI=your_outlook_redirect_uri
  OPENAI_API_KEY=your_openai_api_key

## Run the Application
npm start
