
# 💼 FinanceAI Analytics  
**AI-powered financial analyst assistant** that interprets uploaded reports and responds intelligently to user queries through a structured chat flow.

![image-2](https://github.com/user-attachments/assets/4a9a1330-5a67-42a8-b31e-132b2bfc8d0b)
![%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-04-04%20%D0%B2%203 27 58%E2%80%AFAM](https://github.com/user-attachments/assets/d435ddf4-796a-4529-b33e-e791cba262de)


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

![WhatsApp Image 2024-12-13 at 06 55 55 (1)](https://github.com/user-attachments/assets/314cd7bd-539c-415f-96b1-db15bdf7f0ea)
![WhatsApp Image 2024-12-13 at 06 56 28 (1)](https://github.com/user-attachments/assets/02b67940-2902-4bd8-bdcf-ef444ce4b1aa)

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
