# 🛠️ FixIt.ai - AI-Powered Hyperlocal Service Marketplace


## 📖 Table of Contents
- [Problem Statement](#-problem-statement)
- [The Solution](#-the-solution)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Installation & Setup](#-installation--setup)
- [Usage Guide](#-usage-guide)
- [Project Structure](#-project-structure)
- [Future Scope](#-future-scope)

---

## 🚩 Problem Statement
Finding reliable local service professionals is currently fragmented and inefficient.
* **Diagnosis Difficulty:** Customers struggle to explain technical issues (e.g., "Is this a pipe leak or waterproofing?").
* **Trust Deficit:** Lack of transparent pricing and verified reviews.
* **Privacy Concerns:** Sharing personal phone numbers often leads to spam.

## 💡 The Solution
**FixIt.ai** bridges the gap using Generative AI. Instead of just listing numbers, we allow users to upload a video of their issue. Our AI analyzes the visual data, diagnoses the problem, estimates the cost, and automatically filters the right experts for the job.

---

## 🌟 Key Features

### 🤖 AI Video Diagnosis (Gemini Vision)
* Upload a video of the problem (e.g., a leaking sink).
* AI identifies the issue (e.g., "Corroded Pipe Joint"), suggests the trade (Plumber), and estimates cost.

### 🧠 Smart Provider Ranking
* Algorithms rank professionals based on a weighted score:
    * **40%** Rating & Reviews
    * **30%** Experience
    * **20%** Bio Relevance (Keyword Matching)
    * **10%** Hyperlocal Proximity

### 💬 Secure & Private Chat
* Built-in chat system allowing users to negotiate and share images without revealing phone numbers.

### 📍 Interactive Map View
* View providers on a dynamic map to find help nearest to you.

### 🛠️ Tools Marketplace
* A secondary platform to **buy or rent** professional tools (Drills, Ladders, etc.) from local experts.

---

## 💻 Tech Stack

* **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript (Glassmorphism UI).
* **Backend:** Python (Flask).
* **Database:** SQLite (via SQLAlchemy) - *Auto-seeding included.*
* **AI Engine:** Google Gemini 2.5 Flash API (for text & vision analysis).
* **Mapping:** Leaflet.js / OpenStreetMap.

---

## 🚀 Installation & Setup

Follow these steps to run the project locally.

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/FixIt.ai.git](https://github.com/your-username/FixIt.ai.git)
cd FixIt.ai
