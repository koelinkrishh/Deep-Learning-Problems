## Vegetable Classifier

#### Overview:
The Vegetable Classifier is a Convolutional Neural Network (CNN) model built using TensorFlow and Keras to classify images of vegetables into 15 different categories.
The model is trained on a dataset of labeled vegetable images and achieves high accuracy in classification.

<!-- #### How to Run project:

1. **Clone the Repository:**
   ```bash
   git clone "https://github.com/koelinkrishh/Deep-Learning-Problems.git"
   cd "Deep-Learning-Problems/Vegetable Classifier"
   ```

2. **Activate the virtual environment:**
   ```bash
   ..\.venv\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Project:**
   Go to Juypter notebook and run it on your local machine. -->

#### Dataset:
The dataset consists of images categorized into 15 vegetable classes:
1. Bean
2. Bitter Gourd
3. Bottle Gourd
4. Brinjal
5. Broccoli
6. Cabbage
7. Capsicum
8. Carrot
9. Cauliflower
10. Cucumber
11. Papaya
12. Potato
13. Pumpkin
14. Radish
15. Tomato

The dataset is structured into training and validation sets, located in the Vegetable_Images directory.

#### Features:
- Automatic dataset extraction if not already extracted.
- Data normalization to improve model performance.
- Visualization of the first image from each class.
- CNN-based model with multiple convolutional layers.
- Early stopping and learning rate reduction for optimal training.
- Performance plots for accuracy and loss evaluation.

#### Results:
- The model achieves over 95% accuracy on the training and validation sets.
- Performance is comparable to human-level classification.
- The trained model can be used for real-world vegetable recognition tasks.

