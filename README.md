# AIssistant, Local LLM Chatbot App for Mobile Devices

A privacy-first, offline-capable mobile application powered by local Large Language Models (LLMs) using [`llama.rn`](https://github.com/PocketPal/llama.rn) and `llama.cpp`. Built with React Native, this app brings the power of AI assistants directly to your Android and iOS devices — no internet required.

## 🚀 Features

- 🧠 **Local AI Chat** – Chat with LLMs fully on-device with no data leaving your phone.
- 🔄 **RAG Support** – Retrieval Augmented Generation using your own knowledge bases.
- 🔒 **Offline First** – 100% offline chat once a model is downloaded.
- 📚 **Knowledge Base Management** – Import and embed content for contextual responses.
- 🎛️ **Model Settings** – Load different LLMs (GGUF format) and adjust system prompts.
- 🧪 **Performance Tracking** – Measure tokens per second (TPS), memory usage, and load time.
- 💾 **Chat History** – Persist your conversations locally (SQLite).
- 📂 **Multimodal UI** – A tabbed interface for navigating chats, models, knowledge, and more.

## 📸 Screenshots

[//]: # (TODO: Add screenshots to readme)
[//]: # (Screenshots of ChatScreen, DrawerNavigation, KnowledgeBase interface, etc.)

## 📦 Technologies Used

- **React Native** – Cross-platform mobile framework
- **llama.rn** – React Native bindings for `llama.cpp`
- **SQLite** – Local database for chat history and knowledge base
- **RNFS** – File system access
- **AsyncStorage** – Persisted settings and flags
- **DeviceInfo** – Memory usage metrics
- **Snackbar, Sliders, Switches** – Modern and intuitive UI

## 📂 GGUF Model Support

To chat offline, locate a huggingface repository of your preference in GGUF format `*.gguf` and download it throught the model settings screen.

- Use models like `Llama 3.2`, `Qwen`, `Phi`, `Gemma`, `TinyLlama`, etc.
- Download them from the **Model Settings** screen and load them with the on-screen selector.
- We recommend quantized versions depending on your hardware (`q8`, `q4_K_M`, `q5_0`) for better mobile performance. FP16 models are compatible but performance varies depending on model size and hardware.

## 💡 Usage Tips

- For best results, use smaller models (1–3B parameters).
- Test the results with different models to find the best performace and accuracy for your needs.
- Use RAG with indexed PDFs/texts to answer questions based on your data.
- Monitor RAM usage and context token settings to optimize for your device.

## ✅ Installation

App will soon be available on the Play Store!

### 📄 Acknowledgements

- `llama.rn`
- `llama.cpp`
- PocketPal

## 🔐 License

Copyright 2025 big-damian. All rights reserved.

This software and associated documentation files (the "Software") are the proprietary property of big-damian. No part of the Software may be copied, modified, distributed, sold, sublicensed, or used in any form or by any means without the prior written permission of the copyright holder.

Unauthorized use of the Software is strictly prohibited and may result in civil and criminal penalties. The use of this software is governed by a commercial license agreement.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
