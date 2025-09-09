# 🐍 AI Python Debugging Assistant

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)  
[![OpenAI](https://img.shields.io/badge/OpenAI-API-green?logo=openai&logoColor=white)](https://openai.com/)  

> **An intelligent, student-friendly AI mentor that helps learners debug Python code without giving away the solution.**

---

## 🚀 Overview

This project demonstrates an **advanced AI prompt** designed to guide students in debugging Python code.  
The AI behaves like a **patient, encouraging mentor**, providing hints, questions, and debugging strategies **without revealing the solution**.  

This approach promotes **self-learning, problem-solving, and coding confidence**.

---

## 🧩 Features

- ✅ **Bug Analysis**: Identifies logical or syntactical issues in code.  
- ✅ **Constructive Hints**: Offers guidance to help students figure out errors themselves.  
- ✅ **Probing Questions**: Encourages reflection and critical thinking.  
- ✅ **Student-Friendly Tone**: Friendly, patient, and motivational.  
- ✅ **Supports Beginner & Advanced Learners**: Adjusts hint complexity based on the learner’s level.  

---

## 💡 Prompt Design

The AI is instructed to:

1. Act as a **mentor**, not a solver.  
2. Highlight potential bugs and misconceptions.  
3. Provide **guiding hints and debugging strategies**, never the solution.  
4. Ask **reflective questions** to make students reason about the code.  
5. Use **positive reinforcement** to maintain engagement.  

**Example Input (Buggy Python Code):**
```python
def add_numbers(a, b):
    return a + b + c
Expected AI Response:

Recognizes c is undefined and explains why it causes an error.

Suggests checking function parameters and variable accessibility.

Asks guiding questions like:

"What do you expect this variable to hold here?"

"Have you checked all inputs before returning?"

Maintains a positive tone: “You’re very close! Think about which variables are accessible in this function.”

🎯 Reasoning Behind Design

Mentor-style AI → Encourages self-learning and reduces dependency.

Hints and questions → Teach debugging patterns rather than just the fix.

Explicit rules → Prevent giving away exact solutions.

Tone and style → Friendly, patient, and reflective for better engagement.

Adaptability → Works for beginners (step-by-step hints) and advanced learners (conceptual guidance and edge-case probing).
