# Sample of Projects:

## LLM LangChain 
#### [ALS Resume–job matching](https://github.com/ALS-MDS2026/ALS-LLM-project)
Resume–job matching Package.
Ranking candidates against job descriptions using lexical and semantic retrieval, fusion methods, and an advisory anti-gaming layer.

#### [Amazon Beauty Assistant](https://github.com/UBC-MDS/DSCI_575_project_yasieft_purityj)
Amazon Beauty Assistant is a context-aware product search and recommendation system that retrieves relevant Amazon beauty products from natural language queries and generates grounded answers using a large language model. 

Here we used:
- BM25 index    +    FAISS index
- Hybrid retriever (RRF)
- RAG pipeline → Llama 3.3 70B (Groq) → Answer


#### [QA LLM](https://github.com/yasi44/LangChain_Practices)

## Regression
#### [Predicting Marketing Campaign Response Using Logistic Regression](https://github.com/Roccolee18/bank_marketing_group_24)
The project builds a machine-learning pipeline to predict whether a customer will subscribe to a marketing campaign. We use Logistic regression with a preprocessing pipeline (StandardScaler and OneHotEncoder) to handle numerical and categorical features. Since the dataset is highly imbalanced, we enabled the class_weight = "balanced" to help the model detect the minority class more efficiently.

## Classification
- An example Python implementation for building a QA module using Google PaLM through LangChain, combined with FAISS for vector-based similarity search.
- Here a sample QA example is used. in real project, there must be a QA database where each entry contains a question and its corresponding answer.
   
#### [Unsupervised Image Classification Using Pretrained model Cosine Similarity and ResNet50 ](https://github.com/yasi44/Image_Classification_Unsupervised)
- For any input image, classify the input into one of the following classes:
Character1, Character2, Character3, or none of them

- The training dataset comprises 92,350 .jpeg images(unlabeled) stored in the images.tar file.
- The images vary in size, necessitating resizing for consistency.
- The dataset is unlabelled, meaning similar images are not grouped under specific classes.
- Embeddings of the images in the images.tar file are available in embeddings.npy, where each image is represented by a 512-dimensional vector.
- The test set (test_set.csv) consists of 100 image indices from the training set, chosen to evaluate the final classification model.

#### [Will people comprehend the news as a Bulish or not?](https://github.com/yasi44/Classifier_BulishPredictor_NLPCryptoNews_Prices)
![Alt text](https://tse4.mm.bing.net/th?id=OIP.zU3UWFU3dREt9TXVHJmwOAHaEK&pid=Api&P=0&h=180)
- This predictor can help to know how people will comprehend a news, before publishing that news. Thus, a market movement from people reaction may be partially predicted. Here a classifier model, trained on the data created from combination of news and price, and all the features engineered and extracted. Given a news, this classifier determines if a news will be comprehend from readers as a Bulish news or not.
- Data: Text and Price
- Algorithm: RandomForestClassifier

#### [Transfer Learning on both image and text](https://github.com/yasi44/TransferLearning)
![Alt text](https://learnopencv.com/wp-content/uploads/2019/05/transfer-learning.jpg)
-  Get pretrained models (for both image and text) from tensorflow hub and retrain them on a set of data to achieve our business goal.
-  Data: Text and image
-  Algorithm: -

## Clustering
#### [Customer Segmentation(Marketing Analytics)](https://github.com/yasi44/Market-Analytics---Customer-Segmentation)
![Alt text](https://tse2.mm.bing.net/th?id=OIP.fWML8gojKp5PnKKjJqBqXwHaEh&pid=Api&P=0&h=180)
- Here we are going to find different shoping groups based on demographics information(age,income) and shoping score to better understand the target group for marketing campaigns
- Data: Customer's demographics information
- Algorithm: KMeans

## Visualization
#### [Uber Data VisualizationUsing Shiny in R](https://github.com/yasi44/Uber-Data-Visualization-Shiny-in-R-)


## Game using Reinforcement Learning
#### [Here a non-player character (NPC) is created that learns to navigate a simple grid-based environment using reinforcement learning. Here we used Q-learning, a popular RL algorithm to teach the NPC to reach a target while avoiding obstacles.](https://github.com/yasi44/Game/tree/main)


## Data Processing (ETL)

#### [datajanitor package](https://github.com/UBC-MDS/DSCI_524_group31_datajanitor)
Datajanitor is a Python package that focuses on basic data cleaning and validation tasks for tabular data, mainly pandas DataFrames. The goal is to make common cleaning steps easier and clearer than writing everything manually in pandas, especially by providing simple function interfaces and clearer error messages.

#### [Accelerated ETL](https://github.com/yasi44/PySpark_Snippets)
![Alt text](https://tse2.mm.bing.net/th?id=OIP.od8CVSZu83bcqG0Trw8N9QHaEL&pid=Api&P=0&h=180)
- Here I used PySpark to accelerate the analysis of 1TB Bitcoin coin data(BTCUSD) from Binance stored in AWS S3, using AWS EMR cluster.
- Data: Cryptocurrency data
- Tools/Techniques: PySpark on AWS EMR

#### [Web Crawler](https://github.com/yasi44/Web-Scrapper)
![Alt text]()
- Some pieces of my development for customized Web Crawler.
- Data: Text and Numbers
- Tools/Techniques: Selenium



