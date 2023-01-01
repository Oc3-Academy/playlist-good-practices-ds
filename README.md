# playlist-good-practices-ds

Here you can find all material for this specific playlist

# Why to create a method to cluster images?

- Você não conhece a base de dados!
- Sua base de dados pode conter muitas imagens idênticas!
- Imagens idênticas não favorecem seu modelo de machine learning!
- Imagens idênticas podem enviesar seu modelo para um tipo de padrão, e assim você não consegue uma boa acurácia!
- Então, precisamos criar um dataset o mais **informativo** possível!


# Example of informative dataset

- Image features vs Semantic properties

# Possible Solution

- Most of the cases we randomly sampling the data
- But this approach not always is the best solution
- Remove closest datapoints

# Generate Hashing Map

- Here we want to find an signature of the image
- Remove the noise - Rescale - Binarize

# Learning a metric of the data

- Sample equidistant data
- We can also, learn most relevant diverse data

# Strategie

- Remove almost identical datapoints
- identify cluster of similar data
- sample uniformly within each cluster

