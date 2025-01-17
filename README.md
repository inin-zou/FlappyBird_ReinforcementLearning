# FLAPPYBIRD_ReinforcementLearning

This project uses [NEAT-Python](https://github.com/CodeReclaimers/neat-python) to train an AI agent to play Flappy Bird. It includes:

1. **Flappy Bird Game Mechanics**: Uses Pygame, featuring pipe movement, collision detection, scoring, etc.  
2. **Reinforcement Learning**: Uses the NEAT algorithm to evolve network structures and weights so that the “bird” learns to avoid pipes over time.

## Project Structure
```
FLAPPYBIRD_REINFORCELEARNING 
├── imgs/ # Image assets for the game 
├── .gitpod.yml # Gitpod configuration file 
├── .replit # Replit configuration file 
├── best.pickle # Stores the best genome from training 
├── config-feedforward.txt # NEAT configuration file 
├── flappy_bird.py # Main game logic and training script 
├── README.md # Project documentation 
├── requirements.txt # Python dependencies 
└── visualize.py # Visualizations for the NEAT process and results
```

# To play:
Run *flappy_bird.py* and watch AI start training itself to play the game of FlappyBird!
