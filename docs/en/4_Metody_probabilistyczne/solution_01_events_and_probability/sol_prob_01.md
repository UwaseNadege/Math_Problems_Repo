# Task 1 – Random Events and Probability

## Theory (Simple Version)
- **Sample Space** ($\Omega$) is all possible outcomes.  
  Example:  

  $$
  \Omega = \{\omega_1, \omega_2, \omega_3, \omega_4, \omega_5\}
  $$

- **Event** is a subset of outcomes.  
  Example:  

  $$
  A = \{\omega_1, \omega_3, \omega_5\}, \quad B = \{\omega_2, \omega_3, \omega_4\}
  $$

- **Union ($A \cup B$)**: all outcomes in A or B or both.  
- **Intersection ($A \cap B$)**: only outcomes in both A and B.  
- **Difference ($A \backslash B$)**: outcomes in A but not in B.  
- **Difference ($B \backslash A$)**: outcomes in B but not in A.  

---

## Problem
Find:  

1. 

$$
A \cup B
$$

2. $$
A \cap B
$$

3. $$
B \backslash A
$$

4. $$
A \backslash B
$$

---

## Solution (Step by Step)

1. **Union ($A \cup B$)**  

- Take all from A: $\omega_1, \omega_3, \omega_5$  
- Take all from B: $\omega_2, \omega_3, \omega_4$  
- Remove duplicates  

  $$
  A \cup B = \{\omega_1, \omega_2, \omega_3, \omega_4, \omega_5\}
  $$

---

2. **Intersection ($A \cap B$)**  

- Only outcomes in **both** A and B  

  $$
  A \cap B = \{\omega_3\}
  $$

---

3. **Difference ($B \backslash A$)**  

- Take B: $\omega_2, \omega_3, \omega_4$  
- Remove outcomes also in A ($\omega_3$)  

  $$
  B \backslash A = \{\omega_2, \omega_4\}
  $$

---

4. **Difference ($A \backslash B$)**  

- Take A: $\omega_1, \omega_3, \omega_5$  
- Remove outcomes also in B ($\omega_3$)  

  $$
  A \backslash B = \{\omega_1, \omega_5\}
  $$

---

## Quick Reminder
- **Union** = everything together  
- **Intersection** = only what is common  
- **Difference** = take one set, remove what’s shared