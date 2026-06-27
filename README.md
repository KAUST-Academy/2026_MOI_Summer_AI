# MOI MEng-AI Cohort 3 — Summer AI Training
*Designed by the KAUST Academy*

A static course website with lectures and labs for the three-week MEng-AI Cohort 3
Summer Training. Content is organised into one page per day, grouped by week. Each
day links to its lecture slides (`Week*/Day*/Lecture/`) and to its labs and
exercises (`Week*/Day*/Labs/`), which open directly in Google Colab.

The site is fully responsive and works on desktop and mobile.

---

## Structure

```
index.html          # Home — hero + all three weeks
w1d1.html … w3d4.html   # one page per day (14 days)
assets/             # Bootstrap, icons, AOS, CSS and JS
Week1/ Week2/ Week3/    # course content: Lecture/ (PDF) + Labs/ (.ipynb)
```

Colab links point to this repository on the `main` branch:
`https://colab.research.google.com/github/KAUST-Academy/2026_MOI_Summer_AI/blob/main/…`
They become live once the repository is pushed to GitHub.

---

## Week 1 — Foundations & Computer Vision
Neural network fundamentals, CNNs, and the core computer vision tasks of detection
and segmentation.

1. **Introduction to Neural Networks** — Fundamentals of deep learning; PyTorch basics; NN from scratch (NumPy & PyTorch) on MNIST.
2. **Deep Learning** — Data augmentation, transfer learning, fine-tuning (Cats & Dogs), pretrained VGG.
3. **Convolutional Neural Networks** — CNN architectures; CNN from scratch (Fashion-MNIST); CIFAR-10 classifier.
4. **Object Detection** — Faster R-CNN, YOLO, and PPE detection.
5. **Image Segmentation** — Custom U-Net, SMP U-Net, brain MRI tumor segmentation, YOLO fire & smoke.

## Week 2 — Sequence Models & Modern Architectures
Recurrent networks, Transformers, Vision Transformers, and self-supervised learning.

1. **Recurrent Neural Networks** — RNN/LSTM/GRU, many-to-one, one-to-many, image captioning.
2. **Transformers** — Self-attention & multi-head attention, Transformer captioning, BERT.
3. **Vision Transformers** — ViT fine-tuning.
4. **Self-Supervised Learning** — SimCLR, JEPA models.
5. **Contrastive Learning** — SimCLR, JEPA models.

## Week 3 — Reinforcement Learning
From RL foundations to policy gradients, continuous control, and advanced topics.

1. **RL Foundations & Value-Based Methods** — Q-learning, SARSA, DQN.
2. **Policy Gradient Methods** — REINFORCE, Actor-Critic, PPO, TRPO.
3. **Continuous Control** — SAC, DDPG, reward design.
4. **Advanced RL Topics** — Inverse RL, multi-agent PPO, multi-armed bandits, SAC manipulation.

---

*Note: exercise notebooks are paired with their `_Solution` versions where available.
Recording and uploading lectures online is not permitted.*

Website created by **Ali Habibullah**.
