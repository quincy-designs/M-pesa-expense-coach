# M-Pesa Expense Coach – AI Integration & Repository Management

# Overview
This repository contains my individual contribution to the M-Pesa Expense Coach project. My role focused on AI API integration, prompt design, JSON response validation, AI financial summaries, and GitHub repository management.

# Files Included
-ai_handler.py: Connects the Python application to the AI API securely using environment variables stored in .env.
-prompts.py: Contains the system instructions that guide the AI to analyze spending in KES and give practical financial advice.
-json_validator.py: Validates the AI's JSON response to ensure all required fields are present before displaying results.
-ai_summary.py: Formats the validated JSON data into a clear spending summary for the user.
-requirements.txt: Lists the required Python packages (openai,python-dotenv).
-Github Repository Management: Manage the group repository structure,
configure "gitignore" to block sensitive files like; env and coordinate branch merges across the team.

# Setup & Installation
1. Clone this repository from Github and copy its URL from Github
2. Install the required libraries:
    python-dotenv and openai
    bash
   pip install requirements.txt
3. Create a `.env` file in the project folder and add your API key:
   text
   OPENAI_API_KEY=your_api_key_here
   
