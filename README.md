# 🐶🐱 Cat vs Dog Image Classifier (ResNet18 + PyTorch)

This project is an image classification model built using **ResNet18** and **transfer learning** with **PyTorch**. It classifies images of cats and dogs using a custom dataset structured in the `ImageFolder` format.

Used in Kaggle, but you can adapt to local files or Google Drive.

## 🚀 Model

- **Architecture:** ResNet18 (pretrained)
- **Loss:** CrossEntropyLoss
- **Optimizer:** Adam
- **Metric:** Accuracy

## 🧠 Features

- Uses transfer learning from pretrained ResNet18.
- Handles datasets using `torchvision.datasets.ImageFolder`.
- Applies normalization, resizing, and batching.
- GPU-enabled training (if available).

## 📝 Dependencies

Install dependencies using pip:

```bash
pip install -r requirements.txt
```
## Author
- Satyam Kurum
- B.Tech, NITK Surathkal

