# 🧠 C++ Style Guide

This repository contains a **personalized C++ coding style guide**, crafted to ensure clarity, consistency, and maintainability across all C++ projects.

Best C++ style in the world! ( for me )

## ✅ Summary

| Rule Type         | Style               |
|-------------------|---------------------|
| Indentation       | 4 spaces, no tabs   |
| Braces            | End-of-line (K&R)   |
| Encoding          | UTF-8               |
| Header guards     | `#pragma once`      |
| File extensions   | `.cpp` / `.h`       |

---

## 🧾 Naming Conventions

| Type               | Naming Style        | Example                          |
|--------------------|---------------------|----------------------------------|
| Variable           | `snake_case`        | `user_name`, `max_value`         |
| Function           | `snake_case`        | `get_score()`, `process_input()` |
| Class / Struct     | `PascalCase`        | `PlayerInfo`, `NetworkManager`   |
| Member Variable    | `_snake_case`       | `_name`, `_score`                |
| Constant           | `ALL_CAPS_SNAKE`    | `MAX_COUNT`, `PI`                |
| Macro              | `ALL_CAPS_SNAKE`    | `#define BUFFER_SIZE 1024`       |
| Enum Member        | `PascalCase`        | `Red`, `Green`, `Blue`           |
| Namespace          | `lowercase`         | `math`, `engine`, `graphics`     |

---

## 🛠 Format Automation

To automatically format your code according to this style, place the provided [.clang-format](https://github.com/shizuku-kamiya/cplusplus-style/blob/main/.clang-format) file at the root of your project. Compatible with:

- VS Code (`Clang-Format` extension)
- Clion / Qt Creator
- Command line: `clang-format -i your_file.cpp`

---

## 📁 Project Structure

```
project_name/
├── src/
├── include/
├── tests/
├── .../
├── CMakeLists.txt
├── README.md
└── ...
```

---

## 🛠 Suggested Tools

- `Visual Studio Code`
- `CMake`
- `Git`
- `C/C++ Extension Pack` ( vscode extension )
- `Clang-Format` ( vscode extension )

---

## 📄 License

This style guide is free to use and modify in any C++ projects.
