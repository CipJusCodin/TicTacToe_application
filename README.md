# TicTacToe_mad_project

<div align="center">
  <img src="https://img.shields.io/badge/Java-8%2B-blue" alt="Java Version">
  <img src="https://img.shields.io/badge/Android%20Studio-MAD-green" alt="Android Studio (MAD)">
  <img src="https://img.shields.io/badge/Mobile-App-yellow" alt="Mobile App">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
</div>

<p align="center">
  <strong>Classic Tic-Tac-Toe game built as a Mobile Application Development project in Java</strong>
</p>

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Overview
TicTacToe_mad_project is a simple yet engaging implementation of the classic Tic-Tac-Toe game for Android devices. Developed as part of a Mobile Application Development (MAD) course, this project demonstrates fundamental Android concepts including UI design, event handling, and basic game logic in Java.

## Features
- Two Player Mode: Play locally against another player on the same device
- Simple and Intuitive UI: Easy-to-understand layout for quick games
- Win/Tie Detection: Automatic detection of wins, ties, and invalid moves
- Restart Option: Quickly reset the game for a new match
- Responsive Design: Optimized for various screen sizes

## Project Structure
```
TicTacToe_mad_project/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/
│   │   │   │       └── example/
│   │   │   │           └── tictactoe/
│   │   │   │               ├── MainActivity.java      # Main activity with game logic
│   │   │   │               └── ...                   # Additional Java files (if any)
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml             # UI layout for the main activity
│   │   │   │   └── drawable/                         # Game graphics and icons
│   │   │   └── AndroidManifest.xml                   # App manifest
├── README.md                                         # Project documentation
├── LICENSE                                           # Project license
└── ...                                               # Other configuration and gradle files
```

## Installation

### Prerequisites
- Java 8 or higher
- Android Studio

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/CipJusCodin/TicTacToe_mad_project.git
   cd TicTacToe_mad_project
   ```

2. Open the project in Android Studio:
    - Start Android Studio
    - Select **Open an existing project**
    - Navigate to the project directory and open it

3. Build and Run:
    - Connect your Android device or start an emulator
    - Click **Run** (▶) in Android Studio

## Usage
1. Launch the app on your Android device or emulator.
2. The main screen displays a 3x3 Tic-Tac-Toe grid.
3. Two players take turns tapping empty cells to place their symbol (X or O).
4. The game automatically detects a win or tie and displays the result.
5. Use the restart button to play another round.

## How It Works
- The game board is implemented as a 2D array.
- Player turns are tracked and alternated after each valid move.
- After every move, the app checks for winning combinations or a tie.
- The UI updates in real-time to reflect player moves and game state.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---
