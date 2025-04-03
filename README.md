Fake Currency Detection Using Autoencoder

Overview
This project focuses on detecting fake Indian currency notes using Autoencoder and image processing techniques. The model learns the patterns of real currency and identifies anomalies to detect fake notes.

How It Works
1️⃣ Data Collection – Collected real Indian currency note images.
2️⃣ Preprocessing – Resized images for consistency.
3️⃣ Data Splitting – Split into 80% training, 10% validation, and 10% testing.
4️⃣ Loading Images – Preprocessed and loaded the images.
5️⃣ Building Autoencoder Model – Created an Autoencoder to learn real note patterns.
6️⃣ Training the Model – Trained the Autoencoder using only real currency images.
7️⃣ Saving and Loading Model – Saved the trained model for future use.
8️⃣ Testing – Compared new images to learned patterns:
     - If the image matches the real currency pattern ➝ Real Note ✅
     - If the image deviates from the learned pattern ➝ Fake Note ❌
     
Tech Stack & Tools
🔹 Python
🔹 OpenCV (Image Processing)
🔹 TensorFlow / Keras (Autoencoder Model)
🔹 NumPy, Pandas (Data Handling)

Results & Insights
Successfully detected fake currency notes based on image patterns.
Learned practical applications of deep learning, anomaly detection, and image processing.
Improved model performance with better preprocessing and training techniques.
