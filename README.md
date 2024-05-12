## Gemini Chatbot | GDSC AJCE
---

### Description
This is a chatbot built using Gemini API. It is a simple chatbot that can answer some basic questions. It is built using Python and Streamlit.

### Prerequisites
1. Python ([Installation Guide](https://www.python.org/downloads/))
2. Streamlit ([Installation Guide](https://docs.streamlit.io/library/installation-installation))
3. Gemini API Key ([Get your API key from here](https://aistudio.google.com/app/apikey))

### Installation
1. Clone the repository
```bash
git clone https://github.com/zameel7/GeminiChatbot.git
```
2. Change the directory
```bash
cd GeminiChatbot
```
4. Create a `.env` file and add the following
```bash
GOOGLE_GEMINI_KEY=YOUR_API_KEY
```
(Replace `YOUR_API_KEY` with your Gemini API key.)
4. Create a virtual environment
```bash
python -m venv venv
```
5. Activate the virtual environment
(For Windows)
```bash
venv\Scripts\activate
```
(For Linux/Mac)
```bash
source venv/bin/activate
```
6. Install the required packages
```bash
pip install -r requirements.txt
```
7. Run the app
```bash 
streamlit run main.py
```