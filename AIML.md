<h1 align="center">Hello 👋, We are e-Designing and Marketing </h1>
<h3 align="center">Artificial Intelligence <br>and<br> Machine Learning</h3>

## 💯 #100DaysOfAIML

<p> This is an intitiation which is for freshers and any person who wishes to learn any technology with a roadmap, resources, practical experience, and guidence/mentorship. </p>

## Mentor Details:

 1. Name:  **Vishnu Sai Nadella (SD)**
 2. LinkedIn: [Click Here](https://www.linkedin.com/in/vishnu-nadella-007/)
 3. GitHub: [Click Here](https://www.github.com/VishnuNadella)


# Introduction to Ai / Ml
Artificial Intelligence (AI) and Machine Learning (ML) are two related fields that involve using computer algorithms to perform tasks that typically require human intelligence.

AI involves creating machines that can perform tasks that normally require human intelligence, such as speech recognition, decision making, and image analysis. ML is a subset of AI that involves building systems that can automatically learn and improve from data, without being explicitly programmed.

ML algorithms use statistical techniques to identify patterns in data and make predictions or decisions based on that data. For example, a ML algorithm can be trained on a dataset of images to identify certain objects, such as cars or trees. The algorithm will learn to recognize the patterns that correspond to those objects and can then apply that knowledge to new images it hasn't seen before.

# Road-Map
> Note: Please refer to the resources that are mentioned at the end of the file

## (Day 1 - Day 10)
### Python 
- Youtube: [Click Here](https://goo.gl/eVauVX)
- Official Docs: [Click Here](https://www.python.org/doc/)

## (Day 11 - Day 20)
### NumPy
- Youtube: [Click Here](https://www.youtube.com/watch?v=uRsE5WGiKWo)

### Pandas
- Youtube: [Click Here](https://www.youtube.com/watch?v=tRKeLrwfUgU)

### Data Wrangling
- Blog: [Click Here](https://www.shanelynn.ie/summarising-aggregation-and-grouping-data-in-python-pandas/)
- Youtube: [Click Here](https://www.youtube.com/watch?v=gtjxAH8uaP0)

## (Day 21 - Day 30)
### Matplotlib
- Youtube: [Click Here](https://www.youtube.com/watch?v=3Xc3CA655Y4)
- Docs: [Click Here](https://matplotlib.org/)

### Seaborn
- Youtube: [Click Here](https://www.youtube.com/watch?v=hLbVXF70BCE&list=PLjVLYmrlmjGfhqSO3rF4n02rrj9w2Ch2C)
- Docs: [Click Here](https://seaborn.pydata.org/tutorial.html)

## (Day31 - Day 40)
### Statistics (Math for Machine Learning)
- Matrices : [Click Here](https://www.khanacademy.org/math/precalculus/x9e81a4f98389efdf:matrices)
- Linear algebra : [Click Here](https://www.khanacademy.org/math/linear-algebra)
- Probability and Statistics : [Click Here](https://www.khanacademy.org/math/statistics-probability)
- Bayesian inference : [Click Here](https://seeing-theory.brown.edu/bayesian-inference/index.html)
- Time series analysis : [Click Here](https://www.tableau.com/learn/articles/time-series-analysis)

## (Day 41 - Day 50)
### Sci-kit learn (Machine Learning)
<img src = "https://scikit-learn.org/stable/_static/ml_map.png">

Video Tutorial: [Click Here](https://www.youtube.com/watch?v=pqNCD_5r0IU&t=748s)

- Classification
  - Linear
  - KNN (data with discrete labels)
- Regression
  - Linear
  - KNN (data with continuous labels)
- Clustering
  - SVM
  - K-Means
  - Hierarchical
- Dimensionality reduction

## (Day 51 - Day 70)
### Neural Networks (Deep Learning)

- ANN: [Click Here](https://www.kaggle.com/learn/intro-to-deep-learning)
- CNN: [Click Here](https://poloclub.github.io/cnn-explainer/)
- RNN: [Click Here](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-recurrent-neural-networks)
- NLP: [Click Here](https://monkeylearn.com/blog/what-is-natural-language-processing/)
- Activation Functions: [Click Here](https://www.mygreatlearning.com/blog/activation-functions/)
- Pytorch: [Click Here](https://www.udacity.com/course/deep-learning-pytorch--ud188?irclickid=Xf1XoHWb-xyNU2WwauzlbwGNUkAyWkXpOQV2RA0&irgwc=1&utm_source=affiliate&utm_medium=&aff=2406137&utm_term=&utm_campaign=__&utm_content=&adid=786224)
- Tensorflow: [Click Here](https://www.udacity.com/course/intro-to-tensorflow-for-deep-learning--ud187?irclickid=Xf1XoHWb-xyNU2WwauzlbwGNUkAyWkXJOQV2RA0&irgwc=1&utm_source=affiliate&utm_medium=&aff=2406137&utm_term=&utm_campaign=__&utm_content=&adid=786224)

## (Day 71 - Day 80)
### Deployment:
- Streamlit: [Click Here](https://streamlit.io/)
- Fast API: [Click Here](https://fastapi.tiangolo.com/)
- Deta: [Click Here](https://deta.space/)

## (Day 81 - Day 90)
### Extras:
- SQL: [Click Here](https://mode.com/sql-tutorial/)
- Git and Github: [Click Here](https://www.youtube.com/watch?v=SWYqp7iY_Tc)

### Activation Functions

| Activation Function | Formula | Range | Derivative | Use Cases |
|---|---|---|---|---|
| Binary Step | f(x) = {1 if x >= 0, 0 otherwise} | [0, 1] | f(x) = 0 if x < 0, f(x) = 1 if x >= 0 | Binary classification |
| Linear | f(x) = w * x + b | R | f(x) = w * x + b | Regression |
| Sigmoid | f(x) = 1 / (1 + exp(-x)) | (0, 1) | f(x) = exp(-x) / (1 + exp(-x))^2 | Binary classification |
| Tanh | f(x) = (exp(x) - exp(-x)) / (exp(x) + exp(-x)) | (-1, 1) | f(1 - f(x)) | Binary classification |
| ReLU | f(x) = max(0, x) | R | f(x) = 1 if x >= 0, f(x) = 0 if x < 0 | Regression, classification |
| Leaky ReLU | f(x) = {0.01x if x < 0, x otherwise} | R | f(x) = 0.01 if x < 0, f(x) = 1 if x >= 0 | Regression, classification |
| Parametric ReLU | f(x) = {alpha * x if x < 0, x otherwise} | R | f(x) = alpha if x < 0, f(x) = 1 if x >= 0 | Regression, classification |
| Exponential Linear Unit (ELU) | f(x) = {alpha * (exp(x) - 1) if x < 0, x otherwise} | R | f(x) = alpha * (exp(x) - 1) if x < 0, f(x) = 1 if x >= 0 | Regression, classification |
| Swish | f(x) = x * sigmoid(x) | R | f(x) = x * (1 / (1 + exp(-x))) | Regression, classification |
| Softmax | f(x) = exp(x) / sum(exp(x)) | (0, 1) | f(x) = exp(x) / sum(exp(x)) | Multiclass classification |


### Resources
- Image Annotation: [Click Here](https://www.makesense.ai/)
- Live Python: [Click Here](https://pythontutor.com/visualize.html#mode=edit)

### Latest Models Description
- BERT: [Click Here](https://ai.googleblog.com/2018/11/open-sourcing-bert-state-of-art-pre.html)
- Transformers: [Click Here](https://towardsdatascience.com/transformers-89034557de14)
- OpenAI chatGPT: [Click Here](https://chat.openai.com/chat)
- OpenAI Dall-E2: [Click Here](https://openai.com/blog/dall-e/)
- Google: [Click Here](https://ai.google/)
