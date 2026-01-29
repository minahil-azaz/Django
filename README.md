# 📝 TextUtils – Django Text Analyzer

TextUtils is a simple and user-friendly Django web application that allows users to analyze and transform text efficiently. It provides multiple text-processing utilities through an intuitive Bootstrap-based UI.

---

## 🚀 Features

- ✅ Remove punctuation from text  
- 🔠 Convert text to UPPERCASE  
- 🧹 Remove extra spaces  
- 📄 Remove new line characters  
- 🔢 Count characters (optional & conditional)  
- 🎨 Clean and responsive UI using Bootstrap 5  
- 🔐 CSRF-protected Django forms  

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, Bootstrap 5
- **Template Engine:** Django Templates
- **Styling:** Bootstrap CDN

---

## 📂 Project Structure

textutils/
│
├── textutils/ # Project settings
├── analyzer/ # Main app
│ ├── views.py # Text processing logic
│ ├── urls.py
│ └── templates/
│ ├── index.html
│ └── analyze.html
│
├── manage.py
└── README.md
