# AI Mouse

## Overview

**AI Mouse** is an innovative project designed to revolutionize the way users interact with their computers. By leveraging cutting-edge artificial intelligence and computer vision technologies, AI Mouse enables hands-free, intuitive control of the mouse pointer using only hand gestures or facial recognition. This project aims to improve accessibility, ergonomics, and user experience for a diverse range of users, including those with limited mobility.

## Features

- **Hand Gesture Recognition:** Control the mouse pointer, click, and perform other common actions using predefined hand gestures captured via webcam.
- **Facial Recognition (Optional):** Move the cursor by tracking head movements, enabling a truly touchless experience.
- **Customizable Gestures:** Easily configure which gestures trigger specific mouse actions according to user preferences.
- **Real-Time Processing:** Low-latency gesture detection ensures smooth and responsive cursor movement.
- **Cross-Platform Support:** Designed to work on major operating systems, including Windows, macOS, and Linux.
- **Accessibility-Focused:** Helps users with physical disabilities interact with computers more effectively.

## Technologies Used

- **Python / OpenCV:** For real-time video capture and image processing.
- **MediaPipe / TensorFlow / PyTorch:** For hand and face landmark detection and gesture classification.
- **PyAutoGUI / pynput:** For programmatically controlling mouse events.
- **Tkinter / PyQt (Optional):** For the graphical user interface.

## Getting Started

### Prerequisites

- Python 3.7+
- Webcam (built-in or external)
- Required Python packages (see `requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/manoj2004111/AIMouse.git
   cd AIMouse
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python main.py
   ```

## Usage

- Launch the application and allow webcam access.
- Follow on-screen instructions to calibrate gestures or facial tracking.
- Use your hand gestures or head movements to control the mouse pointer and execute actions like clicks or drags.

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements, bug fixes, or new features.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenCV](https://opencv.org/)
- [MediaPipe](https://mediapipe.dev/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [PyTorch](https://pytorch.org/)

---

> **AI Mouse**: Making computers accessible, one gesture at a time!
