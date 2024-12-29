# Identifying The Tuberculosis In Chest X-Ray With <br> An Accuracy Of Ninety Percent 
<p align="center">
</a>
</p>
<img src="https://cdn.the-scientist.com/assets/articleNo/66278/aImg/33044/tb.jpg" alt="tomato" width="900" height="580">
<p>Tuberculosis is one of the deadliest diseases and ranks 10th in the leading cause of death worldwide; alone in 2023, there was an estimated total of 1,250,000 tuberculosis-related deaths.The major symptoms of tuberculosis are the cough that lasts more than three weeks, loss of appetite and unintentional weight loss, fever, chills, and night sweats. Most people die because of tuberculous mainly die because of the negligence of symptoms or not getting proper health treatment at the proper time. To fight against this problem and to save countless life I have created this convolutional neural network-based deep learning model that is capable of identifying Tuberculosis with an accuracy of 90%. </p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Numpy</li>
  <li>Open CV</li>
  <li>Glob</li>
</ul> 
<h2>Data Visualization</h2>
<p align="center">
<img src="https://github.com/user-attachments/assets/456b6a87-4c69-4e2b-adc5-c7ff24f4f585" width="730" height="430">
</p>  
<h2>Model Details</h2>
<p> For the identification of tuberculosis, the model at its core uses convolutional and fully connected layers. The model consists of four convolutional layers for feature extraction from the chest x-ray, each followed by a max-pooling layer.  After the four convolutional and max-pooling layers, the model uses three dense layers for the classification task.</p>
<h2>Model Training</h2>
<p>The model was trained for 20 epochs with batch size equals 19. During the training process parse, the binary cross-entropy loss function was used along with the Adam optimizer. The dataset on which the model has trained has been downloaded from Kaggle.com (https://bit.ly/3vw3FJQ). </p>
<h2>Model Evaluation</h2>
<img src="https://github.com/user-attachments/assets/0f589c38-9c79-4003-af57-85d6a13610a8" width="450" height="300">
<p>After training process the model has shown loss: 0.1270 and accuracy: 0.9445 for training data and loss: 0.4219 and accuracy: 0.8955 for validation data (this clearly shows that model trained perfectly without overfitting or underfitting)</p>
<h2>Conclusion</h2>
<p>In this project, I have created a convolution deep neural network architecture that correctly identifies tuberculosis infected chest x-ray with an impressive accuracy of 90 percent.</p>
