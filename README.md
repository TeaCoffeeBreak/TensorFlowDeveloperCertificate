# TensorFlow Developer Certificate

About exam : https://www.tensorflow.org/certificate

# exam scope
- Category 1: ​Basic / Simple model
- Category 2: ​Model from learning dataset
- Category 3: ​Convolutional Neural Network with real-world image dataset
- Category 4: ​NLP Text Classification with real-world text dataset
- Category 5: ​Sequence Model with real-world numeric dataset

# coursera 
https://www.coursera.org/professional-certificates/tensorflow-in-practice#courses

- Course 1: Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning
- Course 2: Convolutional Neural Networks in TensorFlow
- Course 3: Natural Language Processing in TensorFlow
- Course 4: Sequences, Time Series and Prediction



TensorFlow tutorial : https://www.tensorflow.org/tutorials

2X spped spped to get high level picture
https://www.youtube.com/watch?v=tpCFfeUEGs8&t=22995s

What is TensorFlow ?
- End to end Platform for ML
- Write fast deep learning code in Python/Ohter accessible languages (able to run on a GPU/TPU)
- Able to access many pre-buit deep learning models (TensorFlow Hub)
- Whole stack
-- preprocess data
-- model data
-- deploy model in (your) application


Tensor Processing Unit (TPU) is an AI accelerator application-specific integrated circuit (ASIC) developed by Google specifically for neural network machine learning, particularly using Google's own TensorFlow software
https://en.wikipedia.org/wiki/Tensor_Processing_Unit


What is tensor ?
https://www.youtube.com/watch?v=tpCFfeUEGs8&t=22995s
43:05 - [Keynote] 6. What is a tensor?
https://www.youtube.com/watch?v=f5liqUk0ZTw

not quite understadning :( 

```
write code
- if in doubt, run the code
Explore & Experiment
- Experiment,  Experiment, Experiment
- Visualise, Visualise, Visualise
Ask Questions even Dumb question.
Do the excerise
Share my work! : learning from explaination. 
```

https://colab.research.google.com

- enrol course

https://www.coursera.org/professional-certificates/tensorflow-in-practice#about

Enrol date : 08/Jun/2021

basic information for Colab : TODO read it 
https://research.google.com/colaboratory/faq.html


Google playground
http://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.64931&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false




------
TODO : read later
https://ai.google/responsibilities/responsible-ai-practices/

how dense is working in hidden network
https://www.youtube.com/watch?v=fXOsFF95ifk


totall local env set 
jupther install, -> tensorflow -> python 3

matplotlib 로 프린팅 하는법
```import numpy as np
np.set_printoptions(linewidth=200)
import matplotlib.pyplot as plt
plt.imshow(training_images[0])
print(training_labels[0])
print(training_images[0])
```





Computer Vision
- flatten will be tricky!
- 

```
model = tf.keras.Sequential([
          keras.layers.Dense(units=1, input_shape=[1])
])

model = tf.keras.models.Sequential([
          tf.keras.layers.Flatten(),
          tf.keras.layers.Dense(512, activation=tf.nn.relu),
          tf.keras.layers.Dense(10, activation=tf.nn.softmax)
])
```


Convolutional Neural Network

pooling -> compression.
image - > filter -> polling (lartest from filter) 
https://www.youtube.com/playlist?list=PLkDaE6sCZn6Gl29AoE31iwdVwSG-KnDzF

https://www.tensorflow.org/api_docs/python/tf/keras/layers/Conv2D

https://www.tensorflow.org/api_docs/python/tf/keras/layers/MaxPool2D

https://en.wikipedia.org/wiki/Kernel_(image_processing)

iLode's Computer Graphics Tutorial
https://lodev.org/cgtutor/filtering.html
