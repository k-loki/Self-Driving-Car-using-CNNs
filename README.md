# Self-Driving-Car-using-CNNs

Here we learn a car to drive itself on the lane using convolutional nerual networks.

- The model needs to drive the steering to make the car stay on lane (even without lane markings) 
- The input to the cnn will be images of the road ahead in 3 view points.
- The model learns appropriate weights to minimize the loss.
- The loss function we used here is mean squared error (mse)
- The outcome of the neural network is the steering angle to be rotated.
- The mse loss shows the model how far the steering angle is from the actual angle in training phase.
- After the model is trained, its tested on the simulated road.
- The training data and testing track all are from udacity's car driving simulator.

The Drive.py file helps you connect with the udacity simulator.
Open the udacity simulator and select autonomoud mode to see the car drive itself on the track.

NOTE: 

Make sure you have the socketio version --> 0.2.1 and eventlet vesrsion --> 0.33.0 to run driver code without any issues.
