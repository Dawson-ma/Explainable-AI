# Explainable AI

Implementing various techniques for explainable AI, including Lime, Saliency Map, Smooth Grad, Filter Extraction, Integrated Gradient for CNN model visualization, and applying Attention Visualization, Embedding Visualization, and Embedding Analysis on BERT.

## CNN Visualization Techniques
1. [Lime](https://github.com/marcotcr/lime): Utilizes localized perturbations to interpret model predictions.
2. [Silency Map](https://medium.datadriveninvestor.com/visualizing-neural-networks-using-saliency-maps-in-pytorch-289d8e244ab4): Visualizes the areas of an input image that contribute most to the model's decision.
3. [Smooth Grad](https://arxiv.org/pdf/1706.03825.pdf): Enhances the interpretability of CNN models by adding noise to the input image and observing its effect on the model's output.
4. Filter Extraction: Extracts and visualizes the features learned by individual filters in the CNN layers.
5. Integrated Gradient: Calculates the gradient of the model's output with respect to the input image to reveal important pixels contributing to the prediction.

## BERT Visualization Techniques
1. [Attention Visualization](https://exbert.net/exBERT.html): Provides insights into the attention mechanism of BERT by visualizing attention weights between input tokens.
2. Embedding Visualization: Visualizes the embedding space of BERT to understand relationships between tokens.
3. Embedding Analysis: Analyzes the embeddings produced by BERT to extract meaningful insights.

## Dataset and Model
The provided [dataset](https://drive.google.com/file/d/1G7DAsAOPFazTkQyd8O5uMr0TP4cgcTVS/view?usp=sharing), [CNN model](https://drive.google.com/file/d/your_cnn_model/view?usp=sharing), [BERT's embedding](https://drive.google.com/file/d/1jYWRyqZOlhNa3B7WLAIuKL8fvapMKm9Z/view?usp=sharing), and [display font](https://drive.google.com/file/d/1oQ9OByXz0pzfelGZY8R1N3aeANl2luaQ/view?usp=sharing) are included.

For detailed implementation and usage instructions, please refer to the provided [code](https://github.com/Dawson-ma/Explainable-AI/blob/main/ExplainableAI.ipynb).
