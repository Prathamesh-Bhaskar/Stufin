# Personalized Financial Advice Chatbot 💸

This project is a web-based financial advisor that provides personalized financial advice based on user inputs such as income, expenses, savings, investments, risk tolerance, and financial goals. It uses the `Streamlit` framework for the frontend, and `Hugging Face` models via `Langchain` for generating the financial analysis.

## Features
- Input fields for monthly income, expenses, savings, investments, and risk tolerance.
- Text area to specify financial goals and any questions.
- Personalized financial advice based on user data, considering options like Mutual Funds, Stocks, Real Estate, PPF, NPS, Sukanya Samriddhi Yojana, etc.

## Technologies Used
- **Streamlit**: For the user interface and interactive elements.
- **Langchain**: For managing the prompt and generating the output.
- **Hugging Face**: To provide text generation using the `Mixtral-8x7B-Instruct-v0.1` model.
- **Python**: Backend logic for data processing and integration.

## Prerequisites
- Python 3.7+
- Hugging Face API Token (Add it to a `.env` file as `HUGGINGFACEHUB_API_TOKEN`).

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/financial-advice-chatbot.git
    cd financial-advice-chatbot
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Add your Hugging Face API token to a `.env` file in the project root:
    ```
    HUGGINGFACEHUB_API_TOKEN=your_huggingface_api_token
    ```

## Running the App

To run the Streamlit app, use the following command:

```bash
streamlit run app.py
