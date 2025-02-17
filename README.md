# Project Title
1.	Tensor Manipulations & Reshaping
2.  Loss Functions & Hyperparameter Tuning
3.	Train a Model with Different Optimizers
4.	Train a Neural Network and Log to TensorBoard
## Description

1.Tensor manipulations involve modifying tensors through operations like slicing, concatenation, or transposing. Reshaping changes the structure of a tensor (e.g., converting a 2D matrix to a 1D vector) without altering its data. These operations are essential for preparing data for machine learning tasks.

2.Loss functions measure how well a model's predictions match the actual data, guiding the training process. Hyperparameter tuning involves optimizing settings like learning rate or batch size to improve model performance. Both are critical for building effective machine learning models.

3.This task involves training an MNIST model using two optimizers: Adam and SGD. Adam adapts learning rates for faster convergence, while SGD uses a fixed learning rate. Comparing their performance helps understand optimizer impact on model training.

4.This task involves training a neural network while logging metrics like loss and accuracy to TensorBoard. TensorBoard provides visualizations to monitor and analyze training progress, making it easier to debug and improve the model.

## Student Info
- **Name**: Jyostna Marella
- **Student ID**: 700761880

## Screenshots
Had uploaded through repository

4.1 :

1. Both Accuracies Increase
What we observe: Training and validation accuracy go up together.
What it means: Model is learning well and generalizing to new data.

2. Training Accuracy Goes Up, Validation Stops
What we observe: Training accuracy keeps improving, but validation accuracy stalls or drops.
What it means: Model is overfitting (memorizing training data but not generalizing).

3. Both Accuracies Are Low
What we observe: Training and validation accuracy stay low.
What it means: Model is underfitting (not learning enough).

4. Big Gap Between Training and Validation
What we observe: Training accuracy is much higher than validation accuracy.
What it means: Model is overfitting.

5. Validation Accuracy Jumps Around
What we observe: Validation accuracy fluctuates a lot.
What it means: Validation dataset might be too small, or learning rate is too high.

6. Both Accuracies Are Similar but Low
What we observe: Training and validation accuracy are close but not high enough.
What it means: Model has reached its limits and needs improvement.

What to Do?
If overfitting: Add dropout, use more data, or simplify the model.
If underfitting: Make the model more complex or train longer.
If validation fluctuates: Use more validation data or lower the learning rate.

4.2 :

1.Check Loss Curves
If training loss keeps going down but validation loss starts going up, it’s overfitting.

2.Check Accuracy Curves
If training accuracy keeps going up but validation accuracy stops improving or drops, it’s overfitting.

3.Look for a Growing Gap
A big and growing gap between training and validation metrics (loss or accuracy) means overfitting.

4.Use TensorBoard Tabs
Scalars Tab: Compare train_loss vs. val_loss and train_accuracy vs. val_accuracy.
Histograms Tab: Check if weight distributions change too much (optional).

How to Fix Overfitting
Add dropout or regularization.
Use data augmentation.
Make the model simpler.
Stop training early if validation loss stops improving.

4.3
When you increase the number of epochs:

Model Learns More: The model gets more time to learn patterns in the training data.
Risk of Overfitting: If trained too long, the model may memorize the training data and perform poorly on new data.
Training Time Increases: More epochs mean longer training time.
Accuracy May Improve: Training accuracy usually increases, but validation accuracy may stop improving or drop if overfitting occurs.

More epochs can help learning but may cause overfitting if not controlled.
## License
This project is licensed under the [License Name] - see the [LICENSE](LICENSE) file for details.
