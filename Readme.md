# GAN Basics – Generative Adversarial Network from Scratch

Learn the fundamentals of GANs (Generative Adversarial Networks) using TensorFlow and Python, with a step-by-step Jupyter Notebook tutorial.

---

## 🎯 Objective

This project demonstrates how to build and train a basic Generative Adversarial Network (GAN) to generate handwritten digits that resemble the MNIST dataset.

It's ideal for **beginners** who want to understand:
- How GANs work
- How to construct generator and discriminator models
- How adversarial training improves both models over time

---

## 🛠️ Technologies Used

- 🐍 Python
- 🧠 TensorFlow (Deep Learning Framework)
- 📊 NumPy
- 📉 Matplotlib
- 📓 Jupyter Notebook

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `GAN Basics.ipynb` | Main notebook that walks through GAN implementation and training |
| `helper.py`        | Helper functions (like plotting generated images, generating noise, etc.) |

---

## 🤖 What the GAN Does

- The **Generator** creates fake handwritten digit images from random noise.
- The **Discriminator** tries to distinguish real MNIST digits from fake ones.
- Over time, both models get better:
  - The **Generator** produces more realistic images.
  - The **Discriminator** becomes harder to fool.

The result: A model that can generate synthetic, MNIST-like digits!

---

## 🧪 Output Samples

During training, the notebook displays generated images after every few epochs, showing how the GAN improves over time.

![Sample Output](https://raw.githubusercontent.com/rishi7838/GANBasics/main/sample_output.png) <!-- Replace with your own output screenshot -->

---

## ▶️ How to Run

1. **Clone the repo**:
   ```bash
   git clone https://github.com/rishi7838/GANBasics.git
   cd GANBasics
    
2. **Install dependencies**:
   ```bash
    pip install tensorflow numpy matplotlib

3. **Launch Jupyter Notebook**:
   ```bash
    jupyter notebook

4. **Open GAN Basics.ipynb and run the cells**:



