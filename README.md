# tinyml-on-the-edge
Arduino nano 33 ble sense can be used to recognize gesture using machine learning. A tensorflow model is designed, built and trained using inertia sensors data on google colaboratory. Later the model is converted to tensorflow-lite model nano hardware can use as header file. The sensors include accelerometer sensor, gyroscope and magnetometer. In this work we are going to use accelerometer and gyroscope data to predict Sitting and standing body gesture. This is based on [arduino tutorials](https://github.com/arduino/ArduinoTensorFlowLiteTutorials).

This mini project will conform to the following procedure.
1. Revisit [setting up arduino IDE](https://github.com/billiyz/nano-33-ble-sense) without going through the programming part on sensor data collection.
2. Look into accelerometer and gyroscope (inertia sensors)
3. Write a sketch to collect accelerometer and gyroscope sensors data
4. Upload the data to the google colaboratory platform.
5. Train a neural
6. Convert the model into tensorflow lite model
7. Encode the model in arduino header file.


