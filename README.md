
# Bingo Game - C++ Semester Project

Welcome to the Bingo Game project! This is a C++ console-based application developed for a semester project. It provides a fun and interactive Bingo game where users can log in, create accounts, and play multiple rounds of Bingo. This project highlights concepts like random number generation, file handling, and basic user authentication.

## Features

- **Login/Signup System**: Users can create an account or log in using an existing one.
- **Random Bingo Board Generation**: Each player gets a unique randomly generated 5x5 Bingo board.
- **File Handling**: User data (credentials and scores) are stored in files.
- **Cross-platform (Windows)**: While designed for Windows, with slight modifications it can run on other platforms.
- **User-friendly Menu**: Navigate through different options (e.g., start game, view scores) easily.
- **Real-time Number Drawing**: Numbers are drawn randomly and players can mark their boards in real-time.

## How to Install

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/bingo-game.git
    cd bingo-game
    ```

2. **Compile the code**:
    Make sure you have a C++ compiler installed. For Windows, use MinGW or Visual Studio. On Linux or macOS, you can use g++.

    ```bash
    g++ -o bingo main.cpp
    ```

3. **Run the executable**:

    ```bash
    ./bingo
    ```

## How to Play

1. **Start the game**: Run the program and choose between logging in or signing up.
2. **Generate your board**: Once logged in, a unique Bingo board will be generated for you.
3. **Mark numbers**: As numbers are drawn, mark them on your board.
4. **Winning**: The game will declare a winner once the conditions for a Bingo are met (5 in a row, column, or diagonal).

## Tech Stack

- **Language**: C++
- **Platform**: Windows (can be adapted for Linux/macOS)
- **Tools**: File handling, random number generation, basic I/O streams

## Future Improvements

- Adding a multiplayer mode to allow users to play against each other.
- Adding a graphical user interface (GUI) for better interaction.
- Extending to different Bingo variations (e.g., 75-ball Bingo, 90-ball Bingo).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to fork this project, submit issues, or make pull requests. All contributions are welcome!

### Contact

For any questions or feedback, you can reach me at [your.email@example.com].
