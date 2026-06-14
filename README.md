# 🔐 Password Strength Analyzer

A browser-based tool that evaluates the strength of user-entered passwords in real time.

##  Live Demo
 [Try it here](https://krishsingh06.github.io/password-strength-analyzer)

##  Features

-  Real-time password strength scoring (Very Weak → Very Strong)
-  Checks length, complexity, and common password patterns
-  Estimates crack time based on entropy calculation
-  Suggests 3 stronger password alternatives
-  Session history of recently tested passwords
-  One-click password generator
-  Show/hide & copy password buttons
-  Works offline — no backend, no data sent anywhere

##  Security Checks

| Check | Description |
|-------|-------------|
| Length | Minimum 8 and 12 characters |
| Uppercase | A–Z characters |
| Lowercase | a–z characters |
| Numbers | 0–9 digits |
| Symbols | !@#$%&* etc. |
| Common passwords | Checked against a dictionary |
| Repeated characters | e.g. `aaa`, `111` |
| Sequential patterns | e.g. `abc`, `123` |

## 🧮 How Entropy is Calculated

Entropy = length × log₂(character pool size)

Crack time = 2^entropy / 10,000,000,000 guesses per second
