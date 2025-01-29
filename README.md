# 🎭 Happy Primes Checker

## 📜 Overview
This project classifies numbers as:
- **Happy Prime**: A prime number that is also a happy number.
- **Sad Prime**: A prime number that is not a happy number.
- **Happy Non-Prime**: A non-prime number that is happy.
- **Sad Non-Prime**: A non-prime number that is not happy.

## 🎯 Features
- **Checks for Primality**: Determines if a number is prime.
- **Happy or Sad Classification**: Uses an iterative approach to classify numbers.
- **Continuous Input Mode**: Users can check multiple numbers.

A **Happy Number** follows this rule:
1. Take a number and **replace it with the sum of the squares of its digits**.
2. Repeat this process.
3. If it eventually reaches **1**, the number is **happy**.
4. If it enters a **loop (not reaching 1)**, it is **sad**.

### 🧮 Example Calculations
- **19** (Happy Prime)
1² + 9² = 82
8² + 2² = 68
6² + 8² = 100
1² + 0² + 0² = 1 ✅ (Happy)

- **17** (Sad Prime)
1² + 7² = 50
5² + 0² = 25
2² + 5² = 29
2² + 9² = 85
8² + 5² = 89 🔄 (Loops infinitely) ❌ (Sad)
