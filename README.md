
# Chat with SQL

A Streamlit-based application that allows users to interact with an SQL database using natural language, powered by Langchain and Groq.

## 🔍 Concept

This project bridges the gap between SQL databases and non-technical users by enabling natural language queries to retrieve and analyze data from a database. It leverages:
- **Langchain**: A framework for building LLM-powered applications.
- **Groq**: A powerful LLM that interprets the user's intent.
- **Streamlit**: A lightweight frontend for interactive web applications.

The application connects to a SQLite database (`pr_report.db`) and uses Langchain agents to translate natural language inputs into SQL queries. The results are then returned to the user in real time.

## Screenshot of the Application
![image](https://github.com/user-attachments/assets/cc079d87-1bfb-4afe-8e5e-5ddbfc35309f)

## ⚙️ How to Use

1. **Install Requirements**:
    ```bash
    pip install -r requirements.txt
    ```

2. **Set Up Your Environment**:
    - Make sure your `.env` file contains the necessary Groq API key:
      ```env
      GROQ_API_KEY=your_groq_api_key_here
      ```

3. **Run the App**:
    ```bash
    streamlit run app.py
    ```

4. **Use It**:
    - Enter natural language questions about your database (like “List top 5 artists with the most albums”).
    - Get SQL-backed answers instantly.


---

Made with ❤️ using Langchain + Groq + Streamlit.
