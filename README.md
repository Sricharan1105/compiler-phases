# 🖥️ Phases of a Compiler — Interactive Project

> An interactive web-based project that demonstrates all **6 phases of a compiler** using real C programs as input. Built for the **FJ3 Components** module.

---

## 🌐 Live Demo

🔗 [Click here to open the project](https://YOUR-USERNAME.github.io/compiler-phases/)

> *(Replace the link above with your actual GitHub Pages URL after deploying)*

---

## 📌 About the Project

This project visually explains how a **C compiler** processes source code step by step — from raw characters all the way to machine-level assembly instructions.

Each phase is interactive:
- **Load** any of the 14 sample C programs from the dropdown
- **Click a phase** in the pipeline bar to jump to it
- **Run This Phase** to see the output in table/tree format
- **Run All Phases** to see the complete compilation pipeline at once

---

## ⚙️ The 6 Compiler Phases

| # | Phase | Output Format | What it does |
|---|-------|--------------|--------------|
| 1 | **Lexical Analysis** | Token Table | Breaks source code into tokens (keywords, identifiers, operators, literals) |
| 2 | **Syntax Analysis** | Parse Tree (AST) | Builds an Abstract Syntax Tree showing hierarchical program structure |
| 3 | **Semantic Analysis** | Symbol Table | Checks types, scope, declarations — fills the symbol table |
| 4 | **Intermediate Code** | TAC Table | Converts AST to Three-Address Code (machine-independent IR) |
| 5 | **Code Optimization** | Optimization Table | Applies constant folding, dead code elimination, strength reduction |
| 6 | **Code Generation** | Assembly Table | Generates x86-style target assembly instructions |

---

## 📂 Sample Programs Included

All 14 programs from the **FJ3 PDF** are preloaded:

| # | Program |
|---|---------|
| 1 | Rectangle border pattern using `*` |
| 2 | Multiplication table (5×5) |
| 3 | Triangle pattern (1 2 3…) |
| 4 | Chessboard pattern (W / B) |
| 5 | Right triangle using `*` |
| 6 | Palindrome number check |
| 7 | While loop counter (1 to 5) |
| 8 | Sum of digits |
| 9 | Reverse of a number |
| 10 | Vowel / Consonant / Digit checker |
| 11 | Largest of three numbers |
| 12 | Grade system (marks → A/B/C/Fail) |
| 13 | Leap year check |
| 14 | Positive / Negative Even / Odd |

---

## 🚀 How to Run Locally (VS Code)

### Requirements
- [VS Code](https://code.visualstudio.com/)
- [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) by Ritwick Dey

### Steps

```bash
# 1. Clone this repository
git clone https://github.com/YOUR-USERNAME/compiler-phases.git

# 2. Open the folder in VS Code
cd compiler-phases
code .
```

3. Right-click on `compiler_phases.html` → **"Open with Live Server"**
4. Your browser opens at `http://127.0.0.1:5500/compiler_phases.html`

> **No installation needed** — you can also just double-click the `.html` file to open it directly in any browser.

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure and layout |
| CSS3 | Styling, colors, responsive design |
| Vanilla JavaScript | Lexer, parser, phase renderers |

No external libraries or frameworks — **100% pure HTML/CSS/JS**, works offline.

---

## 📸 Features

- ✅ **Interactive pipeline bar** — click any phase to jump to it
- ✅ **Visual parse tree** for Syntax Analysis with color-coded nodes
- ✅ **Table output** for all other 5 phases
- ✅ **14 preloaded sample programs** from the FJ3 syllabus
- ✅ **Run All Phases** — see the entire compilation flow at once
- ✅ **Color-coded tokens** — keywords, identifiers, operators, literals
- ✅ **Symbol table** with data type, scope, size, and init value
- ✅ **TAC (Three-Address Code)** intermediate representation
- ✅ **x86-style assembly** code generation
- ✅ Works in any modern browser — no internet required

---

## 📁 Project Structure

```
compiler-phases/
│
├── compiler_phases.html    # Main project file (all-in-one)
└── README.md               # This file
```

---

## 👨‍💻 Author

**Your Name**
- GitHub: [@YOUR-USERNAME](https://github.com/YOUR-USERNAME)

---

## 📄 License

This project is submitted as part of the **FJ3 Components** academic module.

---

> *"A compiler is a program that can read a program in one language and translate it into an equivalent program in another language."* — Alfred V. Ahor
