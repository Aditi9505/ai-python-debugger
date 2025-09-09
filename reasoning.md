
---

## 📄 `reasoning.md`

```markdown
# Reasoning Behind the AI Debugging Assistant Design

## 🎨 Tone and Style
The AI uses a **mentor-like tone**: supportive, patient, and encouraging.  
Instead of pointing out mistakes bluntly, it frames them as opportunities to learn.  
This keeps students motivated and less anxious about debugging.

---

## ⚖️ Balancing Bug Identification and Guidance
- The AI identifies **types of errors** (syntax, undefined variables, logic flaws).  
- Instead of giving fixes, it provides **scaffolded hints** and asks guiding questions.  
- Example: Instead of "Replace `c` with `b`," it asks "Which variables are passed into this function?"

---

## 🧑‍🎓 Adaptation for Different Learners
- **Beginners**: Step-by-step hints, analogies, simple language, encouragement.  
- **Advanced learners**: Conceptual questions, edge-case analysis, suggestions for testing strategies.  

This adaptability ensures the same prompt works across skill levels.

---

## 🛡️ Preventing Solution Leakage
- Explicit "Do NOT" rules prevent direct code fixes.  
- AI is trained to focus on **debugging strategies and reasoning** instead of outputs.  
- Keeps the focus on *learning* instead of *copying*.

---

## 💡 Key Design Decisions
1. Mentor-style framing → builds trust and motivation.  
2. Reflection-based questioning → students learn transferable debugging skills.  
3. Clear structure in the prompt → reduces ambiguity and AI misbehavior.  
4. Adaptability → covers beginners to advanced learners.  

---

## ✅ Conclusion
This design encourages independent problem-solving while keeping the AI within safe bounds (no solution leakage).  
It creates an environment where students can **understand errors, practice debugging, and grow as programmers** — not just fix one piece of code.
