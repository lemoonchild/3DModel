# 3D Model Renderer in Rust

This project is a 3D rendering program written in Rust, capable of displaying and interacting with a 3D model, specifically a spaceship created in Blender and exported as a `.obj` file. The program allows you to move and scale the model, as well as rotate it using keyboard controls.

## Features 
- **Model Rendering:** Load and render a 3D model exported as .obj.
- **Camera Movement:** Move the camera to observe the model from different angles.
- **Scaling:** Zoom in or out to view the model at different sizes.
- **Rotation:** Rotate the model around the X, Y, and Z axes


## Getting Started
### Prerequisites
To run this program, you'll need to have Rust installed on your system.


### Installation
1. Clone the repository: 

        git clone https://github.com/lemoonchild/3DModel.git

2. Navigate to the project directory: 

        cd model3d

3. Build and run the project in release mode: 

        cargo run --release

## Controls
You can interact with the spaceship model using the following keyboard controls:

### Movement
- Right Arrow (→): Move camera to the right.
- Left Arrow (←): Move camera to the left.
- Up Arrow (↑): Move camera up.
- Down Arrow (↓): Move camera down.

### Scaling
- S: Zoom in (increase scale).
- A: Zoom out (decrease scale).

### Rotation
- Q: Rotate on the X-axis (counter-clockwise).
- W: Rotate on the X-axis (clockwise).
- E: Rotate on the Y-axis (counter-clockwise).
- R: Rotate on the Y-axis (clockwise).
- T: Rotate on the Z-axis (counter-clockwise).
- Y: Rotate on the Z-axis (clockwise).

### GIF
![Lab 03 Gráficas Starship Model3D](https://github.com/user-attachments/assets/077e1d87-273e-4867-9550-22a34f624a01)
