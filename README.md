# The Mosquito Marauder
This is an ongoing work in progress to autonomously detect, physically track and kill mosquitos.

My wife and children hate mosquitos and are terrorized by them. I masked 4,000 unique photos of mosquitos over sixteen hours to train the object detection.
This project *aims* to...


1) (COMPLETE) Create object recognition weights to detect mosquitos with a 4k camera using YOLOv5
2) (COMPLETE) Send relative mosquito coordinates to Arduino Uno R3
3) (IN DEVELOPMENT) Position two servos to track mosquito position via received coordinate from the Arduino
4) (COMPLETE) Check for possible "casualties" in view (people, dogs, birds, etc...)
5) (NOT STARTED) Fire at the targeted mosquito with "ordinance" (haha, salt gun or a class 4 laser, tbd)
6) (NOT STARTED) Determine if target was "neutralized"
7) (NOT STARTED) Save feed of each event to cloud for review
8) (COMPLETE) Reset and contiue scanning room

I started this project in November, 2020. Progress has been faster than expected as of July 26, 2021.
The languages used here include Python, C#, C and uses the Arduino IDE

Edit May 05, 2023: Minification became a priority for this project. Carrying around a laptop in order to deploy this is not the best implimentation. I have a great path toward minification that will require some refactoring. This project is not the priority right now, but I plan to come back to it.
