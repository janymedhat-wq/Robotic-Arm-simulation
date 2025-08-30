# Robotic Arm Simulation
This is an interactive 3D simulation of a multi-joint robotic arm, built entirely within a single HTML file. The simulation allows users to manipulate the arm's joints in real-time using a simple control panel.

# Features
Interactive 3D Model: A realistic-looking robotic arm with a base, three articulated links, and a gripper.

Hierarchical Joint Control: The arm's structure is grouped hierarchically, allowing each joint's rotation to be controlled independently without affecting the others.

Manual Control Panel: A user-friendly interface with sliders to precisely adjust the rotation of each of the four main joints.

Camera Controls: Users can rotate, pan, and zoom the camera to view the arm from any angle using a mouse.

# How to Use
Simply open the robotic_arm.html file in any modern web browser.

To rotate the arm joints: Use the sliders in the "Manual Controls" panel on the right side of the screen.

Joint 1 (Base Rotation): Rotates the entire arm on its vertical axis.

Joint 2 (Shoulder Angle): Moves the lower arm up and down.

Joint 3 (Elbow Angle): Bends the elbow.

Joint 4 (Wrist Twist): Rotates the wrist.

To control the camera:

Rotate: Click and drag anywhere on the canvas.

Zoom: Use the scroll wheel.

Pan: Right-click and drag on the canvas.

# Technology
HTML5: Provides the structure for the web page.

Tailwind CSS: Used for all the styling and layout of the control panel, ensuring a clean and responsive design.

Three.js: A powerful JavaScript 3D library used to create and render the 3D graphics, handle the camera, and manage the object hierarchy.

OrbitControls.js: A Three.js addon that enables the intuitive camera controls.

Possible Future Improvements
Add a functional gripper that can open and close.

Implement an inverse kinematics solver to allow users to move the end effector directly, and have the joints automatically adjust.

Add a target object (like a cube) for the arm to interact with.

Animate the arm to perform a sequence of predefined movements.
