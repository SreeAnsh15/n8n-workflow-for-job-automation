# n8n Job Automation Workflow (AI-Based Internship Monitor)

## 🚀 Overview
This project automates internship discovery using n8n, AI, and web scraping.

It scrapes internship listings from LinkedIn, processes the data, evaluates each role using AI, and sends alerts via Telegram.

---

## 💡 Problem Solved
Finding relevant internships manually is time-consuming and inefficient.  
This system automates discovery, filtering, and evaluation using AI.

## ⚙️ Features
- Scrapes internships from LinkedIn
- Extracts title, company, location, and link
- Cleans and formats job data
- Uses Google Gemini AI to analyze internships
- Assigns AI score and category
- Filters duplicate entries
- Stores data in Google Sheets
- Sends Telegram alerts for high-quality roles
- Runs using Docker

---

## 🛠 Tech Stack
- n8n
- JavaScript
- Google Gemini API
- Google Sheets API
- Telegram Bot API
- Docker
- PowerShell

---

## 📂 Files
- workflow.json → n8n workflow
- scripts/ → custom logic
- screenshots/ → proof of working system

---

## 📌 How to Use
1. Import `workflow.json` into n8n
2. Add credentials (Google Sheets, Telegram, Gemini)
3. Run the workflow

---

## 📸 Demo
(Add screenshots here)

---

## 🧠 Notes
- Includes duplicate filtering logic
- Uses AI scoring to rank internships

## 📸 Demo

### Workflow
![Workflow]("C:\Users\SreeAnsh\Documents\My Stuff (made by ansh)\Projects\n8n-job-automation\Screenshots\Screenshot 2026-03-24 224113.png")

### Output (Google Sheets)
![Sheets]("C:\Users\SreeAnsh\Documents\My Stuff (made by ansh)\Projects\n8n-job-automation\Screenshots\Screenshot 2026-03-24 224312.png")