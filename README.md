# 🚀 RawLang — Custom Programming Language & VS Code Support

<p align="center">
  <img src="icons/rawlang.png" width="140" />
</p>

---

## ✨ Overview

**RawLang** is a custom-built programming language designed from scratch with its own interpreter, CLI, and now full **VS Code integration**.

This extension provides:

* 🎨 Syntax Highlighting
* 🧩 Custom File Icons (`.raw`)
* 📄 Language Recognition
* ⚡ Developer-friendly experience

---

## 📦 Features

### 🟢 Language Support

* Recognizes `.raw` files
* Custom language configuration

### 🎨 Syntax Highlighting

* Keywords: `if`, `else`, `while`, `for`, `func`, `return`
* Built-ins: `out`, `in`
* Strings, numbers, variables

### 🧩 File Icons

* Custom RawLang icon for `.raw` files
* Clean and modern branding

---

## ⚙️ Installation

### From VS Code Marketplace

1. Open **Extensions** (`Ctrl + Shift + X`)
2. Search: `RawLang Support`
3. Click **Install**

---

## 🎯 Enable File Icons (IMPORTANT)

After installation:

1. Press `Ctrl + Shift + P`
2. Search: **File Icon Theme**
3. Select: **RawLang Icons**

👉 This step is required to see `.raw` file icons

---

## 🧪 Example RawLang Code

```raw
func add(a,b){
    return a + b
}

x = in

if x > 5 {
    out(add(x,10))
}
else {
    out("Value too small")
}
```

---

## 🚀 Running RawLang

Make sure you have the RawLang CLI installed.

```bash
rawlang program.raw
```

---

## 🏗️ Project Structure

```
rawlang/
│
├── lexer.py
├── parser.py
├── interpreter.py
├── ast_nodes.py
├── rawlang.py
│
├── icons/
├── syntaxes/
└── package.json
```

---

## 🧠 Built With

* Python (Interpreter)
* VS Code Extension API
* TextMate Grammar

---

## 🌍 Vision

RawLang aims to become:

* A beginner-friendly scripting language
* A fully featured developer tool
* A complete ecosystem (CLI + IDE + OS integration)

---

## 🤝 Contributing

Contributions, ideas, and improvements are welcome!

---

## 👨‍💻 Author

**Tejwardeep Singh**

* GitHub: https://github.com/Tejwardeep-Singh
* LinkedIn: https://www.linkedin.com/in/tejwardeep-singh/

---

## ⭐ Support

If you like this project:

👉 Star the repository
👉 Share with others
👉 Try building something in RawLang

---

## 🔥 Future Plans

* Auto-completion
* Error highlighting
* Debugging support
* Package manager

---

<p align="center">
  ⚡ Built with passion — RawLang ⚡
</p>
