# Chatbot-with-DeepSeek-R1-Ollama-Streamlit
Local LLM App using DeepSeek-R1-Distill-Qwen-1.5B


This mini project demonstrates how to run the DeepSeek-R1-Distill-Qwen-1.5B model locally using Ollama and build an interactive web interface with Streamlit, integrating LangChain to enhance prompt handling and LLM interaction.


Features

🧠 Runs DeepSeek-R1-Distill-Qwen-1.5B model locally via ollama

🌐 Simple and interactive Streamlit web app

🛠️ Integrated with LangChain for prompt management and flexibility

🔒 Completely private & offline – no cloud API usage


Tech Stack

Ollama — to pull and run LLM models locally

Streamlit — for frontend UI

LangChain — to interact with the LLM

Python 3.9+ — base language



🛠️ Setup Instructions

1. Clone the Repository
   git clone https://github.com/surya-aiml20/Chatbot-with-DeepSeek-R1-Ollama-Streamlit.git
   cd Chatbot-with-DeepSeek-R1-Ollama-Streamlit

2. Install Dependencies
   pip install -r requirements.txt

3. Pull the Model using Ollama
   Make sure Ollama is installed and running.

   ollama pull deepseek-r1:1.5b

4. Run the Model Locally
   ollama run deepseek-r1:1.5b

5. Run the Streamlit App
   streamlit run app.py


🧩 Sample Usage

Start Ollama and ensure the DeepSeek model is loaded.

Launch the app with Streamlit.

Enter your query in the Streamlit interface.

Get answers powered by DeepSeek-R1 running locally.


🔐 Privacy Focus

This project uses a local LLM – no data is sent to external servers. Everything runs on your machine, ensuring complete privacy and control.

📄 License

This project is for educational and experimental purposes.




