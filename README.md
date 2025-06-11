# 📄 Smart Resume Analyser – AI-Powered Resume Insights 💡  
> An intelligent resume analyzer built with ❤️ using **Python, Streamlit, PDFMiner & PyResparser**

![GitHub Repo stars](https://img.shields.io/github/stars/Shristirajpoot/Resume_analyser?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/Shristirajpoot/Resume_analyser?color=brightgreen)
![Built with](https://img.shields.io/badge/Built%20with-Python%20%7C%20Streamlit%20%7C%20Machine%20Learning-blue)

---

## 🌟 Overview
**Smart Resume Analyser** is a powerful AI-based web app that analyzes resumes to extract key details and provides users with:
- 🎯 Resume scoring  
- 📚 Skill & course recommendations  
- 📹 Relevant YouTube videos  
- 💼 Career suggestions  
- 📝 Resume writing tips  

Live Demo: [📺 Watch on YouTube](https://www.youtube.com/watch?v=3oNHNVa-kWE)

---

## 🖼️ Screenshots

### 👤 User Interface
| Upload Resume | Analyzed Data |
|---------------|----------------|
| ![](./Screenshot%20(32).png) | ![](./Screenshot%20(33).png) |
| ![](./Screenshot%20(34).png) | ![](./Screenshot%20(35).png) |
| ![](./Screenshot%20(36).png) | ![](./Screenshot%20(37).png) |

### 🛠️ Admin Panel
| Dashboard | Resume Review |
|-----------|----------------|
| ![](./Screenshot%20(38).png) | ![](./Screenshot%20(39).png) |

| Website |
|------------------|
| ![Screenshot11](./Screenshot%20(31).png) |

---

## 🚀 Features
- 🔐 User/Admin login system  
- 🧾 Resume parsing using NLP  
- 🧠 Career & course recommendations  
- 🧪 Resume scoring based on skills and experience  
- 📺 Suggested learning resources (YouTube, etc.)  
- ✍️ Resume improvement tips  
- 📊 Admin dashboard to review uploads  

---

## 🗂️ Project Structure
```plaintext
Resume_analyser/
├── main.py                 # Streamlit web app entry point
├── Courses.py              # Contains course & video data
├── requirements.txt        # Python dependencies
├── Uploaded_Resumes/       # Folder for user-uploaded resumes
├── Classifier.py           # KNN classifier logic
├── procfile, setup.sh      # Heroku deployment files
├── SRA_Logo.jpg            # App logo
├── *.png                   # UI screenshots
└── README.md               # You're reading it!
```
## ⚙️ Getting Started

### 📥 Clone the repository
```bash
git clone https://github.com/Shristirajpoot/Resume_analyser.git
cd Resume_analyser
```
### 🧪 Install dependencies
```bash

pip install -r requirements.txt
```
### ▶️ Run the app
```bash

streamlit run main.py
```
Admin login credentials:
```makefile

Username: naman_jain
Password: naman@123
```
Make sure XAMPP or any local server is running (Apache + SQL).

## 📦 Built With
- 🐍 Python 3

- 🖥️ Streamlit – web interface

- 📄 PDFMiner – extract text from resumes

- 🤖 PyResparser – NLP resume parser

- 📊 Scikit-learn – KNN-based predictions

- 💡 Custom logic for recommendations

## 👩‍💻 Author
### Shristi Rajpoot
- 📧 shristirajpoot369@gmail.com
- 🔗 GitHub @Shristirajpoot

## 📄 License
This project is licensed under the MIT License — feel free to use, modify & share with attribution.

### 🌟 If you find Gestura helpful, please ⭐ star the repo and spread the



