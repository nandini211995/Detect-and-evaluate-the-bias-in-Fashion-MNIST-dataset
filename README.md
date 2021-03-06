# -Detect-and-evaluate-the-bias-in-Fashion-MNIST-dataset

Dataset : **Fashion MNIST**

Motive of this project is to use metrics to detect and evaluate the bias in the machine learning model.The work contains these things :

1. I consider a 2-class classification between ​Pullover​ and ​Coat

2. Training data split:​ Take all the training samples corresponding to Pullover, and only 500 samples for Coat.

3. Testing data split:​ Take all the testing samples corresponding to Pullover and Coat

4. Cross-validation:​ Repeat each of the experiments 2 more times by taking different 500 samples of Coat.

5. Algorithms:​ Perform classification using:

      ○ A linear SVM. (You may use sklearn library)
      
      ○ A 5 layer neural network with architecture: [ 128 -- 128 -- 128 -- 64 -- 1 ] (These numbers denote the number of nodes in each layer)

6. The project results are in terms of  :
    
      ○ Testing performance (mean ± std)
      
      ○ Comparison of Testing Accuracy and  Confusion matrix for the classification performed using SVM vs Neural Network
      
      ○ ROC curve for each algorithm and report EER (Equal Error Rate).
      
      ○ Draw the Precision-Recall curve for analyzing which algorithm is more reliable for biased/imbalanced data
      
      

