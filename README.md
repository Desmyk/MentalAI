# Capstone Project Presentation: Mental Health AI Assistant
## Project Overview
The Mental Health AI Assistant is a full-stack web application designed to provide accessible, empathetic, and intelligent support for mental well-being. Leveraging advancements in AI, Natural Language Processing (NLP), and web technologies, the platform offers users a safe space to express themselves, reflect on their emotional state, and receive relevant support resources.

Mental health remains a critical global concern, and many individuals lack access to immediate or affordable support. This project aims to bridge that gap by offering an always-available, AI-driven assistant capable of engaging users in meaningful conversations, tracking emotional trends, and providing personalized wellness tools.

## Objectives
*AI-Powered Conversations*: Enable users to chat with an empathetic, conversational AI trained to understand emotional tone and offer supportive dialogue.

*Real-Time Sentiment Analysis*: Analyze and respond to the emotional tone of user messages using NLP models like VADER and Hugging Face Transformers.

*Mood & Journal Logging*: Let users track their daily mood and thoughts through journaling features to promote emotional awareness and reflection.

*Curated Mental Health Resources*: Provide access to helpful articles, videos, and coping strategies tailored to the user's mental state.

*Personalized Dashboard*: Offer a secure, personalized user interface for engaging with the assistant, viewing sentiment trends, and accessing tools.

*Deployment for Accessibility*: Ensure the application is hosted online, making it easily accessible to users seeking support anytime, anywhere.

## Technology Stack
Layer	Tools & Frameworks
Backend	Django (Python)
AI/NLP	Hugging Face Transformers (DialoGPT), VADER Sentiment
Frontend	React.js (planned), Tailwind CSS
Database	SQLite (development), PostgreSQL (production)
Deployment	Render / Heroku / AWS (TBD)
Dev Tools	VS Code, Postman, GitHub, Virtualenv, PyTorch

## Key Features
### AI Chatbot
Built using Hugging Face’s DialoGPT, the chatbot carries on open-domain conversations designed to be non-judgmental and empathetic.

Sentiment-aware responses adapt to the user’s mood in real time using VADER sentiment analysis.

### Sentiment & Mood Analysis
VADER analyzes user input to detect and score emotional tone.

This feedback is visualized over time, allowing users to recognize emotional patterns.

### Mood Tracker & Journal
Simple UI for logging daily mood (e.g., scale from 1–5).

Journaling feature for expressive writing, which can be reflected back in a user’s dashboard.

### Mental Health Resource Center
Dynamically serves videos, articles, and self-help guides based on mood analysis and user interests.

### Secure User Dashboard
Custom dashboards show personal sentiment trends, journal entries, and recommended content.

Secure login and authentication built with Django.

## Deployment & Future Plans
The app is set to be deployed on Render, with scalable infrastructure planned via AWS or Heroku for real-world use.

Upcoming improvements include:

Integration of voice-based interaction

Use of more advanced transformer models for deeper emotional understanding

Inclusion of CBT-based prompts to support therapeutic self-reflection

## Challenges & Learning Outcomes
Fine-tuning conversational AI for sensitivity and emotional appropriateness required careful prompt engineering and model testing.

Balancing user privacy with helpful sentiment logging posed data handling and ethical considerations.

Gained strong practical experience in full-stack development, AI integration, and deploying user-centric mental health technology.

## Impact Statement
This project demonstrates the powerful intersection of AI and mental health support, offering a scalable and sensitive tool that can provide real-time comfort and guidance. While it’s not a replacement for professional help, it serves as a companion tool to support mental well-being in the digital age.
