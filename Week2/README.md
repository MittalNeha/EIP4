LOGS:
Epoch 00001: LearningRateScheduler setting learning rate to 0.01.
60000/60000 [==============================] - 12s 200us/step - loss: 0.3021 -
acc: 0.9298 - val_loss: 0.0593 - val_acc: 0.9817
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0075815011.
60000/60000 [==============================] - 8s 133us/step - loss: 0.0935 -
acc: 0.9747 - val_loss: 0.0414 - val_acc: 0.9879
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0061050061.
60000/60000 [==============================] - 8s 133us/step - loss: 0.0742 -
acc: 0.9793 - val_loss: 0.0418 - val_acc: 0.9878
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.005109862.
60000/60000 [==============================] - 8s 133us/step - loss: 0.0618 -
acc: 0.9828 - val_loss: 0.0296 - val_acc: 0.9910
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0043936731.
60000/60000 [==============================] - 8s 133us/step - loss: 0.0557 -
acc: 0.9839 - val_loss: 0.0309 - val_acc: 0.9906
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0038535645.
60000/60000 [==============================] - 8s 134us/step - loss: 0.0507 -
acc: 0.9848 - val_loss: 0.0235 - val_acc: 0.9932
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.003431709.
60000/60000 [==============================] - 8s 133us/step - loss: 0.0462 -
acc: 0.9858 - val_loss: 0.0223 - val_acc: 0.9926
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0030931024.
60000/60000 [==============================] - 8s 133us/step - loss: 0.0442 -
acc: 0.9872 - val_loss: 0.0254 - val_acc: 0.9913
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0028153153.
60000/60000 [==============================] - 8s 134us/step - loss: 0.0405 -
acc: 0.9879 - val_loss: 0.0185 - val_acc: 0.9943
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0025833118.
60000/60000 [==============================] - 8s 133us/step - loss: 0.0418 -
acc: 0.9873 - val_loss: 0.0194 - val_acc: 0.9940
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0023866348.
60000/60000 [==============================] - 8s 133us/step - loss: 0.0382 -
acc: 0.9885 - val_loss: 0.0201 - val_acc: 0.9937
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.0022177866.
60000/60000 [==============================] - 8s 134us/step - loss: 0.0358 -
acc: 0.9891 - val_loss: 0.0227 - val_acc: 0.9928
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.002071251.
60000/60000 [==============================] - 8s 132us/step - loss: 0.0353 -
acc: 0.9894 - val_loss: 0.0212 - val_acc: 0.9933
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0019428793.
60000/60000 [==============================] - 8s 132us/step - loss: 0.0335 -
acc: 0.9898 - val_loss: 0.0184 - val_acc: 0.9941
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0018294914.
60000/60000 [==============================] - 8s 133us/step - loss: 0.0335 -
acc: 0.9895 - val_loss: 0.0201 - val_acc: 0.9935
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0017286085.
60000/60000 [==============================] - 8s 132us/step - loss: 0.0321 -
acc: 0.9901 - val_loss: 0.0177 - val_acc: 0.9937
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.00163827.
60000/60000 [==============================] - 8s 134us/step - loss: 0.0315 -
acc: 0.9904 - val_loss: 0.0190 - val_acc: 0.9937
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0015569049.
60000/60000 [==============================] - 8s 134us/step - loss: 0.0302 -
acc: 0.9909 - val_loss: 0.0176 - val_acc: 0.9946
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0014832394.
60000/60000 [==============================] - 8s 133us/step - loss: 0.0294 -
acc: 0.9914 - val_loss: 0.0167 - val_acc: 0.9943
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.00141623.
60000/60000 [==============================] - 8s 133us/step - loss: 0.0279 -
acc: 0.9916 - val_loss: 0.0176 - val_acc: 0.9943
<keras.callbacks.History at 0x7feb21c641d0>

OUTPUT
[0.017622454202570952, 0.9943]

My Strategy:
1. Since we know that for this dataset the Global Receptive Field should be 5
   x 5. I took care of that when designing the Network.
2. With the starting learning rate of 0.003, after about 10 epochs, the
   accuracy wasn't changing much. So I changed that to 0.01 instead and after
   this change the accuracy reached 0.994 at 9th epoch



