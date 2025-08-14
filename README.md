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

## Project Structure

```
Advanced-Tic-Tac-Toe-Game/
├── aiAlgorithm.cpp/.h         # AI logic
├── boardPage.cpp              # Game board UI
├── databasemanager.cpp/.h     # SQLite database management
├── game.cpp/.h                # Game logic
├── mainwindow.cpp/.h/.ui      # Main application window
├── player.cpp/.h              # Player logic
├── session.cpp/.h             # User session management
├── ...                        # Other UI and logic files
├── aitest/                    # AI unit tests
├── database_test/             # Database unit tests
├── gametest/                  # Game logic tests
├── executableApp/             # Compiled app and dependencies
├── pictures/                  # Image assets
├── README.md                  # Project documentation
├── TIC_TAC_TOE_CPP_QT_SQLITE.pro # Qt project file
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

![Main Window](pictures/bg3.png)

## Documentation
- **SRS.pdf**: Software Requirements Specification
- **SDS.pdf**: Software Design Specification
- **Testing Documentation.pdf**: Test plans and results

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.


