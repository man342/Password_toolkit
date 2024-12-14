# Password Cracking and Protection Toolkit

Welcome to the **Password Cracking and Protection Toolkit**, a comprehensive project designed to explore and understand password vulnerabilities while promoting secure password practices. This interactive toolkit demonstrates password hashing, cracking techniques, encryption methods, and strong password policy enforcement.



 **Purpose of the Toolkit**

In today’s digital age, password security is critical for protecting sensitive information. However, weak passwords remain a significant vulnerability. This project was developed as both an educational tool and a hands-on resource for understanding:

- How passwords are hashed and stored securely.
- The risks of weak or predictable passwords.
- Modern encryption techniques for protecting sensitive data.
- The importance of strong password policies in enhancing security.

This toolkit is ideal for cybersecurity students, enthusiasts, and professionals who want to learn, practice, and demonstrate secure password management.



#**Features of the Toolkit**

The toolkit offers a wide range of functionalities, including:

# **1. Password Hashing**
Securely hash passwords using industry-standard algorithms such as SHA-256 and bcrypt. Verify the strength and validity of password hashes.

#### **2. Password Cracking**
Explore the risks of weak passwords by performing:

- **Brute Force Attacks**: Generate and test all possible combinations of passwords based on a character set.
- **Dictionary Attacks**: Use a predefined list of common passwords to identify vulnerabilities.

# **3. Password Policy Enforcement**
Generate strong and random passwords to meet modern security standards. This feature highlights the importance of complex, non-predictable passwords.

#**4. Encryption**
Learn and practice encryption techniques with:

- **AES Encryption**: Secure data with symmetric encryption.
- **RSA Encryption**: Protect data with public-private key encryption.

# **5. Interactive Interface**
A user-friendly and engaging interface enhanced with loading animations, emojis, and clear instructions, ensuring a fun and practical learning experience.

---

# **Getting Started**

# **Prerequisites**
To run this project, you need:
- Python 3.8 or higher
- Required libraries: Install dependencies using the command:
  ```bash
  pip install bcrypt cryptography
  ```

# **How to Run**
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run the main script:
   ```bash
   python3 main.py
   ```
4. Follow the on-screen menu to explore the toolkit's features.

---

# **Examples of Use**

1. **Hashing a Password**
   Enter a password, and the toolkit generates both SHA-256 and bcrypt hashes. Test verification to ensure hash validity.

2. **Brute Force a Password**
   Provide a hashed password, character set, and maximum length. Watch the toolkit attempt to crack the password step-by-step.

3. **Encrypt and Decrypt Data**
   Input sensitive data, and the toolkit demonstrates encryption using AES or RSA algorithms. The decrypted output ensures correctness.

4. **Generate Strong Passwords**
   Let the toolkit create a random, complex password, ensuring it adheres to modern security standards.


# **Future Enhancements**

This project will continue to evolve, with planned features including:
- Integration with databases for storing and retrieving hashed passwords.
- Multi-threading to optimize cracking performance.
- A graphical user interface (GUI) for easier interaction.


