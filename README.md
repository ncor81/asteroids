# Asteroids

A Python clone of the classic Asteroids arcade game, built with Pygame.

## Gameplay

Pilot your spaceship through an endless asteroid field. Shoot asteroids to split them into smaller pieces, and avoid getting hit. The game ends when an asteroid collides with your ship.

## Features

- Asteroids that split into smaller pieces when shot
- Smooth player movement with forward/backward thrust and rotation
- Shoot with a 0.3 second cooldown between shots
- Continuous asteroid spawning
- Collision detection between player, shots, and asteroids
- Event logging via a built-in logger

## Controls

| Key | Action |
|-----|--------|
| `W` | Thrust forward |
| `S` | Thrust backward |
| `A` | Rotate left |
| `D` | Rotate right |
| `Space` | Shoot |

## Requirements

- Python 3.13+
- pygame 2.6.1

## Installation

Clone the repository and install dependencies using `uv`:

```bash
git clone https://github.com/ncor81/asteroids.git
cd asteroids
uv sync
```

Or with pip:

```bash
pip install pygame==2.6.1
```

## Running the Game

```bash
python main.py
```

## Project Structure

| File | Description |
|------|-------------|
| `main.py` | Game loop and entry point |
| `player.py` | Player ship logic and controls |
| `asteroid.py` | Asteroid behavior and splitting logic |
| `asteroidfield.py` | Asteroid spawning system |
| `shot.py` | Projectile logic |
| `circleshape.py` | Base class for circular game objects |
| `constants.py` | Game configuration values |
| `logger.py` | Event and state logging |
