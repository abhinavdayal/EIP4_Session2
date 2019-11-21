# EIP4_Session2

## Logs for 20 epochs

```
Model: "sequential_37"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_266 (Conv2D)          (None, 26, 26, 10)        90        
_________________________________________________________________
batch_normalization_214 (Bat (None, 26, 26, 10)        40        
_________________________________________________________________
dropout_214 (Dropout)        (None, 26, 26, 10)        0         
_________________________________________________________________
conv2d_267 (Conv2D)          (None, 24, 24, 16)        1440      
_________________________________________________________________
batch_normalization_215 (Bat (None, 24, 24, 16)        64        
_________________________________________________________________
dropout_215 (Dropout)        (None, 24, 24, 16)        0         
_________________________________________________________________
max_pooling2d_42 (MaxPooling (None, 12, 12, 16)        0         
_________________________________________________________________
conv2d_268 (Conv2D)          (None, 12, 12, 10)        160       
_________________________________________________________________
batch_normalization_216 (Bat (None, 12, 12, 10)        40        
_________________________________________________________________
dropout_216 (Dropout)        (None, 12, 12, 10)        0         
_________________________________________________________________
conv2d_269 (Conv2D)          (None, 10, 10, 16)        1440      
_________________________________________________________________
batch_normalization_217 (Bat (None, 10, 10, 16)        64        
_________________________________________________________________
dropout_217 (Dropout)        (None, 10, 10, 16)        0         
_________________________________________________________________
conv2d_270 (Conv2D)          (None, 8, 8, 16)          2304      
_________________________________________________________________
batch_normalization_218 (Bat (None, 8, 8, 16)          64        
_________________________________________________________________
dropout_218 (Dropout)        (None, 8, 8, 16)          0         
_________________________________________________________________
conv2d_271 (Conv2D)          (None, 6, 6, 16)          2304      
_________________________________________________________________
batch_normalization_219 (Bat (None, 6, 6, 16)          64        
_________________________________________________________________
dropout_219 (Dropout)        (None, 6, 6, 16)          0         
_________________________________________________________________
conv2d_272 (Conv2D)          (None, 6, 6, 10)          160       
_________________________________________________________________
batch_normalization_220 (Bat (None, 6, 6, 10)          40        
_________________________________________________________________
dropout_220 (Dropout)        (None, 6, 6, 10)          0         
_________________________________________________________________
conv2d_273 (Conv2D)          (None, 1, 1, 10)          3600      
_________________________________________________________________
flatten_34 (Flatten)         (None, 10)                0         
_________________________________________________________________
activation_34 (Activation)   (None, 10)                0         
=================================================================
Total params: 11,874
Trainable params: 11,686
Non-trainable params: 188
```


```
Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 31s 508us/step - loss: 0.2235 - acc: 0.9301 - val_loss: 0.0587 - val_acc: 0.9810
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 8s 128us/step - loss: 0.0685 - acc: 0.9785 - val_loss: 0.0408 - val_acc: 0.9867
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 8s 127us/step - loss: 0.0549 - acc: 0.9827 - val_loss: 0.0333 - val_acc: 0.9892
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 8s 129us/step - loss: 0.0455 - acc: 0.9862 - val_loss: 0.0285 - val_acc: 0.9901
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 8s 129us/step - loss: 0.0415 - acc: 0.9872 - val_loss: 0.0289 - val_acc: 0.9913
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 8s 128us/step - loss: 0.0388 - acc: 0.9879 - val_loss: 0.0294 - val_acc: 0.9902
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 8s 128us/step - loss: 0.0347 - acc: 0.9890 - val_loss: 0.0236 - val_acc: 0.9925
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 8s 128us/step - loss: 0.0318 - acc: 0.9896 - val_loss: 0.0220 - val_acc: 0.9926
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 8s 128us/step - loss: 0.0310 - acc: 0.9903 - val_loss: 0.0234 - val_acc: 0.9924
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 8s 127us/step - loss: 0.0283 - acc: 0.9910 - val_loss: 0.0215 - val_acc: 0.9927
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 8s 128us/step - loss: 0.0283 - acc: 0.9915 - val_loss: 0.0228 - val_acc: 0.9932
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 8s 135us/step - loss: 0.0267 - acc: 0.9912 - val_loss: 0.0194 - val_acc: 0.9937
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 8s 129us/step - loss: 0.0263 - acc: 0.9912 - val_loss: 0.0201 - val_acc: 0.9932
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 8s 129us/step - loss: 0.0267 - acc: 0.9913 - val_loss: 0.0205 - val_acc: 0.9931
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 8s 129us/step - loss: 0.0246 - acc: 0.9919 - val_loss: 0.0199 - val_acc: 0.9932
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 8s 128us/step - loss: 0.0238 - acc: 0.9920 - val_loss: 0.0196 - val_acc: 0.9936
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 8s 127us/step - loss: 0.0224 - acc: 0.9927 - val_loss: 0.0198 - val_acc: 0.9942
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 8s 128us/step - loss: 0.0223 - acc: 0.9928 - val_loss: 0.0202 - val_acc: 0.9939
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 8s 128us/step - loss: 0.0216 - acc: 0.9928 - val_loss: 0.0193 - val_acc: 0.9939
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 8s 130us/step - loss: 0.0208 - acc: 0.9932 - val_loss: 0.0205 - val_acc: 0.9941
```

## result of model.evaluate
```
[0.020474573148114725, 0.9941]
```

## Strategy

I applied several things that I learnt:

1. Before first Max Pooling, I chose receptive field of 5x5, because for 28x28 image that is sufficient.
2. I used less number of channels because the MNIST images are very simple and have only 10 classes to predict. So did not go beyond 16.
3. I fixed final resolution to around 4x4 or more, because I must have at least as many pixels as classes. There were two ways, another max pooling, or multiple convolution layers. I tried both but got better accuracy with multipe conv layers with final resolution of 6x6. 
5. I tried with more layers also and goot 99.95+ accuracy initally and then I tried to go even lower in number of parameters.
6. Finally, As needed, I disabled bias in all conv layers using use_bias=False parameter.

I did experiment with several dropout rates, but actually not very clear on whether dropout should be applied on every layer or sometimes. The difference between train and validation accuracy seems to lower with epocs telling that things are improving. The train accuracy is consistently improving with every epocs, seems that we are on right track. And the validation accuracy is doing some zig zag but with an upward trend but since its difference from validation accuracy is reducing its a good sign.

The topic of overfitting is tricky as usually we call it to overfit when model is doing really well on training data but not so well on validation.

I did not experiment removing normalization and dropouts. It was encouraging that with so little parameters we did achieve good learning accuracy. I even tried with less than 7000 parameters and in 20 epocs got arounf 99.93+ which is encouraging as well. It finally depends upon the computation power we have. For simple mnist, we do not need so many parameters as I used in Assignment 1. 

It will be nice if we get some insights on what is loss and accuracy (bith training and validation) and how it is measured? I hope we will go through in depth of back propagation.
