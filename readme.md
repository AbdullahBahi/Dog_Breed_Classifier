# Dog Breed Classifier

This Project is the first project of Udacity's [AI Programming with Python Nanodegree program](https://www.udacity.com/course/ai-programming-python-nanodegree--nd089).

## Project Goal
In this project I used a pre-built image classifier to identify dog breeds focusing on Python programming and structuring the program, not on the actual classifier.

## Example Application:

Your city is hosting a citywide dog show and you have volunteered to help the organizing committee with contestant registration. Every participant that registers must submit an image of their dog along with biographical information about their dog. The registration system tags the images based upon the biographical information.  
Some people are planning on registering pets that aren’t actual dogs. You need to use an already developed Python classifier to make sure the participants are dogs.

## Program Outline:

- **Timing the program**
  - Use Time Module to compute program runtime
  
- **Get program Inputs from the user**
  - Use command line arguments to get user inputs

- **Create Pet Images Labels**
  - Use the pet images filenames to create labels
  - Store the pet image labels in a data structure (e.g. dictionary)

- **Create Classifier Labels and Compare Labels**
  - Use the Classifier function to classify the images and create the classifier labels
  - Compare Classifier Labels to Pet Image Labels
  - Store Pet Labels, Classifier Labels, and their comparison in a complex data structure (e.g. dictionary of lists)

- **Classifying Labels as "Dogs" or "Not Dogs"**
  - Classify all Labels as "Dogs" or "Not Dogs" using dognames.txt file
  - Store new classifications in the complex data structure (e.g. dictionary of lists)

- **Calculate the Results**
  - Use Labels and their classifications to determine how well the algorithm worked on classifying images

- **Print the Results**
  - repeat these tasks for each of the three available image classification algorithms (ResNet, AlexNet, or VGG).
  
## Principal Objectives:

1. Correctly identify which pet images are of dogs (even if breed is misclassified) and which pet images aren't of dogs.
 
2. Correctly classify the breed of dog, for the images that are of dogs.
 
3. Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve the objectives 1 and 2.
 
4. Consider the time resources required to best achieve objectives 1 and 2, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms take to run.
