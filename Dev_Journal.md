# 🗓️ Daily Progress Log

This file tracks my daily learning progress during my career rebuild challenge.

---

### 📅 Day 1 – July 10, 2025
- ✅ Created `career-rebuild` repo on GitHub
- ✅ Added 30-day roadmap and learning structure to README
- ✅ Recommitted to CS50P Week 8 (OOP) and boot.dev goals

---

### 📅 Day 2 – July 11, 2025
- ✅ Used cs50.dev cloud VS Code to practice OOP (CS50P Week 8)
- ✅ Watched first 30 minutes of lecture (total 2h 48m)
- ✅ Built a `Student` class with `__init__` and `__str__`
- ✅ Modularized code: moved class to `student/student.py` + `__init__.py`
- 📌 Plan: Set up local Python environment and try 3 CS50P exercises tomorrow

---

### 📅 Day 3 – July 12, 2025

- Learned `@property` method in Python OOP
- Built `Person` and `Student` classes with encapsulation
- Added validation logic with getters and setters
- Completed "Encapsulation" chapter in Boot.dev OOP course

---

### 📅 Day 4 – July 13, 2025
✅ Progress:

🧠 CS50P Week 8 (Object-Oriented Programming)
– Watched up to 1 hour 40 minutes of the lecture.
– Covered: defining classes, instantiating objects, encapsulation with private attributes, and @property.

🐍 100 Days of Code – Day 01: Band Name Generator
– Completed project using Object-Oriented Programming.
– Created BandNameGenerator class with input handling and name generation.
– Structured project cleanly under day_01/, created .gitignore, and set up Git repository.
– Learned about .pyc files, __pycache__, and Git best practices.

🧑‍💻 Boot.dev – OOP Course
– Finished the Abstraction chapter.
– Understood the importance of hiding complexity using public methods and internal logic separation.

---

### 📅 Day 5 - July 14, 2025

✅ Completed
- 🔹 **Boot.dev (OOP Track)**
  - Finished optional coding challenges in the **Abstraction** chapter
- 🔹 Worked on the `ocr_api` project:
  - Continued development and debugging
  - Integrated learning into real-world code

🔜 Next Steps
- 📘 Resume **CS50P Week 8** – start the coding exercises
- 📘 Boot.dev – Start **Inheritance** chapter in OOP
- 🐍 100 Days of Code – Continue with **Day 2** (use OOP, type hints, and testing)

---

### 📅 Day 6 - July 15, 2025

✅ Completed
- 🔹 Built an **OCR API using FastAPI** with EasyOCR
  - API accepts image uploads and returns extracted text
  - Learned about request handling, async functions, and directory structure
- 🔹 **Boot.dev (OOP Track)**
  - Completed exercises in the **Inheritance** chapter

🔜 Next Steps
- 📘 Boot.dev – Continue with **Polymorphism**
- 🐍 100 Days of Code – Start **Day 2** project (OOP + type hints + testable code)
- 🧪 Add unit tests to OCR API

---

### 📅 Day 7 - July 16, 2025

✅ Completed:
- 📘 100 Days of Code - Day 2
  - Rebuilt the Tip Calculator using a class-based approach.
  - Focused on getting more comfortable with writing modular code using classes.
  - Practiced using Python type hints in a real-world style example.

🧠 Notes:
- Continued building foundational skills in class design and type hinting.
- Emphasis on clarity and step-by-step progression toward clean, modular code.

---

### 📅 Day 8 - July 17, 2025

✅ Completed:
- 🧠 Built a working **OCR + LLM Summarizer** pipeline:
  - OCR: Extracted text from both digital and scanned PDFs using Tesseract.
  - Sent extracted text to local LLM (DeepSeek via LM Studio) for summarization.
  - Saved summarized output to timestamped `.txt` files in `static/summaries/`.

🛠️ Tech Stack:
- Python, FastAPI
- Tesseract OCR
- LM Studio (DeepSeek LLM)
- File handling (PDF, text)

🧠 Notes:
- Implemented PDF type detection (scanned vs digital).
- Practiced FastAPI routing, file upload handling, and modular code organization.
- Improved integration between OCR and LLM for document summarization.

---

### 📅 Day 9 - July 18, 2025

**Progress:**
- ✅ Tested the `ocr_llm_summarizer` project on Windows using Git Bash
- ✅ Confirmed it works properly in a Windows environment
- ✅ Added support for accepting `.txt` files as input
- ✅ Created a detailed `README.md` for setup and usage instructions

**Thoughts:**
- Good progress on cross-platform testing and usability.
- Clean documentation will help others (and future me!) use the tool easily.

---

### 📅 Day 10 - July 19, 2025

**Progress:**
- Fixed bugs in the summarizer flow.
- Updated API to return the generated summary in the response JSON.

---

### 📅 Day 11 - July 20, 2025

**Progress:**
- ✅ Completed CS50P Week 8 OOP lecture (Object-Oriented Programming).
- Learned about classes, objects, `__init__`, `__str__`, encapsulation, properties, class methods, inheritance, and more.
- ✅ Practiced OOP exercises on Boot.dev to reinforce concepts.
- 🔜 Ready to begin CS50P Week 8 coding exercises for hands-on practice.

---

### 📅 Day 12 - July 21, 2025

**Progress:**
- 🔍 Started researching and exploring the PaddleOCR model for improved OCR support.
- ⚙️ Attempted setup of PaddleOCR on the local machine.
- 🐛 Faced dependency issues during installation; debugging in progress.

---

### 📅 Day 13 – July 22, 2025
- ✅ Completed the **AI Agent** project from Boot.dev.
- 🚀 Started the **Data Structures and Algorithms** (DSA) course.
- 🧠 Reviewed algorithmic concepts and began working on DSA exercises.
- 🧪 Successfully got **PaddleOCR** running on the system (CPU-based).
- ⚡️ GPU acceleration for PaddleOCR still pending setup.

---

### 📅 Day 14 – July 23, 2025
- ✅ Completed core functionality in `ocr_llm_summarizer` using **PaddleOCR** to extract and summarize text.
- 🧪 Verified the end-to-end OCR + summarization pipeline is functional.
- 🧠 Completed **Algorithm Introduction** exercises on Boot.dev as part of the DSA track.

---

### 📅 Day 15 – July 24, 2025
- 🛠️ Tried implementing **PaddleOCR with GPU acceleration**.
- ✅ Resolved PaddleOCR setup issues by updating **NVIDIA drivers** and installing **CUDA 12.9**.
- 🔍 Explored **PaddleOCR 3.0**; referred to official documentation for correct GPU-compatible setup.
- ⚠️ Faced a few deprecated method issues but finally managed to get **OCR text extraction from images** working.
- 📚 Practiced a bit of **DSA** and **OOP** on Boot.dev.

---

### 📅 Day 16 – July 25, 2025
- 📘 Practiced **DSA exercises** on Boot.dev.
- ➗ Started the **Math section** in Boot.dev (under Algorithms track).
- 🔍 Continued exploring **PaddleOCR**, experimenting with different model configurations and capabilities.

---

### 📅 Day 17 – July 26, 2025
- ✅ Completed the **Math section** in the DSA course on Boot.dev.
- 🧠 Practiced **DSA problems** to reinforce algorithmic thinking.
- 🗄️ Explored **RDBMS** basics using the FreeCodeCamp curriculum.
- 💻 Worked through exercises in the **Certified Full Stack Developer** track (FreeCodeCamp).

---

### 📅 Day 18 – July 27, 2025
- ✅ Completed **Big-O Notation** section in the Boot.dev DSA course.
- 📚 Continued progressing through **core computer science foundations**.

---

---

### 📅 **Day 19 – July 28, 2025**
- 🚧 Started integrating **PaddleOCR GPU version** for the OCR + LLM summarizer project.
- 🧪 Experimented with GPU acceleration and verified PaddleOCR on images.
- 📚 Continued **Boot.dev DSA** course.

---

### 📅 **Day 20 – July 29, 2025**
- ✅ Completed integration of **PaddleOCR GPU version** in the `ocr_llm_summarizer` app.
- 📝 Wrote supporting documentation and finalized code changes.
- 📊 Continued Boot.dev DSA course — currently in the **Sorting Algorithms** section.

---

### 📅 **Day 21 - July 30, 2025**

- ✅ Completed Day 6 of the 100 Days of Code (Angela Yu)  
- ✅ Learned and practiced Bubble Sort in Boot.dev's Sorting Algorithms section (DSA)  
- ✅ Gave a demo of the LLM Summarizer app to a client  
- ✅ Pushed the LLM Summarizer project to Bitbucket  

---

### 📅 **Day 22 - July 31, 2025**
- ✅ Learned and practiced Merge Sort and Insertion Sort in Boot.dev's Sorting Algorithms section (DSA)  
- ✅ Started Day 7 of the 100 Days of Code (Angela Yu)

---

### 📅 **Day 23 - August 1, 2025**
- ✅ Completed the Sorting Algorithms section in Boot.dev's DSA course (except Selection Sort, needs review)  
- ✅ Continued with Day 7 of the 100 Days of Code (Angela Yu)  

---

### 📅 **Day 24 - August 2, 2025**
- ✅ Started the "Exponential Time" topic in Boot.dev's DSA course  
- ✅ Completed exercises related to exponential time complexity  

---

### 📅 **Day 25 - August 3, 2025**
- ✅ Continued with the "Exponential Time" topic in Boot.dev's DSA course  
- ✅ Completed more exercises on exponential time complexity

---

### 📅 **Day 26 - August 4, 2025**
- ✅ Completed the "Exponential Time" section in Boot.dev's DSA course  

---

### 📅 **Day 27 - August 5, 2025**
- ✅ Completed the "Data Structures Introduction" section in Boot.dev's DSA course  
- ✅ Started the "Stack" section in Boot.dev's DSA course  
- ✅ Explored HTML basics on freeCodeCamp  

---

### 📅 **Day 28 - August 6, 2025**
- ✅ Completed the "Queue" section in Boot.dev's DSA course  

---

### 📅 **Day 29 - August 7, 2025**
- ✅ Started the "Linked List" section in Boot.dev's DSA course  
- ✅ Completed a few exercises on linked lists  

---

### 📅 **Day 30 - August 8, 2025**
- ✅ Continued the "Linked List" section in Boot.dev's DSA course  
- ✅ Practiced HTML on Scrimba  

---

### 📅 **Day 31 - August 9, 2025**
- ✅ Completed the "Linked List" section in Boot.dev's DSA course  
- ✅ Started the "Binary Search Tree (BST)" section in Boot.dev's DSA course  

---

### 📅 **Day 32 - August 10, 2025**
- ✅ Continued the "Binary Search Tree (BST)" section in Boot.dev's DSA course  
- ✅ Practiced HTML on freeCodeCamp  

---

### 📅 **Day 33 - August 11, 2025**
- ✅ Continued practicing HTML on freeCodeCamp  
- ✅ Felt quite exhausted, took it a bit easier  

---

### 📅 **Day 34 - August 12, 2025**
- ✅ Completed the HTML section in freeCodeCamp's Responsive Web Design course  

---

### 📅 **Day 35 - August 13, 2025**
- ✅ Maintained streak in Boot.dev by completing some OOP exercises  
- ⚡ Took a light day due to low motivation  

---

### 📅 **Day 36 - August 14, 2025**
- ✅ Started learning JavaScript  
- ✅ Covered: Variables, Comparisons, and Functions chapters  
- ✅ Started solving Python problems on HackerRank  

---

### 📅 **Day 37 - August 15, 2025**
- ✅ Completed the "Functions" chapter in JavaScript  
- ✅ Started the "Objects" chapter in JavaScript  
- ✅ Solved Python exercises on HackerRank.

---

### 📅 **Day 38 - August 16, 2025**
- ✅ Continued learning JavaScript

---

### 📅 **Day 39 - August 17, 2025**
- ✅ Continued learning JavaScript

---

### 📅 **Day 40 - August 21, 2025**
- ✅ Completed the "Objects" chapter in JavaScript (past days)  
- ✅ Continued learning JavaScript, currently on the "Classes" chapter  

---

### 📅 **Day 41 - August 22, 2025**
- ✅ Completed the "Classes" chapter in JavaScript  

---

### 📅 **Day 42 - August 23, 2025**
- ✅ Started the "Loops" chapter in JavaScript  

---

### 📅 **Day 43 - August 26, 2025**
- ✅ Completed the "Loops" chapter in JavaScript  
- ✅ Started the "Arrays" chapter in JavaScript  
- ✅ Enrolled in Web Development with Scrimba (Full-Stack Development track)  

---

### 📅 **Day 44 - August 27, 2025**
- ✅ Completed the "Arrays" chapter in JavaScript  
- ✅ Completed 75% of the HTML course in Scrimba’s Full-Stack Development track  

---

### 📅 **Day 45 - August 28, 2025**
- ✅ Onboarded on a freelance project for an LLM-based chatbot  
- ✅ Redid some exercises in JavaScript  
- ✅ Practiced HTML exercises  

---

### 📅 **Day 47 - August 30, 2025**
- ✅ Continued learning JavaScript in Boot.dev  
- ✅ Worked on freelance LLM chatbot project (using Qwen3 + Streamlit)  

---

### 📅 **Day 48 - August 31, 2025**
- ✅ Practiced more JavaScript exercises  
- ✅ Explored chatbot improvements with Ollama + RAG concepts  

---

### 📅 **Day 49 - September 1, 2025**
- ✅ Started the Full-Stack Development path on Scrimba  
- ✅ Reviewed HTML basics  

---

### 📅 **Day 50 - September 2, 2025**
- ✅ Built and deployed first personal profile site on Netlify 🚀  
- ✅ Continued HTML course on Scrimba  

---

### 📅 **Day 51 - September 3, 2025**
- ✅ Researched fine-tuning vs RAG for LLM chatbot project  
- ✅ Made progress on Boot.dev JavaScript section  

---

### 📅 **Day 52 - September 4, 2025**
- ✅ Continued working with Qwen3 on Ollama + Streamlit chatbot integration  
- ✅ Completed exercises in JavaScript  

---

### 📅 **Day 53 - September 5, 2025**
- ✅ Started learning CSS in Scrimba  
- ✅ Began working on a business card project with CSS  

---

### 📅 **Day 54 - September 6, 2025**
- ✅ Progressed further in Boot.dev JavaScript course  
- ✅ Explored more CSS styling techniques  

---

### 📅 **Day 55 - September 7, 2025**
- ✅ Focused on JavaScript Promises in Boot.dev  
- ✅ Improved styling on CSS business card project  

---

### 📅 **Day 56 - September 8, 2025**
- ✅ Currently learning JavaScript Promises on Boot.dev  
- ✅ Continuing CSS business card project in Scrimba  
- ✅ Iterated on LLM chatbot (Qwen3 + Streamlit + Ollama)  

---
