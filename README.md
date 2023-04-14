# YOLOv5toAdversarialAttacks
Evaluating the Vulnerability of YOLOv5 to Adversarial Attacks for Enhanced Cybersecurity in MASS

A paper was submitted to the Journal of Marine Science and Engineering. https://www.mdpi.com/journal/jmse

We will provide a link to the paper once it is published.
In the paper, we generate adversarial examples with four types of attacks (FGSM, I-FGSM, MI-FGSM, PGD), six types of DNN algorithms (AlexNet, VGG16, GoogLeNet, ResNet50, InceptionNetv3, and EfficientNetv2s), and varying values of the epsilon hyperparameter to evaluate the vulnerability of YOLOv5.

The source code is written in Python and uses the PyTorch framework.
We preprocess the SMD-Plus dataset according to the experimental procedure described in the paper (source codes 1-3). Then, generate adversarial examples using various settings (source code 4) and finally train and evaluate YOLOv5 using these adversarial examples (source code 5).

We used the SMD-Plus dataset for our experiments. SMD-Plus Download in below url: https://github.com/kjunhwa/SMD-Plus

Please refer to the following link for YOLOv5. https://github.com/ultralytics/yolov5
