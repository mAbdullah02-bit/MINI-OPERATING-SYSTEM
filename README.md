# 🖥️ Mini Operating System (C++)

Welcome to the **Mini Operating System**, a lightweight and educational OS simulation developed in **C++**.  
It’s packed with features like **multitasking**, basic **audio support**, fun **built-in games**, and a custom **command-line interface** — all designed to provide hands-on experience with core operating system concepts.

---

## 🚀 Features

- 🔄 **Multitasking**  
  Simulates concurrent process execution using scheduling algorithms (e.g., Round Robin, FCFS).

- 🗂️ **Virtual File System**  
  Create, delete, read, and manage files within a simulated file system environment.

- 🎮 **Built-in Games**  
  Enjoy simple terminal-based games like Tic-Tac-Toe and Snake to explore interactive programming.

- 🔊 **Audio Module**  
  Play beeps and tones (on compatible systems) to demonstrate sound handling.

- 🧠 **Memory Management**  
  Dynamic memory allocation and tracking using data structures.

- 🖥️ **Command-Line Interface**  
  User-friendly CLI with commands like `run`, `ls`, `clear`, `mem`, `games`, and more.

---

## 🛠️ Built With

- **C++** (Core logic)
- **Standard Template Library (STL)** for queues, stacks, etc.
- **Console I/O** (platform-dependent APIs for input/output and sound)
- Optional: **Windows API** or **ncurses** for UI enhancements

---

## 💻 How to Run

### 🔧 Requirements

- C++ Compiler  
  - **Linux**: `g++`  
  - **Windows**: `MinGW` or Visual Studio

### 🐧 On Linux

```bash
# Clone the repository
git clone https://github.com/mAbdullah02-bit/MINI-OPERATING-SYSTEM.git
cd MINI-OPERATING-SYSTEM

# Compile
g++ MiniOs.cpp src/*.cpp -o miniOS

# Run
./miniOS
