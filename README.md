# Password-Strength-Evaluation
A hands-on exploration of password complexity, strength scoring, and resistance to common attacks using tools like PasswordMeter and Bitwarden.


# Objective  

Evaluate password strength using online tools and understand how complexity impacts security. Test multiple passwords, analyze attack vectors, and identify best practices for creating secure passwords.

# Tools Used

1. PasswordMeter (https://www.passwordmeter.com/) – For scoring based on structural complexity  
2. Bitwarden Password Strength Checker (https://bitwarden.com/password-strength/) – For entropy and time-to-crack estimates  
3. GitHub – For report organization and documentation

# Passwords Evaluated 

1. sEek@1#MnC@8p - Score: 100, Estimated crack time- 9 years, Very Strong
2. Pass@78@#12 - Score: 100, Estimated crack time- 2 days, Strength: Strong
3. Ab@B1_66 - Score: 88, Estimated crack time- 3 hours, Strength: Strong
4. nIcE_GUY_1 - nIcE_GUY_1	73	4 days	Mixed case, underscore, number	Short length, lack of middle symbols	Moderate
5. 11234ab - Score: 48, Estimated crack time-	28 seconds, Strength: Very Weak

# Screenshots  

Contains screenshots of the test results from two websites- **PasswordMeter** and **Bitwarden**.

# Tips & Best Practices (What I Noticed)

  1. Mixing uppercase, lowercase, numbers, and symbols boosts password strength.

  2. Avoid sequences like 1234 or abcd—they're easy to crack.

  3. Placing symbols or digits in the middle is more secure than at the ends.

  4. Longer passwords often perform better than short, complex ones.

  5. Patterns like Ab@B1_66 may look strong but lack randomness and can be weak.

  6. Repeated characters or digits (like 66) reduce real-world strength.

  7. Different tools revealed different weaknesses—entropy matters as much as structure.

  8. Passphrases like River+Swan_Cactus9 were strong and memorable.

  9. Reusing or slightly changing passwords isn’t safe—variation is key.

  10. MFA adds essential protection if a password is compromised.

      
# Common Password Attacks

1. **Brute Force Attack**  
   Attempts every possible character combination. Short, simple passwords are especially vulnerable to this.

2. **Dictionary Attack**  
   Uses lists of common words and passwords to guess login credentials. Predictable or word-based passwords are at risk.

These methods highlight the need for length, randomness, and character diversity when creating secure passwords.

# Conclusion  

Password complexity through length, variety, and unpredictability significantly increases resistance to brute-force and dictionary attacks, making passwords stronger both structurally and practically.
