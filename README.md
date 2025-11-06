# Snake.ioo

A classic Snake game implementation built with Python. Guide the snake to eat food, grow longer, and achieve the highest score while avoiding collisions with walls and yourself.

## Features

- **Classic Gameplay**: Experience the timeless Snake game mechanics
- **Interactive Controls**: Use arrow keys or WASD to navigate the snake
- **Score Tracking**: Keep track of your current score as you play
- **Simple Graphics**: Clean, minimalist game interface
- **Game Over Detection**: Collision detection with walls and self

## Requirements

- Python 3.6 or higher
- No external dependencies required (uses standard library modules)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/nikunj555/Snake.ioo.git
cd Snake.ioo
```

2. Ensure you have Python 3.6+ installed:
```bash
python --version
```

## Usage

Run the game with:
```bash
python main.py
```

Or run the main script directly from the repository root directory.

### Game Controls

- **Arrow Keys** or **WASD**: Move the snake up, down, left, and right
- **Q** or **ESC**: Quit the game
- **Space**: Pause/Resume (if implemented)

## How to Play

1. Start the game by running the script
2. Control the snake to eat the food (usually represented by a colored block)
3. Each food consumed increases your score and grows the snake
4. Avoid hitting the walls and the snake's own body
5. The game ends when a collision occurs
6. Try to achieve the highest score possible!

## Project Structure

```
Snake.ioo/
├── main.py              # Main game file
├── README.md            # This file
└── [other source files] # Supporting modules (if any)
```

## Game Mechanics

- **Movement**: The snake moves continuously in the last direction commanded
- **Growth**: The snake grows by one segment each time it eats food
- **Collision**: The game ends if the snake hits a wall or collides with itself
- **Scoring**: Each piece of food consumed increases the score

## Future Enhancements

Potential features for future versions:
- Difficulty levels (easy, medium, hard)
- Speed increase as score grows
- Multiple game modes
- High score persistence
- Sound effects and music
- Graphical improvements with custom sprites

## Contributing

Contributions are welcome! Feel free to:
- Fork the repository
- Create a feature branch
- Submit pull requests
- Report bugs and suggest improvements

## License

This project is open source and available under the MIT License. Feel free to use, modify, and distribute as per the license terms.

## Author

Created by [nikunj555](https://github.com/nikunj555)

## Support

If you encounter any issues or have questions about the project, please open an issue on the GitHub repository.

---

**Enjoy the game and happy coding! 🐍**
