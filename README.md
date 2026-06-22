# 🏦 ATMBeginner

A practical Python script I put together to practice the core basics of software logic by building a secure, interactive ATM simulator. 

Instead of just printing static text to the screen, I wanted to create an app that handles real banking logic, keeps track of user data across multiple transactions, and—most importantly—won't completely explode if a user accidentally types a typo.

---

## ⚙️ What's going on under the hood:

This project allowed me to get hands-on with fundamental programming structures and understand how data flows through a backend script:

* **The Loop (`while True`):** Keeps the program running continuously. This allows you to do multiple transactions in a single session rather than kicking you out after just one action.
* **Menu Routing (`if / elif / else`):** The core decision-maker of the app. It cleanly directs the user to the right code block based on whether they want to check their balance, deposit, withdraw, or exit.
* **PIN Authentication:** A simple security step at the very beginning. It gives the user 3 attempts to enter the correct PIN before completely locking down the session for safety.
* **Persistent Balance Tracking:** Keeps track of account funds mathematically so your cash balance updates and stays accurate across deposits and withdrawals.
* **Error Prevention (`try / except`):** My absolute favorite part. Normally, if a script expects a number and the user types letters like "abc", Python crashes instantly. This safety net catches that mistake, handles it nicely, and keeps the program running smoothly.
* **f-strings:** Used to easily inject real-time variables (like the current live balance) directly into text outputs.

---

## 🚀 How it works:

1. **Secure Login:** Enter the default PIN (`1234`) to gain access. You get 3 attempts before a security lockout.
2. **Main Menu:** Choose from four classic banking options.
3. **Smart Validation:** The script actively checks for human errors (like trying to deposit negative money, withdrawing more than you own, or entering text characters instead of digits).

---

## 👤 Author

* **Created by:** [ Youssef Hassan Abdalla ]
* **Github Page:** [( https://github.com/yhassan01111 )]
* **Project Track:** Fundamental Python Engineering
* **Project Name:** [ ATMBeginner! ]

---
*"Built to learn how to write clean, predictable, and user-friendly software foundations."*
