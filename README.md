# Space Combat Game with Pygame

Welcome to the Space Combat Game created using Pygame! In this game, players control two spaceships (Red and Yellow) and engage in aerial combat. The objective is to reduce your opponent's health by shooting bullets. The last spaceship flying wins!

## Features

- **Spaceships**: The game features two spaceships, Yellow and Red. Each can move in four directions (up, down, left, right) within the game screen.
- **Bullets**: Players can shoot bullets to reduce the opponent's health. There's a maximum number of bullets allowed on screen at a time.
- **Sound Effects**: Enjoy immersive sound effects when bullets are fired and when they hit a spaceship.
- **Health**: Each spaceship starts with a certain amount of health. Health decreases when a spaceship is hit by a bullet. When health drops to zero, the other spaceship wins.

## Installation and Dependencies

To play this game, ensure you have [Pygame](https://www.pygame.org/download.shtml) installed. If you haven't, simply install it using:

```
pip install pygame
```

## Assets

Make sure to have the following assets in the "Assets" directory:

- `space.png`: Background for the game screen.
- `spaceship_yellow.png`: Image for the yellow spaceship.
- `spaceship_red.png`: Image for the red spaceship.
- `Grenade+1.mp3`: Sound effect for bullet hits.
- `Gun+Silencer.mp3`: Sound effect for bullet fires.

## How to Play

1. **Controls for Yellow Spaceship**:
    - Move Left: `A`
    - Move Right: `D`
    - Move Up: `W`
    - Move Down: `S`
    - Shoot: `Left Control`

2. **Controls for Red Spaceship**:
    - Move Left: `Left Arrow`
    - Move Right: `Right Arrow`
    - Move Up: `Up Arrow`
    - Move Down: `Down Arrow`
    - Shoot: `Right Control`

3. When a spaceship's health drops to zero, the game displays the winner and then restarts.

## Running the Game

To run the game, simply execute the Python script in your terminal or preferred Python environment.

## Conclusion

This is a basic space combat game, and there's room for many enhancements. Feel free to contribute or suggest improvements!
