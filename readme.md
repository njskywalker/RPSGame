# Rock-Paper-Scissors README

A man-vs-computer game where you play rock-paper-scissors with your camera against your computer. Whoever can trump the opponent's class, wins!

# Milestone 1: Training the Project

I used TeachableMachine to train my model to recognise four classes: rock, paper, scissors, and nothing (just my face!). I used a range of conditions (different lighting and different angles/distances from camera) to increase model accuracy.

I used TeachableMachine because it's fast and easy to use for this goal.

# Milestone 2: Installing dependencies

I installed opencv-python, ipykernel, and tensorflow. The latter for obvious reasons (need to be able to run model). OpenCV provides the cv2 package, which allows Python to use a webcam to record, and thus provide input data to my model. Finally, ipykernel is needed to allow me to run notebooks.

# Milestones 3 and 4: Create a Rock-Paper-Scissors game

I made a rock-paper-scissors game where a human plays against the computer. There are up to three rounds: the computer chooses a random weapon, whereas the human must model their choice with their hand (either left or right) in front of the webcam.

There is a countdown timer which allows the human to know how much time they have left to make a choice, as well as feedback as to what the CV model is predicting the human is showing. The game is packaged into a function. I also made some accessory functions (such as a multi-line cv2.putText() and a camera initialisation function) to neat up the code.

I made the game use the camera straight away, without an intermediate stage (Milestone 3).