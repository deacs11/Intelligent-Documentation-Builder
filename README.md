
# 🧠 Intelligent Documentation Generator (AutoGen)

Multi-agent system that generates intelligent documentation for Python code using AutoGen, GPT-4, and PDF export.

This project is an intelligent multi-agent system that collaboratively generates professional documentation from Python code using [AutoGen](https://github.com/microsoft/autogen) and GPT-4.

## 🚀 What It Does

Given a Python script, the system launches a multi-agent discussion to analyze and improve documentation quality across multiple dimensions:
- 📚 *TechnicalWriter*: creates clear and precise documentation
- 🪶 *LanguageEditor*: corrects grammar and style
- 🔍 *LogicChecker*: ensures logical consistency
- 🧩 *SemanticReviewer*: checks terminology and vocabulary
- 🎓 *FormalityAdjuster*: adapts tone and formality to the intended audience

The conversation is then summarized and exported as a **PDF report**, containing:
- 🗨️ Full transcript of the agent debate
- 🧾 A professional summary

## 🛠️ Technologies Used

- Python 3.11+
- [AutoGen](https://github.com/microsoft/autogen)
- OpenAI GPT-4 API
- Google Colab + Colab Secrets
- `fpdf2` for PDF export
