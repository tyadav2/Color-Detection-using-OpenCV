# Color-Detection-using-OpenCV

The goal of this project was to use color detection and segmentation techniques for detecting a specific color of choice(in this case, red) and making it “disappear.” In simple words, this technique uses the removal of the foreground frame which is opposite of the green screening technique where you remove the background. (Inspired from Cloak of Invisibility in Harry Potter)

Algorithm-
- First capture the background frame and store it
- Then detect red colored cloth using color detection and segmentation algorithm
- Generate a mask to segment out the red colored cloth
- Finally, to achieve the finalized effect, generate the augmented output

Python libraries used-
Numpy - Used for array purpose in this project
openCV- Used for image processing aspect of the project
Time - Used to capture the video in that time
