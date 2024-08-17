# Sugarcane Leaf Disease Classification Using Deep Learning

I am excited to share one of my latest works in deep learning: implementing and extending the **Sugarcane Leaf Disease Classification Using Deep Learning** paper published by Springer, with additional experiments and modifications to deep learning architectures.

In this work, I applied a range of advanced techniques, including:

- **Data Balance Analysis** (Count Plot)
- **Image Preprocessing** (Resizing, Normalization)
- **Transfer Learning and Early Stopping**
- **Modifications of Deep Learning Architectures** (InceptionV3, LeNet, VGG16, EfficientNet, Xception, DenseNet169, and DenseNet201)
- **Training Performance Monitoring** (Accuracy Curves, Loss Curves)
- **Model Evaluation** (Accuracy, Confusion Matrix, Classification Report)

I trained all models for 100 epochs, with early stopping triggered if validation loss did not improve for 10 consecutive epochs.

The results of my experiments outperformed those reported in the original paper by around 3%. While the paper’s top accuracy, achieved with a customized VGG16, was **94.47%**, my best result came from a customized Xception model, which achieved an impressive accuracy of **97.77%**.


## All Models Results

![Models Results](https://github.com/user-attachments/assets/52081396-f473-4a9d-9863-a0adce1122c6)

---

Feel free to explore the code and experiments in this repository. Contributions and feedback are welcome!
