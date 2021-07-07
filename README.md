# stroke-prediction-neural-net
a fully connected adaline neural net which try to predict the probability of having a stoke in the future
using the BCE loss function and adam optimizer and train on 5 epochs
# model architecture
Model: "sequential_1"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
flatten_1 (Flatten)          (None, 10)                0         
_________________________________________________________________
dense_3 (Dense)              (None, 128)               1408      
_________________________________________________________________
dense_4 (Dense)              (None, 128)               16512     
_________________________________________________________________
dense_5 (Dense)              (None, 1)                 129       
=================================================================
Total params: 18,049
Trainable params: 18,049
Non-trainable params: 0
_________________________________________________________________
# accuracy
- trainning accuracy 94.67 %
- validation accuracy 99.99 %
- testing accuracy 99.99 % 
# learning curves 
