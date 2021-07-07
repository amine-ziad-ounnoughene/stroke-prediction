# stroke-prediction-neural-net
a fully connected adaline neural net which try to predict the probability of having a stoke in the future
using the BCE loss function and adam optimizer and train on 5 epochs
# model architecture
```bash
Model: "sequential_1"
_________________________________________________________________
Layer (type)                 Output Shape              Param   
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
```
# accuracy
- trainning accuracy 94.67 %
- validation accuracy 99.99 %
- testing accuracy 99.99 % 
##  learning curves 
# model accuracy
![App Screenshot](https://github.com/amine-ziad-ounnoughene/stroke-prediction-neural-net/blob/c4e73973605191cdd47e1f51bec6e1f1a05b1e9b/model-accuracy.jpg)
# model loss
![App Screenshot](https://github.com/amine-ziad-ounnoughene/stroke-prediction-neural-net/blob/6321d3a922a02edf8e7a47ee0fd2443cde4b7bee/model-loss.jpg)
