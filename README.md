
# 💼 FinanceAI Analytics  
**AI-powered financial analyst assistant** that interprets uploaded reports and responds intelligently to user queries through a structured chat flow.

![FinanceAI UI](image.png)

---

## Overview  
**FinanceAI Analytics** is an intelligent assistant designed to help investors and analysts make sense of complex financial documents. It supports `.pdf`, `.csv`, and `.xlsx` formats, using document parsing and GPT-4o-powered workflows to produce modular, explainable insights such as profitability, risk, and valuation metrics.

---

## 🧩 Core Architecture

### 🔁 Flow-Based Logic

- ✅ **Document Extraction**: Parses financial reports for structured data.  
- ✅ **Proficiency Routing**: Users are routed differently based on financial knowledge (beginner or advanced).  
- ✅ **GPT-4o Region Bot**: Outputs insights tailored to different business regions and stakeholder concerns.  
- ✅ **Question Classifier**: Routes user questions to correct analysis modules:
  - Profitability Analysis  
  - DuPont Breakdown  
  - Cash Flow Interpretation  
  - Risk Metrics  
  - Custom Advice

<img src="file-STtev2LrxTyFa8dosanuGH" width="100%" alt="Region Reports Bot Logic"/>

<img src="file-BnXs7xc7W6Lb3S2xpCEW29" width="100%" alt="Question Classifier Bot Flow"/>

---

## ✨ Key Features

- 📁 Upload **PDF, Excel, or CSV** reports
- 🤖 Chat with a GPT-4o-powered **financial assistant**
- 🧠 Modular responses based on user expertise and document type
- 📊 Real-time **stock valuation**, **EPS**, **P/E**, **Beta**, and **regional strategy** suggestions
- 📌 Personalized conclusions for each stakeholder

---

## 🏗️ Tech Stack

| Layer      | Tools Used                   |
|------------|------------------------------|
| Backend    | Python, FastAPI              |
| AI/NLP     | OpenAI GPT-4o (via Flow)     |
| Frontend   | React.js                     |
| File Parsing | pandas, openpyxl, PyMuPDF  |
| Automation | Flow-based chatbot builder   |

---

## 📦 Getting Started

```bash
git clone https://github.com/yourusername/financeai-analytics.git
cd financeai-analytics
pip install -r requirements.txt
npm install && npm run dev
```

---

## 📊 Sample Use Cases

- Upload a **Q4 Excel Report** to ask “How is profitability trending this year?”
- Drop in an **Annual PDF Report** and ask for **stakeholder-oriented conclusions**
- Upload a **CSV Revenue Breakdown** and request a **DuPont Analysis**

---

## 🧭 Future Enhancements

- Dynamic file comparison across multiple years
- Sector benchmarks integration
- B2B dashboard and PDF report generator
