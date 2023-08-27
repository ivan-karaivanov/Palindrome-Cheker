# Palindrome Checker

A simple JavaScript project that checks whether a given word is a palindrome or not.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Palindrome Checker is a small web application built with JavaScript that allows users to input a word and determine whether it is a palindrome. A palindrome is a word, phrase, number, or other sequence of characters that reads the same forward and backward (ignoring spaces, punctuation, and capitalization).

The project includes an HTML file, a CSS file for basic styling, and a JavaScript file for implementing the palindrome checking logic.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/ivan-karaivanov/palindrome-checker.git
   ```

2. Open the `index.html` file in a web browser.

3. Enter a word in the input field and click the "Check" button.

4. The result will be displayed below the input field, indicating whether the entered word is a palindrome or not.

## How It Works

The core logic of the palindrome checker is implemented in the JavaScript file (`script.js`). The script uses event listeners to respond to user input and trigger the palindrome checking function. The function does the following:

1. Retrieves the user-entered word from the input field.
2. Divides the word into two halves and compares them after converting both halves to lowercase.
3. Reverses the second half of the word and checks if it matches the first half.
4. Displays the result on the web page.

```javascript
const btn = document.querySelector(".btn");
const result = document.querySelector(".result");

btn.addEventListener("click", palindrome);

function palindrome() {
  // ... (etc...)
}
```

## Contributing

Contributions to this project are welcome. If you find any issues or have ideas for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
