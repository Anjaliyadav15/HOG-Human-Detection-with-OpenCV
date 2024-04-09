# Human Detection using OpenCV and HOG Descriptor

This project provides a simple Python script for detecting humans in images, video files, or live camera feed using OpenCV and the HOG (Histogram of Oriented Gradients) descriptor.

## Features
- Detect humans in images, video files, or live camera feed.
- Display bounding boxes around detected humans with unique IDs.
- Count and display the total number of persons detected.
- Support for both command-line interface and direct function calls.
- Option to output the results to video files.

## Installation
1. Clone this repository to your local machine:

   ```
   git clone https://github.com/your-username/human-detection.git
   ```

2. Navigate to the project directory:

   ```
   cd human-detection
   ```

3. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

## Usage
You can use the provided Python script `human_detection.py` to detect humans using various sources.

### Command-Line Interface
```
python human_detection.py -i path/to/image.jpg
python human_detection.py -v path/to/video.mp4
python human_detection.py -c true
```

Options:
- `-i/--image`: Path to the input image file.
- `-v/--video`: Path to the input video file.
- `-c/--camera`: Set to `true` if you want to use the camera for live detection.
- `-o/--output`: Path to the optional output video file.

### Function Calls
You can also call the `humanDetector` function directly in your Python scripts by passing appropriate arguments.

## Dependencies
- Python (>=3.6)
- OpenCV (opencv-python)
- imutils
- numpy

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
