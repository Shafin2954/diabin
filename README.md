# Diabin

An app to manage your glucose levesl and insuli intake. I am using an AI model to predict the glucose level of the user at any time with live data of the user's food intake, insulin intake. The AI model gets adapted to the user's biological data each time the user input's their glucose level in the app.

## App

The app is developed using flutter and dart. Features includes:

- Log food intake with image recognition
- Log insulin intake
- Log glucose level
- View glucose level prediction graph
- View food intake history

## Database

The database used is Firebase Firestore.

## AI Model

The architecture used is LSTM and CNN. The model is developed using pytorch. Features includes:

- Predict glucose level at any time of the day
- Adapt to user's biological data
- Detect food items from image and log it in the app

## Future Plans

Introduce IR sensor to measure glucose level without pricking the finger and directly log it in the app.

PS: The app is still in development phase. The AI model is still in research phase. Any suggestions and contributions are welcome. :D