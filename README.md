# Neural_Network_Charity_Analysis

## Overview of Project

The purpose of this project is to predict whether applicants will be successful when funded by Alphabet Soup through binary classifier. 

## Result

The value IS_SUCCESSFUL is the binary classifier to compile, train, and evaluate the neural network model to predict successful when funded by Alphabet Soup. 
I selected relu and sigmoid for output layer and used 80 and 30 neurons for first and second hiddenlayer. 
The model achieved 
![스크린샷(120)](https://user-images.githubusercontent.com/85276431/140628552-d69e25ca-daf3-495d-a936-cb8e2ffba41f.png)

### Optimization
The accuracy is not optimized until 75%. Thus, I am going to to three different approach. 
- dropping more column and adding more bins
 ![스크린샷(121)](https://user-images.githubusercontent.com/85276431/140628578-f58ed14c-ec1e-48c2-946e-3d143e427df2.png)
Accuracy dropped to nearly 70%.

- adding more neurons to a hidden layer and hidden layers
![스크린샷(122)](https://user-images.githubusercontent.com/85276431/140628581-31debf5d-ab0e-4a40-9204-57bfdc1bcb21.png)
Accuracy dropped to 53%.

- using different activation functions and adding more epochs 
![스크린샷(123)](https://user-images.githubusercontent.com/85276431/140628582-948db277-0fc8-433a-8a07-fe51dcd19860.png)
Accuracy increased to 72% which is close enough to target accuracy. 
