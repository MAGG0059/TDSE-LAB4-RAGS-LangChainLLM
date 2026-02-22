
# TDSE LAB4 LangChainLLM Manuel Alejandro Guarnizo

I built a conversational AI agent using LangChain and Google Gemini that provides personalized restaurant recommendations. The agent maintains memory for each user, remembers their cuisine preferences, and responds with food-themed wordplay. It uses custom tools to determine user preferences and fetch restaurant data based on city and cuisine type. The system handles both location-aware queries and direct requests, normalizes city names (like SF, NYC), and returns structured responses containing restaurant names, price ranges, and descriptions. Each user has their own conversation thread with persistent memory, demonstrating key concepts from the LangChain real-world agent tutorial including context management, tool integration, structured outputs, and conversational memory. The code is organized in a Jupyter notebook with clear step-by-step implementation following the official LangChain quickstart guide. My API key is stored locally in a .env file which is not included in the repository for security reasons - users need to create their own .env file with their Google API key to run the agent.


## In this repository are the notebooks:
Basic-LangChainLLM.ipynb

## Project Overview
This repository contains one Jupyter Notebooks that demonstrate:
    where we show the  logistic regression diferrent uses


## Setup Instructions
python-dotenv         
google-generativeai   
langchain           
langchain-google-genai 
langgraph             
tiktoken             
typing-extensions     
dataclasses-json     


API Key Setup (IMPORTANT)

-Create a .env file in the project root (this file is listed in .gitignore and will NOT be pushed to GitHub)

-Add your Google API key to the .env file:

GOOGLE_API_KEY=your-actual-api-key-here
Get your free API key from: https://aistudio.google.com


### Arquitecture LangChainLLLM

User → System Prompt → Chat Prompt Template → Model (Google Gemini) → Output Parser → Response

### Requirements
- **Python 3.10+** (compatible with most Python 3.x versions)
- **Jupyter Notebook** or **JupyterLab**
- Python libraries: `numpy`, `matplotlib`, `pandas`

### Installation Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>