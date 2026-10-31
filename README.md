# FeedbackAI — AI-Powered Customer Complaint Management

**What if no customer complaint went unanswered?**

FeedbackAI is an AI-powered customer complaint management platform developed as part of the **ThirdUni AI Program**. It helps businesses automate complaint processing, analyze customer sentiment, and deliver intelligent, context-aware responses using Artificial Intelligence, Retrieval-Augmented Generation (RAG), and workflow automation.

Ooredoo Algeria is used as an illustrative use case to demonstrate the platform's capabilities. FeedbackAI is an independent project and is not affiliated with or endorsed by Ooredoo Algeria.

## Project Overview

FeedbackAI streamlines the customer feedback lifecycle, from complaint submission to AI-generated responses and team monitoring.

### How It Works

1. **Feedback Submission:** Customers submit complaints through the web application.
2. **Data Storage:** Feedback is securely stored in Firebase Cloud Firestore.
3. **AI Processing:** The backend uses AI and RAG to analyze complaints and generate context-aware responses.
4. **Classification:** Feedback is categorized and analyzed to identify sentiment and priority.
5. **Response Delivery:** Automated workflows handle email communication.
6. **Dashboard Monitoring:** Administrators can monitor feedback, responses, and analysis through a real-time dashboard.

## Explore the Project

The project is organized into three independent repositories:

| Component | Description | Repository |
|---|---|---|
| Frontend | Web application, authentication, feedback submission, and admin dashboard. | [feedbackai-frontend](https://github.com/FeedbackAI-2026/feedbackai-frontend) |
| Backend | AI processing, complaint analysis, and API services. | [feedbackai-backend](https://github.com/FeedbackAI-2026/feedbackai-backend) |
| Email Workflow | Email automation and workflow integration. | [EmailWorkflow](https://github.com/FeedbackAI-2026/EmailWorkflow) |

## Technology Stack

- **Frontend:** Next.js, TypeScript, Tailwind CSS
- **Backend:** Python and AI integration
- **AI:** Large Language Models (LLMs), Retrieval-Augmented Generation (RAG)
- **Database:** Firebase Cloud Firestore
- **Authentication:** Firebase Authentication
- **Automation:** n8n
- **Email Integration:** Gmail API

## Live Demo

- **Main Platform:** https://feedbackaipro.vercel.app/
- **Ooredoo Algeria Demo:** https://feedbackai-ooredoo.vercel.app/

## About

FeedbackAI was developed as a collaborative project within the **ThirdUni AI Program**, exploring how AI can transform customer support by making complaint management more efficient, intelligent, and responsive.

The platform is designed to serve businesses across different industries, with Ooredoo Algeria serving solely as a demonstration use case.
