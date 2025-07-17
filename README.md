# LUNG-CANCER-DETECTION
This project uses a Convolutional Neural Network (CNN) to detect lung cancer from chest X-ray images. It includes data preprocessing, model training, validation, and single image prediction. Ideal for beginners in deep learning or healthcare-related AI applications.

🔬 Lung Cancer Detection Using CNN
This project implements a Convolutional Neural Network (CNN) to detect lung cancer from chest X-ray images using Python and TensorFlow (Keras). The model is trained to classify images as either CANCER or NORMAL.

📁 Project Structure

Lung Cancer Detection Project Code.ipynb

└── train/             # Training images (CANCER / NORMAL folders)

└── val/               # Validation images (CANCER / NORMAL folders)

└── test/              # Testing images (CANCER / NORMAL folders)

🧠 Key Features

1.Preprocesses image data using ImageDataGenerator

2.Builds and trains a CNN model using Keras

3.Evaluates accuracy and loss on validation data

4.Accepts single image upload for prediction after training

5.Returns "CANCER" or "NORMAL" label for uploaded X-ray

🛠 Requirements

Install the following Python libraries before running:

  pip install tensorflow opencv-python numpy matplotlib

🚀 How to Run the Project

1.Download Dataset: Organize your images in the following directory structure:

/train/CANCER

/train/NORMAL

/val/CANCER

/val/NORMAL

/test/CANCER

/test/NORMAL

2.Open the Jupyter Notebook

3.Launch Lung Cancer Detection Project Code.ipynb using Jupyter Notebook or Google Colab.

4.Run All Cells

5.Execute all cells in order to:

6.Load and preprocess the dataset

7.Train and evaluate the CNN model

8.Save the model

9.Predict on a Single Image

10.After training, upload an X-ray image using the file upload cell. The model will return either "CANCER" or "NORMAL" as the prediction.

📌 Example Output

✅ Prediction: This X-ray image shows signs of CANCER.

📎 Notes

Model works best when trained with sufficient and high-quality labeled data.

No visualizations included — only results for clarity and focus.

Can be extended with GUI or real-time camera input in future versions.

👤 Author

B R VIMAL AANANTH

GitHub: github.com/Ashwinvimal

