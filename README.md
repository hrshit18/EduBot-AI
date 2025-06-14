# 🤖 EduBot AI – A Multimodal AI Assistant for Students & Educators

**Microsoft x Edunet Foundation Internship Project – June 2025**

**EduBot AI** is a smart, multimodal assistant built using Azure AI and Generative AI to support students and educators. It helps extract, summarize, translate, vocalize, and generate questions from educational content using AI services like Azure Vision, Language, and Speech APIs. The application is developed using Python and Streamlit.

---

## 🎯 Features

- 📤 **Image & Document Upload:** Extract text using OCR (Azure Vision).
- 🧠 **Summarization:** Condense long content using AI-powered summarizer.
- 🌐 **Translation:** Translate content into various languages using Azure Translator.
- 🔊 **Text-to-Speech:** Convert text into speech in multiple languages.
- ❓ **Question Generator:** Generate comprehension questions from academic text.
- 🎛️ **Clean UI:** Easy-to-use interface for all age groups, powered by Streamlit.

---

## 🧠 System Workflow

```mermaid
graph TD
    A[Start: Upload Image or Text] --> B[Extract Text via OCR (if image)]
    B --> C[Choose Operation: Summarize / Translate / TTS / Q&A]
    C --> D[Process with Azure AI Services]
    D --> E[Display Results in Interface]
    E --> F[Optional: Listen or Download Output]

git clone https://github.com/your-username/EduBot-AI.git
cd EduBot-AI

pip install -r requirements.txt

streamlit run app.py

EduBot-AI/
│
├── app.py                     # Main Streamlit app
├── requirements.txt           # List of Python dependencies
├── README.md                  # Project documentation
├── utils/
│   ├── ocr.py                 # OCR functionality using Azure Vision
│   ├── summarizer.py          # Text summarization module
│   ├── translator.py          # Language translation module
│   ├── tts.py                 # Text-to-Speech converter
│   └── qna.py                 # Question generation module
├── assets/                    # Static assets and sample images
└── .gitignore
🧩 Technologies Used
Microsoft Azure AI – Vision, Language, Speech, Translation

Python – Core programming language

Streamlit – For web UI

OpenAI / Hugging Face Transformers – (for optional model tuning)

OCR / NLP / TTS / Q&A – AI capabilities used

❗ Troubleshooting
Azure API Key Issues:

Ensure you have valid Azure keys set in environment variables or configuration.

Streamlit Not Starting:

Ensure your virtual environment is active and dependencies are installed.

Model or API Errors:

Double-check Azure region settings, endpoint URLs, and correct subscription level.

🤝 Contributing
You’re welcome to fork this repository and contribute!
Feel free to open issues or pull requests for improvements or new features.

📄 License
This project is licensed under the MIT License. See the LICENSE file for more information.

✨ Acknowledgment
This project was developed as part of the Generative AI Internship by Edunet Foundation in collaboration with Microsoft.
It reflects learnings from beginner to advanced modules in AI, vision, translation, and responsible AI practices.

📌 Author
Harshit Gupta
B.Tech Mechanical Engineering | Kamla Nehru Institute of Technology, Sultanpur
Email: harshitgupta.knit@gmail.com


---

### ✅ What to Do Now:

1. Open your GitHub repo.
2. Click the `README.md` file.
3. Click the ✏️ pencil icon to edit.
4. Paste the entire content above.
5. Scroll down and **Commit changes**.

Let me know if you want a **project banner**, **demo GIF**, or **custom badges** next!



