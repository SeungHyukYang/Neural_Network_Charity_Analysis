# Neural_Network_Charity_Analysis
## Overview of the analysis
The purpose of the study is to predict whether the application witll be successful when it got funded by Alphabet Soup through preprocessing the data with the neural network binary classifier. 

## Result
The value IS_SUCCESSFUL in the dataset is binary and I compile, train, and evaluate it with the neural network model. Since it is binary model, the activation function is relu and sigmoid for output layer and 80 and 30 hidden layer. 
![스크린샷(120)](https://user-images.githubusercontent.com/85276431/140628128-146e0f62-9a8b-4ad2-a79e-f73a40f91389.png)

 ### Optimize the Model
 Since the accuracy is low (Accuracy: 0.6695043444633484), I optimized it in order to achieve more than 75% accuracy. 

I dropped one more column ORGANIZATION, and increase more bin for rare occurrences (200 -> 500).
 ![스크린샷(121)](https://user-images.githubusercontent.com/85276431/140628280-22becda1-3401-4b6f-844b-d895c7fb47a1.png)
Accuracy increased slightly (roughly 3%) but not enought to 75%.

I added more neurons to a hidden layer and hidden layers to increase accuracy (neurons in Layer 1: 80 -> 90, Layer 2: 30 -> 35, Layer = 50). 
![스크린샷(122)](https://user-images.githubusercontent.com/85276431/140628360-7f2f4620-eda5-4774-b67c-ab8f3b7e209b.png)
Result of adding more nurons and hidden layer didn't help increasing accuracy (Accuracy decreased to 53%)

I used different activation model with using same setting with initial attempt and added more epochs. 
![스크린샷(123)](https://user-images.githubusercontent.com/85276431/140628417-1674811d-e505-41e5-9100-9e19c45dca22.png)

The accuracy result increased to 72% close to our target accuracy. 
