# Project: Image De-Raining using Deep-Learning

Rain streaks can blur or distort images, making them visually unappealing or difficult to interpret. Deraining can improve the accuracy and reliability of decision-making systems by providing clear visuals in rainy weather. Rain streak removal can lead to a 25% improvement in object detection accuracy under rainy conditions for surveillance systems and autonomous vehicles. Image Deraining has significance in critical applications, where visibility is critical such as Surveillance applications, Autonomous vehicles, Traffic management, Photography and photo editing, and Satellite imaging.

Given the benchmark dataset of  Rain100H, Rain100L, Test100, Test1200, Test2800 (https://github.com/swz30/MPRNet/blob/main/Deraining/Datasets/README.md, https://www.kaggle.com/datasets/shivakanthsujit/jrdr-deraining-dataset), the code added here (a part of a group project) does the following:
 * Give a denoised (de-rained) high-quality image output from an input rainy image using a CNN.
 * Train, validate, test, and evaluate the architecture using metrics: MSE, Peak Signal to Noise Ratio (PSNR), Structural Similarity Index (SSIM).


This was an academic group project where we implemented De-Noising using CNN and C-GAN models. I developed the CNN part and this folder contains to the code for the same. The GAN part was developed by my colleague, the details of which are mentioned in the draft paper. We also developed a UI for this project (details in the draft paper).
