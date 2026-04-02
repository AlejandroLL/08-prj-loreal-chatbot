# Project 8: L'Oréal Chatbot

L’Oréal is exploring the power of AI, and your job is to showcase what's possible. Your task is to build a chatbot that helps users discover and understand L’Oréal’s extensive range of products—makeup, skincare, haircare, and fragrances—as well as provide personalized routines and recommendations.

## 🚀 Launch via GitHub Codespaces

1. In the GitHub repo, click the **Code** button and select **Open with Codespaces → New codespace**.
2. Once your codespace is ready, open the `index.html` file via the live preview.

## ☁️ Cloudflare Note

When deploying through Cloudflare, keep the OpenAI API key only in the Worker secret named `OPENAI_API_KEY`. The browser should call the Worker URL, send a `messages` array, and read `data.choices[0].message.content` from the response.

Do not load a local `secrets.js` file in the browser. That would expose the key to anyone who opens DevTools.

Enjoy building your L’Oréal beauty assistant! 💄
