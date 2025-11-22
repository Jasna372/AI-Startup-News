AI Startup News – Analyst Agent

Automated News Extraction, Hype Filtering, Deduplication & Structured JSON Pipeline
Project Links
YouTube Demo Video:
[YouTube Demo Video](https://youtu.be/k46BnAkkvLQ?si=mIeulFADhFi_qRy19)

Task Chosen:0
Option 2 – The “Analyst” Agent (Advanced Automation)
AI/ML & Automation Internship Challenge.

1. Introduction
The Analyst Agent is an automated system designed to collect, clean, analyse, and structure news articles related to AI startups. Modern news feeds contain large amounts of repetitive, low-value, and hype-driven content. This project develops an intelligent workflow that removes noise and extracts only meaningful, event-based information.
The system uses APIs to fetch news articles, an AI model (Gemini) to extract structured data, and a deduplication mechanism to ensure each event appears only once.

2. Objective
The main objective of this project is to build an automation workflow that:
1. Collects AI startup–related news
2. Filters out hype or low-information articles
3. Extracts structured fields using an LLM
4. Removes duplicate articles that describe the same event
5. Produces clean, ready-to-use data for analytics
This ensures high-quality, meaningful information suitable for databases, dashboards, or decision-making tools.
3. Workflow Overview
The Analyst Agent follows a step-by-step pipeline:
Step 1: News Collection
The system connects to a public News API (such as NewsAPI) and fetches articles related to “AI startups.”
It retrieves the title, description, publication date, and source.
Step 2: Data Preprocessing
The raw article content is cleaned and reduced to essential parts.
This helps improve AI model performance and reduces token usage.
Only three fields are kept:
•	Title
•	Description
•	Source Name
This compact representation is used for analysis.
Step 3: LLM-Based Information Extraction
A Large Language Model (Gemini) analyzes each article and extracts specific structured fields:
	Company name
	Category or domain
	Sentiment score
	Funding or non-funding event
	Event summary
	Unique event ID (slug)
These structured fields help convert unstructured text into clean, standardized records.
Step 4: Hype Filtering
Some articles are promotional or generic and do not contain real technical events.
Examples include:
Top-10 trends lists
Product marketing
General discussions without new information
These articles are automatically ignored by the model using rule-based prompts.
Step 5: Deduplication
Multiple news sources often report the same event.
To avoid repeated information, the system removes duplicates using:
1. Primary method: LLM-generated event_id
2. Fallback: Hashing the event summary
This ensures each event is recorded only once, even if multiple articles describe it.
Step 6: Output Generation
After processing and filtering, the system produces:
A JSON file containing clean event data
A CSV file for spreadsheets or further analytics
This provides structured, ready-to-use data for downstream tasks.

4. Key Features
✔ LLM-Powered Analysis
Uses a large language model to understand article content and extract structured insights.
✔ Event-Based Deduplication
Ensures articles describing the same event are merged.
✔ Hype Filtering
Removes low-value content automatically.
✔ Token-Efficient Processing
Sends only essential parts of the article to the LLM.
✔ Reliable and Robust
Handles API rate limits, failed responses, and invalid data.

5. Advantages of This System
•	Produces high-quality, non-repetitive, informative news datasets
•	Reduces noise from marketing or generic articles
•	Automatically categorizes and summarizes event information
•	Saves time compared to manual news review
•	Supports decision-making for AI startup tracking or investment analysis

6. Conclusion
The Analyst Agent provides an intelligent, automated solution for processing AI startup–related news.
By combining API integration, AI-powered analysis, hype filtering, and intelligent deduplication, the system produces clean and structured data that can be directly used by analysts, dashboards, or machine learning models.
This project demonstrates strong skills in:
Automation logic, API integration, Data cleaning, LLM prompting, Deduplication strategies, JSON structuring.

Author
Name: Jasna K
Email: jasnak779@gmail.com
Location: Kerala, India
