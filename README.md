# Text-From-Image

Custom-Object Character Recognition(OCR) on Streamlit

Build a Custom OCR by combining YOLO and Tesseract, to read the specific contents of a Lab 

Report and convert it into an editable file. Use  YOLO_V3 to trained on the personal dataset. 

Then the coordinates of the detected objects are passed for cropping the detected objects and 

storing them in another list. This list is passed through the Tesseract to get the desired output. 

# Model 

● You can train a custom YOLO_V3 model using your custom dataset. 

● Make a folder named model and put the weights file inside it.
