# Maati-
## AI BASED CROP RECOMMENDATION SYSTEM

### Developers- 
Rashi Srivastava, IIIrd Semester - rashisrivastava@ieee.org

Ankit Jailwal, IVth Semester - jailwalankit@gmail.com

Shivam Sawarn, IVth Semester - shivamsawarn@ieee.org

Vivek Kumar, IIIrd Semester - vivekkaushik480@gmail.com


#### Problem Statement - 
Selecting Crops for farmers is a hectic job as they have to consider many different factors. Hence, developing an app which will help farmers in making their jobs easy.

#### Aim - 
The aim is to design an AI based crop recommendation application which can recommend different crops to the farmers by analysing all the relevant factors for a particular land area such as rainfall, temperature, season, ground water available, soil type and location. The application is based on Deep Learning and Machine Learning algorithms to detect the soil type given an image and recommend the best fit crop along with further suggestions for that very crop such as expected revenue generated per hectare, demand of the crop, required fertilizers, cost of cultivation per hectare, quantity of seeds per hectare, duration of cultivation and the crops which can be used for mixed cropping with the primary crop. Along with this
    
#### Working of Maati App - 
- The app starts after an easy user login using mobile number but for the prototype the mobile number feature hasn't been implemented completely and the app is currently working on a dummy user name and phone number. 

- After login the user is taken to the main menu page where, the user can navigate through different features of MAATI APP.

- For Crop prediction, the user is required to click the image of the land on which the farming has to be done and send it to the server for processing and to predict soil type using Deep learning model.

- The predicted soil type will be used as a parameter for crop recommendation.

- User's current location and weather conditions will also be sent to the server for crop prediction and altogether all the parameters will be used to predict the crop which is suitable for cultivation.

- After crop prediction the relevant details related to the crops will be fetched and shown as the output to the users.
- Users can also access other features of the app such as: Kisan Call Centre, Maati News for agriculture news and happenings, Maati analysis for weather updates, History of previous recommendations etc. 

This app also includes a portal for farmers where they can buy the products needed while the cultivation period,right from seeds to machies/tools, sell their produce directly in the market and also register their land, machine for rent. It aims to cover all the needs of a farmer.

Added to this, an additional feature to predict vcrop type and crop disease is also added in the app.

#### All the Python Scripts for ML and DL models can be found here: https://github.com/Rashi-Srivastava/A10-5-BIT/tree/main/Python_Scripts

- CRS.py contains the Machine Learning Model for Crop Recommendation

- SoilNET.py conatins the deep learning neural network architecture for Soil type recognition.

## Videos for working part of the model can be found here: https://github.com/Rashi-Srivastava/A10-5-BIT/tree/main/Videos

## PPt shared can be found here: https://github.com/Rashi-Srivastava/A10-5-BIT/blob/main/Videos/Maati.pptx


