# push_swap

![Language](https://img.shields.io/badge/language-C-blue)
![Status](https://img.shields.io/badge/status-complete-success)
![42](https://img.shields.io/badge/42-common%20core-black)
![Score](https://img.shields.io/badge/score-84%2F100-yellow)

---

## 🗒️ Personal Note
This was a tough project for me, especially when it came to optimizing the number of operations and handling edge cases efficiently.  
It may not be perfect, but I’ve learned so much from it. I pushed myself beyond what I thought I was capable of, and I’m proud of the journey.

---

## 🔍 Project Overview

`push_swap` is a sorting algorithm project.
The goal is to sort a stack of integers using a limited set of operations and the **smallest number of moves** possible.

The project is divided into two parts:
1. A **program** that calculates and prints the list of operations to sort the stack.
2. A **checker** (optional/bonus) that reads operations and verifies if they sort the stack correctly.

---

## ✅ Allowed Operations

You can only use the following stack operations:

- `sa` / `sb` / `ss` – Swap the top two elements of stack A, B, or both.
- `pa` / `pb` – Push the top element from one stack to the other.
- `ra` / `rb` / `rr` – Rotate stack A, B, or both upwards.
- `rra` / `rrb` / `rrr` – Reverse rotate stack A, B, or both.

---
## 📈 Optimization Goal

Your program will be evaluated based on:

- Correctness

- Number of operations

- Performance with larger stacks (100 and 500 numbers)

---

🧠 Algorithm Strategy

Implemented algorithms:

Hard-coded sorting for 3–5 elements

Radix sort for larger datasets (base 2)

Optional: custom optimizations for 100/500 values

---

## 🧪 Testing

You can test the program by combining `push_swap` and `checker` like this:

```bash
ARG="4 67 3 87 23"
./push_swap $ARG | ./checker $ARG
```
If everything works correctly, the output should be:
```
OK
```

If something is wrong, it will output:
```
KO
```
---
## 📄 License

This project is for educational purposes only and is part of the 42 Common Core curriculum. [42 Common Core curriculum](https://www.42network.org/),

---

🔗 If you found this project helpful or interesting, consider supporting it by starring ⭐️ or forking.
