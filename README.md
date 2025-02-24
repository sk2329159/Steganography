# **Image Steganography using Python**

## **Overview**
This project demonstrates how to hide (encode) a secret message inside an image using steganography techniques and later extract (decode) it using Python and OpenCV.

## **Features**
- Upload an image in Google Colab.
- Hide a secret message inside the image.
- Encrypt the message using a simple passcode-based authentication.
- Extract the hidden message by entering the correct passcode.

## **Requirements**
- Python 3
- OpenCV (`cv2`)
- Google Colab (for running the notebook)

## **Installation**
Ensure you have the required libraries installed. If using a local setup, install OpenCV using:
```bash
pip install opencv-python
```

## **Usage**
### **1. Upload an Image**
Run the following command in the Colab notebook:
```python
from google.colab import files
uploaded = files.upload()
```
Manually upload an image file.

### **2. Encode the Message**
- Run the encoding script.
- Enter the secret message and a passcode when prompted.
- The message will be stored in the blue channel of the image.
- A new image (`encryptedImage.jpg`) will be saved.

### **3. Decode the Message**
- Run the decryption script.
- Enter the correct passcode.
- If authenticated, the secret message will be extracted and displayed.


📢 Contact If you have any questions or suggestions, feel free to connect:

🔗 LinkedIn: www.linkedin.com/in/swarnimkumar2134
