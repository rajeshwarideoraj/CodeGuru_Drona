# Drona: AI-Guided Learning Companion for CS1 Coding Assignments

**Drona** is a guided problem-solving application designed to enhance learning in introductory computer science courses (CS1) by offering context-aware coding support through generative AI. Built using Python, Streamlit, Django, and OpenAI APIs, Drona provides students with hint-based guidance while preserving cognitive engagement and learning integrity.

---

## 🚀 Project Overview

This tool was part of an academic research study exploring the role of generative AI in CS education. The application integrates:
- 🧠 **Retrieval-Augmented Generation (RAG)** with OpenAI + LangChain
- 🧑‍💻 **Interactive coding environment** with instructions, code editor, and real-time feedback
- 💬 **Hint-based chatbot** that avoids giving direct answers

---

## 🛠️ Tech Stack

- **Python 3.11**
- **Streamlit** – Frontend for interactive labs
- **Django** – Backend support
- **LangChain + OpenAI API** – Generative AI hint system
- **FAISS** – Semantic document search for RAG
- **GitHub** – Version control
- **PyCharm** – IDE

---

## 🧪 Research Context

This repository supports an IRB-approved study evaluating the following research questions:

1. **Learning Outcomes:** Does Drona help students develop critical thinking in CS1?
2. **Engagement Patterns:** Are students using the tool for meaningful guidance or shortcutting?
3. **AI Integration:** What are the benefits and limitations of AI-supported coding?
4. **User Experience:** How does Drona affect engagement and satisfaction?

**Participants:** 20 undergraduate and graduate students  
**Methodology:** Mixed-methods including interaction logs, surveys, and observations  
**Interface:** Code editor, hint chatbot, instruction panel, run/save buttons

---

## 📊 Results Snapshot

- Average rating for "usefulness of hints": **4.32 / 5**
- Participants reported increased **confidence**, **engagement**, and **skill development**
- Most users stated they would recommend Drona to peers

---

## 📦 Installation

```bash
git clone https://github.com/your-username/drona-ai-lab.git
cd drona-ai-lab
pip install -r requirements.txt
streamlit run Welcome.py
Make sure your OpenAI API key is set in an .env file or provided securely into the runtime environment.
