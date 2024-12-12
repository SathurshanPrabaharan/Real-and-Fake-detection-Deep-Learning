OBJECTIVE:
Create a model that classifies the faces into real and fake.

PROPOSED MODELS:
1. Convolutional Neural Network (CNN)
2. Transfer Learning with VGG16


CONCLUSION:
This group project, undertaken as part of the Deep Learning course by Sajishvar M, Sathurshanth P, Joshua J T, and Paul Tharukshan T, aimed to evaluate the performance of two models.

The CNN model demonstrated a validation loss of 0.9330 and a validation accuracy of 49.75%, whereas the Transfer Learning model achieved a lower validation loss of 0.87555 and a higher validation accuracy of 53.19%. These metrics suggest that the Transfer Learning model, benefiting from pre-trained weights and a larger dataset, generalizes better during validation.

However, real-world testing reveals a different outcome. The CNN model classified 9 out of 10 test images correctly (90% accuracy), outperforming the Transfer Learning model, which classified only 6 out of 10 test images correctly (60% accuracy). This notable difference indicates that despite its lower validation metrics, the CNN model performs more effectively in real-world scenarios.

Recommendation:
Based on the findings, the CNN model is recommended for practical deployment due to its superior test accuracy.
