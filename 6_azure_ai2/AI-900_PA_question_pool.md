# Practice Assessment Question Pool for Exam AI-900

## Question Pool

---

**Question:** Which three sources can be used to generate questions and answers for a knowledge base? Each correct answer presents a complete solution.

- [x] a webpage
- [ ] an audio file
- [x] an existing FAQ document
- [ ] an image file
- [x] manually entered data

**Explanation:** A webpage or an existing document, such as a text file containing question and answer pairs, can be used to generate a knowledge base. You can also manually enter the knowledge base question-and-answer pairs. You cannot directly use an image or an audio file to import a knowledge base.

**Source(s):**

- Build a bot with the Language Service and Azure Bot Service - Training | Microsoft Learn

---

**Question:** At which layer can you apply content filters to suppress prompts and responses for a responsible generative AI solution?

- [ ] Metaprompt and grounding
- [ ] Model
- [x] Safety system
- [ ] User experience

**Explanation:** The safety system layer includes platform-level configurations and capabilities that help mitigate harm. For example, the Azure OpenAI service includes support for content filters that apply criteria to suppress prompts and responses based on the classification of content into four severity levels (safe, low, medium, and high) for four categories of potential harm (hate, sexual, violence, and self-harm).

**Source(s):**

- [Responsible generative AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/responsible-ai-studio/)

---

**Question:** [Answer choice] can return responses, such as natural language, images, or code, based on natural language input.

- [ ] Computer vision
- [ ] Deep learning
- [x] Generative AI
- [ ] Machine learning
- [ ] Reinforcement learning

**Explanation:** Generative AI models offer the capability of generating images based on a prompt by using DALL-E models, such as generating images from natural language. The other AI capabilities are used in different contexts to achieve other goals.

**Source(s):**

- [What is generative AI? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-generative-ai/2-what-is-generative-ai)

---

**Question:** Select the answer that correctly completes the sentence. [Answer choice] can be used to identify constraints and styles for the responses of a generative AI model.

- [ ] Data grounding
- [ ] Embeddings
- [x] System messages
- [ ] Tokenization

**Explanation:** System messages should be used to set the context for the model by describing expectations. Based on system messages, the model knows how to respond to prompts. The other techniques are also used in generative AI models, but for other use cases.

**Source(s):**

- [Improve generative AI responses with prompt engineering - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-generative-ai/6-writing-prompts)

---

**Question:** Which two capabilities are examples of a GPT model? Each correct answer presents a complete solution.

- [x] Create natural language
- [ ] Detect specific dialects of a language
- [ ] Generate closed captions in real-time from a video
- [ ] Synthesize speech
- [x] Understand natural language

**Explanation:** Azure OpenAI natural language models can take in natural language and generate responses. GPT models are excellent at both understanding and creating natural language.

**Source(s):**

- [What is generative AI? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-generative-ai/2-what-is-generative-ai)

---

**Question:** Which three capabilities are examples of image generation features for a generative AI model? Each correct answer presents a complete solution.

- [ ] Animation of static images
- [x] Creating variations of an image
- [x] Editing an image
- [ ] Extracting RGB values from an image
- [x] New image creation

**Explanation:** Image generation models can take a prompt, a base image, or both, and create something new. These generative AI models can create both realistic and artistic images, change the layout or style of an image, and create variations of a provided image.

**Source(s):**

- [Fundamentals of Generative AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-generative-ai/)

---

**Question:** You plan to develop an image processing solution that will use DALL-E as a generative AI model. Which capability is NOT supported by the DALL-E model?

- [x] Image description
- [ ] Image editing
- [ ] Image generation
- [ ] Image variations

**Explanation:** Image description is not a capability included in the DALL-E model; therefore, it is not a use case that can be implemented by using DALL-E, while the other three capabilities are offered by DALL-E in Azure OpenAI.

**Source(s):**

- [Fundamentals of Generative AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-generative-ai/)

---

**Question:** Which generative AI model is used to generate images based on natural language prompts?

- [x] DALL-E
- [ ] Embeddings
- [ ] GPT-3.5
- [ ] GPT-4
- [ ] Whisper

**Explanation:** DALL-E is a model that can generate images from natural language. GPT-4 and GPT-3.5 can understand and generate natural language and code but not images. Embeddings can convert text into numerical vector form to facilitate text similarity. Whisper can transcribe and translate speech to text.

**Source(s):**

- [Azure OpenAI Service models - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/azure/ai-services/openai/concepts/models)

---

**Question:** [Answer choice] can search, classify, and compare sources of text for similarity.

- [ ] Data grounding
- [x] Embeddings
- [ ] Machine learning
- [ ] System messages

**Explanation:** Embeddings is an Azure OpenAI model that converts text into numerical vectors for analysis. Embeddings can be used to search, classify, and compare sources of text for similarity.

**Source(s):**

- [Fundamentals of Generative AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-generative-ai/)

---

**Question:** Which natural language processing (NLP) workload is used to generate closed caption text for live presentations?

- [x] Azure AI Speech
- [ ] Conversational language understanding (CLU)
- [ ] Question answering models
- [ ] Text analysis

**Explanation:** Azure AI Speech provides speech-to-text and text-to-speech capabilities through speech recognition and synthesis. You can use prebuilt and custom Speech service models for a variety of tasks, from transcribing audio to text with high accuracy, to identifying speakers in conversations, creating custom voices, and more.

**Source(s):**

- [Understand Text Analytics - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-text-with-text-analytics-service/2-understand-text-analytics)

---

**Question:** Which type of artificial intelligence (AI) workload provides the ability to classify individual pixels in an image depending on the object that they represent?

- [ ] Image analysis
- [ ] Image classification
- [ ] Object detection
- [x] Semantic segmentation

**Explanation:** Semantic segmentation provides the ability to classify individual pixels in an image depending on the object that they represent. The other answer choices also process images, but their outcomes are different.

**Source(s):**

- [Understand computer vision - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/4-understand-computer-vision)

---

**Question:** Which type of artificial intelligence (AI) workload has the primary purpose of making large amounts of data searchable?

- [ ] Image analysis
- [x] Knowledge mining
- [ ] Object detection
- [ ] Semantic segmentation

**Explanation:** Knowledge mining is an artificial intelligence (AI) workload that has the purpose of making large amounts of data searchable. While other workloads leverage indexing for faster access to large amounts of data, this is not their primary purpose.

**Source(s):**

- [Understand knowledge mining - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/6-understand-knowledge-mining)

---

**Question:** Which artificial intelligence (AI) workload scenario is an example of natural language processing (NLP)?

- [x] Extracting key phrases from a business insights report
- [ ] Identifying objects in landscape images
- [ ] Monitoring for sudden increases in quantity of failed sign-in attempts
- [ ] Predicting whether customers are likely to buy a product based on previous purchases

**Explanation:** Extracting key phrases from text to identify the main terms is an NLP workload. Predicting whether customers are likely to buy a product based on previous purchases requires the development of a machine learning model.

**Source(s):**

- [Analyze text with the Language service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-text-with-text-analytics-service/)

---

**Question:** Which two artificial intelligence (AI) workload scenarios are examples of natural language processing (NLP)? Each correct answer presents a complete solution.

- [ ] Extracting handwritten text from online images
- [ ] Generating tags and descriptions for images
- [ ] Monitoring network traffic for sudden spikes
- [x] Performing sentiment analysis on social media data
- [x] Translating text between different languages from product reviews

**Explanation:** Translating text between different languages from product reviews is an NLP workload that uses the Azure AI Translator service. Performing sentiment analysis on social media data is an NLP workload that uses the sentiment analysis feature of the Azure AI Service for Language.

**Source(s):**

- [Microsoft Azure AI Fundamentals: Explore natural language processing - Training | Microsoft Learn](https://learn.microsoft.com/training/paths/explore-natural-language-processing/)

---

**Question:** In a regression machine learning algorithm, how are features and labels handled in a validation dataset?

- [ ] Features are compared to the feature values in a training dataset.
- [x] Features are used to generate predictions for the label, which is compared to the actual label values.
- [ ] Labels are compared to the label values in a training dataset.
- [ ] The label is used to generate predictions for features, which are compared to the actual feature values.

**Explanation:** In a regression machine learning algorithm, features are used to generate predictions for the label, which is compared to the actual label value. There is no direct comparison of features or labels between the validation and training datasets.

**Source(s):**

- [What is regression? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/train-evaluate-regression-models/2-what-is-regression)

---

**Question:** Which feature makes regression an example of supervised machine learning?

- [x] use of historical data with known label values to train a model
- [ ] use of historical data with unknown label values to train a model
- [ ] use of randomly generated data with known label values to train a model
- [ ] use of randomly generated data with unknown label values to train a model

**Explanation:** Regression is an example of supervised machine learning due to the use of historical data with known label values to train a model. Regression does not rely on randomly generated data for training.

**Source(s):**

- [What is regression? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/train-evaluate-regression-models/2-what-is-regression)
- [What is clustering? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/train-evaluate-cluster-models/2-what-is-clustering)

---

**Question:** A bank is developing a new artificial intelligence (AI) system to support the process of accepting or rejecting mortgage applications. Which two issues should be considered as part of the responsible AI principle of fairness to avoid biased decision making? Each correct answer presents part of the solution.

- [ ] Credit utilization
- [ ] Current salary
- [x] Ethnicity
- [x] Gender
- [ ] Payment history

**Explanation:** The AI system must be designed to ensure that biased decision making is avoided and not based on factors such as ethnicity and gender. The system will consider salary, payment history, and credit utilization, which are standard metrics.

**Source(s):**

- [Understand Responsible AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/8-understand-responsible-ai)

---

**Question:** Which two principles of responsible artificial intelligence (AI) are most important when designing an AI system to manage healthcare data? Each correct answer presents part of the solution.

- [x] Accountability
- [ ] Fairness
- [ ] Inclusiveness
- [x] Privacy and Security

**Explanation:** The accountability principle states that AI systems are designed to meet any ethical and legal standards that are applicable. The system must be designed to ensure that the privacy of healthcare data is of the highest importance, including anonymizing data where applicable. The fairness principle is applied to AI systems to ensure that users of the systems are treated fairly. The inclusiveness principle states that AI systems must empower people in a positive and engaging way.

**Source(s):**

- [Understand Responsible AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/8-understand-responsible-ai)

---

**Question:** Which principle of responsible artificial intelligence (AI) ensures that an AI system meets any legal and ethical standards it must abide by?

- [x] Accountability
- [ ] Fairness
- [ ] Inclusiveness
- [ ] Privacy and Security

**Explanation:** The accountability principle ensures that AI systems are designed to meet any ethical and legal standards that are applicable. The privacy and security principle states that AI systems must be designed to protect any personal and/or sensitive data. The inclusiveness principle states that AI systems must empower people in a positive and engaging way. The fairness principle is applied to AI systems to ensure that users of the systems are treated fairly.

**Source(s):**

- [Microsoft Azure AI Fundamentals: Explore computer vision - Training | Microsoft Learn](https://learn.microsoft.com/training/paths/explore-computer-vision-microsoft-azure/)
- [Understand Responsible AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/8-understand-responsible-ai)

---

**Question:** Which artificial intelligence (AI) technique serves as the foundation for modern image classification solutions?

- [ ] semantic segmentation
- [x] deep learning
- [ ] linear regression
- [ ] multiple linear regression

**Explanation:** Modern image classification solutions are based on deep learning techniques. Semantic segmentation provides the ability to classify individual pixels in an image depending on the object that they represent. Both linear regression and multiple linear regression use training and validating predictions to predict numeric values, so they are not part of image classification solutions.

**Source(s):**

- [Machine learning for computer vision - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-images-computer-vision/2b-computer-vision-models)
- [Fundamentals of machine learning - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/)

---

**Question:** Which computer vision service provides bounding coordinates as part of its output?

- [ ] Image analysis
- [ ] Image classification
- [x] Object detection
- [ ] Semantic segmentation

**Explanation:** Object detection provides the ability to generate bounding boxes that identify the locations of different types of objects in an image, including the bounding box coordinates, designating the location of the object in the image. Semantic segmentation provides the ability to classify individual pixels in an image. Image classification classifies images based on their contents. Image analysis extracts information from the image to label it with tags or captions.

**Source(s):**

- [Get started with image analysis on Azure - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-images-computer-vision/2-image-analysis-azure)
- [Understand computer vision - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/4-understand-computer-vision)

---

**Question:** Which process allows you to use optical character recognition (OCR)?

- [x] Digitizing medical records
- [ ] Identifying access control for a laptop
- [ ] Identifying wildlife in an image
- [ ] Translating speech to text

**Explanation:** OCR can extract printed or handwritten text from images. In this case, it can be used to extract text from scanned medical records to produce a digital archive from paper-based documents. Identifying wildlife in an image is an example of a computer vision solution that uses object detection and is not suitable for OCR. Identifying a user requesting access to a laptop is done by taking images from the laptop’s webcam and using facial detection and recognition to identify the user requesting access. Translating speech to text is an example of using speech translation and uses the Azure AI Speech service as part of Azure AI Services.

**Source(s):**

- [Read text with the Computer Vision service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/read-text-computer-vision/)

---

**Question:** Which process allows you to use object detection?

- [ ] Analyzing sentiment around news articles
- [ ] Extracting text from manuscripts
- [ ] Granting employee access to a secure building
- [x] Tracking livestock in a field

**Explanation:** Object detection can be used to track livestock animals, such as cows, to support their safety and welfare. For example, a farmer can track whether a particular animal has not been mobile. Sentiment analysis is used to return a numeric value based on the analysis of a text. Employee access to a secure building can be achieved by using facial recognition. Extracting text from manuscripts is an example of a computer vision solution that uses optical character recognition (OCR).

**Source(s):**

- [Machine learning for computer vision - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-images-computer-vision/2b-computer-vision-models)

---

**Question:** Which feature of computer vision involves associating an image with metadata that summarizes the attributes of the image?

- [ ] Categorizing
- [ ] Content organization
- [ ] Detecting image types
- [x] Tagging

**Explanation:** Tagging involves associating an image with metadata that summarizes the attributes of the image. Detecting image types involves identifying clip art images or line drawings. Content organization involves identifying people or objects in photos and organizing them based on the identification. Categorizing involves associating the contents of an image with a limited set of categories.

**Source(s):**

- [Get started with image analysis on Azure - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-images-computer-vision/2-image-analysis-azure)

---

**Question:** Which analytical task of the Azure AI Vision service returns bounding box coordinates?

- [ ] Image categorization
- [x] Object detection
- [ ] Optical character recognition (OCR)
- [ ] Tagging

**Explanation:** Detecting objects identifies common objects and, for each, returns bounding box coordinates. Image categorization assigns a category to an image but does not return bounding box coordinates. Tagging involves associating an image with metadata that summarizes the attributes of the image, but it does not return bounding box coordinates. OCR detects printed and handwritten text in images, but it does not return bounding box coordinates.

**Source(s):**

- [Get started with image analysis on Azure - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-images-computer-vision/2-image-analysis-azure)

---

**Question:** Which two specialized domain models are supported by using the Azure AI Vision service? Each correct answer presents a complete solution.

- [ ] Animals
- [ ] Cars
- [x] Celebrities
- [x] Landmarks
- [ ] Plants

**Explanation:** The Azure AI Vision service supports the celebrities and landmarks specialized domain models. It does not support specialized domain models for animals, cars, or plants.

**Source(s):**

- [Get started with image analysis on Azure - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-images-computer-vision/2-image-analysis-azure)

---

**Question:** Which additional piece of information is included with each phrase returned by an image description task of the Azure AI Vision?

- [ ] Bounding box coordinates
- [x] Confidence score
- [ ] Endpoint
- [ ] Key

**Explanation:** Each phrase returned by an image description task of the Azure AI Vision includes the confidence score. An endpoint and a key must be provided to access the Azure AI Vision service. Bounding box coordinates are returned by services such as object detection, but not image description.

**Source(s):**

- [Get started with image analysis on Azure - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-images-computer-vision/2-image-analysis-azure)

---

**Question:** When using the Face Detect API of the Azure AI Face service, which feature helps identify whether a human face has glasses or headwear?

- [x] Face attributes
- [ ] Face ID
- [ ] Face landmarks
- [ ] Face rectangle

**Explanation:** Face attributes are a set of features that can be detected by the Face Detect API. Attributes such as accessories (glasses, mask, headwear, etc.) can be detected. Face rectangle, face ID, and face landmarks do not allow you to determine whether a person is wearing glasses or headwear.

**Source(s):**

- [What is the Azure Face service? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/overview-identity)
- [Detect and analyze faces with the Face service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/detect-analyze-faces/)

---

**Question:** Which service can you use to train an image classification model?

- [ ] Azure AI Vision
- [x] Azure AI Custom Vision
- [ ] Azure AI Face
- [ ] Azure AI Language

**Explanation:** Azure AI Custom Vision is an image recognition service that allows you to build and deploy your own image models. The Azure AI Vision service, Azure AI Face service, and Azure AI Language service do not provide the capability to train your own image model.

**Source(s):**

- [What is Custom Vision? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/custom-vision-service/overview)
- [Understand Text Analytics - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-text-with-text-analytics-service/2-understand-text-analytics)

---

**Question:** You need to identify numerical values that represent the probability of humans developing diabetes based on age and body fat percentage. Which type of machine learning model should you use?

- [ ] Hierarchical clustering
- [ ] Linear regression
- [x] Logistic regression
- [ ] Multiple linear regression

**Explanation:** Multiple linear regression models a relationship between two or more features and a single label. Linear regression uses a single feature. Logistic regression is a type of classification model, which returns either a Boolean value or a categorical decision. Hierarchical clustering groups data points that have similar characteristics.

**Source(s):**

- [Fundamentals of machine learning - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/)
- [What are classification models? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/understand-classification-machine-learning/2-what-is-classification)

---

**Question:** Predicting rainfall for a specific geographical location is an example of which type of machine learning?

- [ ] Classification
- [ ] Clustering
- [ ] Featurization
- [x] Regression

**Explanation:** Predicting rainfall is an example of regression machine learning, as it will predict a numeric value for future rainfall by using historical time-series rainfall data based on factors such as seasons. Clustering is a machine learning type that analyzes unlabeled data to find similarities in the data. Featurization is not a machine learning type, but a collection of techniques, such as feature engineering, data-scaling, and normalization. Classification is used to predict categories of data.

**Source(s):**

- [Regression - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/4-regression)

---

**Question:** A company deploys an online marketing campaign to social media platforms for a new product launch. The company wants to use machine learning to measure the sentiment of users on the Twitter platform who made posts in response to the campaign. Which type of machine learning is this?

- [x] Classification
- [ ] Clustering
- [ ] Data transformation
- [ ] Regression

**Explanation:** Classification is used to predict categories of data. It can predict which category or class an item of data belongs to. In this example, sentiment analysis can be carried out on the Twitter posts with a numeric value applied to the posts to identify and classify positive or negative sentiment. Clustering is a machine learning type that analyzes unlabeled data to find similarities in the data. Regression is a machine learning scenario that is used to predict numeric values. Data transformation is not a machine learning type.

**Source(s):**

- [Clustering - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/7-clustering)

---

**Question:** A retailer wants to group together online shoppers that have similar attributes to enable its marketing team to create targeted marketing campaigns for new product launches. Which type of machine learning is this?

- [ ] classification
- [x] clustering
- [ ] multiclass classification
- [ ] regression

**Explanation:** Clustering is a machine learning type that analyzes unlabeled data to find similarities present in the data. It then groups (clusters) similar data together. In this example, the company can group online customers based on attributes that include demographic data and shopping behaviors. The company can then recommend new products to those groups of customers who are most likely to be interested in them. Classification and multiclass classification are used to predict categories of data. Regression is a machine learning scenario that is used to predict numeric values.

**Source(s):**

- [Regression - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/4-regression)

---

**Question:** In a regression machine learning algorithm, how are features and labels handled in a validation dataset?

- [ ] Features are compared to the feature values in a training dataset
- [x] Features are used to generate predictions for the label, which is compared to the actual label values
- [ ] Labels are compared to the label values in a training dataset
- [ ] The label is used to generate predictions for features, which are compared to the actual feature values

**Explanation:** In a regression machine learning algorithm, features are used to generate predictions for the label, which is compared to the actual label value. There is no direct comparison of features or labels between the validation and training datasets.

**Source(s):**

- [What is regression? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/train-evaluate-regression-models/2-what-is-regression)

---

**Question:** Which feature makes regression an example of supervised machine learning?

- [x] use of historical data with known label values to train a model
- [ ] use of historical data with unknown label values to train a model
- [ ] use of randomly generated data with known label values to train a model
- [ ] use of randomly generated data with unknown label values to train a model

**Explanation:** Regression is an example of supervised machine learning due to the use of historical data with known label values to train a model. Regression does not rely on randomly generated data for training.

**Source(s):**

- [What is regression? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/train-evaluate-regression-models/2-what-is-regression)
- [What is clustering? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/train-evaluate-cluster-models/2-what-is-clustering)

---

**Question:** In a regression machine learning algorithm, what are the characteristics of features and labels in a validation dataset?

- [x] known feature and label values
- [ ] known feature values and unknown label values
- [ ] unknown feature and label values
- [ ] unknown feature values and known label values

**Explanation:** In a regression machine learning algorithm, a validation set contains known feature and label values.

**Source(s):**

- [What is regression? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/train-evaluate-regression-models/2-what-is-regression)

---

**Question:** In a regression machine learning algorithm, what are the characteristics of features and labels in a training dataset?

- [x] known feature and label values

**Explanation:** In a regression machine learning algorithm, a training set contains known feature and label values.

**Source(s):**

- [What is regression? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/train-evaluate-regression-models/2-what-is-regression)

---

**Question:** What is the purpose of a validation dataset used for as part of the development of a machine learning model?

- [ ] cleaning missing data
- [x] evaluating the trained model
- [ ] feature engineering
- [ ] summarizing the data

**Explanation:** The validation dataset is a sample of data held back from a training dataset. It is then used to evaluate the performance of the trained model. Cleaning missing data is used to detect missing values and perform operations to fix the data or create new values. Feature engineering is part of preparing the dataset and related data transformation processes. Summarizing the data is used to provide summary statistics, such as the mean or count of distinct values in a column.

**Source(s):**

- [Regression - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/4-regression)

---

**Question:** You need to use Azure Machine Learning to train a regression model. What should you create in Machine Learning studio?

- [x] a job
- [ ] a workspace
- [ ] an Azure container instance
- [ ] an Azure Kubernetes Service (AKS) cluster

**Explanation:** A job must be created in Machine Learning studio to use Machine Learning to train a regression model. A workspace must be created before you can access Machine Learning studio. An Azure container instance and an AKS cluster can be created as a deployment target after training of a model is complete.

**Source(s):**

- [Fundamentals of machine learning - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/)

---

**Question:** Which three supervised machine learning models can you train by using automated machine learning (automated ML) in the Azure Machine Learning studio? Each correct answer presents a complete solution.

- [x] Classification
- [ ] Clustering
- [ ] inference pipeline
- [x] regression
- [x] time-series forecasting

**Explanation:** Time-series forecasting, regression, and classification are supervised machine learning models. Automated ML learning can predict categories or classes by using a classification algorithm, as well as numeric values as part of the regression algorithm, and at a future point in time by using time-series data. Clustering is unsupervised machine learning and automated ML only works with supervised learning algorithms.

**Source(s):**

- [Fundamentals of machine learning - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/)

---

**Question:** Which machine learning algorithm module in the Azure Machine Learning designer is used to train a model?

- [ ] Clean Missing Data
- [ ] Evaluate Model
- [x] Linear Regression
- [ ] Select Columns in Dataset

**Explanation:** Linear regression is a machine learning algorithm module used for training regression models. The Clean Missing Data module is part of preparing the data and data transformation process. Select Columns in Dataset is a data transformation component that is used to choose a subset of columns of interest from a dataset. Evaluate model is a component used to measure the accuracy of trained models.

**Source(s):**

- [Regression - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/4-regression)

---

**Question:** Which natural language processing (NLP) technique assigns values to words such as plant and flower, so that they are considered closer to each other than a word such as airplane?

- [ ] frequency analysis
- [ ] lemmatization
- [ ] N-grams
- [x] vectorization

**Explanation:** Vectorization captures semantic relationships between words by assigning them to locations in n-dimensional space. Lemmatization, also known as stemming, normalizes words before counting them. Frequency analysis counts how often a word appears in a text. N-grams extend frequency analysis to include multi-term phrases.

**Source(s):**

- [Understand Text Analytics - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-text-with-text-analytics-service/2-understand-text-analytics)

---

**Question:** What is the first step in the statistical analysis of terms in a text in the context of natural language processing (NLP)?

- [ ] creating a vectorized model
- [x] removing stop words
- [ ] counting the occurrences of each word
- [ ] encoding words as numeric features

**Explanation:** Removing stop words is the first step in the statistical analysis of terms used in a text in the context of NLP. Counting the occurrences of each word takes place after stop words are removed. Creating a vectorized model is not part of statistical analysis. It is used to capture the semantic relationship between words. Encoding words as numeric features is not part of statistical analysis. It is frequently used in sentiment analysis.

**Source(s):**

- [Understand Text Analytics – Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-text-with-text-analytics-service/2-understand-text-analytics)

---

**Question:** Which two Azure AI Services features can be used to enable both text-to-text and speech-to-text between multiple languages? Each correct answer presents part of the solution.

- [ ] Conversational Language Understanding
- [ ] key phrase extraction
- [ ] language detection
- [x] the Speech service
- [x] the Translator service

**Explanation:** The Azure AI Speech service can be used to generate spoken audio from a text source for text-to-speech translation. The Azure AI Translator service directly supports text-to-text translation in more than 60 languages. Key phrase extraction, Conversational Language Understanding, and language detection are not used for language translation for text-to-text and speech-to-text translation.

**Source(s):**

- [Translate text and speech – Training | Microsoft Learn](https://learn.microsoft.com/training/modules/translate-text-with-translation-service/)
- [Azure Cognitive Services Translator documentation – quickstarts, tutorials, API reference – Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/translator/)

---

**Question:** Which two features of Azure AI Services allow you to identify issues from support question data, as well as identify any people and products that are mentioned? Each correct answer presents part of the solution.

- [ ] Azure AI Bot Service
- [ ] Conversational Language Understanding
- [x] key phrase extraction
- [x] named entity recognition
- [ ] Azure AI Speech service

**Explanation:** Key phrase extraction is used to extract key phrases to identify the main concepts in a text. It enables a company to identify the main talking points from the support question data and allows them to identify common issues. Named entity recognition can identify and categorize entities in unstructured text, such as people, places, organizations, and quantities. The Azure AI Speech service, Conversational Language Understanding, and Azure AI Bot Service are not designed for identifying key phrases or entities.

**Source(s):**

- Key Phrase Extraction cognitive skill – Azure Cognitive Search | Microsoft Learn
- Extract insights from text with the Language service – Training | Microsoft Learn
- [Analyze text with the Language service – Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-text-with-text-analytics-service/)

---

**Question:** Which Azure AI Service for Language feature allows you to analyze written articles to extract information and concepts, such as people and locations, for classification purposes?

- [ ] Azure AI Content Moderator
- [ ] key phrase extraction
- [x] named entity recognition
- [ ] Personally Identifiable Information (PII) detection

**Explanation:** Named entity recognition can identify and categorize entities in unstructured text, such as people, places, organizations, and quantities, and is suitable to support the development of an article recommendation system. Key phrase extraction, Content Moderator, and the PII feature are not suited to entity recognition tasks to build a recommender system.

**Source(s):**

- [What is the Named Entity Recognition (NER) feature in Azure Cognitive Service for Language? – Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/named-entity-recognition/overview)
- [Analyze text with the Language service – Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-text-with-text-analytics-service/)

---

**Question:** Which feature of the Azure AI Language service includes functionality that returns links to external websites to disambiguate terms identified in a text?

- [x] entity recognition
- [ ] key phrase extraction
- [ ] language detection
- [ ] sentiment analysis

**Explanation:** Entity recognition includes the entity linking functionality that returns links to external websites to disambiguate terms (entities) identified in a text. Key phrase extraction evaluates the text of a document and identifies its main talking points. Azure AI Language detection identifies the language in which text is written. Sentiment analysis evaluates text and returns sentiment scores and labels for each sentence.

**Source(s):**

- [Get started with text analysis – Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-text-with-text-analytics-service/2-get-started-azure)

---

**Question:** Which Azure resource provides direct access to both Azure AI Translator and Azure AI Speech services through a single endpoint and authentication key?

- [ ] Azure AI Bot Service
- [x] Azure AI Services
- [ ] Azure Machine Learning
- [ ] Azure AI Language service

**Explanation:** Azure AI Services provides direct access to both Azure AI Translator and Azure AI Speech services through a single endpoint and authentication key. Azure AI Language service can be used to access Azure AI Language service, but not the Azure AI Translator and Azure AI Speech services.

**Source(s):**

- [Get started with translation in Azure - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/translate-text-with-translation-service/2-get-started-azure)

---

**Question:** Which three features are elements of the Azure AI Speech service? Each correct answer presents a complete solution.

- [ ] document translation
- [x] language identification
- [x] speaker recognition
- [ ] text translation
- [x] voice assistants

**Explanation:** Language identification, speaker recognition, and voice assistants are all elements of the Azure AI Speech service. Text translation and document translation are part of the Translator service.

**Source(s):**

- [What is the Speech service? | Azure Cognitive Services  | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/speech-service/overview)
- [Recognize and synthesize speech - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/recognize-synthesize-speech/)

---

**Question:** [Answer choice] can search, classify, and compare sources of text for similarity.
Select the answer that correctly completes the sentence.

- [x] Embeddings

**Explanation:** Embeddings is an Azure OpenAI model that converts text into numerical vectors for analysis. Embeddings can be used to search, classify, and compare sources of text for similarity.

**Source(s):**

- [Fundamentals of Generative AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-generative-ai/)

---

**Question:** Which principle of responsible artificial intelligence (AI) raises awareness about the limitations of AI-based solutions?

- [ ] accountability
- [ ] privacy and security
- [ ] reliability and safety
- [x] transparency

**Explanation:** Transparency provides clarity regarding the purpose of AI solutions, the way they work, as well as their limitations. The privacy and security, reliability and safety, and accountability principles focus on the capabilities of AI, rather than raising awareness about its limitations.

**Source(s):**

- [Understand Responsible AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/8-understand-responsible-ai)
- [Identify principles and practices for responsible AI - Training | Microsoft Learn](https://learn.microsoft.com/training/paths/responsible-ai-business-principles/)

---

**Question:** Which principle of responsible artificial intelligence (AI) defines the framework of governance and organization principles that meet ethical and legal standards of AI solutions?

- [x] accountability

**Explanation:** Accountability defines the framework of governance and organizational principles, which are meant to ensure that AI solutions meet ethical and legal standards that are clearly defined. The other answer choices do not define the framework of governance and organization principles, but provide guidance regarding the ethical and legal aspects of the corresponding standards.

**Source(s):**

- [Understand Responsible AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/8-understand-responsible-ai)

---

**Question:** Select the answer that correctly completes the sentence. [Answer choice] use plugins to provide end users with the ability to get help with common tasks from a generative AI model.

- [x] Copilots
- [ ] Language Understanding solutions
- [ ] Question answering models
- [ ] RESTful API services

**Explanation:** Copilots are often integrated into applications to provide a way for users to get help with common tasks from a generative AI model. Copilots are based on a common architecture, so developers can build custom copilots for various business-specific applications and services.

**Source(s):**

- [What are copilots? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-generative-ai/5-copilots)

---

**Question:** As per the NIST AI Risk Management Framework, what is the first stage to consider when developing a responsible generative AI solution?

- [x] Identify potential harms.
- [ ] Measure the presence of potential harms.
- [ ] Mitigate potential harms.
- [ ] Operate the solution.

**Explanation:** Identifying potential harms is the first stage when planning a responsible generative AI solution.

**Source(s):**

- [Responsible generative AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/responsible-ai-studio/)

---

**Question:** Which artificial intelligence (AI) technique should be used to extract the name of a store from a photograph displaying the store front?

- [ ] image classification
- [ ] natural language processing (NLP)
- [x] optical character recognition (OCR)
- [ ] semantic segmentation

**Explanation:** OCR provides the ability to detect and read text in images. NLP is an area of AI that deals with identifying the meaning of a written or spoken language, but not detecting or reading text in images. Image classification classifies images based on their contents. Semantic segmentation provides the ability to classify individual pixels in an image.

**Source(s):**

- [Understand computer vision - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/4-understand-computer-vision)

---

**Question:** Which computer vision solution provides the ability to identify a person's age based on a photograph?

- [x] facial detection
- [ ] image classification
- [ ] object detection
- [ ] semantic segmentation

**Explanation:** Facial detection provides the ability to detect and analyze human faces in an image, including identifying a person's age based on a photograph. Image classification classifies images based on their contents. Object detection provides the ability to generate bounding boxes identifying the locations of different types of vehicles in an image. Semantic segmentation provides the ability to classify individual pixels in an image.

**Source(s):**

- [Get started with image analysis on Azure - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-images-computer-vision/2-image-analysis-azure)
- - [Understand computer vision - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/4-understand-computer-vision)

---

**Question:** You have a set of images. Each image shows multiple vehicles. What allows you to identity different vehicle types in the same traffic monitoring image??

- [ ] image classification
- [ ] linear regression
- [x] object detection
- [ ] optical character recognition (OCR)

**Explanation:** Object detection can be used to evaluate traffic monitoring images to quickly classify specific vehicle types, such as car, bus, or cyclist. Linear regression is a machine learning training algorithm for training regression models. Image classification is part of computer vision that is concerned with the primary contents of an image. OCR is used to extract text and handwriting from images.

**Source(s):**

- [Machine learning for computer vision - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-images-computer-vision/2b-computer-vision-models)

---

**Question:** What can be used for an attendance system that can scan handwritten signatures?

- [ ] face detection
- [ ] image classification
- [ ] object detection
- [x] optical character recognition (OCR)

**Explanation:** OCR is used to extract text and handwriting from images. In this case, it can be used to extract signatures for attendance purposes. Face detection can detect and verify human faces, not text, from images. Object detection can detect multiple objects in an image by using bounding box coordinates. It is not used to extract handwritten text. Image classification is the part of computer vision that is concerned with the primary contents of an image.

**Source(s):**

- [Read text with the Computer Vision service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/read-text-computer-vision/)

---

**Question:** Which two prebuilt models allow you to use the Azure AI Document Intelligence service to scan information from international passports and sales accounts? Each correct answer presents part of the solution.

- [ ] business card model
- [x] ID document model
- [x] invoice model
- [ ] language model
- [ ] receipt model

**Explanation:** The invoice model extracts key information from sales invoices and is suitable for extracting information from sales account documents. The ID document model is optimized to analyze and extract key information from US driver’s licenses and international passport biographical pages. The business card model, receipt model, and language model are not suitable to extract information from passports or sales account documents.

**Source(s):**

- [Analyze receipts with the Form Recognizer service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-receipts-form-recognizer/)
- [Document processing models - Form Recognizer - Azure Applied AI Services | Microsoft Learn](https://learn.microsoft.com/azure/applied-ai-services/form-recognizer/concept-model-overview?view=form-recog-3.0.0)

---

**Question:** Which two Azure AI Document Intelligence models include identifying common data fields as part of its data extraction capabilities? Each correct answer presents a complete solution.

- [x] business card model
- [ ] general document model
- [x] invoice model
- [ ] layout model
- [ ] read model

**Explanation:** The business card model analyzes and extracts key information from business card images and includes common data field extractions, such as name and email. The invoice model extracts key information from sales invoices and includes common data fields used in invoices for extraction. The read model, layout model, and general document model do not identify and extract common data fields.

**Source(s):**

- [Document processing models - Form Recognizer - Azure Applied AI Services | Microsoft Learn](https://learn.microsoft.com/azure/applied-ai-services/form-recognizer/concept-model-overview?view=form-recog-3.0.0)
- [Analyze receipts with the Form Recognizer service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-receipts-form-recognizer/)

---

**Question:** When using the Azure AI Face service, what should you use to perform one-to-many or one-to-one face matching? Each correct answer presents a complete solution.

- [ ] Custom Vision
- [ ] face attributes
- [x] face identification
- [x] face verification
- [ ] find similar faces

**Explanation:** Face identification in the Azure AI Face service can address one-to-many matching of one face in an image to a set of faces in a secure repository. Face verification has the capability for one-to-one matching of a face in an image to a single face from a secure repository or a photo to verify whether they are the same individual. Face attributes, the find similar faces operation, and Azure AI Custom Vision do not verify the identity of a face.

**Source(s):**

- [What is the Azure Face service? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/computer-vision/overview-identity)
- [Detect and analyze faces with the Face service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/detect-analyze-faces/)

---

**Question:** Which type of artificial intelligence (AI) workload provides the ability to generate bounding boxes that identify the locations of different types of vehicles in an image?

- [ ] image analysis
- [ ] image classification
- [ ] optical character recognition (OCR)
- [x] object detection

**Explanation:** Object detection provides the ability to generate bounding boxes identifying the locations of different types of vehicles in an image. The other answer choices also process images, but their outcomes are different.

**Source(s):**

- [Understand computer vision - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/4-understand-computer-vision)

---

**Question:** Which AI service can be integrated into chat applications and generate content in the form of text?

- [ ] Azure AI Language
- [ ] Azure AI Metrics Advisor
- [ ] Azure AI Vision
- [x] Azure OpenAI

**Explanation:** Azure OpenAI is the only service capable of generating text that can be used in chat applications to create conversational experiences. The other workloads are Azure Cognitive Services used for different purposes, but not for generating text used in chat applications.

**Source(s):**

- [Understand generative AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/6-understand-generative-ai)

---

**Question:** Which principle of responsible artificial intelligence (AI) involves evaluating and mitigating the bias introduced by the features of a model?

- [ ] accountability
- [x] fairness
- [ ] privacy
- [ ] transparency

**Explanation:** Fairness involves evaluating and mitigating the bias introduced by the features of a model. Privacy is meant to ensure that privacy provisions are included in AI solutions. Transparency provides clarity regarding the purpose of AI solutions, the way they work, as well as their limitations. Accountability is focused on ensuring that AI solutions meet ethical and legal standards that are clearly defined.

**Source(s):**

- [Understand Responsible AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/8-understand-responsible-ai)

---

**Question:** Which type machine learning algorithm predicts a numeric label associated with an item based on that item’s features?

- [ ] classification
- [ ] clustering
- [x] regression
- [ ] unsupervised

**Explanation:** The regression algorithms are used to predict numeric values. Clustering algorithms groups data points that have similar characteristics. Classification algorithms are used to predict the category to which an input value belongs. Unsupervised learning is a category of learning algorithms that includes clustering, but not regression or classification.

**Source(s):**

- [Fundamentals of machine learning - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/)
- [What are classification models? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/understand-classification-machine-learning/2-what-is-classification)
- [What is clustering? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/train-evaluate-cluster-models/2-what-is-clustering)

---

**Question:** You plan to use machine learning to predict the probability of humans developing diabetes based on their age and body fat percentage. What should the model include?

- [ ] three features
- [ ] three labels
- [x] two features and one label
- [ ] two labels and one feature

**Explanation:** The scenario represents a model that is meant to establish a relationship between two features (age and body fat percentage) and one label (the likelihood of developing diabetes). The features are descriptive attributes (serving as the input), while the label is the characteristic you are trying to predict (serving as the output).

**Source(s):**

- [Multiple linear regression and R-squared - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/understand-regression-machine-learning/4-multiple-linear-regression)

---

**Question:** Which assumption of the multiple linear regression model should be satisfied to avoid misleading predictions?

- [ ] Features are dependent on each other.
- [ ] Features are independent of each other.
- [ ] Labels are dependent on each other.
- [ ] Labels are independent of each other.

**Explanation:** Multiple linear regression models the relationship between several features and a single label. The features must be independent of each other, otherwise, the model's predictions will be misleading.

**Source(s):**

- [Multiple linear regression and R-squared - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/understand-regression-machine-learning/4-multiple-linear-regression)

---

**Question:** A company is using machine learning to predict house prices based on appropriate house attributes. For the machine learning model, which attribute is the label?


- [ ] age of the house
- [ ] floor space size
- [ ] number of bedrooms
- [x] price of the house

**Explanation:** The price of the house is the label you are attempting to predict through the machine learning model. This is typically done by using a regression model. Floor space size, number of bedrooms, and age of the house are all input variables for the model to help predict the house price label.

**Source(s):**

- [Fundamentals of machine learning - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/)

---

**Question:** You need to use the Azure Machine Learning designer to deploy a predictive service from a newly trained model. What should you do first in the Machine Learning designer?

- [ ] Add a dataset.
- [ ] Add training modules.
- [x] Create an inference pipeline.
- [ ] Create an inferencing cluster.

**Explanation:** To deploy a predictive service from a newly trained model by using the Machine Learning designer, you must first create a pipeline in the Machine Learning designer. Adding training modules by using the Machine Learning designer takes place before creating a trained model, which already exists. Adding a dataset by using the Machine Learning designer requires that a pipeline already exists. To create an inferencing cluster, you must use Machine Learning studio.

**Source(s):**

- [Regression - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/4-regression)

---

**Question:** Which three data transformation modules are in the Azure Machine Learning designer?

- [x] Clean Missing Data
- [ ] Model Evaluate Model
- [x] Normalize Data
- [x] Select Columns in Dataset
- [ ] Train Clustering

**Explanation:** Normalize Data is a data transformation module that is used to change the values of numeric columns in a dataset to a common scale, without distorting differences in the range of values. The Clean Missing Data module is part of preparing the data and data transformation process. Select Columns in Dataset is a data transformation component that is used to choose a subset of columns of interest from a dataset. The train clustering model is not a part of data transformation. The evaluate model is a component used to measure the accuracy of training models.

**Source(s):**

- [Clustering - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/7-clustering)

---

**Question:** For which two scenarios is the Universal Language Model used by the speech-to-text API optimized? Each correct answer presents a complete solution.

- [ ] acoustic
- [x] conversational
- [x] dictation
- [ ] language
- [ ] pronunciation

**Explanation:** The Universal Language Model used by the speech-to-text API is optimized for conversational and dictation scenarios. The acoustic, language, and pronunciation scenarios require developing your own model.

**Source(s):**

- [Get started with speech on Azure - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/recognize-synthesize-speech/2-get-started-azure)

---

**Question:** Which type of translation does the Azure AI Translator service support?

- [ ] speech-to-speech
- [ ] speech-to-text
- [ ] text-to-speech
- [x] text-to-text

**Explanation:** The Azure AI Translator service supports text-to-text translation, but it does not support speech-to-text, text-to-speech, or speech-to-speech translation.

**Source(s):**

- [Get started with translation in Azure - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/translate-text-with-translation-service/2-get-started-azure)

---

**Question:** Which feature of the Azure AI Translator service is available only to Custom Translator?

- [ ] document translation
- [x] model training with a dictionary
- [ ] speaker recognition
- [ ] text translation

**Explanation:** Model training with a dictionary can be used with Custom Translator when you do not have enough parallel sentences to meet the 10,000 minimum requirements. The resulting model will typically complete training much faster than with full training and will use the baseline models for translation along with the dictionaries you have added.

**Source(s):**

- [What is Custom Translator? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/translator/custom-translator/overview)
- [Introduction to Translator - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/intro-to-translator/)

---

**Question:** When using the Azure AI Service for Language, what should you use to provide further information online about entities extracted from a text?

- [x] entity linking
- [ ] key phrase extraction
- [ ] named entity recognition
- [ ] text translation

**Explanation:** Entity Linking identifies and disambiguates the identity of entities found in a text. Key phrase extraction is not used to extract entities and is used instead to extract key phrases to identify the main concepts in a text. Named entity recognition cannot provide a link for each entity to view further information. Text translation is part of the Azure AI Translator service.

**Source(s):**

- [What is entity linking in Azure Cognitive Service for Language? - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/entity-linking/overview)
- [Analyze text with the Language service - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-text-with-text-analytics-service/)

---

**Question:** Which feature of the Azure AI Speech service can identify distinct user voices?

- [ ] language identification
- [x] speech recognition
- [ ] speech synthesis
- [ ] speech translation

**Explanation:** Speech recognition uses audio data to analyze speech and determine recognizable patterns that can be mapped to distinct user voices. Azure AI Speech synthesis is concerned with vocalizing data, usually by converting text to speech. Azure AI Speech translation is concerned with multilanguage translation of speech. Language identification is used to identify languages spoken in audio when compared against a list of supported languages.

**Source(s):**

- [Speaker recognition overview - Speech service - Azure Cognitive Services | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/speech-service/speaker-recognition-overview)
- [Recognize and synthesize speech - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/recognize-synthesize-speech/)

---

**Question:** Which two specialized domain models are supported by Azure AI Vision when categorizing an image? Each correct answer presents a complete solution.

- [x] celebrities
- [ ] image types
- [x] landmarks
- [ ] people_
- [ ] people_group

**Explanation:** When categorizing an image, the Azure AI Vision service supports two specialized domain models: celebrities and landmarks. Image types is an additional capability of the computer vision service, allowing it to detect the type of image, such as a clip art image or a line drawing. Both people_ and people_group are supported categories when performing image classification.

**Source(s):**

- [Get started with image analysis on Azure - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-images-computer-vision/2-image-analysis-azure)

---

**Question:** You are exploring solutions to improve the document search and indexing service for employees. You need an artificial intelligence (AI) search solution that will include searching text in various types of documents, such as images. Which type of AI workload is this?

- [ ] semantic segmentation
- [ ] computer vision
- [ ] conversational AI
- [x] data mining

**Explanation:** Data mining workloads primarily focus on the searching and indexing of data. The computer vision can be used to extract information from images, but it is not a search and indexing solution. Conversational AI is part of natural language processing (NLP) and facilitates the creation of chatbots. Semantic segmentation provides the ability to classify individual pixels in an image depending on the object that they represent.

**Source(s):**

- [Microsoft Azure AI Fundamentals: Explore knowledge mining - Training | Microsoft Learn](https://learn.microsoft.com/training/paths/explore-fundamentals-of-knowledge-mining/)

---

**Question:** A company is currently developing driverless agriculture vehicles to help harvest crops. The vehicles will be deployed alongside people working in the crop fields, and as such, the company will need to carry out robust testing. Which principle of responsible artificial intelligence (AI) is most important in this case?

- [ ] accountability
- [ ] inclusiveness
- [x] reliability and safety
- [ ] transparency

**Explanation:** The reliability and safety principles are of paramount importance here as it requires an AI system to work alongside people in a physical environment by using AI controlled machinery. The system must function safely, while ensuring no harm will come to human life.

**Source(s):**

- [Understand Responsible AI - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/8-understand-responsible-ai)

---

**Question:** Which type of machine learning algorithm finds the optimal way to split a dataset into groups without relying on training and validating label predictions?

- [ ] classification
- [x] clustering
- [ ] regression
- [ ] supervised

**Explanation:** A clustering algorithm is an example of unsupervised learning, which groups data points that have similar characteristics without relying on training and validating label predictions. Supervised learning is a category of learning algorithms that includes regression and classification, but not clustering. Classification and regression algorithms are examples of supervised machine learning.

**Source(s):**

- [Fundamentals of machine learning - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/)
- [What are classification models? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/understand-classification-machine-learning/2-what-is-classification)
- [What is clustering? - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/train-evaluate-cluster-models/2-what-is-clustering)

---

**Question:** A company wants to predict household water use based on the number of people in a house, the weather temperature, and the time of year. In terms of data labels and features, what is the label in this use case?

- [ ] number of people in the house
- [ ] time of year
- [x] water use
- [ ] weather temperature

**Explanation:** Water use is the label value that you want to predict, also known as the independent variable. Number of people in the house, weather temperature, and time of year are features, and are values that are dependent on the label. Number of people in the house, weather temperature, and time of year can influence the water consumed in a household.

**Source(s):**

- [Fundamentals of machine learning - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/)

---

**Question:** You need to use the Azure Machine Learning designer to train a machine learning model. What should you do first in the Machine Learning designer?

- [ ] Add a dataset.
- [ ] Add training modules.
- [x] Create a pipeline.
- [ ] Deploy a service.

**Explanation:** Before you can start training a machine learning model, you must first create a pipeline in the Machine Learning designer. This is followed by adding a dataset, adding training modules, and eventually deploying a service.

**Source(s):**

- [Regression - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/fundamentals-machine-learning/4-regression)

---

**Question:** You train a regression model by using automated machine learning (automated ML) in the Azure Machine Learning studio. You review the best model summary. You need to publish the model for others to use from the internet. What should you do next?

- [ ] Create a compute cluster.
- [x] Deploy the model to an endpoint.
- [ ] Split the data into training and validation datasets.
- [ ] Test the deployed service.

**Explanation:** You can deploy the best performing model for client applications to use over the internet by using an endpoint. Compute clusters are used to train the model and are created directly after you create a Machine Learning workspace. Before you can test the model’s endpoint, you must deploy it first to an endpoint. Automated ML performs the validation automatically, so you do not need to split the dataset.

**Source(s):**

- [What is automated ML? AutoML - Azure Machine Learning | Microsoft Learn](https://learn.microsoft.com/azure/machine-learning/concept-automated-ml)
- [Regression - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/fundamentals-machine-learning/4-regression)

---

**Question:** Which natural language processing (NLP) technique normalizes words before counting them?

- [ ] frequency analysis
- [ ] N-grams
- [x] stemming
- [ ] vectorization

**Explanation:** Stemming normalizes words before counting them. Frequency analysis counts how often a word appears in a text. N-grams extend frequency analysis to include multi-term phrases. Vectorization captures semantic relationships between words by assigning them to locations in n-dimensional space.

**Source(s):**

- [Understand Text Analytics - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/analyze-text-with-text-analytics-service/2-understand-text-analytics)

---

**Question:** You want to create a model to predict sales of ice cream based on historic data that includes daily ice cream sales totals and weather measurements. Which Azure service should you use?

- [x] Azure Machine Learning
- [ ] Azure AI Bot Service
- [ ] Azure AI Language

**Explanation:** Azure Machine Learning enables you to train a predictive model from the existing data. The Azure AI Bot Service provides a platform for conversational AI. The Language Service is used for understanding and analyzing text, and creating intelligent applications.

**Source(s):**

- [Fundamental AI Concepts - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/get-started-ai-fundamentals/)

---

**Question:** You work for a wildlife sanctuary and are considering using AI to identify bird species from images. Which AI service should you use to prototype your idea?

- [x] Azure AI Vision
- [ ] Azure AI Search
- [ ] Azure OpenAI

**Explanation:** Azure AI Vision allows you to add images to the existing model to improve the image identifier model. This is a good choice for identifying the small differences between bird species. Azure AI Search includes data extraction and indexing capabilities for knowledge mining. Azure OpenAI helps organizations generate content and insights. Another Azure AI service should be used to identify bird species from images.

**Source(s):**

- [Fundamental AI Concepts - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/get-started-ai-fundamentals/)

---

**Question:** A predictive app provides audio output for visually impaired users. Which principle of Responsible AI is reflected here?

- [ ] Transparency
- [x] Inclusiveness
- [ ] Fairness

**Explanation:** Inclusiveness is about how AI should bring benefits to all parts of society, regardless of physical ability, gender, sexual orientation, ethnicity, or other factors. Transparency is about fully communicating the purpose of the system, how it works, and what limitations might be expected. Fairness is about developing models and applications without incorporating any bias based on gender, ethnicity, or other factors that might result in an unfair advantage or disadvantage to specific groups.

**Source(s):**

- [Fundamental AI Concepts - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/get-started-ai-fundamentals/)

---

**Question:** You want to create a model to predict the cost of heating an office building based on its size in square feet and the number of employees working there. What kind of machine learning problem is this?

- [x] Regression
- [ ] Classification
- [ ] Clustering

**Explanation:** Regression models predict numeric values. Classification models predict the class to which an observed case belongs. Clustering models group similar items together.

**Source(s):**

- [Fundamentals of Machine Learning - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/fundamentals-machine-learning/)

---

**Question:** You need to evaluate a classification model. Which metric can you use?

- [ ] Mean squared error (MSE)
- [x] Precision
- [ ] Silhouette

**Explanation:** Precision is a useful metric for evaluating classification models. MSE is used to evaluate regression models. Silhouette is used to evaluate clustering models.

**Source(s):**

- [Fundamentals of Machine Learning - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/fundamentals-machine-learning/)

---

**Question:** In deep learning, what is the purpose of a loss function?

- [ ] To remove data for which no known label values are provided
- [x] To evaluate the aggregate difference between predicted and actual label values
- [ ] To calculate the cost of training a neural network rather than a statistical model

**Explanation:** A loss function determines the overall variance, or loss, between predicted and actual label values. A loss function does not remove data. A loss function does not calculate cost.

**Source(s):**

- [Fundamentals of Machine Learning - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/fundamentals-machine-learning/)

---

**Question:** What does automated machine learning in Azure Machine Learning enable you to do?

- [ ] Automatically deploy new versions of a model as they're trained
- [ ] Automatically provision Azure Machine Learning workspaces for new data scientists in an organization
- [x] Automatically run multiple training jobs using different algorithms and parameters to find the best model

**Explanation:** Automated machine learning runs multiple training jobs, varying algorithms and parameters, to find the best model for your data. Automated machine learning does not automatically deploy models. Automated machine learning does not automate workspace provisioning.

**Source(s):**

- [Fundamentals of Machine Learning - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/fundamentals-machine-learning/)

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

---

**Question:**

- [ ]
- [ ]
- [ ]
- [ ]

**Explanation:**

**Source(s):**

- []()

