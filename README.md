# 🔁 HireWise – A Gale-Shapley Based Job Matching System

A terminal-based job and recruitment simulation system that uses the **Gale-Shapley stable matching algorithm** to optimally assign applicants to companies based on **qualifications, preferences, and recruiter requirements**. This C++ project demonstrates a real-world application of algorithmic matchmaking and file-based data storage.

---

## 📌 Key Features

- 👤 Account creation for both Applicants and Recruiters
- 📝 Skill assessment based on structured questionnaire
- 📊 Score-based eligibility check
- ❤️ Preference list input by Applicants
- 🏢 Recruiter-side job posting with skill criteria
- ⚖️ Stable matching via Gale-Shapley Algorithm
- 📁 Data storage using file I/O (no database needed)
- 🎮 Menu-driven CLI interface

---

## 🧠 Core Concepts Used

- Gale-Shapley Stable Matching Algorithm
- Object-Oriented Programming (C++)
- File Handling in C++
- First-Come-First-Serve as tie-breaker
- Sorting and filtering logic for score matching

---

## 🛠️ Technologies Used

- **Language:** C++
- **Environment:** Terminal / Console
- **Storage:** File I/O (`.txt` files for data persistence)

---

## 🚀 How It Works

1. **Applicant Module:**
   - Registers with name, qualifications, experience
   - Takes a questionnaire to generate a **Skill Score**
   - Enters a ranked preference list of companies
   - Gets matched based on score and preference

2. **Recruiter Module:**
   - Registers and posts job requirements
   - Inputs desired skill thresholds
   - Reviews matched candidates

3. **Matching Engine:**
   - Compares scores of applicants to job criteria
   - Applies Gale-Shapley Algorithm for fair & stable matching
   - Stores final job placements

---

## 📂 Project Structure

```bash
📁 Project Gale/
├── main.cpp                  # Entry point & menu system
├── applicant.cpp/.h         # Applicant functions
├── recruiter.cpp/.h         # Recruiter functions
├── matching.cpp/.h          # Gale-Shapley matching logic
├── file_handler.cpp/.h      # File input/output handling
├── data/
│   ├── applicants.txt
│   ├── recruiters.txt
│   └── matches.txt

## How to run

1. Clone the project;
2. Run main.cpp file on your cpp compiler
3. Follow the menu for further instructions
