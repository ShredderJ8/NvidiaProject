## Hand Number Project

This project uses a USB camera to detect a number on a single hand (1, 2, 3, 4, 5) and then outputs said number. It also can detect a plus or minus sign. 

## The Algorithm

Using the widgets from the output screen, the user can create their own dataset with the numbers and operations (1, 2, 3, 4, 5, +, -). Then, they can train or evaluate the model using the corresponding buttons and allocate however many epochs they want. While either training or evaluation is running, it will show the progress, loss, and accuracy. After the training is finished, the user can save the model with a custom name or even load another model. The project utilizes the Resnet-18 Convolutional Neural Network (CNN) to take an image that from the live camera feed and predict what the user is holding up. The prediction is shown through the vertical sliders and prediction text box. 

## Running the Project

1. Download HandNumberProject.ipynb, dataset.py, and utils.py
2. Setup Nvidia Jetson Nano
3. Plug in a USB camera
4. After setting up the DLI Docker, run ./docker_dli_run.sh in the terminal and copy the link in your browser to acess the Jupyter Notebook
5. Upload all the files
6. Slowly run through each cell by pressing the run button or shift+enter
7. The second to last cell runs the output
8. Don't run the last cell until you're finished
9. Add photos of your hand for each of the categories
10. Train the model
11. Save the model
12. Repeat steps 9-11 until you're happy with the accuracy of the predictions


[VIDEO](https://youtu.be/CaiOU4Dijkg)
