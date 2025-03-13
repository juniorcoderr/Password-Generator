# 🔐 Password Generator  

A simple password generator built using Python that allows users to create strong passwords based on their preferences. The program prompts users to specify the number of letters, symbols, and numbers they want in their password and generates a secure random password accordingly.  

## 🚀 Features  
✔️ Customizable password length  
✔️ Includes letters (uppercase & lowercase), numbers, and symbols  
✔️ Uses Python's `random` module for randomness  
✔️ Simple and easy-to-use command-line interface  

## 🛠️ Technologies Used  
- Python  
- Random module  

## 🎯 How It Works  
1️⃣ The user enters the number of letters, symbols, and numbers they want in the password.  
2️⃣ The program randomly selects characters from predefined lists.  
3️⃣ The generated password is displayed in the random sequence. 

## 📌 Usage  
Run the script and follow the on-screen prompts to generate a password.  

Feel free to contribute and enhance the functionality! 🚀💡  

## Explaination
Here's a breakdown of the key parts of the password generator code:

1. **Setup and Input**: We import the random module and set up three lists containing all possible letters, numbers, and symbols. Then we ask the user how many of each character type they want in their password.

2. **Character Selection**: We use three separate loops to randomly select the requested number of letters, symbols, and numbers from our predefined lists and add them to a password list.

3. **Randomization**: We use `random.shuffle(password)` to rearrange all characters in the password list into a random order, which improves security by avoiding predictable patterns.

4. **Output Formatting**: Finally, we convert the shuffled list into a string using `''.join(password)` and display the result to the user. The join method combines all elements in the list with no separator between them.
