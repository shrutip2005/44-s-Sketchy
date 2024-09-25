# 44's Sketchy

## Project Structure:
44's-Sketchy/
│
├── app.py                             # Main Python script for running the application
├── static/
│   └── uploads/
│       ├── various images (.jpg, .png)
│       └── corresponding sketch images (.jpg)
├── templates/
│   └── home.html                      # HTML template for the home page
└── __pycache__/
    └── Compiled Python files (.pyc)


## Overview
44's Sketchy is a web application that allows users to upload an image and receive a sketch-like version of the image. The application uses image processing techniques to convert photos into sketch drawings.

## Features
- Upload images in formats like JPG and PNG.
- Automatically generate a sketch version of the uploaded image.
- View both the original and sketch images in the browser.

## Installation

1. **Clone the repository:**
    
    git clone https://github.com/shrutip2005/44-s-Sketchy.git
    cd 44's-Sketchy
    

2. **Install dependencies:**
    Make sure you have Python installed, then run:
    
    pip install <The libraries which has yellow warnings>
  

3. **Run the application:**
    
    python app.py
    

4. **Open your browser:**
    Navigate to `http://127.0.0.1:5000` to use the app.

## Usage 
1. Launch the application by running python app.py.
2. Upload an image through the provided interface.
3. The app will display both the original and the generated sketch.

## Dependencies
This project requires the following Python libraries:
- Flask: For creating the web application.
- Pillow (or OpenCV): For image processing and generating sketches.

Install them via `pip`:

pip install Flask Pillow
