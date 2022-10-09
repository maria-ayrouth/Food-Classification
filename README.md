# Food-Classification


In this Notebook ,we get specific and see how a special kind of neural network, convolutional neural networks (CNNs) can be used for computer vision (detecting patterns in visual data).

Because convolutional neural networks work so well with images, The images we're going to work with are from the Food-101 dataset, a collection of 101 different categories of 101,000 (1000 images per category) real-world images of food dishes.

At a first stage , we're only going to use two of the categories, pizza 🍕 and steak 🥩 and build a binary classifier.

```
Example of file structure

pizza_steak <- top level folder
└───train <- training images
│   └───pizza
│   │   │   1008104.jpg
│   │   │   1638227.jpg
│   │   │   ...      
│   └───steak
│       │   1000205.jpg
│       │   1647351.jpg
│       │   ...
│   
└───test <- testing images
│   └───pizza
│   │   │   1001116.jpg
│   │   │   1507019.jpg
│   │   │   ...      
│   └───steak
│       │   100274.jpg
│       │   1653815.jpg
│       │   ...    
 ```

## Binary classification: Let's break it down

1. Become one with the data (visualize, visualize, visualize...)
2. Preprocess the data (prepare it for a model)
3. Create a model 
4. Fit the model
5. Evaluate the model
6. Adjust different parameters and improve model (try to beat your baseline)
7. Repeat until satisfied

finally , we got 

![Screenshot (812)](https://user-images.githubusercontent.com/90212538/193805834-ec630c28-928a-40dd-a84d-afa169588396.png)


Making a prediction with our trained model

![Screenshot (811)](https://user-images.githubusercontent.com/90212538/193805814-dde55db2-b6bd-4a6e-9756-5c9b2a4d976a.png)




## Multi-class Classification

How about we go through those steps again, except this time, we'll work with 10 different types of food:
 * chicken_curry
 * chicken_wings
 * fried_rice
 * grilled_salmon
 * hamburger
 * ice_cream
 * pizza
 * ramen
 * steak
 * sushi

Some predictions:

![Screenshot (817)](https://user-images.githubusercontent.com/90212538/194745431-f68eac9a-faa4-4a3b-bb96-4e9c2a34f7c3.png)


Our model's predictions aren't very good, this is because it's only performing at ~50% accuracy on the test dataset.


