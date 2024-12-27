# Text Detection Project

This project demonstrates text detection in images using EasyOCR and OpenCV. The application extracts text from images and displays the detected text along with bounding boxes.

## Features
- Detects text in images using EasyOCR.
- Displays text with bounding boxes drawn around detected areas.
- Thresholding to filter detected text based on confidence.

## Requirements
To run this project, you'll need the following:

- Python 3.x
- EasyOCR
- OpenCV (headless version)
- NumPy
- Matplotlib

### Installing Requirements
Install the required Python libraries using:

```bash
pip install -r requirements.txt
```

### Requirements File
The `requirements.txt` includes:
```
easyocr
matplotlib
opencv-python-headless
numpy
```

## Project Structure
```
.
|-- main.py                 # Script for text detection
|-- dataset/                # Folder containing input images
|   |-- test3.png           # Example test image
|-- results/                # Folder containing output images
|   |-- figure_1.png        # Example result image 1
|   |-- figure_2.png        # Example result image 2
|-- requirements.txt        # Required Python packages
```

## Usage

### Detect Text in an Image
To detect text in an image, update the `image_path` variable in `main.py` with the path to your image and run the script:

```bash
python main.py
```

#### Key Features:
- Detected text is printed to the console.
- An image with bounding boxes around detected text is displayed using Matplotlib.

## Results

### Example Results

#### Input Image
The input image (`test3.png`) from the `dataset/` folder is used for detection.

#### Output
- The detected text is printed to the console.
- Bounding boxes and detected text are drawn on the image. Below are sample results:

**Result 1:**
![Result 1](figure_1.png)

**Result 2:**
![Result 2](figure_2.png)

## Credits
- EasyOCR: [https://github.com/JaidedAI/EasyOCR](https://github.com/JaidedAI/EasyOCR)
- OpenCV: [https://opencv.org](https://opencv.org)
- computervisionengineer: [https://youtube/@ComputerVisionEngineer](https://youtu.be/n-8oCPjpEvM?si=wPm7oqn66JCWPamU)

## License
This project is licensed under the MIT License - see the LICENSE file for details.

