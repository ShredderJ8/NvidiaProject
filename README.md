# Hand Calculator Project

This project uses a USB camera to detect a number on a single hand (1, 2, 3, 4, 5) and then outputs said number. It also can detect a plus or minus sign. 

## The Algorithm

Using the widgets from the output screen, the user can create their own dataset with the numbers and operations (1, 2, 3, 4, 5, +, -). Then, they can train or evaluate the model using the corresponding buttons and allocate however many epochs they want. While either training or evaluation is running, it will show the progress, loss, and accuracy. After the training is finished, the user can save the model with a custom name or even load another model. The project utilizes the Resnet-18 Convolutional Neural Network (CNN) to take an image that from the live camera feed and predict what the user is holding up. The prediction is shown through the vertical sliders and prediction text box. 

## Running the Project

