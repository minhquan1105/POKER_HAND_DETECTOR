AI Poker Dealer – Real-Time Card Recognition
Overview
This project is an AI-powered poker dealer that uses computer vision to recognize playing cards from a live webcam feed and determine the best poker hand in real time. By combining YOLO object detection with OpenCV and a custom hand-evaluation algorithm, the program can detect cards on the table and instantly display results such as Full House, Straight, or Royal Flush.
Inspiration
Poker is a fun game, but checking hands manually can slow things down, especially for new players who aren’t familiar with the rankings. I built this project to create a simple AI dealer that can recognize cards automatically and evaluate hands instantly. The goal was to make casual games faster and help beginners understand poker hands more easily.
Tech Stack
Python – Main programming language
YOLO (Ultralytics) – Real-time object detection for identifying cards
OpenCV + cvzone – Webcam input, bounding boxes, and UI overlays
Custom Poker Logic – Python functions to evaluate the best possible hand
Features
Detects all 52 playing cards (2–10, J, Q, K, A across all suits)
Identifies poker hands such as:
Royal Flush
Straight Flush
Four of a Kind
Full House
Flush
Straight
and more
Processes card detection in real time using a webcam
Displays the best hand directly on the screen
How to Run
1. Clone the repository
git clone https://github.com/minhquan1105/POKER_HAND_DETECTOR.git
cd POKER_HAND_DETECTOR
2. Install dependencies
pip install ultralytics opencv-python cvzone
3. Run the program
python main.py
