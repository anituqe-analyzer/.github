# <div align="center"><img src="images/logo.png" alt="Antique Analyzer Logo" width="300"/></div>

<div align="center">

# Antique Analyzer

**Platform for verifying the authenticity of antique auctions using Multimodal AI**

[About](#-about-the-project) • [Key Features](#-key-features) • [Architecture](#%EF%B8%8F-system-architecture) • [Tech Stack](#%EF%B8%8F-tech-stack) • [Repositories](#-repositories) • [Video](#-live-demo) • [Documentation](#-documentation) • [Team](#%E2%80%8D-meet-the-team)

</div>

---

## 🧐 About the Project

**Antique Analyzer** is a project created for the "Projekt zespołowy" (Team Project) course by a team of Computer Science Master's students at the **University of Information Technology and Management in Rzeszów (UITM)**.

The platform addresses the problem of counterfeit antiques in e-commerce. It combines **Artificial Intelligence** (multimodal analysis of images and text) with **Community Verification** (experts and users) to assess the authenticity of items listed on platforms like **Allegro, OLX, and eBay**.

## 🚀 Key Features

* **🔍 AI-Powered Verification:** Uses **EfficientNet-B0** (Vision) and **DistilBERT** (NLP) to analyze auction photos and descriptions, detecting potential scams or replicas.
* **🕷️ Automated Scraping:** Intelligent web scrapers (Selenium, Apify) automatically fetch auction data from URL links.
* **👥 Expert Crowdsourcing:** A dedicated panel for domain experts (Numismatics, Furniture, etc.) to validate AI results and provide professional opinions.
* **🗳️ Community Voting:** A democratic voting system where the community can agree or disagree with the verdict.
* **📊 Confidence Scoring:** The system provides an authenticity probability score (Original vs. Scam/Replica).

## ⚙️ System Architecture

The system operates on a microservices architecture:
1.  **Core Backend (Ruby on Rails):** Manages users, auth, database, auctions, and community interactions.
2.  **AI Service (Python/FastAPI):** Exposes endpoints for scraping and running the ML inference.
3.  **Frontend (React/TypeScript):** A modern, responsive web interface.

## 🛠️ Tech Stack

### **AI & Data Science**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)

### **Web Scraping**
![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Apify](https://img.shields.io/badge/Apify-97D700?style=for-the-badge&logo=apify&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-white?style=for-the-badge&logo=python&logoColor=black)

### **Core Backend**
![Ruby](https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/rails-%23CC0000.svg?style=for-the-badge&logo=rubyonrails&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

### **Frontend**
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)

### **DevOps & Tools**
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-yellow?style=for-the-badge)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## 📂 Repositories

Here are the open-source components of our platform:

| Component | Description | Tech |
| :--- | :--- | :--- |
| **[Analysis Model](https://github.com/anituqe-analyzer/analyse-model)** | Multimodal ML model & FastAPI service. | Python, PyTorch |
| **[Backend](https://github.com/anituqe-analyzer/backend)** | Core logic, database management, and user handling. | Ruby on Rails |
| **[Frontend](https://github.com/anituqe-analyzer/frontend)** | The user interface for analyzing auctions and voting. | React, TypeScript |
| **[Web Scraper](https://github.com/anituqe-analyzer/web-scraper)** | Tools for fetching training data and live auction info. | Python, Selenium, Apify |

## 🎥 Live Demo

Watch a short video demonstrating how the application works:
[Watch the video](https://youtu.be/NW1DT6g-2LU)


## 📄 Documentation

Complete project documentation (available in Polish):
[View the Full Project Documentation (PDF)](https://github.com/anituqe-analyzer/.github/blob/main/Projekt_zespo%C5%82owy_dokumentacja.pdf)

## 👨‍💻 Meet the Team

We are a team of Master's students passionate about AI and Data Science.

<table>
  <tr>
    <td align="center"><a href="https://github.com/KukielkaKamil"><img src="https://github.com/KukielkaKamil.png" width="100px;" alt=""/><br /><sub><b>Kamil Kukiełka</b></sub></a><br />Leader & Data Scientist</td>
    <td align="center"><a href="https://github.com/kantown"><img src="https://github.com/kantown.png" width="100px;" alt=""/><br /><sub><b>Bartosz Kawa</b></sub></a><br />Backend Developer</td>
    <td align="center"><a href="https://github.com/michalzychowski"><img src="https://github.com/michalzychowski.png" width="100px;" alt=""/><br /><sub><b>Michał Żychowski</b></sub></a><br />Data Engineer</td>
    <td align="center"><a href="https://github.com/kamilmichna"><img src="https://github.com/kamilmichna.png" width="100px;" alt=""/><br /><sub><b>Kamil Michna</b></sub></a><br />Frontend Developer</td>
  </tr>
</table>

---
<div align="center">
  <sub>Designed for <b>Projekt Zespołowy</b> at WSIiZ Rzeszów, 2025/2026.</sub>

</div>

