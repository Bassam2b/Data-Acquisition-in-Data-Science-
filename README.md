FIFA Game Video Analysis Using OpenCV
This project demonstrates the use of computer vision techniques to process and analyze gameplay footage from a FIFA video. The main goals are to extract frames, label key regions and objects, and apply dense counting to estimate player distribution on the field.

Key Steps:

Used cv2.VideoCapture to load and read the video frame by frame.

Saved selected frames as images using cv2.imwrite for further processing.

Manually labeled key elements in the images, including:

Green field regions

Players (Yellow and Blue teams) and Ball

Applied Dense Counting to estimate the number of players in specific regions of the field.
