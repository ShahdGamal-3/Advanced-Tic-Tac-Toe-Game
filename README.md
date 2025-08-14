# Advanced Tic-Tac-Toe Game (C++/Qt/SQLite)

A feature-rich, modern Tic-Tac-Toe game built with C++, Qt, and SQLite. This project demonstrates advanced GUI design, AI algorithms, user authentication, and persistent data storage.

## Features

- **Modern Qt GUI**: Intuitive, responsive, and visually appealing interface.
- **AI Opponent**: Play against a smart AI with adjustable difficulty.
- **User Authentication**: Sign up, sign in, change username/password.
- **Game History**: Track and review previous games.
- **Profile Management**: View and edit user profiles.
- **Persistent Storage**: All data stored securely in SQLite database.
- **Testing**: Includes unit and integration tests for core components.


## Professional Project Hierarchy

```
TIC_TAC_TOE_CPP_QT_SQLITE/
│
├── src/                        # All main source code
│   ├── core/                   # Core game logic
│   │   ├── game.cpp/.h
│   │   ├── player.cpp/.h
│   │   ├── aiAlgorithm.cpp/.h
│   │   └── session.cpp/.h
│   ├── ui/                     # UI components and pages
│   │   ├── mainwindow.cpp/.h/.ui
│   │   ├── boardPage.cpp
│   │   ├── aiPage.cpp
│   │   ├── gamesPage.cpp
│   │   ├── profilePage.cpp
│   │   ├── signinPage.cpp
│   │   ├── signupPage.cpp
│   │   ├── changepasswordPage.cpp
│   │   ├── changeusernamePage.cpp
│   │   ├── sessionsPage.cpp
│   │   └── ...
│   ├── db/                     # Database management
│   │   ├── databasemanager.cpp/.h
│   │   └── database.db
│   └── resources/              # Qt resources
│       └── resources.qrc
│
├── tests/                      # All test projects
│   ├── aitest/
│   ├── database_test/
│   ├── gametest/
│   ├── QtTest/
│   └── QtTest2/
│
├── assets/                     # Images and other static files
│   ├── TicTacToe_Game.png
│   ├── bg3.png
│   └── ...
│
├── docs/                       # Documentation
│   ├── SRS.pdf
│   ├── SDS.pdf
│   ├── Testing Documentation.pdf
│   └── README.md
│
├── build/                      # Build output (ignored in VCS)
│
├── TIC_TAC_TOE_CPP_QT_SQLITE.pro
└── main.cpp                    # Entry point (can also be in src/ if preferred)
```

## Getting Started

### Prerequisites
- **Qt 6.x** (with Qt Creator recommended)
- **C++17** or later
- **SQLite3**
- **CMake** or **qmake**

### Build & Run
1. **Clone the repository:**
   ```sh
   git clone https://github.com/salah0eldin/TIC_TAC_TOE_CPP_QT_SQLITE.git
   ```
2. **Open the project in Qt Creator** or run:
   ```sh
   cd Advanced-Tic-Tac-Toe-Game
   qmake TIC_TAC_TOE_CPP_QT_SQLITE.pro
   make
   ./executableApp/MyTIC_TAC_TOE_CPP_QT_SQLITE.exe
   ```

### Running Tests
- Open the test projects (`aitest`, `database_test`, `gametest`, etc.) in Qt Creator and run tests.

## Screenshots

![Main Window](pictures/TicTacToe_Game.png)

## Documentation
- **SRS.pdf**: Software Requirements Specification
- **SDS.pdf**: Software Design Specification
- **Testing Documentation.pdf**: Test plans and results

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.


