# Overview
This project includes an end-to-end AI system for image segmentation as well as object analysis. These sub-serving processes are; image segmentation, object extraction, object identification, text/data extraction, summarisation of object attributes, data mapping and last but not least; output generation.

# Setup Instructions
Clone the repository:

git clone https://github.com/rahuljoshi1814/rahul-wasserstoff-AiInternTask.git
Navigate to the project directory: cd AiInternTask

Install the required dependencies: requirements.txt

## Usage Guidelines
 1. Collect the images which you will be processing and put them in data/input_images subdirectory.

 2. Run the main notebook to process the images and generate results:Run the main notebook to process the images and generate results: jupyter notebook main.ipynb

 3. Results will be saved in the data/output directory, including the final summary table and annotated images.

## Project Structure
 1. data/: Contains input images, segmented objects, and output.
 2. notebooks/: Contains the Jupyter notebooks for each processing step.
    - AI Pipeline for image and object classifications.ipynb: The main notebook to run the entire pipeline.
    - AI Pipeline for image and object classifications.html: HTML export of the main notebook for easy sharing and viewing.
 3. README.md: This file. Provides an overview of the project, setup instructions, and usage guidelines.
 4. requirements.txt: List of required Python packages.
## Requirements
 - See requirements.txt for a full list of dependencies.
## Notes
 - Ensure Tesseract OCR is installed and its path is configured correctly.
 - This project utilizes Mask R-CNN for object detection and EasyOCR for text extractio
