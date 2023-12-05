# Creating-Brain-MRI-Images-with-DC-GAN

Developed by: Apoorva Goswami

This project leverages Generative Adversarial Networks (GANs) to augment a dataset of brain tumor MRI images for improved machine learning model training. Using TensorFlow and Keras, the code defines a GAN architecture comprising a generator and discriminator. The generator produces synthetic images from random noise, while the discriminator distinguishes between real and synthetic images. Over ten training epochs, the GAN refines its ability to generate convincing images that closely resemble the characteristics of real brain tumor MRI scans. The code provides visualizations of the generated images and evaluates their quality through distribution comparisons with real images, demonstrating the potential effectiveness of synthetic data for enhancing the diversity of the training dataset.

Following training, the project evaluates the generated images by comparing their distributions with those of real images. The close resemblance of the distributions suggests that the synthetic data captures essential variations present in the original dataset. The success of the project is assessed not only through visual inspection but also through potential metrics like Average Log-likelihood, Inception Score, and Wasserstein Metric. The generated images, when integrated into the training dataset, have the potential to enhance the robustness and generalization of machine learning models focused on brain tumor detection in MRI images, contributing to improved performance in medical image analysis tasks.




