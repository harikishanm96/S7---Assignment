# S7---Assignment

## Model1:

Targets:

1. Get the set-up right
2. Set Transforms, Data Loader, Training & Test Loop
3. Add Batch-norm to increase model efficiency

Results:
1. Parameters: 9k,
2. Best Train Accuracy: 99.71,
3. Best Test Accuracy: 99.14 (14th Epoch)

Analysis: Model is over-fitting after batch normalization

## Model 2:

Targets:

1. Add Regularization, Dropout
2. Add GAP

Results:

1. Parameters: 7.5k
2. Best Train Accuracy: 99.36 (14th Epoch)
3. Best Test Accuracy: 99.33 (9th Epoch)

Analysis: Model is not overfitting, model can be improved further to get 99.4% or more using image augmentation techniques.

## Model 3 (Final):

Targets:

1. Add Rotation around 5 - 7 degrees
2. Add LR Scheduler
   
Results:

1. Parameters: 7.5k
2. Best Train Accuracy: 99.51
3. Best Test Accuracy: 99.45
   
Analysis: Test accuracy is above 99.4% after use of image rotation and LR scheduler.

## Logs:

Epoch 1
Train: Loss=0.1658 Batch_id=468 Accuracy=83.19: 100%|██████████| 469/469 [00:25<00:00, 18.28it/s]
Test set: Average loss: 0.1259, Accuracy: 9709/10000 (97.09%)

Epoch 2
Train: Loss=0.1218 Batch_id=468 Accuracy=97.48: 100%|██████████| 469/469 [00:21<00:00, 22.13it/s]
Test set: Average loss: 0.0613, Accuracy: 9829/10000 (98.29%)

Epoch 3
Train: Loss=0.0136 Batch_id=468 Accuracy=98.09: 100%|██████████| 469/469 [00:21<00:00, 21.50it/s]
Test set: Average loss: 0.0420, Accuracy: 9874/10000 (98.74%)

Epoch 4
Train: Loss=0.0729 Batch_id=468 Accuracy=98.52: 100%|██████████| 469/469 [00:22<00:00, 20.59it/s]
Test set: Average loss: 0.0402, Accuracy: 9879/10000 (98.79%)

Epoch 5
Train: Loss=0.0258 Batch_id=468 Accuracy=98.66: 100%|██████████| 469/469 [00:22<00:00, 20.67it/s]
Test set: Average loss: 0.0328, Accuracy: 9894/10000 (98.94%)

Epoch 6
Train: Loss=0.0543 Batch_id=468 Accuracy=98.78: 100%|██████████| 469/469 [00:23<00:00, 20.12it/s]
Test set: Average loss: 0.0307, Accuracy: 9899/10000 (98.99%)

Epoch 7
Train: Loss=0.0265 Batch_id=468 Accuracy=98.90: 100%|██████████| 469/469 [00:21<00:00, 21.90it/s]
Test set: Average loss: 0.0267, Accuracy: 9920/10000 (99.20%)

Epoch 8
Train: Loss=0.0679 Batch_id=468 Accuracy=99.01: 100%|██████████| 469/469 [00:22<00:00, 20.68it/s]
Test set: Average loss: 0.0252, Accuracy: 9922/10000 (99.22%)

Epoch 9
Train: Loss=0.0239 Batch_id=468 Accuracy=99.09: 100%|██████████| 469/469 [00:22<00:00, 20.67it/s]
Test set: Average loss: 0.0241, Accuracy: 9920/10000 (99.20%)

Epoch 10
Train: Loss=0.0190 Batch_id=468 Accuracy=99.17: 100%|██████████| 469/469 [00:22<00:00, 21.05it/s]
Test set: Average loss: 0.0219, Accuracy: 9933/10000 (99.33%)

Epoch 11
Train: Loss=0.0154 Batch_id=468 Accuracy=99.23: 100%|██████████| 469/469 [00:21<00:00, 22.04it/s]
Test set: Average loss: 0.0203, Accuracy: 9938/10000 (99.38%)

Epoch 12
Train: Loss=0.0095 Batch_id=468 Accuracy=99.33: 100%|██████████| 469/469 [00:22<00:00, 20.81it/s]
Test set: Average loss: 0.0183, Accuracy: 9939/10000 (99.39%)

Epoch 13
Train: Loss=0.0195 Batch_id=468 Accuracy=99.43: 100%|██████████| 469/469 [00:22<00:00, 20.53it/s]
Test set: Average loss: 0.0181, Accuracy: 9939/10000 (99.39%)

Epoch 14
Train: Loss=0.0147 Batch_id=468 Accuracy=99.50: 100%|██████████| 469/469 [00:23<00:00, 20.04it/s]
Test set: Average loss: 0.0174, Accuracy: 9943/10000 (99.43%)

Epoch 15
Train: Loss=0.0026 Batch_id=468 Accuracy=99.51: 100%|██████████| 469/469 [00:21<00:00, 21.69it/s]
Test set: Average loss: 0.0170, Accuracy: 9945/10000 (99.45%)
