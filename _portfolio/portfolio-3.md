---
title: "Imitation Learning Methods for Autonomous Driving Systems"
excerpt: "Study on comparison between two Imitation Learning Methods: Behavioral Cloning and DAgger Algorithm on Autonomous Driving Cars<br/><img src='/images/unity_autnomous_car.png'>"
collection: portfolio
---

## Objective
Study on comparison between two Imitation Learning Methods: Behavioral Cloning and DAgger Algorithm on Autonomous Driving Cars. CNN model was trained to predict only the steering angles from both the algorithms. 

## Accomplishments 
* Used two simulators: Pygame based and Unity based. 
* Data Collection: Manually navigated the car for 10 loops in both the simulator, and recorded the steering angle and speed in a csv file. The images of the screen was saved in a separate folder.
* Data preprocessing was conducted on images and the data points as most of the steering angle was zero. It was done separately for the training data from two different simulators. 
* Implemented Behavioral Cloning and DAgger Algorithm on Unity based simulator. 
* Implemented Behavioral Cloning and DAgger Algorithm on Pygame based simulator.


## Results

Both algorithms were able to train models robust enough for a simple self-steering task. However, the DAgger algorithm is able to better respond to scenarios that are not present in the baseline training dataset as it learnt from the additional data generated after every iteration. This introduced many scenarios that was unseen under the perfect training conditions. Since the DAgger algorithm is trained on human and model generated data, it is able to adapt to a broader range of scenarios.
