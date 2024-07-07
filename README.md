# 🦙💬 Llama 2 Chatbot

Llama 2 Chatbot is an interactive and customizable chatbot application, leveraging the Llama-2-7B-Chat-GGML model. Built using Streamlit and the `ctransformers` library, this project allows users to interact with a state-of-the-art language model.

## Features

- **Model Integration:** Uses the Llama-2-7B-Chat-GGML model from Hugging Face.
- **Customizable Parameters:** Adjust temperature and top_p for fine-tuning responses.
- **Chat History:** View and clear chat history.
- **Secure Model Loading:** Load models securely with caching.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/llama2-chatbot.git
   cd llama2-chatbot
   ```
2 . Install the required packages:
```bash
pip install -r requirements.txt
```
3. Ensure you have the necessary authentication for Hugging Face models.

## Usage
1. Run the Streamlit app:

```bash
streamlit run app.py
```
2. Open your web browser and navigate to the provided local URL.

3. Interact with the chatbot by entering your prompt in the chat input.
