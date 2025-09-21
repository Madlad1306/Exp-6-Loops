# Experiment: Loops in C++

### AIM

To study and implement C++ decision-making statements and loops.

---

### SOFTWARE USED

* Visual Studio Code (VS Code)

---

### THEORY

**Loops in C++**
Loops allow a set of instructions to be executed repeatedly until a specific condition is satisfied. They make code concise, avoid redundancy, and improve efficiency.

---

#### 1️⃣ for Loop

* **Purpose:** When the number of iterations is known.
* **Structure:** Combines initialization, condition, and update in one line.
* **Use Cases:** Arrays, patterns, fixed iterations.

**Execution Flow:**

1. Initialize loop control variable.
2. Check condition.
3. Execute loop body if true.
4. Update variable → repeat.

---

#### 2️⃣ while Loop

* **Purpose:** When the number of iterations is unknown.
* **Structure:** Condition checked before execution.
* **Use Cases:** Input-driven programs, waiting until a condition is true.

**Execution Flow:**

1. Check condition.
2. If true, execute loop body.
3. Repeat until false.

---

#### 3️⃣ do-while Loop

* **Purpose:** Executes loop body at least once.
* **Structure:** Condition checked after execution.
* **Use Cases:** Menus, password validation, input confirmation.

**Execution Flow:**

1. Execute loop body.
2. Check condition.
3. If true, repeat loop.

---

### ALGORITHMS

#### Program 1: Password Checker (do-while)

1. Start.
2. Declare `password`, `input`, `attempts = 0`, `max = 3`.
3. User sets password.
4. Repeat while `attempts < max`:

   * Ask for input.
   * If input == password → success message → exit.
   * Else increment attempts.
5. If `attempts == max` → show "Access Denied".
6. End.

---

#### Program 2: Number Reversal (while loop)

1. Start.
2. Declare `num`, `reversed = 0`.
3. Input a number.
4. Repeat while `num != 0`:

   * Extract digit = `num % 10`.
   * `reversed = reversed * 10 + digit`.
   * `num = num / 10`.
5. Display reversed number.
6. End.

---

#### Program 3: Flipped Inverted Pyramid Pattern (for loop)

1. Input rows `n`.
2. Loop `i = 0 → n-1`:

   * Print `i` spaces.
   * Print `n-i` stars.
   * Move to next line.

---

#### Program 4: Flipped Pyramid Pattern (for loop)

1. Input rows `n`.
2. Loop `i = 1 → n`:

   * Print `n-i` spaces.
   * Print `i` stars.
   * Move to next line.

---

#### Program 5: Floyd’s Triangle Pattern (for loop)

1. Input rows `n`.
2. Set `num = 1`.
3. Loop `i = 1 → n`:

   * Inner loop `j = 1 → i`:

     * Print `num`.
     * Increment `num`.
   * Move to next line.

---

#### Program 6: Hourglass Pattern (for loop)

1. Input rows `n`.
2. **Top half:** Loop `i = n → 1`:

   * Print `n-i` spaces.
   * Print `i` stars.
3. **Bottom half:** Loop `i = 2 → n`:

   * Print `n-i` spaces.
   * Print `i` stars.

---

#### Program 7: Pyramid Pattern (for loop)

1. Input rows `n`.
2. Loop `i = 1 → n`:

   * Print `n-i` spaces.
   * Print `i` stars.
   * Move to next line.

---

### CONCLUSION

* Loops in C++ provide **control flow** to repeat instructions efficiently.
* **for loop** is best when iterations are fixed.
* **while loop** is used when repetitions depend on a condition.
* **do-while loop** guarantees at least one execution.
* Loops are useful in **validations, pattern generation, numerical calculations, and data handling**.


