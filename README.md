# Gemini CLI - Image Description Project

This project demonstrates how to analyze and describe images using **Google's Gemini CLI**.

## 📌 Overview
The goal of this project is to:
- Understand how Gemini CLI handles image input
- Run direct image analysis using `gemini describe`
- Build a clean, small-scale AI project structure
- Practice file-based LLM interactions safely and efficiently

---

## 📂 Project Structure

gemini-image-project/
│
├── assets/
│     └── myimage.jpg          # Image used for analysis
│
└── README.md

---

## 🚀 How to Run the Project

### 1. Install Gemini CLI
1. Install Node.js (Required Version)

Gemini CLI ko chalne ke liye Node.js v20+ ki zaroorat hoti hai.

👉 Download Node.js (LTS version):
https://nodejs.org/

Verify installation:

node -v

2. Install Gemini CLI Globally

Gemini CLI ko install karne ke liye npm command:

npm install -g @google/gemini-cli


npm → Node Package Manager

-g → Global installation (kahin se bhi command run ho sakti hai)

Installation check karne ke liye:

gemini -v


Agar version show ho jaye → installation successful! 🎉

🧠 Gemini CLI Basic Commands
1. Start Gemini CLI
gemini


Ye CLI shell start karta hai jahan tum normal AI assistant ki tarah prompts type kar sakte ho.

2. Specific model select karna
gemini --model gemini-2.5-flash


gemini-2.5-flash → fast, latest, low-latency model

Aap kisi bhi model ka naam yahan use kar sakti ho

Ye command ensures karta hai ke aapka request specific model se run ho

# gemini_cli_project
Gemini CLI Image Description Project This project demonstrates how to analyze images using Google's Gemini CLI. This project is ideal for anyone learning: ✔ Gemini CLI basics ✔ File-based AI interaction ✔ Prompt engineering ✔ LLM-powered image understanding
