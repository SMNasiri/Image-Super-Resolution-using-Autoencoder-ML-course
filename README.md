# Image-Super-Resolution-using-Autoencoder-ML-course
Image Super Resolution using Autoencoder implemented in PyTorch, enhancing the resolution of images from a low-resolution input to high-resolution output. This project includes training on a specialized dataset, visualizing reconstructed outputs, and evaluating performance with learning curves and sample comparisons.

This project implements an **Image Super Resolution** technique using **Autoencoders** in PyTorch. The model is designed to enhance low-resolution images to high-resolution versions. The dataset is preprocessed and trained to produce visually improved results while maintaining computational efficiency.

---

## Features
- **Dataset**: Utilizes a custom dataset split into training, validation, and test sets.
- **Model**: A deep autoencoder architecture designed in PyTorch for super-resolution tasks.
- **Training**: Includes the implementation of loss functions, optimizers, and learning rate schedules.
- **Visualization**:
  - Learning curves for monitoring training progress.
  - Comparison of low-resolution images, reconstructed high-resolution images, and ground-truth images.

---


   - Techniques such as early stopping and model checkpoints are used to ensure robust performance.

3. **Evaluation**:
   - Plots of the learning curve are generated to track loss over epochs.
   - Side-by-side visualizations of low-resolution, reconstructed, and high-resolution images from the test set are presented for qualitative analysis.

