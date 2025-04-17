#  MNIST Autoencoder with 3D Latent Space Visualization

This project demonstrates how to build and train an **autoencoder neural network** on the MNIST dataset using TensorFlow/Keras. The model compresses 28×28 pixel images of handwritten digits into a **3-dimensional latent space**, and then reconstructs them. The 3D latent features are visualized using **t-SNE** and **Plotly** to explore how different digit classes cluster in this reduced space.

---

##  Features

- Trains an autoencoder on the MNIST handwritten digit dataset
- Encodes images into a 3D latent representation
- Applies t-SNE for dimensionality reduction
- Generates an interactive 3D scatter plot using Plotly
- Useful for unsupervised learning, clustering, and data visualization

---

##  Dataset

- **MNIST Dataset** (from TensorFlow/Keras)
  - 60,000 training samples
  - 10,000 test samples
  - Grayscale 28x28 pixel images
  - 10 digit classes (0 through 9)

---


# Technology used

- Python 3.7+

- TensorFlow

- scikit-learn

- plotly

- numpy

  
---


##  Installation

Clone the repo and install the dependencies:

```bash
git clone https://github.com/your-username/mnist-autoencoder-3d.git
cd mnist-autoencoder-3d
pip install tensorflow scikit-learn plotly
