# Image Captioning using ANN

This project uses Artificial Neural Networks to generate captions for images using a subset of the Flickr30k dataset.

## Features
- Uses CNNs (like VGG16) to extract image features
- Processes captions with tokenization and embeddings (Word2Vec / GloVe)
- Trains ANN to map image features + tokens to captions
- Evaluated using BLEU Score, Precision, Recall

## Dataset
- Subset of Flickr30k (200 images)
- Each image has 1 associated caption

## How to Run
1. Install dependencies (`tensorflow`, `keras`, `numpy`, `matplotlib`)
2. Open `ann-captioning.ipynb` in Jupyter or Colab
3. Run all cells to train and test caption generation

## Team
- Muhammad Zamin Khan (22K-4104)
- Abdur Rehman (22K-4105)
- Marium Shahid (22K-8707)
