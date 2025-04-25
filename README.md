Virtual Mouse Using Hand Gesture:-
---------------------------------
This is a Python-based project that enables users to control their computer’s mouse cursor using real-time hand gestures captured via webcam. The system uses MediaPipe for hand tracking and PyAutoGUI for mouse control.

Project Structure :-
------------------
The project is structured into the following files:

app.py: Contains the main program logic and webcam feed.
controller.py: Handles gesture recognition and maps them to mouse actions.
requirements.txt: Lists all the required Python libraries for easy setup.

Requirements:-
------------
To run this project, make sure you have Python installed. The following libraries are required:

opencv-python
mediapipe
pyautogui

You can install them individually:

1) pip install opencv-python mediapipe pyautogui

Or, install all dependencies at once:

2) pip install -r requirements.txt
   
▶️ How to Run
Install the required libraries.

Run the project using:

1) python app.py
2) Make sure your webcam is connected and accessible.

Once the program starts, your gestures will be detected and converted into mouse actions in real-time.

✋ Supported Gestures & Actions :-
---------------------------------

Move Cursor:-
![image](https://github.com/user-attachments/assets/30f21e2c-cfb5-4b08-a3bd-db6a1d0085a4)

scroll down :- 
![image](https://github.com/user-attachments/assets/833991fe-7555-4149-99a7-93caf1e632fe)

scroll up:-
![image](https://github.com/user-attachments/assets/9795521b-3d79-422e-bc38-95ff94d4b189)

Freeze Cursor:-
![image](https://github.com/user-attachments/assets/49b147e8-3d8a-4933-85f9-d0e750662a0f)

Zoom In:-
![image](https://github.com/user-attachments/assets/705c0c9d-474e-43f6-8e1e-56198d2f714b)

Zoom Out:-
![image](https://github.com/user-attachments/assets/62582bda-732b-41ae-b539-d0002af7aced)

Right-Click:-
![image](https://github.com/user-attachments/assets/82e151e3-d470-4c58-a026-abf2bbde03e8)

Left Click:-
![image](https://github.com/user-attachments/assets/4126bc8b-c2b2-4221-be9e-b2b7b1b7b119)

Double Click:-
![image](https://github.com/user-attachments/assets/afde62f6-918f-4a92-b776-c54797bd7e2f)


How It Works:-
--------------
- MediaPipe tracks 21 landmarks on your hand in real time.
- These landmarks are analyzed to determine finger positions and gestures.
- controller.py then translates those gestures into specific mouse events using PyAutoGUI.



