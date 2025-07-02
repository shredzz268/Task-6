# Task 6: Create a Strong Password and Evaluate Its Strength

## 1. Project Objective

This project, as part of the Elevate Labs Cyber Security Internship, focuses on understanding the components of a strong password. [cite_start]The primary objective was to create passwords of varying complexity and use online tools to test their strength, thereby gaining practical insight into password security. [cite: 3, 6] The tools used for this evaluation were:

* Kaspersky Password Checker
* Password Monster
* [cite_start]Password Meter [cite: 7]

---

## 2. Password Strength Evaluation

[cite_start]I created and tested two distinct passwords—one weak and one strong—to analyze the feedback from the evaluation tools. [cite: 10, 12]

### A. The Weak Password: `aditya123`

This password was created to be intentionally simple, using a common name followed by a simple number sequence.

**Evaluation Results:**

* **Kaspersky Password Checker:** Immediately flagged that the password lacks complexity (no special symbols or capital letters) and, most critically, has appeared in a database of leaked passwords nearly 50,000 times.
    * ![Kaspersky Weak Password](httpsa://user-images.githubusercontent.com/your-username/your-repo/blob/main/Task%206%201.jpg)
* **Password Monster:** Rated the password as "Weak." It estimated the time to crack it at a mere **4.76 minutes**, highlighting that it contains dictionary words and a predictable sequence.
    * ![Password Monster Weak Password](httpsa://user-images.githubusercontent.com/your-username/your-repo/blob/main/Task%206%202.png)
* **Password Meter:** Gave a low score of **40%**. The analysis showed it met the minimum length but failed on key requirements like including uppercase letters and symbols.
    * ![Password Meter Weak Password](httpsa://user-images.githubusercontent.com/your-username/your-repo/blob/main/Task%206%203.png)

**Conclusion:** The password `aditya123` is extremely insecure due to its predictability, use of a common name, lack of character variety, and its presence in known data breaches.

---

### B. The Strong Password

This password was created using best practices: significant length and a mix of all character types.

**Evaluation Results:**

* **Kaspersky Password Checker:** Rated the password as "Strong," confirming it contains a mix of digits, special symbols, and capital letters, and was not found in any leaked databases.
    * ![Kaspersky Strong Password](httpsa://user-images.githubusercontent.com/your-username/your-repo/blob/main/Task%206%20strong.jpg)
* **Password Monster:** Rated it as "Very Strong" and estimated the time to crack it would be **5 billion years**, demonstrating the power of length and complexity.
    * ![Password Monster Strong Password](httpsa://user-images.githubusercontent.com/your-username/your-repo/blob/main/Task%206%20strong%202.png)
* **Password Meter:** Gave a perfect score of **100%**, noting it exceeded all minimum requirements for length, character variety, and complexity.
    * ![Password Meter Strong Password](httpsa://user-images.githubusercontent.com/your-username/your-repo/blob/main/Task%20strong%203.png)

**Conclusion:** A long password (21 characters in this case) that combines uppercase letters, lowercase letters, numbers, and symbols is exponentially more secure and resistant to common hacking techniques.

---

## [cite_start]3. Best Practices & Key Learnings [cite: 14, 15]

This exercise provided several key insights into password security:

* [cite_start]**Length is King:** Password length is the single most important factor in resisting brute-force attacks. [cite: 22] As seen in the "Very Strong" password, a longer character count dramatically increases the time required to crack it.
* [cite_start]**Complexity is Crucial:** A mix of uppercase letters, lowercase letters, numbers, and symbols is essential. [cite: 11] Simple passwords lacking this variety are easily guessed.
* [cite_start]**Avoid Predictability:** Using personal information, common words, or simple sequences makes a password vulnerable to dictionary attacks and educated guesses. [cite: 23, 27]
* **Check for Breaches:** Tools like Kaspersky's can check if your password has been exposed in a known data breach, which is a critical security step.

---

## [cite_start]4. Common Password Attacks [cite: 16]

* **Brute-Force Attack:** This is an exhaustive attempt to guess a password by systematically trying every possible combination of letters, numbers, and symbols. [cite_start]Longer and more complex passwords make this attack impractical. [cite: 16, 21, 29]
* **Dictionary Attack:** This attack uses a pre-compiled list of common words, phrases, and simple passwords (like "password123") to try and gain access. [cite_start]This is why using a common word, even with a number at the end, is insecure. [cite: 16, 21, 23, 29]

---

## [cite_start]5. Summary of How Complexity Affects Security [cite: 17]

Password complexity directly correlates with security. Each additional character and each new character type (uppercase, number, symbol) exponentially increases the total number of possible combinations an attacker would have to check. A short, simple password might have a few thousand possibilities, which can be cracked in seconds. A long, complex password can have trillions of possibilities, making it resistant to even the most powerful computers for years, as demonstrated by the "5 billion years" crack time estimate.
