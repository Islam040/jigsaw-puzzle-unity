# 2D Jigsaw Puzzle Game (Unity)

## Overview
This project is a mobile 2D jigsaw puzzle game developed using Unity. The player must drag puzzle pieces into the correct position and rotate them to match the original image.

## Objective
Build a 2D puzzle game where users:
- Drag pieces to their correct positions
- Rotate pieces to the correct orientation
- Complete the puzzle with visual feedback

## Features
- Load and display an image
- Slice image into grid pieces (3x3, 4x4, 5x5)
- Shuffle puzzle pieces randomly
- Drag and drop system (mobile touch support)
- Tap to rotate pieces (90 degrees per tap)
- Snap pieces into correct position
- Puzzle completion detection
- Completion message or animation

## Technologies Used
- Unity (2D)
- C#
- Mobile touch input

## Game Logic
- Each puzzle piece starts with a random rotation (0, 90, 180, 270 degrees)
- Player can drag pieces and rotate them by tapping
- A piece is correct when it is near its target position and has correct rotation
- Correct pieces snap into place and can no longer be moved
- The game ends when all pieces are correctly placed

## Project Structure
Assets/
- Scenes/
- Scripts/
- Sprites/
- Prefabs/
- UI/

## Build Settings
- Platform: Android or iOS
- Resolution: 1920x1080 (Canvas Scaler)

## Optional Features
- Timer
- Difficulty levels
- Sound effects

## Assignment
This project was created for Assignment 2 – 2D Puzzle Game.

Requirements included:
- Image slicing
- Drag and drop system
- Rotation system
- Snap detection
- Puzzle completion

## Author
Islam Amangeldi
