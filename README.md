#Driver Drowsiness Detection

Driver Drowsiness Detection System using Python, OpenCV, and dlib. Our objective was to create a real-time monitoring solution that could detect driver fatigue by analyzing eye movements and facial expressions to alert the driver when signs of drowsiness were detected.

##How it works:
We utilized several key technologies:
•	OpenCV for real-time image processing and facial feature detection.
•	dlib to accurately detect 68 facial landmarks, including the eyes and mouth, which allowed us to compute the Eye Aspect Ratio (EAR) to determine drowsiness.
•	SciPy for calculating Euclidean distances between the facial landmarks.
•	Imutils to simplify image processing tasks, and playsound for triggering an audible alert when drowsiness was detected.
