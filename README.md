# FoodLogApp_Group15
To whom it may concern:
this is code repository for our Proof of Concept(POC) for the company S.I.M Solutions which we 'created' as Group 15 of the course Software Engineering Project Management from the University of Ottawa 2022 Fall semester.

## How to run the code:

1. Download the code from the repository
2. In your IDE (e.g Microsoft Visual Studio) use the open folder option to open the folder downloaded and tick the trust author option.
3. We have provided a file called requirements.txt which contains all the necessary libraries and modules needed to run the repository. 
So open a terminal and run the next code line in your IDE to install these requirements in your IDE.

> pip install -r requirements.txt

4. Now install streamlit,keras,tensorflow, and beautifulsoup4 in your IDE by running the next commands in your IDE one by one (it might take a while)

> pip install streamlit

> pip install keras

> pip install tensorflow

> pip install BeautifulSoup4

5. Finally, run the next command in your IDE terminal to execute the streamlite website and the logic code

> streamlit run FoodLogApp.py

6. If there are any errors chances are you are missing a module, just check the error log and try to see what it is about and install the module if this is the case.

7. After you have sucessfully installed every necessary modules you will be prompt to provide an email to use streamlit(you can skip this step by just pressing enter without providing any emails) then your default broswer will open up the app where you can test the code by providing images of food.

- We are using the service Streamlit which allows the user to commit a website in real-time which we use to deploy the app, FoodLogApp.py is the main source of the code, and FoodLogApp.ipynb is a file where we set the machine learning modules where we train the AI. Hence, it learns from several images to understand how to detect food.

- We have used a group of images(dataset) from these two websites [Food Dataset 1](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/) - [Food Dataset 2](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition)

## Proof of Concept Explanation

We have focused our effort on this proof of concept in the machine learning module, the team along with the customer have decided that this part of the app represents both, what can add the most value to the customer business and also what produces the highest uncertainty. Thus, taking this into account we have spent more time than anything in making sure the Machine Learning part of the code was the most optimized. Provided that this [dataset](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/) is used, the accuracy of food recognition will be around 93% as desired by the customer. 

Since this is a proof of concept we concluded that this answers pretty well to the customer's need. There are some limitations such as having small datasets trained which means not all food can be tested at this point, and we also deployed this in a web environment, however, these limitations will be addressed in the future when the prototype is built since they are not very hard to achieve.

## Examples

![image](https://user-images.githubusercontent.com/113482288/200460025-aa259841-795a-4721-b9a7-cadfde99e9a9.png)

![image](https://user-images.githubusercontent.com/113482288/200465432-8bffe5a3-30ee-4118-8a7f-b2f83965b38f.png)

## References:

- This code would not have been possible without all the repository content [here](https://github.com/Spidy20?tab=repositories), credits to its author.
- Datasets from [dataset1](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/) - [dataset2](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition)
