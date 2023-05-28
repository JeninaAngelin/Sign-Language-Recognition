# Sign-Language-Recognition
ProjectDescriptionAmerican Sign Language (ASL) is the primary language used by many deaf individuals in NorthAmerica, and it is also used by hard-of-hearing and hearing individuals. The language is as rich asspoken languages and employs signs made with the hand, along with facial gestures and bodilypostures.In this project, you will train a convolutional neural network to classify images of ASL letters. Afterloading, examining, and preprocessing the data, you will train the network and test its performance.ProjectTasks
1. American Sign Language (ASL)
2. Visualize the training data
3. Examine the dataset
4. One-hot encode the data
5. Define the model
6. Compile the model
7. Train the model
8. Test the model
9. Visualize mistakes
# ProjectDescription
## Task1:
First, load the dataset using a special helper file (sign_language.py).Run the code cell as-is, without modification.
## Task2:
Use matplotlib to visualize some of the images in the training dataset.Assign labels to a Python list with three items: 'A', 'B', and 'C', corresponding to thesigned letters that appear in the images.
## Task3:
Count the number of occurrences of each letter in the train and test datasets.Assign the variable num_B_train to an integer counting the number of times that 1 appearsin y_train.Assign the variable num_C_train to an integer counting the number of times that 2 appearsin y_train.Assign the variable num_B_test to an integer counting the number of times that 1 appearsin y_test.Assign the variable num_C_test to an integer counting the number of times that 2 appearsin y_test.
