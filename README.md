[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/sjskoko/dart_pdf_bounding_box-task/main/pdf_bbox_app.py)

# DART_pdf_bounding_box-task
This project will be used for DART pdf object detection task. 

## Installation
Clone this repo.
```sh
git clone https://github.com/snu-dm/DART_pdf_extractor.git
cd DART_pdf_extractor/
```
This code requires python 3+ and pdfplumber. Please Install dependencies by
```sh
pip install -r requirements.txt
```
## Getting Started
Use following parsers in your Linux terminal:
- text extraction (-text)
- table extraction (-table)
- image extraction (-image)
- caption extraction (-caption)
- pdf_dir (-dir)
- save_dir (-save)
- cropped_file_only (-crop)
- total_page_with_segmentation (-page) 

Example Usage:
```sh
python main.py -text -table -image -caption -crop -page
```
