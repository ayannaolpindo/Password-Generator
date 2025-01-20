# Password-Generator### README for GeniPass: Secure Password Generator

#### Overview
GeniPass is a secure password generator designed to help users create strong, customizable passwords that protect sensitive information. With the increasing importance of cybersecurity, GeniPass allows users to generate passwords tailored to their specific needs, combining security and simplicity.

#### Features
- **Customizable Password Length**: Specify the desired length for your password, with a minimum of 8 characters to ensure strength.
- **Multiple Password Generation**: Generate one or more passwords at a time, depending on your requirements.
- **Character Customization**: Include a mix of uppercase letters, lowercase letters, numbers, and special characters to suit your security needs.
- **Randomized Selection**: Uses a random selection process to generate unique, hard-to-guess passwords.
- **User-Friendly Interface**: Clear prompts guide you through the process of password creation.

#### How It Works
1. **Start the Program**: Run the script to launch GeniPass.
2. **Input Specifications**:
   - Choose the desired password length.
   - Specify the number of passwords you need.
   - Select character types (uppercase, lowercase, numbers, symbols).
3. **Password Generation**:
   - GeniPass validates your inputs and generates passwords based on your preferences.
   - Randomized algorithms ensure strong and unpredictable passwords.
4. **Output**: The program prints the generated passwords.

#### Requirements
- Python 3.x
- `random` module (pre-installed in Python)

#### How to Run
1. Download the script `GeniPass.py`.
2. Open a terminal or command prompt.
3. Navigate to the directory containing `GeniPass.py`.
4. Run the script with the command:
   ```bash
   python GeniPass.py
   ```
5. Follow the on-screen prompts to generate your passwords.

#### Example Usage
```text
✧˖°.Welcome to GeniPass˚｡⋆୨୧˚
Problem solver for your indecisiveness and lack of creativity for passwords! ˶ᵔ ᵕ ᵔ˶

How long would you like your password to be? 12
How many passwords would you like? 2
What would you like in your password? 
Please choose at least 3 options: uppercase, lowercase, numbers, symbols (split by commas). 
uppercase, lowercase, numbers
Your new generated password is: G4yL9bTp2RxQ
Your new generated password is: M7vJnKpX3wYz
```

#### Key Functions
1. **`validating_length(length_of_pass)`**: Ensures the password length is valid and meets the minimum requirement.
2. **`validating_num_of_pass(number_of_pass)`**: Verifies that the number of passwords requested is a positive integer.
3. **`generate_password()`**: The main function that handles user input, validates preferences, and generates secure passwords.

#### Benefits
- **Improved Security**: Prevents weak and guessable passwords.
- **Convenience**: Quickly generates passwords tailored to your needs.
- **Flexibility**: Offers options for customization to suit different platforms and requirements.

#### Customization
Feel free to modify the script to add new features or customize the character sets for specific use cases.

#### Contact
For feedback or support, please reach out to the author of GeniPass.
