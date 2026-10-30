# 🔐 PyPassword Generator

A beginner Python password generator that creates random passwords using letters, numbers and symbols based on the user's preferences.

This project is part of **Angela Yu's 100 Days of Code: The Complete Python Pro Bootcamp**.

## 📌 About the Project

PyPassword Generator is a command-line program that allows users to generate customised random passwords.

The user specifies how many letters, symbols and numbers they want in their password.

The program then:
1. Randomly selects letters from a collection of uppercase and lowercase characters.
2. Randomly selects symbols and numbers.
3. Combines all the selected characters into a list.
4. Randomises their order using `random.sample()`.
5. Joins the characters into a single password string and displays the result.

## 🛠️ Technologies & Concepts Used

- **Python 3** – the programming language used.
- `random` module – for random character selection and shuffling.
- Lists – to store available characters and construct the password.
- `input()` – to collect the user's password preferences.
- `int()` – to convert user input into integers.
- `for` loops – to generate the requested number of characters.
- `range()` – to control how many times each loop runs.
- `random.choice()` – to select random characters.
- `random.sample()` – to randomise the order of the selected characters.
- `append()` – to add generated characters to the password list.
- `join()` – to combine individual characters into a single string.

## 📚 What I Learnt

Through this project, I practised several Python concepts:

1. **Lists** – storing collections of letters, numbers and symbols, as well as building the final password.
2. **User Input** – allowing users to customise their password by entering the desired number of characters.
3. **Type Conversion** – using `int()` to convert input strings into integers.
4. **For Loops** – repeating character selection according to the user's preferences.
5. **The `range()` Function** – generating the required number of loop iterations.
6. **Importing Modules** – importing Python's built-in `random` module.
7. **Random Selection** – using `random.choice()` to select individual characters.
8. **Random Sampling** – using `random.sample()` to produce a random ordering of the password characters.
9. **List Methods** – using `.append()` to add characters to a list.
10. **String Manipulation** – using `"".join()` to combine the generated characters into one password.

## ▶️ How to Run

1. Make sure Python 3 is installed.
2. Clone this repository or download the Python file.
3. Open the project in your preferred code editor or terminal.
4. Run the following command:

```bash
python main.py
```

5. Enter your preferred number of letters, symbols and numbers when prompted.
6. The program will generate and display a random password.

## 💻 Example

```text
Welcome to the PyPassword Generator!
How many letters would you like in your password?
4
How many symbols would you like?
2
How many numbers would you like?
3

a7#B2!k9
```

*Note: The generated password will vary each time the program runs.*

## 💡 Possible Improvements

As I continue learning Python, I could improve this project by:

- Adding input validation to prevent negative numbers or invalid entries.
- Allowing users to choose a password length instead of specifying each character type separately.
- Creating a graphical user interface (GUI).
- Adding an option to generate multiple passwords.
- Improving password security using Python's `secrets` module instead of `random`.
- Adding an option to copy the generated password.

## 🌱 Learning Journey

This project is part of Angela Yu's **100 Days of Code** bootcamp.

It helped me understand how Python lists, loops and randomisation can work together to create a functional program.

Compared to my earlier exercises, this project combines more concepts and introduces me to building programs that respond to user preferences.

I'm documenting each project, including smaller exercises, to track my progression from learning Python fundamentals to developing more complex applications.

*One project at a time!* 🐍
