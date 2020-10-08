# EYE-BLINK-DETECTION
Eye Blink Detection or Liveliness detection[ through Facial Landmarks and OpenCv ]

We are using Python, OpenCV, and dlib code to:
(1) perform facial landmark detection and 
(2) detect blinks in video streams(from Videofiles or Live Webcam)

Understanding the “eye aspect ratio” (EAR):
we can apply facial landmark detection to localize important regions of the face, including eyes, eyebrows, nose, ears, and mouth. This also implies that we can extract specific facial structures by knowing the indexes of the particular face parts.In terms of blink detection, we are only interested in two sets of facial structures — the eyes.
Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the remainder of the region:




     







