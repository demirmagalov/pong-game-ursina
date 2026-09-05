# Pong Game with Ursina

A classic Pong game where you play against an AI opponent, built with Python and Ursina.

## What It Does

Control your paddle to hit the ball back and forth. Play against a bot that automatically tracks and returns the ball. First to reach a score limit wins!

## Requirements

- Python 3.8+
- Ursina (`pip install ursina`)

## How to Run

```bash
pip install ursina
python pong.py
```

## Controls

- **W** — Move paddle up
- **S** — Move paddle down

## What I Learned

- Game physics (velocity, collision response, ball bouncing)
- AI opponent behavior (tracking ball position, automatic paddle movement)
- Score tracking and game state management
- Paddle and ball collision detection
- Using Ursina for real-time game rendering

## How It Works

The game loop runs continuously. Each frame:
1. Update player paddle position based on input
2. Move the AI paddle to track the ball
3. Update ball position and velocity
4. Check for paddle and wall collisions
5. Update scores if ball passes a paddle
6. Render the scene
