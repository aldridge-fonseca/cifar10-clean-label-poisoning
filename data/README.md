# Data

This repo includes CIFAR-10 in the Python batch format used by torchvision.

The notebooks read the files from:

```text
data/cifar-10-python/cifar-10-batches-py/
```

The experiment uses four classes: Plane, Car, Bird, and Cat. It samples 500 training images per class and 100 test images per class. Ten Plane images are held out as targets, and ten Bird images are used as bases for poison generation.

Generated tensors, trained weights, and checkpoints are not tracked.
