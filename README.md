AI Poker Dealer – Real-Time Card Recognition
Project Overview
This project is an AI-powered poker dealer that uses computer vision to automatically detect playing cards from a live webcam feed and evaluate the best poker hand in real time.
It combines YOLO object detection, OpenCV overlays, and a custom poker-hand evaluation algorithm to deliver instant results such as “Full House” or “Straight Flush.”
Inspiration
Poker is a fun but sometimes slow game, especially when players manually check hands.
We wanted to build an AI dealer that can recognize cards instantly, explain hands to new players, and reduce human error — making casual games faster and more engaging.
Tech Stack
Python – Core development
YOLO (Ultralytics) – Real-time object detection
OpenCV and cvzone – Webcam capture, bounding boxes, UI overlays
Custom Poker Logic – Hand evaluation in Python
Features
Detects 52 unique cards (2–10, J, Q, K, A in all suits)
Recognizes poker hands: Royal Flush, Straight Flush, Four of a Kind, Full House, Flush, Straight, etc.
Real-time detection using a webcam feed
Displays best hand directly on screeN
How to Run
Clone the repository:
git clone https://github.com/minhquan1105/POKER_HAND_DETECTOR.git
cd POKER_HAND_DETECTOR
Install dependencies:
pip install ultralytics opencv-python cvzone
Run the app:
python main.py
Press q to quit the webcam window.
