# ai-snake

# AI Snake

AI Snake is a reinforcement learning-based implementation of the classic Snake game. The AI is trained to navigate and optimize its movements to achieve the highest possible score.

## Features

- **Deep Q-Learning**: Uses a neural network to learn optimal strategies.
- **PyTorch Implementation**: Built using PyTorch for efficient training.
- **Real-time Gameplay**: Watch the AI play and improve over time.
- **Customizable Parameters**: Adjust hyperparameters for training.

## Installation

### Prerequisites
Ensure you have Python installed (preferably Python 3.7 or later).

### Clone the Repository
```bash
git clone https://github.com/YashasSingh/ai-snake.git
cd ai-snake
```

### Install Dependencies


## Usage

### Train the AI
To start training the AI, run:
```bash
python train.py
```

### Play with AI
Run the following command to watch the AI play:
```bash
python play.py
```

## File Structure
- `train.py` - Trains the AI using reinforcement learning.
- `play.py` - Runs the trained AI to play the game.
- `model.py` - Contains the neural network architecture.
- `game.py` - Implements the Snake game mechanics.


## Future Improvements
- Implement different RL algorithms (e.g., PPO, A3C).
- Improve training efficiency with experience replay.
- Add a GUI interface for better visualization.

## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License. See `LICENSE` for details.
