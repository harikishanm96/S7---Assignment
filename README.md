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

## Model 3:

Targets:

1. Add Rotation around 5 - 7 degrees
2. Add LR Scheduler
   
Results:

1. Parameters: 7.5k
2. Best Train Accuracy: 99.51
3. Best Test Accuracy: 99.45
   
Analysis: Test accuracy is above 99.4% after use of image rotation and LR scheduler.
