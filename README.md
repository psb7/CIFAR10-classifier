# Train CIFAR10 on PyTorch
The aim of the project is to compare the performance of a simple fully connected model agianst ResNet 18 for CIFAR 10 image classification.

## ⚙️ Requirements
Python version > = 3.6

```shell
pip install torch
pip install torchvision
pip install numpy
pip install matplotlib   
```

## Results

|  | Custom network | ResNet 18 (finetuned) | ResNet18 (frozen convnet) |
|---|--------|------------|---------------|
|Accuracy( 30 epochs)| 62.8% | 77.85% | 36.63%| 
