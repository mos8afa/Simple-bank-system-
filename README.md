# Simple Bank System (C++ / OOP) 🏦💻

A console-based **Bank Management System** built with **C++** using **Object-Oriented Programming (OOP)** and a simple “screens” architecture (menu screens, transaction screens, user management screens, etc.). ✅

This project is designed as a learning-focused system that demonstrates:
- Clean separation between **models** (Client/User/Currency)
- **UI screens** (menus & workflows)
- **File-based persistence** (TXT files)

> Full project explanation, details, and walkthrough are organized inside the repository files.

---

## Features ✨

### Client Management 👤
- Add new clients
- Update client info
- Delete clients
- Find/search clients
- List clients
- View total balances

### Transactions 💳
- Deposit
- Withdraw
- Transfer between clients
- Transfer log / history

### User Management 🔐
- Login screen
- Login register (logging login activity)
- Add / update / delete / find users
- List users
- Manage users menu

### Currency Exchange 💱
- Currency list
- Find currency
- Currency calculator
- Update currency rate

---

## Project Structure 🧩

The repository is organized around:
- **Core entities (models)**: client, user, currency
- **Screens**: each feature is presented through a dedicated “screen” class
- **Data files**: stored as `.txt` files for simplicity

Common important files:
- `BankSystem.cpp` (entry point)
- `clsBankClient.h`, `clsUser.h`, `clsCurrency.h` (core models)
- `clsMainScreen.h` + multiple screen headers (feature UI)
- `Clients.txt`, `Users.txt`, `Currencies.txt`, `TransfersLog.txt`, `LoginRegister.txt` (data/log files)

---

## Data Storage 📁

This system uses plain text files for storage/logging:
- `Clients.txt` → client records
- `Users.txt` → system users
- `Currencies.txt` → currency rates/info
- `TransfersLog.txt` → transfer history
- `LoginRegister.txt` → login activity log

---

## How to Run ▶️

### Option A — Visual Studio (recommended on Windows) 🪟
1. Open the `.vcxproj` project file in Visual Studio.
2. Build in `Debug` or `Release`.
3. Run the project.

### Option B — Any C++ compiler ⚙️
If you prefer CLI compilers (g++/clang++), compile the project entry + required headers in your environment.

> Note: This repo is structured as a Visual Studio project, so Option A is the easiest.

---

## Future Improvements 🚀
- Replace TXT persistence with a database (SQLite, PostgreSQL, etc.)
- Add input validation + better error messages
- Add role-based permissions (Admin/Employee)
- Export logs to CSV/JSON

---

## License 📜
Educational/portfolio project.
