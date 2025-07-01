# Passwords-Strength-evaluation
Understanding what makes a password strong and test it against password strength tools.
 **Password Strength Evaluation & Security Analysis**

This project demonstrates the process of generating, testing, and analyzing passwords of varying complexity to understand best practices for secure password creation and how complexity defends against common cyberattacks.

Objective

- Create multiple passwords with different complexity levels  
- Test each password using a strength checker tool  
- Record scores and feedback  
- Identify strong password practices  
- Research common password attacks  
- Summarize how complexity improves security

Tools Used

Password Strength Checkers:
[https://www.security.org/how-secure-is-my-password/](https://www.security.org/how-secure-is-my-password/) [https://password.kaspersky.com/](https://password.kaspersky.com/)
Browser Console / Ping Command: To test and generate user scenarios
Text Editor / Spreadsheet: To log results and feedback

Step-by-Step Process

1. Created Passwords with Varying Complexity

| Password          | Complexity  | Description 

| hello123          | Weak        | Lowercase + numbers 
| Hello123          | Medium      | Mixed case + numbers 
| H3ll0_123!        | Strong      | Mixed case + numbers + symbols 
| password          | Very Weak   | Common dictionary word 
| ABCD1234          | Weak        | Pattern-based, predictable 
| P@$$w0rd2025!     | Strong      | Leetspeak + numbers + symbols
| h!tM3h@rd!2025    | Strong      | Complex phrase with variation 
| J#7vG2@l!Xr9$QwP  | Very Strong | Random 16-character secure password 


2. Tested Each Password

Used the two online tools to check:
- Crack time (e.g., seconds, years, centuries)
- Overall strength level (Weak, Strong, Very Strong)
- Suggestions/feedback from the tool

3. Recorded Results

| Password         | Time to Crack | Feedback                          | Rating 

| hello123         | 3 seconds     | Too common                        | Weak 
| Hello123         | 3 minutes     | Better, but predictable           | Medium 
| H3ll0_123!       | 5 years       | Good complexity                   | Strong 
| password         | <1 second     | Very common                       | Very Weak 
| ABCD1234         | 5 seconds     | Easily guessable                  | Weak 
| P@$$w0rd2025!    | 24 years      | Strong, but resembles "password"  | Strong 
| h!tM3h@rd!2025   | 95 years      | Good variety and length           | Strong 
| J#7vG2@l!Xr9$QwP | Centuries     | Excellent randomness and strength | Very Strong 

Password Creation Best Practices (Learned from Tools)

- Use at least 12–16 characters
- Include uppercase, lowercase, numbers, and special symbols
- Avoid real words, patterns, or reused passwords
- Use random generators or password managers for maximum entropy
- Create passphrases using multiple unrelated words


Common Password Attacks

| Attack Type         | Description                               | Prevention 

| Brute Force         | Systematically tries all combinations     | Long, complex passwords 
| Dictionary Attack   | Uses known wordlists                      | Avoid real words   
| Credential Stuffing | Uses leaked credentials on multiple sites | Never reuse passwords 
| Phishing            | Tricking users to reveal passwords        | Be cautious + use 2FA 
| Keylogging          | Malware captures keystrokes               | Use antivirus & secure devices 


Summary: How Complexity Affects Security

- Simple passwords like password or 123456 can be cracked in seconds.
- Moderate passwords may last minutes to days under brute force.
- Strong passwords with length and randomness (e.g., J#7vG2@l!Xr9$QwP) can take centuries to crack.
- Complexity directly impacts resistance to brute force and dictionary attacks.
- Using unique and complex passwords for each account, combined with two-factor authentication, significantly enhances security.


Notes
Password strength tools give estimates — real-world cracking speed may vary.
One should avoid uploading actual passwords used on real accounts — always test with sample/dummy data.
Use a password manager (like Bitwarden, 1Password, or KeePass) to manage strong passwords securely.


