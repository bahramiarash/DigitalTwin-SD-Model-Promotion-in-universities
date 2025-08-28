# 🎓 Promotion SD Digital Twin

A **System Dynamics–based digital twin** built with **Vensim + PySD + FastAPI + Dashboard** for simulating promotion evaluation in academic settings.  
The model supports scenario analysis, research/education scoring, and policy simulations with an interactive API and web dashboard.

---

## 🚀 Features

- 📦 **System Dynamics model** (`.mdl` from Vensim PLW 10.3.2)
- 🔗 **PySD integration** for running the model in Python
- ⚡ **FastAPI backend** with REST API
- 📊 **Interactive Dashboard** with input controls & result visualization (tables + charts)
- 🎲 Support for **randomized input parameters** around user-specified values
- 🌐 Deployable on **local machine or server** (Uvicorn / IIS / Nginx)

---

## 📂 Project Structure

.
├── app/

│ ├── app.py # FastAPI backend

│ ├── models/

│ │ └── my_model.mdl # Vensim model

│ └── static/

│ └── index.html # Dashboard UI

├── requirements.txt

└── README.md
