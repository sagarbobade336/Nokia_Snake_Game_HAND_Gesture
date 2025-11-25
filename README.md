# 🐍 Nokia Snake Game - Gesture Control ✋

Experience the nostalgia of the classic Nokia Snake game, reborn with modern AI-powered hand gesture control via your webcam!✨ 

# Key Features

This project offers a dual experience: a faithful recreation of the retro game and an innovative control system.
👋 Hand Gesture Controls: Control the snake's direction by swiping your hand (up/down/left/right) in front of the camera. Use a pinch gesture (thumb and index finger) for a speed boost.

🎮 Authentic Nokia Graphics: Features an authentic green monochrome theme, grid-based movement, and growing snake mechanics.

🖥️ Dual Window Interface: The game runs in one window (Pygame), and the live webcam feed with real-time MediaPipe hand tracking runs in a separate window, providing visual feedback.

🚀 Smooth Performance: Built with Pygame for the game logic and OpenCV/MediaPipe for fast, reliable computer vision.

🚀 Quick Start (Installation & Run)Get the game running on your local machine in just a few steps.
1. PrerequisitesMake sure you have a working webcam (built-in or external) and Python 3.7+ installed.
2. Setup the EnvironmentIt's highly recommended to use a virtual environment.
   Bash#  Clone the repository (once uploaded to GitHub)
   git clone <YOUR_REPO_URL>
   cd nokia-snake-gesture

# 2. Create and activate a virtual environment
python -m venv .venv

# On Windows (PowerShell): .venv\Scripts\Activate.ps1

# On macOS/Linux: source .venv/bin/activate

3. Install Dependencies
   Use the included setup script to automatically install all required packages:
   # python setup.py
   Required packages include: opencv-python, mediapipe, numpy, and pygame.
4. Run the GameLaunch the game using the main script:
   # python main.py
# 🕹️ Controls & Mechanics
Gesture,Action

Swipe Up, Move snake up

Swipe Down, Move snake down

Swipe Left, Move snake left

Swipe Right, Move snake right

Pinch (thumb + index), Speed boost (faster movement)
# Game Control
Key/Action, Function

ESC (Game Window), Quit game

Q (Gesture Window), Quit all windows

Show UP gesture (Game Over Screen), Restart game
