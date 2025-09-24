# Emotion-Aware Chatbot (Gradio)

An intelligent chatbot that detects **user emotions**, keeps **multi-turn context**, and provides a clean **Gradio interface** with streaming responses.  
Built with [BlenderBot 400M Distill](https://huggingface.co/facebook/blenderbot-400M-distill) for natural conversation and [GoEmotions](https://huggingface.co/SamLowe/roberta-base-go_emotions) for fine-grained emotion classification.

---

## ✨ Features

- 🤖 **Conversational AI** – Human-like replies powered by BlenderBot 400M  
- 🎭 **Emotion Detection** – Shows emotion badges based on GoEmotions classification  
- 🧠 **Context Memory** – Remembers the last 3 exchanges for more coherent dialogue  
- 🛡 **Safety Guardrails** – Detects profanity and potential self-harm content  
- ⚡ **Streaming Responses** – Token-by-token generation for a smooth experience  
- 📝 **Conversation Logging** – Saves chat history to `logs/conversations.jsonl` with timestamps & session IDs  
- 🎚 **Decoding Controls** – Tune temperature, top-p, beams, penalties, etc. in the UI  
- 📤 **Export Conversations** – Save chats as `.json` or `.txt`  
- 🖥 **Clean UX** – Minimal interface, disclaimers, and polished look  

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
pip install -r requirements.txt
