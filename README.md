# Machine_Learning
![Obesifix-Bangkit-2023](https://github.com/Obesifix-Bangkit-2023/Machine_Learning/assets/125628050/fb62b6b9-6b78-4cde-acab-c5ae59efe4b0)

The first model is for classifying food pictures into 19 categories in which we will be able to calculate the nutrition of this food. For the model, we built a sequential model using Tensorflow and Keras API. We use transfer learning InceptionV3. Our input are trained through some parts of the InceptionV3 layers. Then the output is flattened. After that, it is then passed into a Deep Neural Network with Dropout Layers. <br>
Input : image(256, 256)<br>
Output : 19 labels<br>
Total params: 23,851,784<br>
Trainable params: 23,817,352<br>
Time : 5440s<br>
The 19 categories are:<br>
Apple<br>
Banana<br>
Chicken Curry<br>
Chicken Wings<br>
Donuts<br>
French Fries<br>
Fried Chicken<br>
Fried Rice<br>
Hamburger<br>
Hot dogs<br>
Ice Cream<br>
Omelette<br>
Onion Rings<br>
Orange<br>
Pancakes<br>
Pizza<br>
Rice<br>
Spaghetti<br>
Sushi<br>
![image](https://github.com/Obesifix-Bangkit-2023/Machine_Learning/assets/125628050/c8d2c9e2-e526-448b-806d-a9b2d81cf9c7)

For the second model we use KNN for product based recommendation. The recommendation is based on the health condition and preferences.
For the recommendation system the 19 categories of preference are as such:<br>
Beef<br>
Bread<br>
Breakfast<br>
Chicken<br>
Cookies<br>
Dairy Product<br>
Dessert<br>
Duck<br>
Fish<br>
Fruit<br>
Lamb<br>
Lunch<br>
Pasta<br>
Pork<br>
Rice<br>
Seafood<br>
Soup<br>
Soy Product<br>
Vegetable<br>
and health condition as such:<br>
Obese<br>
Overweight<br>
Normal<br>
Underweight<br>
