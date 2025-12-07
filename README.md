---

# **Pacmn – A C++ EnTT + SDL2 Pac-Man Clone**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

A lightweight Pac-Man style game built in **C++**, using the **EnTT ECS framework** and **SDL2**.
Developed and tested on **Zorin OS (Linux)**.

![Screenshot](https://i.imgur.com/J5RDcIz.png)

---

## **About This Project**

I created **Pacmn** to understand how game logic works internally and to prepare myself for future **AI/ML-based game projects**.
The project helped me learn:

* How **Entity-Component-System (ECS)** architecture works using EnTT
* How to structure a full game loop
* How to manage rendering, movement logic, and collision systems
* How to work with SDL2 on Linux

This is my personal version of Pac-Man — not an exact remake — built from scratch for learning and experimentation.

---

## **My Profiles**

🔗 **LinkedIn:** [https://www.linkedin.com/in/ayman-shaikh-53306b206](https://www.linkedin.com/in/ayman-shaikh-53306b206)
🔗 **GitHub:** [https://github.com/aymnsk](https://github.com/aymnsk)

---

## **How to Install & Run on Your PC**

### **1. Install SDL2**

#### Linux (Ubuntu / Zorin / Debian)

```bash
sudo apt update
sudo apt install libsdl2-dev
```

#### MacOS

```bash
brew install sdl2
```

#### Windows (vcpkg)

```bash
vcpkg install sdl2
```

---

### **2. Clone the Repository**

```bash
git clone https://github.com/aymnsk/pacmn.git
cd pacmn
```

---

### **3. Build the Game**

```bash
mkdir build
cd build
cmake -DCMAKE_BUILD_TYPE=Release ..
cmake --build .
```

---

### **4. Run the Game**

```bash
./pacmn
```

---

## **Notes**

* This is my own custom version, simplified intentionally to understand ECS logic.
* The gameplay logic is inspired by the Pac-Man Dossier, but not identical.
* Built completely on **Zorin OS**, using **CMake**, **C++**, **SDL2**, and **EnTT**.

---

Just say **“yes”**.
