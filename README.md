# An AI Code Reviewer 🚀 

## 📌 Overview
This is a Python-based application built using **Streamlit** and **Google Gemini AI** to analyze and review Python code. The application detects potential bugs, logical errors, and areas for improvement, providing suggestions and fixes.

## ✨ Features
- 🤖 **AI-Powered Code Review:** Utilizes Google's **Gemini 1.5 Pro** model for advanced Python code analysis.
- 🐞 **Bug Detection & Fixes:** Identifies issues in the submitted code and provides corrected versions.
- 📚 **Explanations:** Offers clear explanations for detected errors and suggested fixes.
- 🎨 **User-Friendly Interface:** Simple and intuitive UI using **Streamlit**.

## ⚙️ Installation
### 🔹 Prerequisites
Ensure you have **Python 3.7+** installed on your system.

### 🔹 Install Dependencies
Run the following command to install the required packages:
```bash
pip install -r requirements.txt
```

## 🚀 Usage
1. 📥 Clone the repository or copy the script to your local machine.
2. ▶️ Run the Streamlit application:
   ```bash
   python -m streamlit run app.py
   ```
3. ✍️ Enter your Python code in the text area and click the **Review** button.
4. ✅ The AI will analyze the code and provide:
   - 🔎 **Bug Report**
   - 🛠 **Fixed Code**
   - 📖 **Explanations**

## 🔧 Configuration
Replace your **Google Gemini API key** in the script:
```python
ai.configure(api_key = "YOUR_API_KEY")
```

## 📁 Project Structure
```
/ai_code_reviewer
│── app.py               # Main Streamlit app script
│── README.md            # Documentation
└── requirements.txt      # List of dependencies
```

## 🤝 Contributing
Feel free to fork this repository and enhance the functionality!

## 📜 License
This project is licensed under the **MIT License**.

## 📩 Contact
For any questions or feedback, reach out at [your-email@example.com].

