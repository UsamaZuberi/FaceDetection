Face Detection Application

Using Open CV and Python, this application captures pictures using webcam on your laptop or PC and then train the model accordingly.

After training it captures live frames from web cam and recognizes if the face on the webcam is the one that it was trained for or not.

How to use:
First run the program file "FaceDetection.py", this will capture frames and crop faces from them and save them in CaptureFaces folder.

Then run the program file "FaceDetection_Operation.py", this will train the model, then implement the algorithm and it will show:
1) Confidence Percentage
2) Locked or Unlocked State
3) Face Not found (if there is no face)
