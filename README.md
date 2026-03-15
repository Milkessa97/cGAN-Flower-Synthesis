<div align="center">
  <h1>🌸 The Generative Art Studio 🎨</h1>
  <p><i>A Deep Learning Journey into the Latent Space of Flowers</i></p>
  
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" />
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" />
</div>

<br />

## 🎭 The Concept: Minimax Artistry
This project implements a **Conditional Generative Adversarial Network (cGAN)**. Unlike standard GANs, this model doesn't just "paint"—it listens to "prompts" (labels). By training on the **TF Flowers** dataset, the system learned to bridge the gap between random Gaussian noise and botanical reality.

---

## 📽️ Evolution Gallery (Animation)
> **[Instruction for User]**: *To truly make your README "pop," take the `evolution_snapshots` you saved, turn them into a `.gif`, and replace the link below!*

<div align="center">
  <img src="https://media.giphy.com/media/your-cool-gan-gif-here/giphy.gif" width="600" alt="GAN Training Evolution Animation" />
  <p><i>Evolution from Epoch 1 (Noise) to Epoch 200 (Flowers)</i></p>
</div>

---

## 🧪 Technical Performance Audit
On **Day 4**, I conducted a deep dive into the architecture's efficiency.

<table align="center">
  <tr>
    <td align="center"><b>Metric</b></td>
    <td align="center"><b>Result</b></td>
    <td align="center"><b>Analysis</b></td>
  </tr>
  <tr>
    <td><b>Training Cycles</b></td>
    <td>200 Epochs</td>
    <td>Stable convergence achieved.</td>
  </tr>
  <tr>
    <td><b>Memory Footprint</b></td>
    <td>~XX.X MB</td>
    <td>Convolutional layers used 5x less RAM than FC layers.</td>
  </tr>
  <tr>
    <td><b>Optimization</b></td>
    <td>Adam Optimizer</td>
    <td>Learning rate $2e-4$ with $\beta_1=0.5$.</td>
  </tr>
</table>

---

## 🧩 Latent Space Exploration
Using **Seed Arithmetic**, I explored the "manifold" between two random points in the model's imagination.

### 🌓 The Morphing Reel
Moving from **Seed A** to **Seed B** within the same class allows us to see how the model interprets features like petal density and light.

`[zA * (1 - α) + zB * α]`

<div align="center">
  <img src="https://via.placeholder.com/800x200.png?text=Your+Morphing+Reel+Output+Here" width="800" />
</div>

---

## ⚠️ Researcher's Log: Failure Insights
Every great artist has a "Blue Period." Mine was the **Pink Sunflower Period**.

> **Leakage Detected:** During Epoch 160+, the model began to "leak" colors across classes. 
> * **Symptom:** Sunflowers sprouted rose-pink petals. 
> * **Lesson:** Localized features are difficult to disentangle when the dataset shares high color-variance.
> * **Artifact:** Noticed the **"Chequerboard Pattern"** due to Transposed Convolutions.

---

<div align="center">
  <h3>Stop by the Studio again!</h3>
  <p>Project completed for the <b>Generative Art Studio Challenge</b></p>
  <p>📅 Deadline: Friday 7:00 PM EAT | ✅ Status: Submitted</p>
</div>
