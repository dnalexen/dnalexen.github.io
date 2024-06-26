## Alexandre Djossou Portfolio

This is an overview of some of my data science projects. I have a big interest in Artificial Intelligence and its applications in Business Intelligence, Computer Vision, Natural Language Processing and IoT.

My experiences include an understanding of classic Machine Learning and Deep Learning algorithms. I have developed Sales Forecasting, Customers Churn Prediction, Anomalies Detection models and Computer Vision application with Python and its well known libraries such as Numpy, Pandas, PyTorch, Sklearn, TensorFlow.

Hereafter, some projects.

### Data Science projects

#### 1- AI for Water Meter Reading
The objective of this project was to design an algorithm to read the exact consumption index from a valid picture of a meter.
We used an implementation of the YOLOv4 algorithm that we customed to our [dataset](https://challengedata.ens.fr/participants/challenges/30/).
The model is live on a [web app](https://aiformeterreading-egtfacxaga-ew.a.run.app).
You can have a look on the code on the [project's Github Repository](https://github.com/dnalexen/ai_water_meter_reading). 

#### 2- Customer Churn Prediction
The objective of the project is to predict if a customer of a Telecom company is about to leave. We used the unsupervised and supervised approaches.
The notebook is available on [Google Colab](https://colab.research.google.com/drive/1hxmAAv_u4T6FptgBtSZQXdnVlsX8vp7y?usp=sharing) or on the [project's Github Repository](https://github.com/dnalexen/Customer-Churn-Prediction).

#### 3- Link prediction
The goal of this project is to predict whether or not two restaurants facebook pages will mutually like them in the future.
The dataset is composed of two files:
'fb-pages-food.nodes' contains the information on the nodes or the restaurants facebook pages,
'fb-pages-food.edges' contains the existing edges between the nodes: there is an edge between two nodes if these two nodes or pages have mutually liked them.
We used a graph learning approach with NetworkX. The notebook is available at [Google Colab](https://colab.research.google.com/drive/1fydeCFKegXcXS631ffZ3q94gdS71eX7K#scrollTo=PP_EfiynvYjK) or on the [project's Github Repository](https://github.com/dnalexen/link_prediction-fb_pages_food).

#### 4- News Analysis
The objective of the project is to predict the category to which an article belongs to given its headline. The notebook is available on [Google Colab](https://colab.research.google.com/drive/1A9xwy11OE_ZBrvljHHpnWdr57tg4SHS4?usp=sharing) or on the [project's Github Repository](https://github.com/dnalexen/News-Analysis).

#### 5- Weather Forecast
The objective of the project is to predict the weather of the city of San Francisco! In the first step, we would predict the temperature, knowing the information of the past days.
The notebook is available at [Google Colab](https://colab.research.google.com/drive/1jSXDF-ncZLScHIvKnP0X_NGaBbRurxiS?usp=sharing) or on the [project's Github Repository](https://github.com/dnalexen/Weather-Forecast).

#### 6- Auto Fuel Consumption prediction - Deployment on GCP with Kubernetes
The objective of the project is to predict the fuel consumption of a car given some of its parameters such as the number of cylinders, the horsepower, the weight, the acceleration, the origin and the model year. First, we built a simple prediction model with a SKlearn Linear Regression algorithm. Then, we built an API with our model that we wrapped in a docker image. Finally, we deploy this docker image on Google Cloud Platform with Kubernetes.
The notebook is available at [Google Colab](https://colab.research.google.com/drive/1RJ8QNmVddWdSGxEwQYg0BJzpF3XBjABj?usp=sharing) or on the [project's Github Repository](https://github.com/dnalexen/auto-mpg).
