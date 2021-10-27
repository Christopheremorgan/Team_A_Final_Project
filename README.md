# Emoji the Possibilies
A facial expression recognition CNN model with emoji labeling.

# Team Sweet Emojis
- Chris Morgan
- Gregory Morales
- Naomi Shields
- Regina Negrycz


# Application Technology Diagram
![image_name](https://github.com/genlgist/Team_A_Final_Project/blob/ChrisAdd/TeamProjectTechDiagram.001.jpeg)


# Dashboard

FINAL DELIVERABLE - v1.0: User uploads a black and white head shot to the dashboard which sets off an event for the image to be processed by a convolutional neural network model that classifies the expression on the headshot. The identified classification will be presented to the user along with the model's confidence level of the prediction.

Bootstrap, HTML, and Javascript will be used to build the front end user interface (dashboard) with the ability to upload (with event listener) a black and white image for the classification model. Leverage Flask as the integration layer between the python model and the Javascript front end. Team is considering the option to include top 3 possible expression classifications sorted by model confidence level.


## Description of the data source

Dataset FER-2013 is a Kaggle dataset consisting of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image.

The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28,709 examples and the public test set consists of 3,589 examples.


# Future Development

v1.1 Add the ability to confirm or correctly classify the expression of the headshot. Once confirmed or correctly classified the image is saved along with model outputs for trends and stats on how well the model is performing. The images may be used for future updates and model refitting to better classify new images.

v1.2 Database of classification results are kept for dashboarding and model health.

v2.1 Zoom 'self-awareness' plug-in that captures camera feed at a set frequency to provide a trend of expressions being telegraphed to other Zoom participants during the course of a meeting. Dashboard includes a timeline trend.

v3.1 Zoom plug-in to provide people with autism a support tool that monitors the expressions of others on the Zoom call. Would include an expanded set of expressions that may be particularly helpful for people with autism.






