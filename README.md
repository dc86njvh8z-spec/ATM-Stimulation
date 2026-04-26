.
🏦 Library, ATM, and Games Suite
This repository contains a collection of three Python mini-projects designed for the Pre-Mock Evaluation. The projects are built using Package Architecture to ensure clean, modular, and maintainable code.
📁 Project Structure
To comply with the assignment instructions, the code is organized as follows:
text
.
├── atm_simulation/
│   ├── __init__.py
│   ├── logic.py       # Contains the ATM class (Logic)
│   └── main.py        # Contains the menu-driven system (UI)
├── mini_games/
│   ├── __init__.py
│   ├── games.py       # Game logic for RPS and Dice
│   └── main.py        # Game selection menu
└── library_system/
    ├── __init__.py
    ├── manager.py     # Dictionary-based management & Fine logic
    └── main.py        # Library interface
Use code with caution.
🚀 Features
1. ATM Simulation
Balance Display: Real-time tracking of funds.
Transaction Logging: A detailed statement history for every deposit and withdrawal.
Error Handling: Validates numerical inputs to prevent system crashes.
2. Mini Games
Stone-Paper-Scissors: Play against a randomized AI.
Dice Roll: A high-score game using the random module.
3. Library Management
Student Tracking: Records student names and issue durations.
Progressive Fines:
Week 1: ₹10/day
Week 2: ₹20/day
Week 3: ₹60/day
🛠️ Assignment Instructions Followed
Infinite Loops: All projects utilize while True for persistent menus.
Separation of Concerns: No business logic is written directly in the main.py files.
Clean Code: Meaningful variable names and structured print statements for better UX.
📥 How to Run
Clone the repo: git clone <your-repo-link>
Navigate to a project: cd atm_simulation
Execute
