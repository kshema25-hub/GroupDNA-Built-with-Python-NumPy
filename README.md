# GroupDNA-Built-with-Python-NumPy
# 📊 GroupDNA – WhatsApp Chat Analytics using Python & NumPy

> Transform a raw WhatsApp chat export into a beautiful personality and activity report using only Python fundamentals and NumPy.

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![NumPy](https://img.shields.io/badge/NumPy-Library-green.svg)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📌 Project Overview

GroupDNA is a Python-based analytics tool that reads a WhatsApp chat export (.txt) and generates meaningful insights about the group's communication patterns.

The project analyzes thousands of chat messages to identify:

- 📈 Most active members
- 🌙 Night owls
- 👻 Ghost users
- 📅 Busiest day and hour
- 🔥 Favourite words
- 📊 Activity heatmap
- 💬 Message statistics
- 🎭 Personality archetypes

The project is built using only **Python Fundamentals** and **NumPy**, without relying on data analysis libraries like Pandas.

---

# 🚀 Features

### ✅ Chat Parser

- Reads WhatsApp exported chat (.txt)
- Parses timestamp, sender, and message
- Handles:
  - System messages
  - Media omitted
  - Deleted messages
  - Empty lines

---

### ✅ Group Overview

Displays:

- Total Messages
- Participants
- Chat Duration
- Messages per Person
- Percentage Contribution

---

### ✅ Most Active Day & Hour

Finds:

- 📅 Busiest Day
- ⏰ Busiest Hour

---

### ✅ Activity Heatmap (NumPy)

Creates a 6 × 24 NumPy matrix showing activity of each participant throughout the day.

Example:

```text
          00 03 06 09 12 15 18 21
Rahul     .  .  .  ▒  █  █  █  ▒
Priya     .  .  .  ▒  █  █  █  ▒
Aman      █  █  .  .  .  ░  ▒  ▒
```

---

### ✅ Favourite Words Analysis

Shows the most frequently used words.

Example

```text
bhai      ████████████████ 342
scene     ████████████     256
yaar      █████████        187
```

---

### ✅ Message Analytics

- Average Message Length
- Longest Message
- Shortest Message

---

### ✅ Media & Deleted Messages

Tracks

- Media Shared
- Deleted Messages

---

### ✅ Personality Archetypes

Automatically assigns personalities like

- 📢 The Spammer
- 🌙 The Night Owl
- 👻 The Ghost
- 👩‍👧 The Group Mom
- 📖 The Storyteller
- 🎭 The Drama Queen

---

# 🛠 Tech Stack

- Python 3
- NumPy
- Jupyter Notebook

---

# 📂 Project Structure

```
GroupDNA/
│
├── hostel_bois.txt
├── GroupDNA.ipynb
├── README.md
└── screenshots/
```

---

# 📊 Sample Output

```
============================================================
GROUP OVERVIEW
============================================================

Total Messages : 3174
Participants   : 6
Duration       : 60 Days

Rahul    ████████████████████ 953 (30.0%)
Priya    ███████████████      718 (22.6%)
Neha     █████████████        635 (20.0%)
Aman     ██████████           490 (15.4%)
Karan    ███████              354 (11.2%)
Vikas    █                    24 (0.8%)
```

---

# 📈 Personality Report

```
============================================================
PERSONALITY ARCHETYPES
============================================================

Rahul  → THE SPAMMER
Priya  → THE GROUP MOM
Aman   → THE NIGHT OWL
Karan  → THE STORYTELLER
Neha   → THE DRAMA QUEEN
Vikas  → THE GHOST
```

---

# 🎯 Learning Outcomes

This project helped me understand

- File Handling
- String Parsing
- Lists
- Dictionaries
- Loops
- Functions
- NumPy Arrays
- Data Analysis
- Frequency Analysis
- Time-based Analytics
- Problem Solving

---

# ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/GroupDNA.git
```

### Open Project

```bash
cd GroupDNA
```

### Install NumPy

```bash
pip install numpy
```

### Run

Open

```
GroupDNA.ipynb
```

using

- Jupyter Notebook
- Google Colab
- VS Code

Upload

```
hostel_bois.txt
```

Run all notebook cells.

---
# 📚 Concepts Used

- File Handling
- Python Fundamentals
- Dictionaries
- Lists
- String Operations
- NumPy
- Frequency Counting
- Sorting
- Date & Time Parsing
- Data Visualization (Console)

---

# 🌟 Future Improvements

- Interactive Dashboard
- Streamlit Web App
- Charts using Matplotlib
- Word Cloud
- Emoji Analysis
- Sentiment Analysis
- Export Report as PDF

---

# 👨‍💻 Author

**Kshema P M**

🎓 B.E. Data Science  
Adichunchanagiri Institute of Technology (VTU)

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

## ⭐ If you like this project, consider giving it a Star!
