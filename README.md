# 🧠 Medical Anomaly Detection using Variational Autoencoder (VAE)

This project uses a **Variational Autoencoder (VAE)** to detect anomalies in medical imaging — specifically chest X-ray-type images — using **unsupervised deep learning**.

## Project Highlights
- Trains a VAE on normal images to learn their latent representation
- Anomalies are detected based on high reconstruction error
- Ideal for situations with limited or no labeled data

## Tech Stack
- Python, PyTorch, Torchvision
- OpenCV, TensorBoard

## Why VAE?
Instead of relying on labeled anomalies, this project learns what "normal" looks like, and flags anything that's reconstructed poorly — a powerful approach for real-world medical applications.

## 👨‍🔬 Author
Made with ❤️ by [Aayush Saxena](https://www.linkedin.com/in/storytellingengineer/)
