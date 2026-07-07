# Cyber Security Internship: Task 6 - Password Strength Evaluation

## Objective
To understand the principles of password security, evaluate the strength of various passwords using complexity metrics, and articulate best practices for secure authentication.

## Methodology
1. **Password Generation:** I generated three distinct sample passwords to represent varying levels of security (Weak, Medium, Strong/Passphrase).
2. **Evaluation:** I analyzed each password based on key entropy factors: length, character variety (uppercase, lowercase, numbers, symbols), and predictability.
3. **Attack Vector Analysis:** I researched how common attacks (like brute-forcing and dictionary attacks) would fare against each sample.
4. **Documentation:** I compiled the findings and established a set of best practices into an HTML report.

*(An HTML report detailing the specific passwords tested and their analysis is included in this directory).*

---

## Interview Questions & Conceptual Answers

**1. What makes a password strong?**
A strong password has high "entropy" (unpredictability). The primary factor is **length** (ideally 14+ characters). Secondary factors include **complexity** (using a mix of uppercase, lowercase, numbers, and special characters) and avoiding dictionary words, personal information, or predictable patterns (like "Password123!").

**2. What are common password attacks?**
*   **Brute-Force Attack:** An automated process that tries every possible combination of characters until the correct password is found.
*   **Dictionary Attack:** Uses a predefined list of common words, phrases, and previously leaked passwords.
*   **Credential Stuffing:** Trying usernames and passwords stolen from one data breach on other services (relying on password reuse).
*   **Phishing:** Tricking the user into providing their password voluntarily.

**3. Why is password length important?**
Length exponentially increases the number of possible combinations an attacker must guess in a brute-force attack. Every character added increases the computational time required to crack the password, making longer passwords significantly more secure than shorter, complex ones.

**4. What is a dictionary attack?**
A dictionary attack is a targeted cracking method that doesn't try every random combination (like brute-force) but instead systematically tries words from a "dictionary" list. These lists contain common words, phrases, names, and millions of passwords exposed in previous data breaches (like the "RockYou.txt" list).

**5. What is multi-factor authentication (MFA)?**
MFA is a security mechanism that requires the user to provide two or more different forms of evidence (factors) to verify their identity before granting access. It typically combines something you *know* (a password) with something you *have* (a smartphone authenticator app or hardware token) or something you *are* (biometrics like a fingerprint).

**6. How do password managers help?**
Password managers securely generate, store, and auto-fill complex, unique passwords for every service a user accesses. They eliminate the need for users to remember dozens of passwords or resort to insecure habits like password reuse or writing them down. They store the vault behind one strong "Master Password" and typically employ heavy encryption.

**7. What are passphrases?**
A passphrase is a sequence of words or text used as a password. They are often longer than traditional passwords (e.g., "CorrectHorseBatteryStaple"), making them highly resistant to brute-force attacks while remaining relatively easy for humans to remember.

**8. What are common mistakes in password creation?**
*   **Password Reuse:** Using the same password across multiple accounts. If one service is breached, all accounts are compromised.
*   **Predictable Substitutions:** Using "leet speak" (e.g., swapping 'a' for '@' or 's' for '$'). Cracking tools automatically check these variations.
*   **Personal Information:** Including names, birth years, or pet names that can be easily researched via social media.
*   **Keyboard Patterns:** Using sequential keys like "qwerty" or "123456".