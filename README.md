# Image-Classification-of-Brain-Tumor-with-Deep-Learning
This project applies transfer learning to classify brain MRI scans into categories based on the presence or absence of tumors. Pre-trained convolutional neural networks such as VGG16/ResNet/Inception (depending on what you used) were fine-tuned on a brain tumor dataset, enabling the model to leverage learned features from large-scale image datasets while adapting to medical imaging.

The MRI images were preprocessed through normalization, resizing, and data augmentation to enhance model robustness. By freezing early layers of the pre-trained model and fine-tuning deeper layers, the model effectively captured complex tumor-related patterns.

Evaluation using metrics like accuracy, precision, recall, F1-score, and confusion matrix demonstrated the model’s ability to classify brain tumors with high reliability. This project highlights the strength of transfer learning in medical imaging, reducing training time while achieving strong performance, and showcasing the role of AI in assisting radiologists with early diagnosis and decision-making.
