# Recommendor-System
The model is content based recommender system which gives recommendation based on similar title and images.

# Dataset
I used the dataset which was on kaggle which consisted of around 1,83,000 reviews. Link: https://www.kaggle.com/ajaysh/women-apparel-recommendation-engine-amazoncom

# Libraries Used
Used Scikit-Learn and Keras.

# Workflow
The text into vectors through TF-IDF and then used distance metrics to find the similarity between the two texts.
Used a pre-trained VGG16 Model to train images and used  distance metrics to find the similarity between the image vectors.
Then printed out the top n results in sorted form.
