Air Canvas

Air Canvas is a project that allows users to draw on the screen by moving their hand in the air. It uses computer vision techniques, primarily OpenCV, to detect hand movements and converts them into drawing strokes on a virtual canvas.

## Features

- **Real-time hand tracking**: Tracks hand movements using a webcam.
- **Air drawing**: Draw on the virtual canvas by moving your hand in the air.
- **Color selection**: Choose different colors for drawing.
- **Clear screen**: Clear the canvas by a specific gesture or key press.

## Requirements

Before running the project, ensure you have the following installed:

- Python 3.x
- OpenCV (`pip install opencv-python`)
- Numpy (`pip install numpy`)
- Mediapipe (`pip install mediapipe`) - for hand tracking

## Installation

1. Clone this repository:


   git clone 
   cd air-canvas
   

2. Install the required libraries:


   pip install -r requirements.txt
   

   (Ensure the `requirements.txt` contains: `opencv-python`, `numpy`, `mediapipe`)

3. Run the script:


   python air_canvas.py

## How It Works

1. **Hand Tracking**: The system uses MediaPipe to detect and track the hand.
2. **Gesture Recognition**: The tip of the index finger is used as the drawing tool, and the tip of the middle finger is used to activate the eraser.
3. **Drawing Mechanism**: By detecting the position of the index finger, drawing happens when the index finger moves across the screen.
4. **Gesture to Erase**: If a specific gesture (like raising the middle finger) is detected, the eraser mode is activated.

## Usage

- **Start Drawing**: Move your index finger in front of the camera, and the software will start drawing on the virtual canvas.
- **Erase**: Hold up your middle finger to activate eraser mode.
- **Change Color**: Use keyboard shortcuts to change the color (e.g., 'r' for red, 'g' for green, 'b' for blue).
- **Clear Screen**: Press 'c' to clear the screen.



## Future Enhancements

- Add more gestures for better control (like undo, redo, etc.).
- Improve accuracy and stability of hand tracking.
- Add more color and brush options.

## Contribution

Feel free to fork this repository and make pull requests to add new features or improve the existing functionality.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Notes

- You can add a demo GIF or image under the **Example** section to showcase how it works.
- Update the URLs to the repository and image links accordingly.
