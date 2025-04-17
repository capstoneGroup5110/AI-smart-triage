SmartTriage AI aims to enhance emergency response and healthcare efficiency through an AIpowered triage system that automates patient assessment and prioritization. 
Uploaded the datasets that will be used for the training purpose
---
# 🧠 AI Smart Triage System – Capstone Project

Welcome to the *AI Smart Triage System, a healthcare assistant powered by **GPT-4o* and a *Random Forest Classifier*, designed to assist in disease prediction, risk assessment, and patient triage using a clean and interactive Gradio interface.

---

## 📁 Project Structure

Main -> finalcode -> RC.ipynb and capstone_finalcode.ipynb
## 🚀 Features

- ✅ GPT-4o-based disease prediction (returns only one likely disease)
- ✅ Age-aware risk classification using GPT-4o (High, Medium, Low)
- ✅ Voice input (Whisper AI) to transcribe spoken symptoms
- ✅ Visual risk distribution graph (color-coded: Red=High, Blue=Medium, Green=Low)
- ✅ Patient management: mark as attended to remove from list
- ✅ Download patient data as normal CSV or encrypted CSV

---

## 💡 How to Use

### ✅ Run in Google Colab

1. Open the repository: [GitHub Repo](https://github.com/capstoneGroup5110/AI-smart-triage/)
2. Navigate to main/finalcode/
3. Open Capstone_finalcode.ipynb and run all cells step-by-step

### 📦 Install Required Libraries

```bash
!pip install gradio openai pandas matplotlib whisper cryptography
