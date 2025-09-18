
# Skin Classifier (Java + ONNX)

This project is a simple skin lesion classifier implemented in Java that uses an ONNX model to classify skin images.
This skin lesion detection model is built using the ResNet-50( a trained model witj 92% of accuracy).


---

##  Features
- The key feature is the utilization of Res-net 50 model, a well known and highly effective and efficient CNN (Convolutional neural networks) model.
- This project initiates the need for an automated skin lesion detection system.
- The implementation of the skin cancer detector was carried out using the TensorFlow.
- This skin lesion detector is trained on a large dataset of skin lesion images. 
- GUI to select and open skin images.
- Downloads a pre-trained ONNX model for catogorizing.
- Predicts skin lesion type and displays result upon scanning the uploaded image.

---

## Technologies Used
- Java (Swing) for GUI,SPRING BOOT.
- ONNX Runtime for running the machine learning model.
- Maven for building and compiling.
- Used thymeleaf for implemeting the GET requests and POST requests in html.
- Python for converting the downloaded .ipynb to .py file.
- Used Python again for converting the .py model to .onnx model.
- The whole working includes java , html and python.

---

## 📂 Project Structure
skin-classifier/
├── src/
│ └── com/example/App.java # Main Java code
├── model.onnx # Pre-trained ONNX model
└── README.md
- Maven is entirely responsible for the Organized Project Structure. It was vert helpful to build it automatically in java

## Conclusion
This project built a skin lesion detection system using the ResNet-50 model implemented with TensorFlow and Keras. The downloaded trained model has the capability to Initiate the patient to visit the actual health care /treatment from professionals. The model has an accuracy of 92% in the field of dermatology. Although this is not an accurate built-in app for real cure, it is definitely an initiative for you to assist early diagnosis, leading to improved health care.





