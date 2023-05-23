# neuralnetworks

## First Neural Network
I began with importing the necessary libraries and reading in the csv file. I drooped unnecessary columns and encoded categorical data. Then I concatenated with the numerical data and saved the encoded dataframe. Next the data was split and scaled. The first neural network with only two layers was not particularly accurate. See Resouces/AlphabetSoup.h5

## Second Neural Network
For the second neural network I tried to add a couple of layers and also changed the activation function to see if that would make a difference. It ended up with a very similar accuracy and loss rate to the original, so no big impact.  

## Third Neural Network
For the third attempt I decided to try some overfitting techniques. I added a few dropout layers and also added regularization into the final layer before output. This however, also did not change the accuracy or loss rates much at all either. 

## Conclusion
My conclusion is that with so many columns, the input data is creating noise and the model is overfitting. If I had more time to work on this I would suggest a deep dive into cleaning the input data further by droppiung extraneous columns and rerunning these three models and seeing if the results vary. This neural network still needs more work to have acceptable accuracy and loss rates. 

