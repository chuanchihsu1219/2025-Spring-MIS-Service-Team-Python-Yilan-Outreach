# Python Curriculum for Jinior High School Students at Yilan

**Designed and delivered by Chuan-Chi Hsu & Ju-Ying (NTU Information Management Service Team Outreach Program)**

## 📌 Context & Purpose

This project was developed as part of NTU's educational outreach to 順安國中. The target audience was junior high students (grades 7–9) with zero prior coding experience.

This teaching initiative aligns with Microsoft TAI core responsibilities:

* Understanding users’ technical background and constraints
* Designing solutions and workflows (lesson plans, auto-setup notebooks)
* Delivering Proof-of-Concept (PoC)-like content (hands-on Jupyter notebooks + live demo)
* Ensuring knowledge transfer to non-technical stakeholders (students)

---

## 📘 Curriculum Package Overview

| Component          | Description                                                                                                |
| ------------------ | ---------------------------------------------------------------------------------------------------------- |
| `進階程式設計.pdf`       | Teaching slide deck covering list, loops, nested loops, sorting, conditional logic, and applied challenges |
| `進階程式設計_學生版.ipynb` | Blank student notebook mirroring the slide deck with code templates and prompts                            |
| `進階程式設計_教師版.ipynb` | Teacher’s annotated version with complete code and pedagogical notes                                       |
| `init.ipynb`       | Initialization script for importing packages, configuring the environment, and streamlining setup          |
| `競賽_競賽版.ipynb`     | Self-contained in-class contest with 9 coding problems (ICPC-inspired)                                     |
| `競賽_解答版.ipynb`     | Fully worked solution notebook for grading and walkthrough                                                 |

---

## 🎓 Teaching Design: Tailored for Beginners

A major challenge was translating abstract programming constructs into understandable formats for students aged 13–15. Here's how we addressed this:

### 1. 🫖 Real-Life Contexts

We used relatable scenarios like a dessert shop to explain list manipulation, allowing students to work with `menu = ["Tiramisu", "Macaron", ...]` to apply `append()`, `remove()`, and indexing.

### 2. ↺ Loop Comprehension via Multiplication Table

Nested loops were introduced using a classic multiplication table. Students wrote logic with `for i in range(1, 10)` and observed indentation-driven behavior changes in printed results.

### 3. 📊 Problem Decomposition

One example asked students to calculate the number of product pairings that exceeded a total value threshold for a discount. This exercise combined looping, condition checking, and counting logic.

### 4. 🧰 Manual Sorting

Instead of using Python’s built-in `sorted()`, students learned to build a sorting algorithm by finding the max and iteratively appending it to a new list. This gave them practical exposure to algorithmic thinking.

---

## ⚙️ Automation & Deployment Tools

To ensure consistency and reduce instructor prep time:

### `init.ipynb`

* Auto-loads notebooks, packages, and clears output cells for a clean start
* Enables instructors to reset the environment in under 30 seconds
* Replaces manual setup steps with scripted automation

### Contest Notebooks

* Include 9 standalone problems simulating a 45-minute contest
* Story-driven problems (e.g., cake price filtering, watering plants)
* Ready for immediate use in class, and adaptable across classrooms
* Enabled rapid, hassle-free setup across distributed and inconsistent computers

---

## 📊 Evidence of Learning Impact

The effectiveness of this curriculum was validated by student surveys collected after each session. In particular, our **Advanced Programming** session—covering nested loops and sorting—ranked among the top-performing modules in terms of learning outcomes:

* Over 90% of students reported they "learned most (80%)" or "learned everything (100%)," the highest reported mastery rate among all six sessions
* It had one of the lowest  students reporting difficulty (only one student)

This demonstrates my ability to **demystify abstract technical logic** for a general audience, which is highly transferable to client-facing roles such as those in Microsoft TAI.

---

## ✅ Relevance to Microsoft TAI

| TAI Responsibility             | Demonstrated In Project                                                             |
| ------------------------------ | ----------------------------------------------------------------------------------- |
| Client Needs Clarification     | Understood student background, and simplified and gamified concepts accordingly  |
| PoC & Demos                    | Delivered interactive notebooks and lecture as in-class proof-of-concept demos                  |
| Technical Communication        | Translated logic into visual stories, metaphors, and beginner-friendly instructions |
| Solution Design                | Developed modular, reusable teaching components with automated setup                |
| Cross-functional Collaboration | Co-led with a teaching partner and other teaching assistants                |
