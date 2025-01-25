# Sample of Projects:

## LLM LangChain 
#### [QA LLM](https://github.com/yasi44/LangChain_Practices)
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

## Data Processing (ETL)
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



