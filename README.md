
# Oxygen Programming Language

**Version 0.4 — Created by Saad Arshad**  
*A lightweight scripting language that breathes life into your code.*

---

## 🚀 Introduction

**Oxygen** is an experimental programming language with simple syntax that compiles directly to C++. It is a modernised version of C++ . Designed for rapid prototyping and learning, it offers a clean, minimal style:
q
```oxygen
#include <fstream>
#include <iostream>
using namespace std;


@cpp {
//Oxygen is invalid here , Cpp block is passed untouched to C++ Source File for Ultra Low Level Coding
cout << "Hello , C++2" ;

}


@cpp {
//Oxygen is invalid here , C++ only
cout << "Hello , Cpp block 2 " ;

}

Start() {
     
    Print "\n Oxygen Programming Language \n \n A Modernized Version of C++ \n"
    Print " Currently in Development \n"
    Print "Version 0.2 \n" 
    Print "Created by Saad Arshad \n"


   //i haven't added support for variables yet so this will not work simply remove this match before compiling
match ('A') {
    'A' => Print "Excellent!"
    'B' => Print "Good!"
    default => Print "Needs improvement."
}
  

@cpp {
//Oxygen is invalid here , C++ only
cout << "Hello , C++" ;

}


}

```
**Output of Above Oxygen Code**
```
#include <fstream>
#include <iostream>
using namespace std;

void oxy_cpp_block_1() {

//Oxygen is invalid here , C++ only
cout << "Hello , C++2" ;


}

void oxy_cpp_block_2() {

//Oxygen is invalid here , C++ only
cout << "Hello , Cpp block 2 " ;


}



void oxy_cpp_block_3() { 

//Oxygen is invalid here , C++ only
cout << "Hello , C++" ;


}

int main() {

    oxy_cpp_block_1();
    oxy_cpp_block_2(); //Cpp blocks are automatically called when compiled
    oxy_cpp_block_3();

    cout << "\n Oxygen Programming Language \n \n A Modernized Version of C++ \n" << endl;
    cout << " Currently in Development \n" << endl;
    cout << "Version 0.2 \n" << endl;
    cout << "Created by Saad Arshad \n" << endl;


//switch does not work currently as of compilation issues

   switch (A) {
        case A:
    cout << "Excellent!" << endl;
            break;
        case B:
    cout << "Good!" << endl;
            break;
        default:
    cout << "Needs improvement." << endl;
            break;
    }
    return 0;
}

```

Run it, convert it, compile it. Oxygen handles the rest.



----

📦 Current Version

Language: Oxygen

Version: 0.4

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

**1. Create an Oxygen script (e.g., hello.oxy)**

```
#include <iostream>
using namespace std;

Start() {
    Print "Hello, Oxygen!"
}
```

**2. Transpile to C++**
   
   Open Terminal in download folder and Type
```
./compiler.exe hello.ox output.cpp

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

[x] Basic syntax: Start() , Print and Cpp Blocks

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
