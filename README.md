# Text Summarizer

A simple **web-based text summarization tool** built with [Bootstrap](https://getbootstrap.com/) for styling and [Transformers.js](https://github.com/xenova/transformers.js) for natural language processing.  
It uses the `Xenova/distilbart-cnn-6-6` model to generate concise summaries of long text directly in the browser — no backend required.

---

## 🚀 Features
- Paste any text into the input box and get a summarized version.
- Runs entirely client-side using WebAssembly/WebGPU.
- **Bootstrap-powered UI** for responsive layout and clean design.
- Gradient-styled button for a modern look.

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/text-summarizer.git
cd text-summarizer
npm install @xenova/transformers

