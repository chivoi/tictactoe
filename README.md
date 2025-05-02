# Tic Tac Toe

<img height="250" alt="Screenshot 2025-05-02 at 12 18 07 pm" src="https://github.com/user-attachments/assets/866f16f2-0d7b-4191-baa0-dff902a72384" />
<img height="250" alt="Screenshot 2025-05-02 at 12 20 46 pm" src="https://github.com/user-attachments/assets/b68b63ec-c0d5-42dd-9864-8b0faa57b5ae" />

A Python implementation of the Tic Tac Toe game that includes classic game functionality and some experimental features.

## What it can do

### Game modes
- **Player vs Player**: Play against another human player, using CLI input.
- **Player vs Computer**: Challenge a (not very smart 🥹) AI opponent.
- **Computer vs Computer**: Watch two AI players compete, with friendly UI, allowing you to follow what's going on.

### Custom stuff
- **Board Size Selection**: Choose from standard or custom board sizes: 3x3, 4x4, 5x5 or your own custom size.
- **Custom Tokens**: Select unique tokens for each player.

### Enhanced CLI
- **Interactive Menus**: Intuitive and user-friendly CLI for seamless navigation.
- **Dynamic Feedback**: Real-time updates and prompts for player actions.
- **Clear Screen**: Keeps the interface clean and focused during gameplay.

### Smarter AI opponent experiments
`ana/smart-computer` branch includes the development of a smarter AI opponent using the Monte Carlo algorithm for the best move search. It's not quite made smart yet, the branch is still in development.

### Replayability
- **Replay Option**: Easily restart the game after a match.
- **Persistent Settings**: Retain board size and player preferences for consecutive games.

## How to install and play

1. Clone the app directory, cd into it
```bash
   git clone git@github.com:chivoi/tictactoe.git
   cd tictactoe
```

2. If you have Docker installed, you can run the app inside the Docker image:
```bash
    # build the image
   docker build . -t chivoi/tictactoe
    # run the app
   docker run  -it chivoi/tictactoe
   # Done 🎉
   ```

3. If you don't have Docker, do this:
   - Install Python as per [Python docs](https://wiki.python.org/moin/BeginnersGuide/Download)
   - Install pip as per [pip docs](https://pip.pypa.io/en/stable/installation/)
   - Install dependencies:
      ```bash
        pip install --no-cache-dir -r requirements.txt
      ```
   - Run the `main.py` script to start the game:
    ```bash
      python3 tictactoe/main.py
   ```
4. Follow the on-screen prompts to configure and play the game!

## What it looks like

https://github.com/user-attachments/assets/ac556da8-8b6b-45f6-88d6-4d3033d36b89
___
❌⭕ Built by Ana Lastoviria and Katie Louise Ross for Zendesk code club  ❌⭕
