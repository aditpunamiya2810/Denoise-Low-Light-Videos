# Denoise-Low-Light-Videos
This project aims to denoise video frames captured in low-light conditions by leveraging overcomplete autoencoders. Low-light videos typically suffer from significant noise, leading to poor visual quality and performance issues in downstream computer vision tasks.
We use deep learning to reconstruct cleaner frames, frame-by-frame, and reassemble them into a final enhanced video.

✨ Features
Extracts frames from a given low-light video.

  Denoises each frame using a trained overcomplete autoencoder.

  Reconstructs the video from the denoised frames.

  Modular code structure for easy customization and extension.

# Model Architecture
  The Overcomplete Autoencoder has:

    An encoder that maps noisy input to a higher-dimensional feature space.

    A decoder that reconstructs the denoised frame.

Key characteristics:

  More neurons in the hidden layers than input dimension.

  Relu activations and skip connections to retain details.
