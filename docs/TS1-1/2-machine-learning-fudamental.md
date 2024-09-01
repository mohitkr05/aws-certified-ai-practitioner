# Machine Learning Fundamentals

Machine learning is the science of developing algorithms that computers use to learn from data and perform tasks without explicit 
instructions.


  Training: Known Data --> Features --> Algorithm (training) --> Output (reliability)
  
  Training gives you
    - Model artifacts - Trained parameters, model definition (how to compute inferences, other metadata)
    - Inference code - Software that implements the model 


  Hosting a model
    - endpoint is always available i.e. Real time inference - Persistent endpoint 
    - batch job - offline, large amount of data and infrequent use 
  
  
  
  Inference : New data --> Features --> Model --> Output 

Types of Structured data
 - csv, rds, redshift, sql 
 - for model training it can be put in s3


Semi  structured 
 - json, yaml, xml
 - DynamoDB, DocumentDb
 - Export it into S3


Unstructured data
 - images, video , social media post
 - objects in S3

  Tokenization

  - Breaks down tasks into smaller tasks that can be done in parallel, e.g words or phrases

Time-series data
 - Performance metrics
 - Uses datetime


To create a  model we need an algorithm which contains mathematical relationship between output and input. 


## Key concepts:

- Algorithm: A mathematical function that takes data as input and produces an output. It is composed of a model and an optimization criterion.
- Training: The process of adjusting model parameters to minimize errors between predicted and actual outputs. This is done by optimizing the optimization criterion.
- Inference: Using a trained model to make predictions on new data.
- Features: The input variables used in machine learning models. Features can be raw data, or transformations of the data (e.g. normalization, feature extraction).
- Data types: Structured, semi-structured, unstructured, and time series.
	+ Structured data: Data that is organized into a table with well-defined columns and rows. Examples include relational databases and CSV files.
	+ Semi-structured data: Data that has some structure, but not enough to be easily stored in a relational database. Examples include JSON, XML, and Avro.
	+ Unstructured data: Data that does not have any predefined structure. Examples include images, audio, and video.
	+ Time series data: Data that is measured over time. Examples include stock prices, sensor readings, and website traffic.
- Data storage: Amazon S3, Amazon RDS, Amazon Redshift, Amazon DynamoDB, Amazon DocumentDB.
- Algorithm example: Linear regression for finding a linear relationship between variables.

## Machine learning process:

- Data preparation: Collect and prepare data (structured, semi-structured, or unstructured).
  This may involve:
  - Data cleaning: Removing missing or duplicate values, and handling outliers.
  - Data transformation: Normalizing or scaling values to a common range.
  - Feature extraction: Extracting relevant information from the data, such as text or image features.
- Algorithm selection: Choose an appropriate algorithm based on the problem and data type.
  - Supervised learning: The algorithm is trained on labeled data to learn a mapping between input and output.
  - Unsupervised learning: The algorithm is trained on unlabeled data to discover patterns or groupings.
  - Reinforcement learning: The algorithm is trained on feedback from the environment to learn a policy or make decisions.
- Model training: Feed the data into the algorithm and adjust parameters to minimize errors.
  - Model selection: Choosing the best model by evaluating different models on a validation set.
  - Hyperparameter tuning: Adjusting the model's parameters to optimize performance.
- Evaluation: Assess the model's performance using metrics like accuracy or error rate.
  - Model evaluation: Evaluating the model on a test set to estimate its performance on unseen data.
  - Model comparison: Comparing different models to determine which one is best.
- Deployment: Use the trained model to make predictions on new data.
  - Model serving: Deploying the model to a production environment to make predictions on new data.



### Supervised learning 

Consider this scenario of Supervised learning.

