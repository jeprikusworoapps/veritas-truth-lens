# Veritas: Truth Lens for Web

A privacy-first Chrome Extension that uses **on-device AI** (Gemini Nano via Chrome’s built-in AI APIs) to help users detect bias, logical fallacies, and misinformation — **100% offline, zero data sent to the cloud**.

> "The browser shouldn’t just show you the web — it should help you *think* about it."  

## 🔍 Features
- Real-time analysis of text for emotional manipulation & unsupported claims  
- Highlights logical fallacies (ad hominem, false dilemma, etc.)  
- Rewrites biased sentences neutrally using **Rewriter API**  
- Summarizes long articles with **Summarizer API**  
- Multimodal analysis: interprets images + captions together (**Prompt API**)  
- Cross-language framing comparison (**Translator API**)  

## 🛠️ Built With
- Chrome Built-in AI APIs:  
  `Prompt` (multimodal), `Summarizer`, `Writer`, `Rewriter`, `Proofreader`, `Translator`  
- JavaScript (ES2023)  
- Manifest V3  
- Web Workers (for smooth on-device AI processing)

## ▶️ How to Test
1. Clone this repo  
2. Open Chrome → go to `chrome://extensions`  
3. Enable **Developer mode** (top-right)  
4. Click **"Load unpacked"** → select the `/src` folder  
5. Visit any news/article page — Veritas works automatically!

> 🔒 All AI runs **on your device**. No internet? No problem. No tracking. Ever.

## 📜 License
MIT License — feel free to learn, fork, and build upon this!
