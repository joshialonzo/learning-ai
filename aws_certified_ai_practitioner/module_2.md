# Module 2: Fundamentals of AI and ML

## Basic AI Concepts

* Artificial Intelligence (AI): It is a field focused on creating systems that perform tasks that normally require human abilities, such as perception, reasoning, and decision-making. It involves various technologies and methods to enable machines to mimic human intelligence.
    * Machine Learning
    * Deep Learning
    * Generative AI
* Machine Learning: It is a subset of Artificial Intelligence that focuses on developing methods for systems to learn from data and improve their performance on specific tasks over time. It enables machines to recognize patterns and make decisions based on data without being explicitly programmed for each task.
* Neural Network: It is a computational model inspired by the way biological neural networks in the human brain process information. It consists of layers of interconnected nodes (neurons) that work together to recognize patterns, learn from data, and make decisions or predictions. Neural networks are fundamental to many machine learning and artificial intelligence applications, especially in tasks like image and speech recognition.
* Deep Learning: It is a subset of machine learning that uses multi-layered neural networks to automatically learn and extract features from large datasets. It enables systems to perform more complex tasks than regular neural networks by learning patterns and representations at multiple levels of abstraction.
* Computer Vision: It is a field of artificial intelligence that enables machines to interpret and understand visual information from the world, such as images and videos. It involves techniques that allow computers to process, analyze, and make decisions based on visual data, mimicking human vision capabilities.
* Natural Language Processing: It is a branch of artificial intelligence that focuses on the interaction between computers and human language. It involves enabling machines to understand, interpret, and generate human language in a way that is both meaningful and useful. NLP combines computational linguistics with machine learning and deep learning models to process and analyze large amounts of natural language data.
* AI model: It is an algorithm that has been trained on data to perform specific tasks like classification, prediction, or pattern recognition. It learns from examples in the training data to improve its accuracy over time, enabling it to make better decisions or predictions based on new data.
* ML Algorithm: It is a set of procedures used to analyze data and make predictions or decisions based on patterns and insights. It is designed for very specific tasks, helping systems learn from data to improve their performance over time.
* AI model training: It is the process of teaching an AI model how to make accurate predictions or generate content by feeding it a large amount of data. During training, the model learns from this data to improve its performance on specific tasks over time.
* AI inferencing: It is the process of taking a trained AI model and using it to generate predictions or make decisions based on the patterns and knowledge it has learned. Essentially, it's how the model applies what it has learned to new data to provide useful outputs.
* AI model fairness: It is the principle of ensuring that an AI model's predictions or decisions do not unfairly disadvantage or bias any particular group or individual. It promotes equity by making sure the model treats all groups fairly, which is crucial for responsible and ethical AI development.
* Model fit: It refers to how well an AI model's predictions align with the data it was trained on. It indicates the model's accuracy in capturing the underlying patterns in the data, which is essential for making reliable predictions or decisions.
* Large Language Models (LLMs): They are advanced AI models designed to understand, generate, and interact with human language by processing vast amounts of text data. They are trained on extensive datasets to learn patterns, context, and nuances in language, enabling them to perform tasks such as text generation, translation, summarization, and more.

### Introduction to machine learning

#### Machine Learning workflow

1. Data collection and preparation: Identifying and preparing various data types (labeled, unlabeled, tabular, time-series, image, structured and unstructured text) is crucial for effective model training.
2. Select the ML algorithm: Different ML algorithms serve different purposes, such as linear regression for prediction, logistic regression for binary classification, K-Nearest Neighbors for classification based on neighbors, and PCA for dimensionality reduction.
3. Train the model on the data: Models can be trained via supervised learning (using labeled data), unsupervised learning (finding patterns in unlabeled data), or reinforcement learning (learning from feedback).
4. Evaluate model performance: Performance is assessed through batch inferencing (processing large data sets at once) or real-time inferencing (quick responses for time-sensitive applications).

#### 1. Types of data

* Labeled data: It refers to datasets that have been tagged with meaningful labels or annotations, which provide the correct output or category for each data point. This labeling is essential for supervised machine learning, where models learn to make predictions or classifications based on these labeled examples.
* Unlabeled data: It refers to datasets that do not have any tags, labels, or annotations indicating the correct output or category for each data point. This type of data is commonly used in unsupervised machine learning, where models try to find patterns or structures in the data without predefined labels.
* Tabular data: It refers to data organized in rows and columns, much like a spreadsheet or database table. It is one of the most common data formats used in machine learning and data science, where each row represents an observation and each column represents a feature or variable.
* Time-series data: It is a sequence of data points collected or recorded at successive points in time, often at uniform intervals. It is commonly used in fields like finance, economics, weather forecasting, and many others to analyze trends, seasonal patterns, and other temporal dynamics.
* Image data: It consists of visual information captured in the form of pixels, typically organized in a grid representing colors or intensities. It is widely used in computer vision tasks such as object detection, image classification, and facial recognition. Handling image data often involves preprocessing steps like resizing, normalization, and augmentation to improve model performance.
* Structured-text data refers to text data that is organized in a predefined format, making it easier to parse and analyze by machines. Common examples include XML (Extensible Markup Language) and JSON (JavaScript Object Notation), which are widely used for data exchange and storage because they provide a clear structure to the data.
* Unstructured data: It refers to information that does not have a predefined data model or is not organized in a predefined manner, making it more complex to collect, process, and analyze compared to structured data. Examples include text documents, images, videos, emails, social media posts, and other formats that lack a consistent structure.

#### 2. Machine Learning Algorithms

Here’s a summary of the ML algorithms covered:

* Linear Regression: Models relationships between variables to predict continuous outcomes (e.g., housing prices).
* Logistic Regression: Used for binary classification tasks, such as determining if an email is spam or not.
* K-Nearest Neighbors (KNN): Classifies data points based on the categories of their nearest neighbors, useful for recommendation systems.
* Principal Component Analysis (PCA): Reduces the dimensionality of large datasets while preserving important features, often used in tasks like facial recognition.

These algorithms serve different purposes and are foundational for building various AI and ML solutions.

#### 3. Ways to train a model

* Supervised Learning: Training the model on labeled data with known input-output pairs, so it can predict outcomes on new data.
* Unsupervised Learning: Training on unlabeled data where the model finds patterns or groupings without predefined labels.
Reinforcement Learning: The model learns by receiving feedback on its predictions, improving decisions based on positive or negative responses.

#### 4. Ways to assess performance

* Batch inferencing involves processing a large volume of data all at once, which is useful when accuracy is prioritized over speed. This approach allows you to analyze results collectively and is efficient for tasks that don't require immediate responses.
* Real-time inferencing, on the other hand, provides quick, on-demand predictions or decisions, which is crucial for applications needing fast interactions, such as self-driving cars or live chatbots.

Understanding when to use each type depends on your application's requirements for speed versus accuracy.

### Introduction to Deep Learning

* Input Layer: Think of it as the factory's loading dock where all raw materials arrive. These materials are like the different features of your data (pixels, measurements, metadata).
* Hidden Layers: These are like the assembly workers inside the factory. Each worker (neuron) processes the inputs, applies transformations, and passes the results along.
* Output Layer: This is the packaging area where the final products are assembled, boxed, labeled, and shipped out. It takes all the processed information and produces the final result, such as a classification or prediction.

## Practical Use Cases for AI

### AI Patterns and anti-patterns

Patterns

* Pattern 1: Content Creation
* Pattern 2: Text Summarization
* Pattern 3: Medical Imaging Annotation
* Pattern 4: Drug Design

Anti-patterns

* Anti-pattern 1: Financial Audit
* Anti-pattern 2: Regulatory Compliance in Pharmaceutical Manufacturing
* Anti-pattern 3: Legal Judgement

## ML Development Lifecycle