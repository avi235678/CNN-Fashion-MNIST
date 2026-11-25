CNN Fashion MNIST Classification



\---



📌 Project Overview



This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify fashion images into 10 different clothing categories.



The model learns image features such as edges, shapes, and patterns to identify different types of clothing.



🎯 Project Objectives



\- Understand Convolutional Neural Networks.

\- Perform image preprocessing and normalization.

\- Build a CNN architecture using TensorFlow and Keras.

\- Train and evaluate the CNN model.

\- Classify fashion images into 10 categories.

\- Analyze model performance using evaluation metrics.



🛠️ Technologies Used



\- Python

\- TensorFlow

\- Keras

\- NumPy

\- Pandas

\- Matplotlib

\- Seaborn

\- Scikit-learn

\- Jupyter Notebook



📂 Dataset Information



Dataset Name: Fashion MNIST



The Fashion MNIST dataset contains 70,000 grayscale images of clothing items.



Description| Details

Training Images| 60,000

Testing Images| 10,000

Total Images| 70,000

Image Height| 28 Pixels

Image Width| 28 Pixels

Color Channel| 1 (Grayscale)

Number of Classes| 10



👕 Fashion Categories



1\. T-shirt/top

2\. Trouser

3\. Pullover

4\. Dress

5\. Coat

6\. Sandal

7\. Shirt

8\. Sneaker

9\. Bag

10\. Ankle boot



🔄 Project Workflow



flowchart TD

&#x20;   A\["Fashion MNIST Dataset"] --> B\["Data Loading"]

&#x20;   B --> C\["Data Visualization"]

&#x20;   C --> D\["Image Preprocessing"]

&#x20;   D --> E\["Normalization"]

&#x20;   E --> F\["Image Reshaping"]

&#x20;   F --> G\["CNN Model Building"]

&#x20;   G --> H\["Model Compilation"]

&#x20;   H --> I\["Model Training"]

&#x20;   I --> J\["Model Evaluation"]

&#x20;   J --> K\["Confusion Matrix"]

&#x20;   K --> L\["Classification Report"]

&#x20;   L --> M\["Image Prediction"]

&#x20;   M --> N\["Save Trained Model"]



🧠 CNN Architecture



The CNN model consists of the following layers:



1\. Input Layer – 28 × 28 × 1

2\. Conv2D – 32 Filters, 3 × 3 Kernel, ReLU

3\. MaxPooling2D – 2 × 2

4\. Conv2D – 64 Filters, 3 × 3 Kernel, ReLU

5\. MaxPooling2D – 2 × 2

6\. Flatten Layer

7\. Dense Layer – 128 Neurons, ReLU

8\. Dropout Layer – 0.5

9\. Output Layer – 10 Neurons, Softmax



CNN Architecture Diagram



flowchart TD

&#x20;   A\["Input Image 28x28x1"] --> B\["Conv2D - 32 Filters"]

&#x20;   B --> C\["MaxPooling2D"]

&#x20;   C --> D\["Conv2D - 64 Filters"]

&#x20;   D --> E\["MaxPooling2D"]

&#x20;   E --> F\["Flatten"]

&#x20;   F --> G\["Dense - 128 Neurons"]

&#x20;   G --> H\["Dropout - 0.5"]

&#x20;   H --> I\["Output - 10 Classes"]



⚙️ Model Training Configuration



Parameter| Value

Optimizer| Adam

Loss Function| Sparse Categorical Crossentropy

Metric| Accuracy

Epochs| 10

Batch Size| 64

Validation Split| 0.1



📊 Model Performance



The CNN model achieved the following results:



Evaluation Metric| Result

Training Accuracy| 91.58%

Validation Accuracy| 91.48%

Testing Accuracy| 90.85%

Testing Loss| 0.2612



📈 Model Evaluation



The model was evaluated using:



\- Training and Validation Accuracy Graph

\- Training and Validation Loss Graph

\- Confusion Matrix

\- Classification Report

\- Precision

\- Recall

\- F1-Score

\- Actual vs Predicted Results



💾 Model Saving



The trained CNN model is saved in Keras format.



Model File: "cnn\_fashion\_mnist.keras"



The saved model can be loaded using TensorFlow Keras.



📁 Project Structure



CNN\_Fashion\_MNIST/

│

├── notebooks/

│   └── CNN\_Fashion\_MNIST.ipynb

│

├── models/

│   └── cnn\_fashion\_mnist.keras

│

├── reports/

│

├── README.md

│

├── requirements.txt

│

└── .gitignore



🚀 Installation and Execution



1\. Clone Repository



git clone YOUR\_GITHUB\_REPOSITORY\_URL



2\. Navigate to Project Folder



cd CNN\_Fashion\_MNIST



3\. Install Required Libraries



pip install -r requirements.txt



4\. Open Jupyter Notebook



jupyter notebook



Open "CNN\_Fashion\_MNIST.ipynb" and run the cells.



📝 Conclusion



This project demonstrates how Convolutional Neural Networks can be used for image classification.



The CNN model successfully classifies Fashion MNIST images into 10 different clothing categories and achieved 90.85% testing accuracy.



Through this project, I gained practical knowledge of CNN architecture, image preprocessing, model training, and model evaluation.



👩‍💻 Author



Shubhangi Salunke



Machine Learning and Deep Learning Enthusiast



\---



⭐ If you find this project useful, consider giving it a star!

