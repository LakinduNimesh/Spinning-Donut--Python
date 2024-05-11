
## Spinning Donut Visualization in Python using Pygame

![Screenshot 2024-05-11 114811](https://github.com/LakinduNimesh/Spinning-Donut--Python/assets/149768006/545ef443-3176-42bb-94c4-5cebef1b015e)

This Python project demonstrates a spinning donut shape using ASCII characters in a graphical window powered by Pygame. It offers a captivating visual experience by performing 3D transformations and rotations to represent a donut in 2D space, with changes in color based on the hue value. Suitable for those interested in graphics programming and mathematical visualizations.
![Screenshot 2024-05-11 114800](https://github.com/LakinduNimesh/Spinning-Donut--Python/assets/149768006/d5d12e68-325b-43a0-bc65-98b93a693ced)

### Requirements
- Python 3.x
- Pygame

To install Pygame, you can use pip:
```bash
pip install pygame
```

### How to Run
1. Save the code into a file named `spinning_donut.py`.
2. Run the script from the terminal:
   ```bash
   python spinning_donut.py
   ```

### Features
- Full-screen and windowed mode support.
- Real-time donut spinning animation.
- Color transitions using HSV to RGB conversion.

### Configuration Options
- `WIDTH` and `HEIGHT` can be adjusted to change the display resolution.
- `x_seperator` and `y_seperator` control the spacing between characters.
- Adjust `spacing1` and `spacing2` to modify the density of the points that form the donut.
- `chars` represents the luminance index where each character corresponds to a different shade in the rendered output.

### Controls
- **Escape Key**: Exit the application.

### Implementation Details
- The donut is rendered using the formulas for a torus in 3D space, rotating around its axes with a projection onto the 2D screen.
- Luminance is calculated using a simplified model to determine which character to display at each point, based on its depth and angle.
- Pygame is used for creating the window, handling events, and updating the display in real-time.

### Limitations
- The performance might vary depending on the system capabilities and display settings.
- The resolution and character density are hardcoded, but can be made configurable with additional parameters or command-line arguments.

### Suggestions for Improvement
- Introduce interactive controls for adjusting the rotation speed and viewing angles.
- Implement performance optimizations to handle higher resolutions and denser donut representations.
- Allow user customization for colors and character sets used for rendering.

This project provides a foundation for more complex graphical simulations and can be extended in numerous ways to enhance both functionality and visual appeal.
