# Text Summarizer

A simple **web-based text summarization tool** built with [Bootstrap](https://getbootstrap.com/) for styling and [Transformers.js](https://github.com/xenova/transformers.js) for natural language processing.  
It uses the `Xenova/distilbart-cnn-6-6` model to generate concise summaries of long text directly in the browser — no backend required.

---
## Images
<img width="1870" height="1005" alt="Screenshot_30-4-2026_192435_127 0 0 1" src="https://github.com/user-attachments/assets/72dcf44f-900a-4c73-a912-271500c25a59" />
<img width="1851" height="975" alt="Screenshot_30-4-2026_191846_127 0 0 1" src="https://github.com/user-attachments/assets/3b247d8f-5db9-4883-a484-47f3f1eeb813" />

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

