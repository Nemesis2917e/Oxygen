
# Oxygen Programming Language

**Version 0.1 — Created by Saad Arshad**  
*A lightweight scripting language that breathes life into your code.*

---

## 🚀 Introduction

**Oxygen** is an experimental programming language with simple syntax that compiles directly to C++. It is a modernised version of C++ . Designed for rapid prototyping and learning, it offers a clean, minimal style:
q
```oxygen
#include <iostream>
using namespace std;

Start() {
    Print "Hello, Oxygen!"
}

```

Run it, convert it, compile it. Oxygen handles the rest.

----

📦 Current Version

Language: Oxygen

Version: 0.1

Author: Saad Arshad

Status: Early Development

License: MIT
---

🔧 Setup & Installation

1. Clone the repository

git clone https://github.com/Nemesis2917e/Oxygen.git
cd Oxygen


3. You should now have:
A main.exe executable in your build directory.




---

▶️ Running Your First Oxygen Script

**1. Create an Oxygen script (e.g., hello.ox)**

```
Start() {
    Print "Hello, Oxygen!";
}
```

**2. Transpile to C++**
   
   Open Terminal in download folder and Type
```
./main.exe hello.ox output.cpp

```

**3. Compile the C++ output**
```
g++ -o output.exe output.cpp

```

**4. Run the executable**
```
./output.exe
```

# Output: Hello, Oxygen!




---

🧠 Language Overview

Feature	Syntax Example	with Output in C++

Entry Point	Start() { … }	to int main() { … }
Print	 "Hello!" to 	std::cout << "Hello!" << '\n';
Comments	// this is a comment	C++-style comment


> More features (like variables, control flow, and expressions) are coming soon!




---

🗺️ Roadmap

[x] Basic syntax: Start() and Print

[ ] Variables & data types

[ ] Arithmetic expressions

[ ] If/else, loops

[ ] Functions and modularization

[ ] Error handling & diagnostics

[ ] Linux/macOS support



---

🤝 Contributing

Pull requests are welcome! Here's how to get started:

1. Fork the repo


2. Create a new branch

git checkout -b feature/my-feature


3. Make changes and commit

git commit -am "Add feature"


4. Push to your fork

git push origin feature/my-feature


5. Open a Pull Request



Please keep your contributions respectful and aligned with the spirit of the project.


---

📄 License

This project is licensed under the MIT License.
See LICENSE for details.


---

👨‍💻 About the Author

Saad Arshad — Creator of the Oxygen Programming Language

> Bringing fresh air to C++ with simplicity and innovation.




---

💬 Final Notes

Oxygen is still in its infancy — but it’s growing fast.
If you're interested in contributing, testing, or just experimenting with a new syntax, this is the perfect time to get involved.
