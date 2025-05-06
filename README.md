# SCConv ResNet Cifar

Reimplementation of **SCConv-ResNet-50** on CIFAR-10 and CIFAR-100 datasets. This project benchmarks SCConv-enhanced ResNet-50 against the baseline ResNet-50 in terms of accuracy, training time, model size, and FLOPs.

---

## 📊 CIFAR-10 Results

| Model              | Accuracy (%) | Training Time (min) | Params (M) | FLOPs (G) |
|-------------------|--------------|----------------------|------------|-----------|
| ResNet-50          | 82.04        | 29.47                | 23.53      | 0.08      |
| SCConv-ResNet-50   | 82.32        | 42.62                | 17.58      | 0.06      |

**Comparative Analysis**  
- Accuracy Gain: **+0.28%**  
- Time Increase: **+789.21 sec (1.45× slower)**  

---

## 📊 CIFAR-100 Results

| Model              | Accuracy (%) | Training Time (min) | Params (M) | FLOPs (G) |
|-------------------|--------------|----------------------|------------|-----------|
| ResNet-50          | 49.49        | 14.74                | 23.71      | 0.08      |
| SCConv-ResNet-50   | 51.04        | 21.29                | 17.76      | 0.06      |

**Comparative Analysis**  
- Accuracy Gain: **+1.55%**  
- Time Increase: **+393.02 sec (1.44× slower)**  

---

## 🛠️ Notes

- This is an **independent reimplementation** of SCConv with ResNet-50 for CIFAR classification.
- Not affiliated with the official paper or authors.

---

## 📁 Project Structure

- `models/` — Modified ResNet-50 with SCConv modules  
- `train.py` — Training script for CIFAR datasets  
- `configs/` — Training configurations for CIFAR-10 and CIFAR-100  

---

## 📜 License

This repository is open for academic and research use. Please cite the original SCConv paper if used in publications.

