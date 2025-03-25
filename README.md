# CIBC Chatbot

Welcome to the CIBC Chatbot repository! This project leverages Natural Language Processing (NLP) to help users extract key insights from CIBC's quarterly financial reports through an interactive chatbot. Users can ask financial queries and receive instant responses, making it easier to analyze financial trends without manually going through extensive reports.





📌 Table of Contents

Overview

Features

Technologies Used

Setup and Installation

Usage

Model Training and Fine-Tuning

Overview

The CIBC Chatbot is designed to simplify financial data retrieval by:

Allowing users to ask natural language questions about financial reports.

Providing insights into key metrics such as revenue, net income, and expenses.

Offering comparisons of financial performance across different quarters or years.

This chatbot is particularly useful for non-technical users who need quick access to financial data without diving into complex reports.

Features

✅ Conversational Interface – Interact with the chatbot in plain English.
✅ Advanced NLP Processing – Extracts meaningful insights from quarterly reports.
✅ Custom Query Handling – Provides context-aware responses based on user queries.
✅ Data Visualization – Generates charts and graphs to illustrate trends.

🛠️ Technologies Used

Component

Technology

Programming Language

Python

NLP Libraries

Hugging Face Transformers, spaCy

Backend Framework

Flask

Frontend Framework

React

Data Storage

SQLite, Pandas

Visualization Tools

Matplotlib, Plotly

Deployment

Docker, AWS

🏗️ Setup and Installation

🔹 Prerequisites

Python 3.8+

Node.js & npm (for frontend)

Docker (optional, for containerized deployment)

🔹 Installation Steps

Clone the repository:

git clone https://github.com/aagam128/CIBC_Chatbot.git
cd CIBC_Chatbot

Run the news release script:

Execute news-release.ipynb to generate required models.

Move generated models to cibc-financial-insight-backend/models.

Install backend dependencies:

cd cibc-financial-insight-backend
pip install -r requirements.txt

Install frontend dependencies:

npm install

Start the backend server:

python app.py

Access the chatbot:

Open your browser and go to http://localhost:8000.

💡 Usage

Once the chatbot is running, users can start querying financial data. Example questions:

"What was the revenue for Q3 2023?"

"Show the trend in net income for the last four quarters."

"Compare Q1 and Q2 expenses for 2024."

The chatbot analyzes the reports and returns text-based responses or visual graphs where applicable.

🎯 Model Training and Fine-Tuning

The chatbot is powered by a fine-tuned transformer model to ensure accurate responses. The training process involves:

Data Preprocessing: Extracting and structuring financial data from quarterly reports.

Tokenization: Processing data using Hugging Face’s tokenizer.

Fine-Tuning: Training a BERT-based model on financial queries and responses.

Evaluation: Validating model performance using real-world queries.

