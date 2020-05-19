# basic-nn-visualizer
A visualizer that uses MNIST dataset and 2 hidden layers to predict the output. It takes a random input and shows the values of all the hidden layers before predicting the output and showing the probabilities of each output.

MNIST dataset: http://yann.lecun.com/exdb/mnist/

## Tech Stack

This visualizer is based on flask and streamlit. The model was trained using tensorflow's keras API on Jupyter Notebook.

## Steps to run locally

1. Clone the repository using `git clone https://github.com/Pallavbh23/basic-nn-visualizer.git`.

2. Run the flask server using `python ml_server.py`. You might need to use `python3` instead of `python` depending on your environment. The server should be live on localhost:5000

3. Run the streamlit script using `streamlit run app.py`. 

4. Go to the localhost address for the streamlit app shown on your command shell.


## How to use

You can click on the `Get random prediction` button to start the process. The script will choose a random image and predict its output. You'll be able to see the values for every hidden unit and the output units. The hidden layers have 32 units and the output layer has 10 units. You can expand the sidebar on the left to see the actual input that was sent to the Neural Network!

## Use cases

1. Being a visual representation, it can help learners or data scientists to easily see how a model behaves. 
2. It can be used to track biases in the neural network units and can thus be used to fixed them. 
3. Most importantly, it can be changed to provide your own image and hosted on a website for prediction purposes while also helping in easily validating how the neural network performs.
