# AI Pipeline for Image Segmentation and Object Analysis

## overview
This project includes an end-to-end AI system for image segmentation as well as object analysis. These sub-serving processes are; image segmentation, object extraction, object identification, text/data extraction, summarisation of object attributes, data mapping and last but not least; output generation.
The pipeline is implemented in a single Jupyter notebook, Building Ai Pipline for Image segmentation and object Analysis.ipynb, which combines code for all steps: segmentation, identification, text extraction, and final results integration.


## Setup Instructions
Clone the repository:

git clone https://github.com/rahuljoshi1814/rahul-wasserstoff-AiInternTask.git
Navigate to the project directory: cd AiInternTask

Install the required dependencies: pip install -r requirements.txt


## Requirements
- To run this project, you'll need to install the required dependencies. The necessary packages are listed in requirements.txt
## Installation
 1. Clone the Repository:
     - Open your terminal and run: git clone https://github.com/rahuljoshi1814/rahul-wasserstoff-AiInternTask.git
     - Navigate to the Project Directory: cd AiInternTask
     - Install Dependencies
          With your virtual environment activated(optional), install the required packages:

## Running the Notebook
 1. Ensure you are in the project directory and the virtual environment is activated. Then start Jupyter Notebook: jupyter notebook
 2. Open Building Ai Pipline for Image segmentation and object Analysis.ipynb
 3. Execute the Notebook
       Follow the cells in the notebook to run the entire pipeline. The notebook is designed to guide you through each step.
    
## Usage Guidelines
 1. Collect the images which you will be processing and put them in data/input_images subdirectory.

 2. Run the main notebook to process the images and generate results:Run the main notebook to process the images and generate results: jupyter notebook main.ipynb

 3. Results will be saved in the data/output directory, including the final summary table and annotated images.

## Project Structure
 1. data/: Contains input images, segmented objects, and output.
 2. notebooks/: Contains the Jupyter notebooks for each processing step.
    - AI Pipeline for image and object classifications in ".ipynb": The main notebook to run the entire pipeline.
 3. README.md: This file. Provides an overview of the project, setup instructions, and usage guidelines.
 4. requirements.txt: List of required Python packages.

## Notes
 - Ensure Tesseract OCR is installed and its path is configured correctly.
 - This project utilizes Mask R-CNN for object detection and EasyOCR for text extractions.
