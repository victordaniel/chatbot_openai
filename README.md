# chatbot_openai
# Echo Bot

Welcome to the **Echo Bot**! This simple Streamlit application acts as a chatbot that echoes back whatever you input. It’s a straightforward demonstration of Streamlit's chat message features and session state management.

## Features

- **Chat Interface**: The app provides a simple chat interface where users can input text and see responses in a chat-like format.
- **Session State Management**: The bot maintains a history of the conversation, so messages persist across app reruns.

## How It Works

1. **Initialize Chat History**: 
    - The app checks if a session state variable `messages` exists. If it doesn’t, it initializes it as an empty list to store chat history.
  
2. **Display Chat Messages**:
    - On every rerun, the app iterates over the `messages` list and displays each message in the chat format according to the sender's role (either "user" or "assistant").

3. **Handle User Input**:
    - The app provides an input box where users can type their messages.
    - Once a message is entered, it is displayed in the chat and added to the chat history.
    - The bot then generates a response by simply echoing back the user's input prefixed with "Echo:".
    - The bot’s response is also displayed and added to the chat history.

## Installation

To run this application, you need to have Python installed along with the `streamlit` package. You can install Streamlit using pip:


pip install streamlit



## Usage

### Clone the repository:


git clone https://github.com/your-username/echo-bot.git


### Navigate to the project directory:


cd echo-bot



### Run the Streamlit app:


streamlit run echo_bot.py




