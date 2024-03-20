# MoodSync
Personal AI Assistant Sentimental Analysis
Our project basically analyses emotions such as happiness, sadness, anger, surprise and recommends you actions accordingly. 
Steps performed in the code:-
1. Importing necessary packages such as tensorflow, pandas, numpy, keras, matplotlib
2. Importing dataset into the folder
3. Loading facial key points data
4. Obtaining relavant information about the dataframe
5. Checking if null values exist in the dataframe
6. Converting this into numpy array using np.fromstring and convert the obtained 1D array into 2D array of shape (96, 96)
7. Obtaining the Shape of the image
8. Plotting a random image from the dataset along with facial keypoints.
9. We access their value using .loc command, which get the values for coordinates of the image based on the column it is refering to.
   

