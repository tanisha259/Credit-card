💳 Credit Card Validator (C++)

This is a simple command-line program written in C++ that uses the Luhn Algorithm to validate credit card numbers. The user is prompted to enter a credit card number, and the program determines whether it is valid or not based on the checksum logic.


---

📌 Overview

The Luhn Algorithm (also known as "modulus 10" or "mod 10") is a checksum formula used to validate identification numbers such as credit card numbers.

This project is designed for educational purposes and provides a basic demonstration of how the Luhn Algorithm works.


---

🧮 How the Luhn Algorithm Works

1. Starting from the rightmost digit (the check digit), move left and double every second digit.


2. If doubling a digit results in a two-digit number, add the digits of that number together.


3. Sum all the digits — both the modified and unmodified ones.


4. If the total sum is divisible by 10, the credit card number is valid.




---

🚀 Getting Started

🔧 Prerequisites

C++ compiler (e.g., g++)

Terminal or command-line interface


📥 Clone the Repository

git clone https://github.com/tanisha259/credit-card-validator.git
cd credit-card-validator

⚙️ Compile the Program

g++ main.cpp -o main

▶️ Run the Program

./main


---

📝 Usage

Once the program starts, you will see:

This program uses the Luhn Algorithm to validate a CC number.
You can enter 'exit' anytime to quit.
Please enter a CC number to validate:

Enter a credit card number to validate. Type exit to quit the program.


---

💡 Example Output

Please enter a CC number to validate: 4263982640269299
Valid!

Please enter a CC number to validate: 4983948596068655
Invalid!

Please enter a CC number to validate: 2223000048410010
Valid!

Please enter a CC number to validate: exit


---

📖 Program Explanation

The program prompts the user for input.

Input is validated to ensure it contains only numeric digits.

The Luhn Algorithm is applied to determine validity.

The result is displayed as:

Valid! if the number passes the Luhn check.

Invalid! if it does not.

