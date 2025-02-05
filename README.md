# Streamlit LangChain Chatbot

##  Overview
This project is a chatbot built using **Streamlit** and **LangChain**, featuring AI-driven responses with memory management. The chatbot can assist users with coding-related queries, following predefined system instructions for concise and effective responses.

##  Features
-  **Conversational Memory**: Maintains chat history using `st.session_state`.
-  **AI-Powered Responses**: Uses LangChain’s `ChatOllama` model.
-  **DeepSeek R1 Model**: Utilizes the **DeepSeek R1** model from **Ollama** for generating AI responses.
-  **Dynamic Prompt Engineering**: Uses `SystemMessagePromptTemplate`, `HumanMessagePromptTemplate`, and `AIMessagePromptTemplate` for structured conversations.
-  **Interactive UI**: Built with **Streamlit** for a smooth and user-friendly experience.

##  Project Structure
```
/streamlit-langchain-chatbot
│── app.py                # Main Streamlit app
│── requirements.txt      # Dependencies
│── .gitignore            # Files to ignore in Git
│── README.md             # Project documentation
└── .streamlit/
    └── config.toml       # Streamlit configuration (if needed)
```

##  Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/YOUR-USERNAME/streamlit-langchain-chatbot.git
   cd streamlit-langchain-chatbot
   ```
2. **Create a virtual environment:**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate     # On Windows
   ```
3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

##  Usage
Run the chatbot with:
```sh
streamlit run app.py
```

##  Configuration
Modify the system prompt inside `app.py`:
```python
system_prompt = SystemMessagePromptTemplate.from_template(
    "You are an expert AI coding assistant. Provide concise, correct solutions with debugging hints."
)
```

##  Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.

##  Contact
- **GitHub**: [Your Profile](https://github.com/YOUR-USERNAME)
- **LinkedIn**: [Your LinkedIn](https://linkedin.com/in/YOUR-LINKEDIN)
