![banner_CC](https://www.linkpicture.com/q/Copy-of-Obesifix-Bangkit-2023-2.jpg)


# Obesifix - Machine Learning
Hello, this is machine learning part of Obesifix application made by Capstone Team C23-PS344 ✨

# Table of Contents
- [Introduction](https://github.com/Obesifix-Bangkit-2023/Machine_Learning#machine-learning-team)
- [ML Team](https://github.com/Obesifix-Bangkit-2023/Machine_Learning#machine-learning-team)
- [What We Do?](https://github.com/Obesifix-Bangkit-2023/Machine_Learning#what-we-do)
- [What We Use?](https://github.com/Obesifix-Bangkit-2023/Machine_Learning#what-packages-that-we-use-in-google-colab/jupyter-notebook?)
- [Repositories](https://github.com/Obesifix-Bangkit-2023/Machine_Learning#repositories)
- [Image Classification Model](https://github.com/Obesifix-Bangkit-2023/Machine_Learning#image-classification-model)
- [Recommendation System](https://github.com/Obesifix-Bangkit-2023/Machine_Learning#recommendation-system)
- [Machine Learning Model](https://github.com/Obesifix-Bangkit-2023/Machine_Learning#endpoint#machine-learning-model)

# Machine Learning Team

|  Name | Bangkit ID | Contacts |
| ------------ | ------------ | ------------ |
| Natasha Clarissa Maharani	 | M151DSY1486		 | [Github](https://github.com/natnaaatcm) & [Linkedin](https://www.linkedin.com/in/natashacentimeter/)  |
| Melody Priscilla Tan	 | M151DSY1458		| [Github](https://github.com/meeeeeeeel) & [Linkedin](https://www.linkedin.com/in/melodyprs/) |

# What We Do?
We are developing a food classification & recommendation model that suggests suitable food options to users.

# What Packages that we use in Google Colab/Jupyter Notebook?

|   Packages |                                
| :----------------: | 
|    Tensorflow |
|  Keras      |  
| Pandas |  
| Scikit-Learn |  
| Numpy |  
| Matplotlib |  

# Repositories

|   Learning Paths       |                                Link                                              |
| :----------------:     | :----------------------------------------------------------------:               |
|   Organization         |            [Github](https://github.com/Obesifix-Bangkit-2023)                    |
|  Machine Learning      |            [Github](https://github.com/Obesifix-Bangkit-2023/Machine_Learning)   |
|  Machine Learning API  |        [Github](https://github.com/Obesifix-Bangkit-2023/ML-services-API)        |
| Mobile Development     |            [Github](https://github.com/Obesifix-Bangkit-2023/Mobile_Development) |


# Image Classification Model

|   Model |                                Classification Output                               |
| :----------------: | :----------------------------------------------------------------: |
|   Transfer Learning : InceptionV3     |      Apple, Banana, Chicken Curry                        |
|  Input : image(256, 256)  |  Chicken Wings, Donuts, French Fries                 |
| Output : 19 labels|  Fried Chicken, Fried Rice, Hamburger      |
| Total params: 23,851,784 |  Hot dogs, Ice Cream, Omelette          |
| Trainable params: 23,817,352 |  Onion Rings, Orange, Pancakes, Pizza         |
| Time : 5440s |  Rice, Spaghetti, Sushi          |

# Recommendation System
Using KNN we filter the food according to user's freference and health condition.

|   Food Preferences (19 type of preferences) |                                Health Conditions                                |
| :----------------: | :----------------------------------------------------------------: |
|   Beef, Bread, Breakfast, Chicken     |      Underweight                        |
|  Cookies, Dairy Product, Dessert, Duck  |  Normal                 |
| Fish, Fruit, Lamb, Lunch, Pasta |  Overweight          |
| Pork, Rice, Seafood, Soup, Soy Product, Vegetable |  Obese          |


# Machine Learning Model

![Machine Learning Model](https://www.linkpicture.com/q/sfer.png)
The first model is for classifying food pictures into 19 categories in which we will be able to calculate the nutrition of this food. For the model, we built a sequential model using Tensorflow and Keras API. We use transfer learning InceptionV3. Our input are trained through some parts of the InceptionV3 layers. Then the output is flattened. After that, it is then passed into a Deep Neural Network with Dropout Layers.

![Machine Learning Model](https://www.linkpicture.com/q/246290439-c8d2c9e2-e526-448b-806d-a9b2d81cf9c7.png)

For the second model we use KNN for product based recommendation. The recommendation is based on the health condition and preferences.
