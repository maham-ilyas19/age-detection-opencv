# Real-Time Age Detection using OpenCV & Caffe DNN 👤

A Computer Vision pipeline that detects human faces in images using OpenCV's Haar Cascade classifier and predicts their corresponding age range using a pre-trained Caffe Deep Neural Network.

## 📌 Features

- **Face Detection:** Leverages OpenCV's pre-trained Haar Cascade (`haarcascade_frontalface_default.xml`) to localize human faces in input images.
- **Deep Learning Age Classification:** Uses a Caffe Deep Neural Network (`age_net.caffemodel`) trained to classify faces into 8 discrete age brackets:
  - `(0-2)`, `(4-6)`, `(8-12)`, `(15-20)`, `(25-32)`, `(38-43)`, `(48-53)`, `(60-100)`
- **Dual Visual Output:** Displays bounding boxes and predicted age labels using both Matplotlib and native OpenCV GUI windows.

