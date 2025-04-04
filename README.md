# Mental Health Chatbot for Pakistan

A compassionate, culturally sensitive mental health support chatbot designed specifically for users in Pakistan. This chatbot provides emotional support, active listening, and calming strategies while maintaining ethical boundaries and cultural sensitivity.


## 📋 Overview

This chatbot is designed to provide accessible mental health support to Pakistani users through:
- Emotional support and active listening
- Culturally appropriate guidance and coping strategies
- Multi-language support (English, Roman Urdu, and Urdu)
- Crisis resource recommendations when necessary

The project leverages Google's Gemini model through LangChain to create a conversational AI that respects Islamic and cultural values while providing mental health assistance.

## ✨ Features

- **Multi-language Support**: Communicates in English, Roman Urdu, and Urdu
- **Culturally Sensitive Responses**: Respects local norms and religious values
- **Crisis Management Support**: Provides emergency contact information for mental health resources in Pakistan
- **Coping Strategies**: Suggests relaxation techniques, grounding exercises, and healthy activities
- **Conversation Memory**: Maintains context through conversation history
- **User-friendly Interface**: Simple Gradio web interface for easy interaction

## 🚀 Quick Start

### Prerequisites
- Python 3.x
- Google API key for Gemini

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/mental-health-chatbot.git
cd mental-health-chatbot
```

2. Install required packages:
```bash
pip install langchain-google-genai langchain langchain-core langchain-community gradio
```

3. Set up your Google API key:
```python
import os
os.environ["GOOGLE_API_KEY"] = "your_google_api_key_here"
```

4. Run the application:
```bash
python app.py
# Or run the notebook in a Jupyter environment
```

## 💻 Usage

After starting the application, a Gradio interface will launch where you can:
1. Enter your message in the text box
2. Click "Submit" to get a response
3. Use "Clear" to reset the conversation
4. Say "exit" or "bye" to end the conversation

## 🛠️ Technical Details

The chatbot is built with:
- **LangChain**: For building the conversational chain and memory management
- **Google Gemini 2.0 Flash**: The underlying AI model
- **ConversationBufferMemory & ConversationBufferWindowMemory**: For maintaining conversation context
- **Gradio**: For creating a simple web interface

## 🤔 Core Guidelines

The chatbot follows these key principles:
- **Confidentiality & Privacy**: Does not store or share user data
- **Cultural & Religious Sensitivity**: Respects Islamic and cultural values
- **Crisis Management**: Redirects to professional help in emergencies
- **Non-judgmental Support**: Uses supportive and encouraging language
- **Professional Help Referral**: Encourages seeking professional help when needed

## 🔗 Mental Health Resources in Pakistan

If you or someone you know needs immediate professional support:
- **Umang Pakistan:** 0333-3412147
- **Rozan Helpline:** 0800-22444
- **Taskeen Mental Health Support:** +92 301 8483141

