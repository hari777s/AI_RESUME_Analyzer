# 🧠 AI Resume Analyzer

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

A web-based AI-powered tool that uses Natural Language Processing (NLP) to **analyze resumes**, extract key information, **predict job roles**, **score resume quality**, and provide **recommendations** for skills, courses, and improvements. Designed for both **applicants** and **recruiters**, with an **admin dashboard** for managing analytics and feedback.

---

## 🚀 Demo

> _Upload your resume → Get tips, predictions, scores, and more!_
> *(Add screenshot or demo link here if available)*

---

## 🔧 Tech Stack

| Layer       | Technologies                               |
|-------------|--------------------------------------------|
| Frontend    | Streamlit, HTML5, CSS3, JavaScript         |
| Backend     | Python, NLP (custom logic), PDFMiner       |
| Database    | MySQL                                      |
| Visualization | Plotly, Pandas                          |

---

## ✨ Features

- 📄 **Resume Parsing**: Extracts name, email, experience, education, and skills from PDFs  
- 🔍 **Job Role Prediction**: Suggests relevant roles based on skillset  
- 🧠 **Skill Recommendations**: Highlights missing or in-demand skills  
- 📊 **Resume Scoring**: Scores resumes and suggests improvements  
- 📈 **Admin Dashboard**: View user analytics, ratings, feedback  
- 📥 **CSV Export**: Download structured resume data  
- 💬 **User Feedback**: Collect and analyze user reviews

---

## 📊 Project Metrics

- ✅ 100+ resumes parsed
- ⚡ < 3 seconds average parsing time
- 🎯 ~85% prediction accuracy
- 📈 6+ interactive analytics charts
- 💬 30+ user feedback entries

---

## 🛠️ Setup Instructions

### Create a virtual environment & activate it

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Install required packages

```bash
pip install -r requirements.txt
```

### Run the app

```bash
streamlit run app.py
```

---

## 📁 Folder Structure

```
📦AI-Resume-Analyzer
 ┣ 📁static
 ┣ 📁utils
 ┣ 📄app.py
 ┣ 📄requirements.txt
 ┣ 📄Courses.py
 ┣ 📄README.md
```

---

## 📌 To Do / Future Scope

- Add support for DOCX resumes  
- Improve experience level prediction using ML  
- Resume ranking for job-specific roles  
- Integrate with real-time job APIs  

---

## 🧑‍💻 Author

- **Deepak Bhabagrahi Padhi** – [LinkedIn](https://linkedin.com/in/your-link)
- Guided by **Dr. Sampada Margaj**
- Kirti M. Doongursee College of Arts, Science & Commerce

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

- [Streamlit Docs](https://docs.streamlit.io/)  
- Udemy Data Science Bootcamp  
- IJITEE & Academia NLP research  
- Resume parsing blogs and [RChilli](https://www.rchilli.com/blog/resume-parsing-101/) NLP guide
