# FeedbackAI — AI-Powered Customer Complaint Management

**What if no customer complaint went unanswered?**

FeedbackAI is an AI-powered customer complaint management platform developed as part of the **ThirdUni AI Program**. It helps businesses streamline complaint handling, analyze customer feedback, and generate intelligent, context-aware responses using Artificial Intelligence, Retrieval-Augmented Generation (RAG), and workflow automation.

Ooredoo Algeria is used solely as an illustrative use case to demonstrate the platform's capabilities. FeedbackAI is an independent project and is not affiliated with, endorsed by, or officially connected to Ooredoo Algeria.

## Project Overview

FeedbackAI streamlines the customer feedback lifecycle, from complaint submission and processing to automated responses and team monitoring.

### How It Works

1. **Feedback Submission:** Customers submit their feedback through the web application.
2. **Data Storage:** Feedback is stored in Firebase Cloud Firestore.
3. **Backend Processing:** The backend API handles feedback data and supports communication between the application and the automation workflow.
4. **AI-Powered Response Generation:** An n8n workflow retrieves feedback details and uses a Groq-powered AI agent to generate personalized responses.
5. **Knowledge Retrieval (RAG):** The AI agent searches a company-specific knowledge base through Pinecone, using Google Gemini embeddings to retrieve relevant information and generate context-aware responses.
6. **Email Delivery:** The generated response is formatted and sent to the customer through Gmail.
7. **Processing Tracking:** Processed feedback is recorded in Firestore, while the workflow updates the backend with the generated response and email status.
8. **Dashboard Monitoring:** Administrators can monitor feedback and responses through the web application's dashboard.

## Explore the Project

The project is organized into three independent repositories:

| Component | Description | Repository |
|---|---|---|
| **Frontend** | Web application, user authentication, feedback submission, and admin dashboard. | [feedbackai-frontend](https://github.com/FeedbackAI-2026/feedbackai-frontend) |
| **Backend** | Backend API services and feedback processing. | [feedbackai-backend](https://github.com/FeedbackAI-2026/feedbackai-backend) |
| **Email Workflow** | n8n automation workflow for AI-powered response generation, knowledge retrieval, and email delivery. | [EmailWorkflow](https://github.com/FeedbackAI-2026/EmailWorkflow) |

## Technology Stack

- **Frontend:** Next.js, TypeScript, Tailwind CSS
- **Backend:** Backend API and application services
- **Database:** Firebase Cloud Firestore
- **Authentication:** Firebase Authentication
- **AI Model:** Groq — `openai/gpt-oss-120b`
- **Retrieval-Augmented Generation (RAG):** Pinecone Vector Store
- **Embeddings:** Google Gemini
- **Workflow Automation:** n8n
- **Email Integration:** Gmail through n8n

## Live Demo

- **Main Platform:** [https://feedbackaipro.vercel.app/](https://feedbackaipro.vercel.app/)
- **Ooredoo Algeria Demo:** [https://feedbackai-ooredoo.vercel.app/](https://feedbackai-ooredoo.vercel.app/)

## About

FeedbackAI was developed as a collaborative project within the **ThirdUni AI Program**, exploring how artificial intelligence can improve customer support by making complaint management more efficient, intelligent, and responsive.

The platform is designed to serve businesses across different industries. Ooredoo Algeria is used exclusively as a demonstration use case and does not represent an affiliation or endorsement.
