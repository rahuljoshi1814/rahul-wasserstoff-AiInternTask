# AiInternTask

## Overview
This project includes an end-to-end AI system for image segmentation as well as object analysis. These sub-serving processes are; image segmentation, object extraction, object identification, text/data extraction, summarisation of object attributes, data mapping and last but not least; output generation.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/rahuljoshi1814/rahul-wasserstoff-AiInternTask.git
   
2. Navigate to the project directory:
  cd AiInternTask
  
3. Install the required dependencies:
  pip install -r requirements.txt

## Usage Guidelines
1. Collect the images which you will be processing and put them in data/input_images subdirectory.

2. Run the main notebook to process the images and generate results:Run the main notebook to process the images and generate results: jupyter notebook main.ipynb

3. Results will be saved in the data/output directory, including the final summary table and annotated images.

## Project Structure
- data/: Contains input images, segmented objects, and output results.
- notebooks/: Contains the Jupyter notebooks for each processing step.
  - AI Pipeline for image and object classifications.ipynb: The main notebook to run the entire pipeline.
  - AI Pipeline for image and object classifications.html: HTML export of the main notebook for easy sharing and viewing.
- README.md: This file. Provides an overview of the project, setup instructions, and usage guidelines.
- requirements.txt: List of required Python packages.

## Requirements
- Python 3.7 or above
- See requirements.txt for a full list of dependencies.

## Notes
- Ensure Tesseract OCR is installed and its path is configured correctly.
- This project utilizes YOLOv5 for object detection and EasyOCR for text extraction.
