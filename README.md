# FoodLogApp_Group15
Hello dear TAs and professor, this is our code repository for our Proof of Concept(POC) for the company S.I.M which we 'created' as Group 15 of the course Software Engineering Project Management from the University of Ottawa Nov-Dec-2022

## How to run the code:

1. Download the code from the repository
2. In your IDE (e.g Microsoft Visual Studio) use the open folder option to open the folder downloaded.
3. We have provided a file called requirements.txt which contains all the necessary libraries and modules needed to run the repository. 
So run the next code line in your IDE to install these requirements in your IDE.

> pip install -r requirements.txt

4. Finally just run the command in your IDE terminal

> streamlit run FoodLogApp.py

5. This will open up the app where you can test the code by providing images of food.

- We are using the service Streamlit which allows the user to commit a website in real time which we use to deploy the app, FoodLogApp.py is the main source of the code and FoodLogApp.ipynb is a file where we set the machine learning modules where we train the AI so it learns from several images to understand how to detect food.

- We have used a group of images(dataset) from these two websites [Food Dataset 1](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/) - [Food Dataset 2](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition)

## Proof of Concept Explaination

We have based our effor in this proof of concept in the machine learning module, the team along with the customer have decided that this part of the app represents both what can add the most value to the customer business and also what produces the highest uncertainty. Thus, taking this into account we have spend more time than anything in making sure the Machine Learning part of the code was the most optimized. Provided that this [dataset](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/) is used, an accuracy of food recognition of around 93% will be obtained as desired from the customer. 

Since this is a proof of concept we concluded that this answers pretty well to the need present here. There are some limitations such as having small datasets trained which means not all food can be tested at this point, and we also deploy this in a web environment,however, these will be addressed in the future when the prototype is built since these limitations are not very important or hard to achieve.

## Examples

![image](https://user-images.githubusercontent.com/113482288/200460025-aa259841-795a-4721-b9a7-cadfde99e9a9.png)

![image](https://user-images.githubusercontent.com/113482288/200460177-fa790e1c-5745-4eed-b159-a1466a853a03.png)

## References:

- This code would have been possible without all the repository content [here](https://github.com/Spidy20?tab=repositories), credits to its author.
