# Produce Quantity and Quality Estimation Using Computer Vision
_
Because there is inaccuracy in produce estimation and its tedious to scan a large farm/orchards which may span many acres, there is a need to have an automated produce quantity and quality estimator to do this work for you
__

specs:
built on python3.11.6 on windows 10.

setup:
`pip install -r requirements.txt`
___
## Training
To train the fruit ripeness classifier, run the cells in core/fruit_classifier.ipynb to make the model. \
To train the yolo model to detect apple bounding boxes, run the cells in core/YOLO_Apple_Detector.ipynb
___
## Usage
To run, simply change to the current directory of the project, and run the following code : \
`python -m streamlit run app.py`
