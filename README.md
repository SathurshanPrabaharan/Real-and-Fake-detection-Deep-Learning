OBJECTIVE: 
Create a model that classifies the faces into real and fake. 
 
PROPOSED MODELS: 
1. Convolutional Neural Network (CNN) 
2. Transfer Learning with VGG16 

DATASET:

 
CONCLUSION: 
Based on the evaluation of both models, we observe distinct advantages and drawbacks in each. 
The CNN model demonstrates a validation loss of 0.9330 and a validation accuracy of 49.75%, 
while the Transfer Learning model achieves a lower validation loss of 0.87555 and a higher 
validation accuracy of 53.19%. These metrics indicate that the Transfer Learning model, 
leveraging pre-trained weights and features from a larger dataset, generalizes better during 
validation and captures more useful features for distinguishing between real and fake faces. 
 
However, practical application and real-world testing reveal a different story. The CNN model 
accurately classifies 9 out of 10 test images, translating to a 90% accuracy rate. In contrast, the 
Transfer Learning model correctly classifies only 6 out of 10 test images, resulting in a 60% 
accuracy rate. Despite its lower validation metrics, this significant difference in practical performance suggests that the CNN model is
more effective in real-world scenarios. 
Considering these results the CNN model is recommended as the better model for deployment in 
practical applications due to its higher accuracy in test scenarios.
 
 


