# Adversarial-Attacks-on-Deep-Neural-Networks


This project investigates both **adversarial attacks** and **defensive strategies** for Deep Neural Networks (DNNs). While adversarial examples exploit vulnerabilities in models by introducing imperceptible perturbations, defensive methods aim to improve robustness and ensure reliable predictions.

### 🎯 Objectives

* Implement popular adversarial attacks such as **FGSM, PGD, and Carlini-Wagner**.
* Train and evaluate models under **clean and adversarial settings**.
* Explore and benchmark **defense mechanisms**, including:

  * **Adversarial training** (robust model retraining).
  * **Input preprocessing** (denoising, normalization).
  * **Regularization techniques** (dropout, weight decay, label smoothing).
* Compare the resilience of different architectures (CNN, ResNet, DenseNet, Inception).
* Provide **visualizations** of perturbations, predictions, and robustness trade-offs.

### 🛠️ Tech Stack

* **Frameworks:** PyTorch, TensorFlow/Keras
* **Models:** CNN, ResNet, DenseNet, Inception
* **Datasets:** MURA (musculoskeletal radiographs), BrainMetShare, and other image classification benchmarks
* **Libraries:** Torchvision, NumPy, scikit-learn, Matplotlib

### 📊 Key Features

* Attack implementations with visualization of adversarial examples.
* Evaluation metrics under clean vs. adversarial conditions.
* **Defensive retraining workflows** to improve robustness.
* Generalization analysis across datasets and architectures.
* Research insights into the **security-accuracy trade-off** in AI.

### 🚀 Applications

* Enhancing the **safety of AI systems** in sensitive domains (medical imaging, self-driving, cybersecurity).
* Benchmarking adversarial robustness for academic and industry ML systems.
* Contributing to **AI security and trustworthiness research**.
