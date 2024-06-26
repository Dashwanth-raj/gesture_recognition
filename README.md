# gesture_recognition
Create a new folder and import gestures.py to the new folder

Open a new folder and Create the Virtual Environment:
To create a virtual environment, use the following command:

python -m venv venv

python -m venv venv tells Python to create a virtual environment
named venv in your project directory. You can name your virtual
environment anything you like, but venv is a common convention.

Activate the Virtual Environment:
After creating the virtual environment, you need to activate it. The command to
activate the virtual environment depends on your operating system.
On Windows:

.\venv\Scripts\activate

When the virtual environment is activated, you should see the environment
name (e.g., (venv) ) at the beginning of your command prompt.
Step 5: Install Required Packages

Once the virtual environment is activated, you can install the required packages
using pip . For this project, we will need OpenCV, MediaPipe, TensorFlow, and
NumPy.
1. Run the gestures.py script to test the gesture recognition and text overlay.
2. Verify that the recognized gestures display the corresponding text.

What to Expect:
When you run the gestures.py script:
1. Video Feed with Hand Detection:
The script will open a window displaying the video feed from your
webcam.
Hand landmarks will be drawn on detected hands.
2. Gesture Recognition and Text Overlay:
When specific hand gestures are recognized, corresponding text will be
displayed on the screen near the hand.
How to Test:

Run the Script:
Open your terminal or command prompt.
Ensure your virtual environment is activated.
Run the script using:


1. Perform the Gestures:
Open Hand (Palm) Gesture:
Hold your hand open with the palm facing the camera.
Ensure your fingers are spread apart.
The text "Syntax Sarcasm" should appear near your hand.
Pointing side Gesture:
Point your index finger upwards with the other fingers folded.
Ensure your hand is pointing the first finger to the side with all fingers
closed

2. Exit the Script:
To stop the script, press the 'q' key on your keyboard.
Gestures to Keep:
For the initial implementation, we have two simple gestures:
1. Open Hand (Palm) Gesture:
Description: Hand open with fingers spread apart.
Displayed Text: "Syntax Sarcasm"
Use Case: This gesture is common and easy to recognize, making it ideal
for a demo.
2. Pointing side Gesture:
Description: Index finger pointing upwards with other fingers folded.
Use Case: This gesture is distinct and easy to perform, making it suitable
for recognition.
