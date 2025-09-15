# Groq Assignment

This repository contains my submission for the **Conversation Management & Classification using Groq API** assignment.

---

## 📌 Tasks

### Task 1: Conversation Management with Summarization
- Maintains conversation history (user ↔ assistant).
- Supports truncation by:
  - Last N messages
  - Character/word length
- Performs **summarization after every k-th run** (demonstrated with k=3).
- Tested with multiple conversation samples.

### Task 2: JSON Schema Classification & Information Extraction
- Defines a JSON schema to extract:
  - Name
  - Email
  - Phone
  - Location
  - Age
- Implements extraction using **Groq API** (OpenAI-compatible SDK).
- Validates outputs with multiple test samples.

---

## ⚙️ Requirements

- Python 3.8+
- `openai` (Groq-compatible client)
- Google Colab (recommended for execution)

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Bhargav200/Grok-Assignment-.git
   cd Grok-Assignment-
   ```

2. **Open the notebook:**
   - Launch [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
   - Upload or open `grok_assignment.ipynb`.

3. **Install dependencies:**
   - Run the following in a notebook cell:
     ```python
     !pip install openai
     ```

4. **Configure API access:**
   - Add your Groq API key where required in the notebook.

5. **Run the notebook:**
   - Execute cells in order and follow instructions in the notebook.

---

## 📁 Repository Contents

- `grok_assignment.ipynb` — Main notebook containing all code and explanations.

---

## 📝 License

This repository is intended for educational use and assignment submission. Please contact the owner for reuse or licensing requests.

---

## 🙋‍♂️ Questions?

Feel free to open an issue or reach out to the repository owner for help or clarification.
