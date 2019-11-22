# Assignemnt-2-TSAI

# Stratergy taken to achieve the result
* Reduced the size of filters so that total number of parameters comes within 15k
* Removed drop out from the last layer
* Added a max pool layer in between
* added use_bias = False argument to remove all biases

# Result of model.evaluate()

[0.020409335430525245, 0.9951]
# Logs for 20 epochs
Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 19s 308us/step - loss: 0.3401 - acc: 0.9474 - val_loss: 0.0955 - val_acc: 0.9873
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 10s 167us/step - loss: 0.0994 - acc: 0.9840 - val_loss: 0.0587 - val_acc: 0.9912
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 10s 166us/step - loss: 0.0683 - acc: 0.9875 - val_loss: 0.0513 - val_acc: 0.9903
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 10s 168us/step - loss: 0.0543 - acc: 0.9889 - val_loss: 0.0417 - val_acc: 0.9922
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 10s 165us/step - loss: 0.0466 - acc: 0.9901 - val_loss: 0.0371 - val_acc: 0.9935
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 10s 165us/step - loss: 0.0394 - acc: 0.9917 - val_loss: 0.0341 - val_acc: 0.9922
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 10s 165us/step - loss: 0.0369 - acc: 0.9917 - val_loss: 0.0282 - val_acc: 0.9948
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 10s 164us/step - loss: 0.0324 - acc: 0.9925 - val_loss: 0.0267 - val_acc: 0.9940
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 10s 165us/step - loss: 0.0308 - acc: 0.9927 - val_loss: 0.0279 - val_acc: 0.9926
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 10s 166us/step - loss: 0.0291 - acc: 0.9931 - val_loss: 0.0269 - val_acc: 0.9939
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 10s 165us/step - loss: 0.0268 - acc: 0.9933 - val_loss: 0.0252 - val_acc: 0.9937
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 10s 164us/step - loss: 0.0248 - acc: 0.9941 - val_loss: 0.0237 - val_acc: 0.9938
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 10s 165us/step - loss: 0.0230 - acc: 0.9941 - val_loss: 0.0243 - val_acc: 0.9942
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 10s 166us/step - loss: 0.0231 - acc: 0.9942 - val_loss: 0.0229 - val_acc: 0.9943
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 10s 165us/step - loss: 0.0222 - acc: 0.9945 - val_loss: 0.0209 - val_acc: 0.9945
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 10s 165us/step - loss: 0.0208 - acc: 0.9951 - val_loss: 0.0229 - val_acc: 0.9937
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 10s 163us/step - loss: 0.0200 - acc: 0.9947 - val_loss: 0.0211 - val_acc: 0.9949
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 10s 163us/step - loss: 0.0193 - acc: 0.9952 - val_loss: 0.0216 - val_acc: 0.9949
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 10s 163us/step - loss: 0.0182 - acc: 0.9953 - val_loss: 0.0223 - val_acc: 0.9942
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 10s 163us/step - loss: 0.0186 - acc: 0.9954 - val_loss: 0.0204 - val_acc: 0.9951
<keras.callbacks.History at 0x7f6cfdb5add8>
