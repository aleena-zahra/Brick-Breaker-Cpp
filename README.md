# Brick-Breaker-Cpp
Welcome to the Brick Breaker Game! This game is a modern take on the classic arcade game where players control a paddle to bounce a ball and break bricks. The game includes various power-ups and different types of bricks, making it an exciting and challenging experience.

## Table of Contents

- [Screenshots](#screenshots)
- [Features](#features)
- [Installation](#installation)
- [Gameplay](#gameplay)
- [Classes and Structure](#classes-and-structure)
- [Power-ups](#power-ups)
- [Bricks](#bricks)
- [Contributing](#contributing)
- [License](#license)

## Level 1
![Screenshot from 2024-06-08 10-42-01](https://github.com/aleena-zahra/Brick-Breaker-Cpp/assets/155615101/593887d7-4b5f-4d7d-b1be-984b7bf84ad7)
## Level 2
![Screenshot from 2024-06-08 10-42-11](https://github.com/aleena-zahra/Brick-Breaker-Cpp/assets/155615101/954156a1-b9ef-46d7-87b8-b5e30498ecac)
## Level 3
![Screenshot from 2024-06-08 10-41-26](https://github.com/aleena-zahra/Brick-Breaker-Cpp/assets/155615101/ec215585-3b95-48bd-960a-6b638eac0d7f)
## Powerups and changing ball and paddle color
![Screenshot from 2024-06-08 10-46-08](https://github.com/aleena-zahra/Brick-Breaker-Cpp/assets/155615101/07c08740-24e9-44be-82d5-d448b0aba43f)


## Features
- Classic brick-breaking gameplay with modern graphics.
- Multiple power-ups that can double the paddle size, halve the paddle size, double the ball speed, halve the ball speed.
- Different types of bricks, each with unique properties and power-ups.
- Player lives and score tracking.
- Dynamic paddle and ball physics.

## Installation
To get the game up and running, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/aleena-zahra/Brick-Breaker-Cpp.git
    cd Brick-Breaker-Cpp
    ```

2. **Install dependencies:**
    Ensure you have a C++ compiler and the necessary graphics libraries installed. This game uses a custom graphics library (`util.h`), along with Glut Library
   ```sh
   sudo apt install freeglut3 freeglut3-dev
   sudo apt install build-essential libx11-dev libxmu-dev libxi-dev libglu1-mesa libglu1-mesa-dev
   ```

4. **Compile the game:**
    ```sh
    make
    ```

5. **Run the game:**
    ```sh
    ./game
    ```

## Gameplay
- Use the mouse to move the paddle left and right.
- Bounce the ball off the paddle to hit and break bricks.
- Collect power-ups that fall from broken bricks.
- Try to break all the bricks to advance to the next level.
- Keep an eye on your lives and score.

## Classes and Structure
The game is organized into several classes, each handling different aspects of the game:

- **Score**: Manages the player's score.
- **Lives**: Manages the player's lives.
- **Paddle**: Controls the paddle's properties and movement.
- **Player**: Combines the paddle, score, and lives into a single entity.
- **Ball**: Manages the ball's properties and movement.
- **Powerup**: Base class for various power-ups.
- **Brick**: Base class for different types of bricks, with inherited classes for specific brick behaviors.

## Power-ups
The game includes several power-ups, each with unique effects:
- **PowerupGreen**: Doubles the size of the paddle.
- **PowerupPink**: Halves the size of the paddle.
- **PowerupBlue**: Halves the speed of the ball.
- **PowerupRed**: Doubles the speed of the ball.
- **PowerupYellow**: Adds additional balls (planned feature).

## Bricks
Different types of bricks are included in the game, each with unique properties:
- **PinkBrick**: Requires two hits to break, contains a pink power-up.
- **YellowBrick**: Requires two hits to break, contains a yellow power-up.
- **RedBrick**: Requires three hits to break, contains a red power-up.
- **BlueBrick**: Requires three hits to break, contains a blue power-up.

## Contributing
Contributions to enhance the game are welcome! To contribute:
1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Enjoy playing the Breakout Game! If you have any questions or feedback, feel free to open an issue on the repository.

