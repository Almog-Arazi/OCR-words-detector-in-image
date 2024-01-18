
# Newspaper Text Extractor - OCR System
<a href="https://ibb.co/nzryStV"><img src="https://i.ibb.co/WgnX1jd/res.jpg" alt="res" border="0" /></a>
## Project Overview
The "Newspaper Text Extractor" is a state-of-the-art OCR (Optical Character Recognition) system developed to efficiently extract text from newspaper articles. Utilizing advanced image processing techniques with Python and OpenCV, this project identifies and extracts textual content, converting scanned newspaper images into editable and searchable text.

https://www.aiismath.com/pages/c_02a_basic_image_processing/ex2/ -the course

## Features
- **Advanced Text Detection**: Uses morphological operations and connected components to identify text regions in a newspaper article.
- **Intelligent Segmentation**: Effectively handles various sizes of text, from large headlines to smaller article text.
- **Robust Preprocessing**: Employs thresholding and dilation to enhance the text for better recognition.
- **Versatile Application**: Tailored to process standard newspaper layouts but adaptable for other document types.

## How It Works
The OCR system performs the following steps:
1. **Grayscale Conversion**: Converts the input image to grayscale to simplify the analysis.
2. **Thresholding**: Applies Otsu's thresholding to binarize the image, distinguishing text from the background.
3. **Morphological Operations**: Uses dilation to merge adjacent text into single connected components, making it easier to identify individual words or lines of text.
4. **Word Detection**: Implements connected components analysis to isolate and highlight each word.
5. **Title Emphasis**: Employs a series of morphological operations to specifically target and mark larger title words.

## Getting Started

### Prerequisites
- Python 3.x
- OpenCV library
- Matplotlib library
- NumPy library

### Installation
1. Install the required libraries (if not already installed):
    pip install numpy opencv-python matplotlib
2. Clone the repository to your local machine:


## Usage
1. Place your newspaper image (e.g., `news.jpg`) in the project directory.
2. Run the script:
    python EX2_2.py
3. The processed images at various stages and the final output will be displayed.

