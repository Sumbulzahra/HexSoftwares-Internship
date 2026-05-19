# AI Chatbot Development

Brief description of project placeholder. ---

## Features

- Advanced NLP Capabilities: Utilizes gemini-2.5-flash to process, understand, and reply to user inputs intelligently.
- Modern UI/UX: Built with Streamlit's native chat components (st.chat_message and st.chat_input) for an elegant dashboard look.
- Session State Management: Dynamically maintains the chat history during the current active session.
- Robust Error Handling: Designed with try-except safety blocks to ensure uninterrupted user conversations.

---

## Tech Stack

The core technologies driving this application include:

- Language: Python 3.9+
- Frontend Framework: Streamlit (Web-based Interface)
- AI Engine & NLP: Google Generative AI SDK (gemini-2.5-flash)

---

## Installation & Setup Guide

Follow these steps to configure and run the chatbot on your local environment or system:

## 1. Clone the Repository
bash
git clone [https://github.com/Sumbulzahra/HexSoftwares-Internship]
cd HexSoftwares_AI_Chatbot

---

##2. Install Dependencies
Install the required packages using pip:
bash
pip install streamlit google-generativeai

---

##3. Configure the API Key
Open the app.py script and replace the placeholder with your actual Gemini API Key inside the configuration block:

Python
genai.configure(api_key="YOUR_ACTUAL_API_KEY")

---

##4. Run the Application
Launch the Streamlit web server from your terminal:

bash
streamlit run app.py

---

##How to Use
Once the application starts, it will automatically open a tab in your default web browser at http://localhost:8501.

Type any prompt, technical question, or customer support query into the chat input bar at the bottom.

The virtual agent will instantly process the natural language context and stream back an intuitive, human-like response.

---

##Project Scope & Guidelines Alignment
Virtual Agent: Successfully handles custom user prompts and simulates customer support workflows flawlessly.

NLP Integration: Seamlessly processes text understanding via Google's Gemini infrastructure.

Web-Based Accessibility: Built on top of Streamlit, making the application fully responsive and ready for cloud web hosting.

---

##Connect with Me
Developed with dedication for the Hex Softwares Internship Tasks. Feel free to check out my profiles to follow my journey!


LinkedIn: Your LinkedIn Profile

