# PROJECT-7
## DISASTER TWEET CLASSIFICATION NLP
Disaster Tweets Analysis and Classification
Dataset Language Library ML Library DL Library

## Project Description
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time.
Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

Total approach towards the project can be seen on kaggle

Machine Learning approach 
Deep Learning approach 

## Project Contents
Exploratory Data Analysis
EDA after Data Cleaning
Data Preprocessing using NLP
Machine Learning models for classifying Tweets data
Deep Learning approach for classifying Tweets data
Model Deployment
Resources Used
Packages : Pandas, Numpy, Matplotlib, Plotly, Word-cloud, Tensorflow, Scikit-Learn, Keras, Keras-tuner, Nltk etc.
Word Embeddings : https://www.kaggle.com/danielwillgeorge/glove6b100dtxt

## 1. Exploratory Data Analysis
Visualising Target Variable of the Dataset

![1](https://github.com/user-attachments/assets/a860868e-3d5a-43c0-a42e-08d9ac4936ed)


Target Variable
Visualising Length of Tweets

![2](https://github.com/user-attachments/assets/f59af75c-778e-477f-a7ae-3751ddadcdef)


Tweet Length
Visualising Average word lengths of Tweets

![3](https://github.com/user-attachments/assets/3c3f171c-bb78-43fa-add9-e424ef4e30ad)


Avg Word Lengths
Visualising most common stop words in the text data

![4](https://github.com/user-attachments/assets/895c06b0-bb68-4088-a865-c98735dcb893)


Stopwords
Visualising most common punctuations in the text data

![5](https://github.com/user-attachments/assets/6b4d0af6-42bc-44e2-9a1a-fd1225be5f55)


Punctuations
2. EDA after Data Cleaning
We use Python Regex library and nltk lemmatizing methods for Data Cleaning

Visualising words inside Real Disaster Tweets
![image](https://github.com/user-attachments/assets/21049845-0b8f-447d-bd6c-290210da2ed7)


Real WC
Visualising words inside Fake Disaster Tweets
![image](https://github.com/user-attachments/assets/cdeb78c4-6784-4f9e-b74f-649e29b39a97)



Fake WC
Visualising top 10 N-grams where N is 1,2,3

![6](https://github.com/user-attachments/assets/715a277f-a0ee-470c-976c-850b1b8ec0a5)


Top N-grams

## 3. Data Preprocessing using NLP
Data Preprocessing for ML models is done using two approaches

Bag of Words using CountVectorizer
Term Frequency and Inverse Document Frequency using TfidfVectorizer
Data Preprocessing for DL models using Tokenization

## 4. Machine Learning models for classifying Tweets data
Machine Learning Models using different n-grams and both Bow and Tf-Idf and visualisation comparing there accuracy

![7](https://github.com/user-attachments/assets/3fac2477-9a90-41c4-8eb9-ab29ca46a92d)

## Ml List
The Best ML model trained as we can see above is Voting Classifer, whose report and confusion matrix is shown below

![8](https://github.com/user-attachments/assets/53eba58c-9b65-417b-9dcd-6e82e0dca1e0)

![9](https://github.com/user-attachments/assets/972f9a43-53fc-4ac7-810e-0266ed6bcf05)

## 5. Deep Learning approach for classifying Tweets data
Using Glove Word Embeddings of embedding dimension = 100 to get embedding matrix for our DL models
For every DL model we create a function and use Keras-Tuner to tune the model
Finally we choose Bidirectional LSTM for the Deployment

## 6. Model Deployment
Bidirectinal LSTM model obtained from Deep Learning approach is used for deployment
Micro Web Framework Flask is used to create web app
Deep Learning Web app working
Deployment Demo
![chrome_TaCrhUOsOR](https://github.com/user-attachments/assets/a545828a-d629-4dc2-b429-3a99b71033d8)


## Scope of Improvemment
We can always use large dataset which covers almost every type of data for both machine learning and deep learning
We can use the best pretrained models but they require a lot of computational power

## Conclusion
The Data analysis and modelling was sucessfully done.

## Acknowledgment

"I would like to express my sincere gratitude to my mentor Ms. Twinkle Baid for her valuable guidance, support, and expertise throughout my project on Pharmaceutical Sales forecasting, which helped me tackle complex challenges and refine my skills significantly."

THANK YOU
