

# Task 2: Event Description for Electrical Circuit

## Useful Definitions and Formulas

1. **Events**:

   * $A_i$ — event that element $a_i$ is functional at time $t$.

2. **Basic Set Operations**:

   * **Intersection**: $A \cap B$ — event that both $A$ and $B$ occur.
   * **Union**: $A \cup B$ — event that at least one of $A$ or $B$ occurs.

3. **Series and Parallel Connections in Terms of Events**:

   * **Series Connection**: Current flows if **all elements** are functional.
     $$ A_\text{series} = A_1 \cap A_2 \cap \dots \cap A_n $$
   * **Parallel Connection**: Current flows if **at least one element** is functional.
     $$ A_\text{parallel} = A_1 \cup A_2 \cup \dots \cup A_n $$

---

## Step-by-Step Solution

1. **Understand the Circuit**:

   * Element $a_1$ is in **series** with a block.
   * The block has $a_2$ and $a_3$ in **parallel**.
   * The current will flow if:

     * $a_1$ is functional **AND**
     * at least one of $a_2$ or $a_3$ is functional.

2. **Express the Parallel Block ($a_2$ and $a_3$)**:

$$ 
A_\text{block} = A_2 \cup A_3
$$

3. **Combine with Series Element $a_1$**:

   * Series connection requires both $a_1$ and the block to be functional:
     $$ A = A_1 \cap (A_2 \cup A_3) $$

---

## ✅ Final Answer

The event $A$ that the current will **not be interrupted** is:

$$
A = A_1 \cap (A_2 \cup A_3)
$$

This formula correctly captures the condition that $a_1$ must work **and** at least one of $a_2$ or $a_3$ must work.


