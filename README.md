# Harmony Wave
Harmony Wave is a 2D dating simulation game inspired by Doki Doki Literature Club!, developed as part of a class project by two students from the Informatics WPU class of 10th grade. The game combines a 2D interface created with Python and CustomTkinter for the visual novel elements, and Ursina Engine for 3D models and environments. Players will experience a story set in a Japanese school, transitioning between 3D and 2D gameplay.

## 📜 Description
Harmony Wave is a unique combination of 2D and 3D elements, blending a visual novel dating simulator with a 3D environment inspired by Japanese school life. The game features:

A 2D dating interface built with Python and CustomTkinter
3D models and environments powered by the Ursina Engine to bring the school setting to life
A narrative that takes players through various scenarios and interactions in a Japanese high school
A seamless transition between 3D exploration and 2D visual novel gameplay


## The project includes:
Installer (Harmony Wave.py): A custom installer to automatically install all necessary dependencies and files
Launcher (launcher/launcher.py): A launcher to start the game with a single click

## ⚙️ Setup
To play the game, you’ll need Python installed, along with the required packages. The installer will handle all necessary installations.

### Install the dependencies manually (if not using the installer):
pip install customtkinter
pip install ursina

## 👥 Created by
We are two students from the 10th grade Informatics WPU working on this project as part of a class assignment. The game was created for our computer science exam.

# 📂 Project Structure
│   Harmony Wave.py
│
├───3d-engine
│   │   classroom.py
│   │   first_person_controller.py
│   │   main.py
│   │   school_hallway.py
│   │
│   └───__pycache__
│           classroom.cpython-311.pyc
│           first_person_controller.cpython-311.pyc
│           school_hallway.cpython-311.pyc
│
├───game
│       main.py
│       start.py
│
├───launcher
│       launcher.py
│
├───resources
│   ├───fonts
│   │       RifficFree-Bold.ttf
│   │
│   ├───game
│   │       game_save.cfg
│   │
│   ├───images
│   │   ├───background
│   │   │       background-home.png
│   │   │       background-launcher.png
│   │   │       background-settings.png
│   │   ├───background-model
│   │   │       background.png
│   │   │       classroom.png
│   │   │       dialog-box.png
│   │   ├───character-model
│   │   │       natsuki-idek.png
│   │   │       natsuki-leckmich.png
│   │   │       natsuki-no.png
│   │   ├───icon
│   │   │       close-icon.png
│   ├───texture
│   │   ├───glb
│   │   │       stuhl.glb
│   │   │       test02.glb
│   ├───model
│       │   Moyonote Natsuki.fbx
│       │   test.py
│
