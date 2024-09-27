# Image_Encryption using Conditional Cycle Gan using encoder-decoder structure
Adversarial Cryptographic Model for Secure Image Transmission
Overview
This project implements an advanced cryptographic model that encrypts images being transmitted over insecure networks. The model combines neural network-based encryption with quantum-safe cryptography to ensure future-proof security. It dynamically adjusts encryption strategies based on real-time network conditions and threat levels, using blockchain for decentralized key management and storage.

Key Features
Neural Network Encryption: Differentiable encryption using custom-trained neural networks for enhanced security.
Quantum-Safe Cryptography: Utilizes quantum-resistant algorithms to safeguard against future quantum threats.
Dynamic Algorithm Selection: Automatically adapts encryption methods based on network conditions and detected threats.
Adversarial Defense: Incorporates adversarial training to protect against attacks aimed at breaking encryption.
Key-Image Encryption: Uses an image as the encryption key for added unpredictability and security.
Blockchain Key Management: Secure, decentralized management of encryption keys using blockchain technology
.![Image (1)](https://github.com/user-attachments/assets/aa92fe26-db01-4bfb-ba91-76260d51b143)

HOW IT WORKS
The generator model learns to transform an input image into an encrypted form based on a conditional key. This transformation is achieved through a series of convolutional layers that process the image data in a way similar to how traditional encryption algorithms operate by scrambling the data.
![1_PVBSmRcCz9xfw-fCNi_q5g](https://github.com/user-attachments/assets/3425e3bc-6406-485e-8a9f-1ae381a3d079)
Encoder: Compresses the image to a latent space, capturing important features for transformation.
Residual Blocks: Ensures that essential information about the image is not lost during the transformation.
Decoder: Expands the compressed features into the target domain while maintaining the structure of the input

