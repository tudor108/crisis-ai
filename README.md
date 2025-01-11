# crisis-ai
CrisisAI is an innovative project that utilizes advanced machine learning and natural language processing techniques to analyze real-time data from news articles, social media, and humanitarian reports. The goal of this project is to predict and mitigate potential humanitarian crises such as refugee movements, famine, or disease outbreaks by processing large volumes of unstructured data.

How it works:
CrisisAI collects and processes data from external sources:

Twitter: Using the Tweepy API, tweets mentioning keywords like "refugee crisis" or "humanitarian crisis" are extracted.
News Articles: Using the newspaper3k library, relevant news articles are extracted and processed to gain valuable insights into humanitarian crises.
AI Models: By leveraging advanced machine learning models such as LSTM and BERT, the system analyzes texts to predict and evaluate the potential risk of humanitarian crises based on their content.
Technologies Used:
Tweepy: for collecting data from Twitter.
newspaper3k: for extracting relevant news articles.
LSTM (Long Short-Term Memory): for analyzing sequential data and making predictions based on patterns in text.
BERT (Bidirectional Encoder Representations from Transformers): for contextualized word embeddings and improving the accuracy of predictions.
Scikit-learn, TensorFlow, Keras: for building and training machine learning models.
Flask: for deploying the model and making it accessible via an API for integration into other systems.
Matplotlib & Seaborn: for data visualization and performance analysis.
Features:
Real-time Data Collection: Automatic collection of real-time data from social media platforms and news websites.
Prediction Models: LSTM and BERT models are used to predict the likelihood of a crisis based on analyzed content.
Early Warning System: The system provides early warnings about potential crises, helping international organizations, governments, and NGOs take timely actions.
Data Visualization: Graphs and charts are generated to visualize the results and predictions from the models.
Benefits:
Proactive Crisis Management: CrisisAI can help identify emerging humanitarian crises before they escalate, ensuring better preparedness and quicker response from international organizations.
Efficient Resource Allocation: By providing predictive insights, the system helps allocate resources more effectively to regions at high risk of crises.
Data-Driven Decisions: CrisisAI supports decision-making with real-time, data-driven insights, improving the overall response to humanitarian issues.
Future Work:
Model Optimization: The current models can be fine-tuned further to improve prediction accuracy.
Integration with Global Data Sources: Additional data sources (e.g., UN reports, refugee data) can be incorporated to enhance the system's ability to predict crises.
Scalability: Expand the system to handle larger datasets, including multilingual support for analyzing crisis-related content in various languages.
