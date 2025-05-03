# AI Virtual Calculator Using Computer Vision 📸

A touchless, intelligent virtual calculator that uses **hand gesture recognition**, **computer vision**, and **generative AI** to interpret and solve mathematical expressions in real-time. This project leverages **OpenCV**, **MediaPipe**, and the **Google Gemini API** to deliver an innovative and accessible human-computer interaction experience.

### Tech Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)


## Features

- ✋ Real-time hand gesture detection using webcam
- 🎨 Virtual canvas to draw mathematical expressions with gestures
- 🤖 Uses Google Gemini to interpret and solve equations
- 📷 Computer Vision powered by OpenCV + MediaPipe
- 🌐 Flask-based web app with dynamic UI
- 📩 Step-by-step solution generation

![image](https://github.com/Punitpawar5/AI-virtual-calculator/blob/main/project/assets/Screenshot%20(249).png)

## How It Works
Gesture Tracking: handTrack.py uses MediaPipe to detect hand landmarks.

Canvas Rendering: main.py draws paths traced by index finger into a canvas.

Image Capture: Drawn image is saved and sent to the backend.

Gemini AI Integration: app.py sends the image to Gemini, receives LaTeX or textual solution.

Result Display: Solution rendered on the webpage for user.


![image](https://github.com/Punitpawar5/AI-virtual-calculator/blob/main/project/assets/aiimage.png)


## Sample Output

![image](https://github.com/Punitpawar5/AI-virtual-calculator/blob/main/project/assets/Screenshot%20(250).png)

## Demo
Check out LinkedIn post about this project demo [here](https://www.linkedin.com/posts/punit-pawar5_ai-computervision-gesturerecognition-activity-7324443708404219904-xurd?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD6bOdEBDSmX6bWWuAxedYglTGFE7pygkwU)

### License

Distributed under The GNU General Public License v3.0 License.<br>
See `LICENSE.txt` for more information.
