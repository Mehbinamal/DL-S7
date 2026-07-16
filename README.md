# DL-S7

# Qn

1. consider a dataset and apply batch gd stochastic and mini bacth(batch size 64) and measure the execution time no parameter updates final loss and based on your observation identify the most suitable optimizer for large scale dataset

2. implement a SIMPLE nn TO classify handwritten digits from mnist dataset
perform the following
a. load and preprpcess dataset
design nn with input layer 1 hidden layer using Re Lu activation fn
output layer ( 10 neurons , SoftMax fn )
train the model separately using SGD with momentum adagrad RMS prop and Adam
keep all the hyperparameter same except the optimiser
compare training accuracy validation accuracy training loss and validation loss
plot acc vs epoch loss vs epoch
identify which optimiser converges fastest and justify your answer as comment in the code
