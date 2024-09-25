# YOLOv7-Based-Weed-Detection-for-Precision-Farming
Develop an automated weed detection system using a CNC-based robot equipped with a YOLOv7 model for real-time classification and management of weeds in a terrace farming setup.
- You must check out the code from ITERATION #4.

**Run the Notebook**: 
Open the YOLOv7_Weed_Detection.ipynb file in Google Colab or Jupyter Notebook and follow the instructions to run the model.

**Data Preparation**:
Upload your own dataset or use the provided sample images to train and test the model.
Ensure that your images are annotated using tools like LabelImg.

**Model Training & Evaluation**:
Train the YOLOv7 model using the preprocessed dataset.
Evaluate model performance using metrics such as mAP and IoU.

**Results**
- The model achieved high accuracy in detecting and classifying weed objects in various scenarios. The integration with the CNC-based robot allows for real-time detection and response, reducing the need for manual intervention.

**Future Work**
- Improve model accuracy by expanding the dataset and applying advanced augmentation techniques.
Enhance the robotic system to include more sensors and tools for better field management.

**Acknowledgements**
- This project was developed as part of my research at BITS Pilani's Mechanical Engineering Department. Special thanks to my team members and mentors for their support and guidance.

- Once we capture the image of the plant in a set area (say 20*20 centimetre square). We can utilise image augmentation techniques, smoothen the image, and identify blobs smaller than the main central plant as "aliens". Hence this is proof of concept that this is a simple implementation of Weed detection. Due to lack of image data, I had to make up my own Image data and use Image augmentation techniques to train the YOLOv7 model. I prepared the data by using LabelImg software to label the images. And I have uploaded them onto this repositor as images and labels for training YOLOv7 model.

- **Motivation**:
- I was a Research Assistant at BITS Pilani in the Mechanical Engineering Department from August 2022 - December 2022 and worked on the ideation and development of a CNC-Based Automation for Terrace Farming.
YOLOv7 based weed detection was a small part of this project. I created a simple way of detecting weed plants which will grow in and around the main plants, and can be identified by way of image capture --> image augmentation --> and finally use this model to detect the weed and notify the user.
