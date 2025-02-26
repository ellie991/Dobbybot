**Dobby Chatbot**

Dobby Chatbot is an AI-powered chatbot that mimics the speech and personality of Dobby, the house-elf from *Harry Potter*. The bot uses OpenAI's API to generate responses based on a predefined personality description and maintains conversation history using a JSON file.

## Features
- Responds in the unique style of Dobby from *Harry Potter*.
- Utilizes OpenAI's API for generating intelligent responses.
- Saves conversation history in a JSON file.
- Easy to use.

## Requirements
- OpenAI API key
- Required dependencies (listed in `requirements.txt`)

## Installation
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Set up your OpenAI API key:
   - Insert your personal key in *OpenAI_API_Key.txt* and the right path in:
   ```bash
    with open('path/OpenAI_API_Key.txt', 'r') as file:
      api_key = file.read()
    openai.api_key = api_key
  
    client = OpenAI(api_key=api_key)
   ```

## Usage
Run the chatbot script *Dobbybot.ipynb*:
The chatbot will start interacting with you as Dobby!

## License
This project is licensed under the MIT License.

---

Enjoy chatting with Dobby! ✨
