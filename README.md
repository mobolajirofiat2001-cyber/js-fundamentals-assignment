# js-fundamentals-assignment

A small collection of beginner JavaScript exercises that demonstrate basic language features: variables, arithmetic, loops, and console output.

## Contents
- `challenge1.js` — Personal information (template literal)
- `challenge2.js` — Simple calculator (basic arithmetic)
- `challenge3.js` — Even-or-odd checker (loop + modulus)

## Prerequisites
- Node.js (recommended v14+). You only need Node to run these scripts in a terminal.

## Running the challenges
From the repository root, run:

```bash
# Run Challenge 1
node challenge1.js

# Run Challenge 2
node challenge2.js

# Run Challenge 3
node challenge3.js
```

Optional: add npm scripts for convenience:

```json
{
  "scripts": {
    "c1": "node challenge1.js",
    "c2": "node challenge2.js",
    "c3": "node challenge3.js"
  }
}
```

Then run with `npm run c1`, `npm run c2`, or `npm run c3`.

## Example outputs

Challenge 1 (example)
```
Hello! My name is Rofiat Mobolaji.
I am 24 years old.
My favorite programming language is JavaScript.
I am currently a student.
I am in my 4th year.
```

Challenge 2 (example)
```
Simple Calculator (num1 = 8, num2 = 3)
----------------------------------------
Addition:         8 + 3 = 11
Subtraction:      8 - 3 = 5
Multiplication:   8 * 3 = 24
Division:         8 / 3 = 2.6666666666666665
Modulus:          8 % 3 = 2
Exponentiation:   8 ** 3 = 512
```

Challenge 3 (example)
```
1 is odd
2 is even
3 is odd
...
20 is even

Summary:
Even numbers: 10
Odd numbers: 10
```

## Notes
- Comments such as `// Save this as challenge1.js and run with node challenge1.js` are optional. They are useful for newcomers but have no effect on program execution.
- These scripts are written to run with Node.js in a terminal. If you want to run them in a browser, include them in an HTML file with a `<script>` tag or bundle them.
- To make a JS file directly executable on Unix-like systems, add a shebang (`#!/usr/bin/env node`) at the top and `chmod +x filename.js`.

## Contributing
Feel free to open issues or submit pull requests to add more exercises, improve formatting, or add tests.

## License
MIT

