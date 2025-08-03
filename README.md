# Multimodal_and_Multi-label_Classification

This project develops a multi-label classifier on images with captions from Flickr datasets. It uses ResNeXt-50 to extract image embeddings and uses Bi-GRU with attentioan layer to extract caption embeddings. After concatenating these two embeddings, it passes them to a fully-connected layers with BCE loss to predict the label of images. 
