# Cat and Dog Image Classifier

## About the Project
This project is a convolutional neural network (CNN) based classifier that distinguishes between images of cats and dogs. The model is built using **TensorFlow 2.0** and **Keras** and achieves an accuracy of at least 63%, with potential improvements up to 70%.

## Dataset
The dataset consists of labeled images of cats and dogs, divided into training, validation, and test sets:
```
cats_and_dogs_filtered/
|__ train/
    |______ cats/
    |______ dogs/
|__ validation/
    |______ cats/
    |______ dogs/
|__ test/
    |______ (unlabeled images)
```

## Technologies Used
- Python
- TensorFlow 2.0
- Keras
- NumPy
- Matplotlib

## Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/cat-dog-classifier.git
   ```
2. Navigate to the project directory:
   ```bash
   cd cat-dog-classifier
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open the `cat_dog_classifier.ipynb` file and execute the cells.

## Model Architecture
The CNN model consists of multiple **Conv2D** and **MaxPooling2D** layers, followed by **Dense** layers. The final layer uses a **sigmoid activation function** to classify the images.

## Training the Model
- Data augmentation is applied to prevent overfitting.
- The model is compiled with **binary cross-entropy loss** and **Adam optimizer**.
- The model is trained using **train and validation datasets**.

## Results
After training, the model achieves a classification accuracy of at least **63%**.

## How to Use
1. Run the notebook to train the model.
2. Use the trained model to classify new images.
3. Evaluate model accuracy and visualize results.

## Contribution
Feel free to contribute to this project by submitting a pull request.

## License
This project is open-source under the [MIT License](LICENSE).
