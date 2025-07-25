<h1>🌾 Crop Detection using Convolutional Neural Networks (CNN)</h1>

<p>
    This project focuses on identifying various crop types using deep learning techniques.
    A Convolutional Neural Network (CNN) is trained on the PlantVillage dataset to automatically classify crops from leaf images.
</p>

<h2>📌 Project Overview</h2>
<p>
    The goal of this project is to develop a machine learning model that can accurately detect the type of crop from an image of its leaf.
    This model can be useful for:
</p>
<ul>
    <li>Farmers and agricultural experts</li>
    <li>Precision agriculture</li>
    <li>Disease and pest management (with extensions)</li>
</ul>

<h2>🧠 Technologies Used</h2>
<ul>
    <li>🐍 Python</li>
    <li>📦 TensorFlow / Keras</li>
    <li>📊 NumPy, Pandas</li>
    <li>🖼️ OpenCV</li>
    <li>📉 Matplotlib & Seaborn</li>
    <li>💻 Jupyter Notebook</li>
</ul>

<h2>🗂️ Dataset</h2>
<p>
    We use the <strong>PlantVillage Dataset</strong>, which contains images of healthy and diseased leaves of multiple crops.
    For this specific project, only healthy crop images are used to train the model.
</p>
<p><strong>📁 Total Images:</strong> ~54,000+</p>
<p><strong>🌿 Classes:</strong> Tomato, Potato, Pepper, Maize, Grape, etc.</p>
<p>📌 You can download the dataset from <a href="https://www.kaggle.com/datasets/emmarex/plantdisease">PlantVillage Dataset on Kaggle</a>.</p>

<h2>🚀 Model Architecture</h2>
<ul>
    <li>✅ <strong>Input layer:</strong> 128x128 RGB images</li>
    <li>✅ Convolution + MaxPooling layers (3 sets)</li>
    <li>✅ Flatten layer</li>
    <li>✅ Fully connected (Dense) layers</li>
    <li>✅ Output layer: Softmax activation for multi-class classification</li>
</ul>

<h2>📊 Training Summary</h2>
<ul>
    <li>Epochs: 10–30 (can be tuned)</li>
    <li>Accuracy Achieved: ~95%+</li>
    <li>Loss Function: Categorical Crossentropy</li>
    <li>Optimizer: Adam</li>
</ul>

<h2>📈 Results</h2>
<p>The model performs well with high training and validation accuracy. Here are some sample outputs:</p>
<table border="1" cellpadding="5" cellspacing="0">
    <tr>
        <th>Actual Crop</th>
        <th>Predicted Crop</th>
        <th>Confidence</th>
    </tr>
    <tr>
        <td>Tomato</td>
        <td>Tomato</td>
        <td>97.2%</td>
    </tr>
    <tr>
        <td>Grape</td>
        <td>Grape</td>
        <td>96.4%</td>
    </tr>
    <tr>
        <td>Potato</td>
        <td>Potato</td>
        <td>95.8%</td>
    </tr>
</table>

<h2>📷 Sample Predictions</h2>
<p>Sample Prediction Image</p>
<p>Sample Prediction Image</p>

<h2>🧪 Evaluation Metrics</h2>
<ul>
    <li>Accuracy</li>
    <li>Confusion Matrix</li>
    <li>Precision / Recall / F1-Score</li>
</ul>

<h2>📌 Future Work</h2>
<ul>
    <li>Add disease classification</li>
    <li>Deploy as a mobile/web app</li>
    <li>Include image segmentation for leaf detection</li>
</ul>

<h2>✍️ Author</h2>
<p>
    Keshavardhan Makireddi<br>
    Department of Computer Science and Engineering<br>
    Indian Institute of Information Technology, Nagpur<br>
    📧 Email: <a href="mailto:bt22csa016@iiitn.ac.in">bt22csa016@iiitn.ac.in</a>
</p>
