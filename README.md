
---

# Password Strength Checker

This Python script checks the strength of a password based on several common criteria, including length, uppercase and lowercase letters, digits, and special characters. The script provides feedback on whether the password meets each criterion and rates its overall strength as "Very Weak," "Weak," "Moderate," or "Strong."


## Introduction

Password security is a critical aspect of online safety. This script helps users assess the strength of their passwords by checking if they meet essential security criteria. By providing feedback on these criteria, the script encourages users to create stronger, more secure passwords.

## Features

- **Length Check:** Ensures that the password is at least 8 characters long.
- **Uppercase Letter Check:** Verifies that the password contains at least one uppercase letter.
- **Lowercase Letter Check:** Verifies that the password contains at least one lowercase letter.
- **Digit Check:** Checks if the password includes at least one numeric digit.
- **Special Character Check:** Ensures that the password contains at least one special character (e.g., `!@#$%^&*()`).
- **Strength Rating:** Rates the password as "Very Weak," "Weak," "Moderate," or "Strong" based on how many criteria it meets.

## Prerequisites

To run this script, you'll need:

- Python 3.x installed on your machine.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/password-strength-checker.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Prodigy-infoTech_cs_intern_03
   ```

3. No additional libraries are required as this script uses only Python's standard libraries.

## Usage

1. Run the script using Python:

   ```bash
   python password_strength_checker.py
   ```

2. The script will prompt you to enter the password you want to check:

   - **Enter a password**: Type the password you want to assess.

3. The script will then provide feedback on whether the password meets each criterion and display an overall strength rating.

### Example:

```bash
Enter a password to check its strength: P@ssw0rd!

Password Strength Feedback:
Length Criteria Met: Yes
Uppercase Criteria Met: Yes
Lowercase Criteria Met: Yes
Digit Criteria Met: Yes
Special Character Criteria Met: Yes
Strength: Strong
```

In this example, the password "P@ssw0rd!" meets all the criteria, and the script rates it as "Strong."

## Functions Overview

- **check_password_strength(password):**
  - **Description:** Checks the password against predefined criteria and returns a dictionary with the results.
  - **Arguments:**
    - `password`: The password to be checked.
  - **Returns:** A dictionary with boolean values for each criterion and the overall strength rating.

## File Structure

```bash
.
├── password_strength_checker.py   # Main script for password strength checking
└── README.md                      # This README file
```


---

### Notes:
- Replace `"https://github.com/your-username/password-strength-checker.git"` with your actual GitHub repository URL.
- If you decide to include any test cases or additional features, update the README accordingly.
