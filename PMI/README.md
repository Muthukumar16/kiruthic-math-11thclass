# Principle of Mathematical Induction (PMI) – Class 11 CBSE Mathematics

## 📘 Introduction
The **Principle of Mathematical Induction (PMI)** is a proof technique used to establish that a statement is true for **all natural numbers (n ∈ N)**.  
It works like a domino effect:
- If the first domino falls (base case is true),
- And each domino knocks down the next (inductive step),
- Then all dominos will fall (statement is true for all n).

---
## Principle of Mathematical Induction (PMI) 
##### Steps
- **Base Case:** Verify statement for n = 1. 2. 
- **Inductive Hypothesis:** Assume true for n = k. 3. 
- **Inductive Step:** Prove true for n = k+1. 4. 
- **Conclusion:** Statement holds for all n ∈ N. 

##### Example:
- Prove: 1 + 2 + 3 + ... + n = n(n+1)/2 
- Base Case (n=1): LHS = 1, RHS = 1 → True 
- Inductive Hypothesis: 
  - Assume true for n = k 1 + 2 + ... + k = k(k+1)/2 
- Inductive Step: 
  - For n = k+1 1 + 2 + ... + k + (k+1) = k(k+1)/2 + (k+1) = (k+1)(k+2)/2 → True 
- ✅ Hence proved by PMI.

---

## 🔹 Applications of PMI
- Proving formulas for sums (e.g., sum of first n natural numbers, squares, cubes).  
- Establishing inequalities (e.g., \(2^n \geq n^2\) for \(n \geq 4\)).  
- Validating divisibility properties.  

---

## 🔹 Importance in CBSE 
- **Chapter Placement:** PMI is a separate unit in the CBSE Class 11 Mathematics syllabus.  
- **Exam Weightage:** Usually carries **4–6 marks** in board exams.  
- **Use Case:** Helps in proving statements for all natural numbers systematically.

---

## 🔹 Key Takeaways
- PMI is a **proof technique**, not a formula.  
- It relies on **two steps: base case + inductive step**.  
- Widely used in higher mathematics, computer science (algorithms), and logic.
