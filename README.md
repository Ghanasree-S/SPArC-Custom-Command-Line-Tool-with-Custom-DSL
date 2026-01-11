# SPARC – Custom Command-Line Tool with Custom DSL

SPARC is a Python-based command-line and GUI system that implements a **custom Domain-Specific Language (DSL)** for executing structured commands. The project demonstrates core concepts of **Formal Languages and Automata**, combined with **NLP-assisted command processing** and a **PyQt-based GUI**.
<img width="2878" height="1700" alt="Screenshot 2026-01-11 231429" src="https://github.com/user-attachments/assets/a0787a09-0d54-4946-ab81-afcc3bffef69" />

---

## 📌 Overview
SPARC allows users to interact with a system using high-level, structured DSL commands instead of traditional rigid command-line syntax. It includes a complete interpreter pipeline and optional NLP-based command translation.

---

## 🧠 Problem Statement
Traditional command-line interfaces require users to memorize strict syntax, which can be error-prone and unfriendly. There is a need for a structured yet flexible interface that simplifies command execution while preserving correctness.

---

## 🚀 Solution
SPARC introduces:
- A **custom DSL** for structured command execution
- A **lexer–parser–interpreter pipeline**
- An **NLP processing layer** for flexible command interpretation
- A **GUI interface** for improved usability

---

## 🛠️ Tech Stack
- **Language:** Python
- **Concepts:** Formal Languages & Automata, Interpreter Design
- **NLP:** Rule-based / lightweight NLP processing
- **GUI:** PyQt5
- **Database:** SQLite

---

## ✨ Features
- Custom Domain-Specific Language (DSL)
- Lexer, Parser, and Interpreter pipeline
- NLP-assisted command translation
- Command-line execution
- PyQt5-based graphical user interface
- Local database support for persistence

---

## ⚙️ How to Run the Project

### 🔹 1. Clone the Repository
```bash
git clone https://github.com/Ghanasree-S/SPArC-Custom-Command-Line-Tool-with-Custom-DSL.git
cd SPArC-Custom-Command-Line-Tool-with-Custom-DSL
```

### 🔹 2. Create and Activate Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate
```

### 🔹 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔹 4. Run SPARC (Command-Line Mode)
```bash
python main_enhanced.py
```

### 🔹 5. Run SPARC (GUI Mode)
```bash
python ui_enhanced.py
```

## 🧪 Example DSL Commands

create file report.txt

delete folder temp

calculate performance score

## 📚 Concepts Demonstrated
- Lexical Analysis
- Syntax Parsing
- Abstract Syntax Trees
- Interpreter Design
- Domain-Specific Language Design
- NLP-assisted command processing

## 📌 Future Enhancements
- Advanced NLP using transformer-based models
- Improved error handling and recovery
- Cross-platform command execution
- Cloud-based command logging and analytics
