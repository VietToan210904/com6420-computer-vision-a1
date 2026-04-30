# com6420-computer-vision-a1
A computer vision project that develops and evaluates deep learning models to classify hand gestures (rock, paper, scissors), including real-world testing through webcam-based data collection.

Made by Tony Hoang - 60858397 MQU

This project focuses on building an image classification system using deep learning techniques to recognize hand gestures (rock, paper, scissors). The workflow begins with dataset preparation, including random partitioning into training, validation, and test sets while maintaining class balance, followed by exploratory data analysis to understand data distribution and quality.

Two classification approaches are implemented and compared. The first approach involves designing a custom convolutional neural network (CNN) using multiple convolutional, pooling, and activation layers. The second approach leverages transfer learning by applying a pre-trained MobileNet model with a modified classification head, while freezing the base model weights. Both models are trained, validated, and evaluated to compare performance based on accuracy, confusion matrices, and error analysis, including identification of common misclassification patterns.

The project further extends to real-world deployment by generating a new dataset using webcam-captured images for each gesture class. The selected model is fine-tuned on this new dataset and evaluated to assess performance differences before and after fine-tuning. This stage highlights model generalization and adaptability to new data distributions.

The final deliverables include a fully executed Jupyter Notebook containing implementation code, visualizations, evaluation results, and analytical explanations, along with a generated dataset of images. The project demonstrates practical skills in computer vision, deep learning, model evaluation, and applied AI system development
