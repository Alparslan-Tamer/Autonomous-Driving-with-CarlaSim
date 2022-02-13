# Autonomous-Driving-with-Udacity-Simulation
 Low-cost deep learning-based project capable of autonomous driving in Udacity Simulation

## How do you run this repo

* Firstly, run the notebook (you need to collect data first!) and train the model.
* Secondly, If you want, you can tune the functions and model on the notebook for a better driving. Also, It is okay for you to execute the notebook directly because it can drive the car in its current state.
* After training, now you have good and powerful a model. You can execute `drive.py` and after that just your need is open Udacity Similator in Autonomous Mode.
* You can also tune the `drive.py` code. But note that the preprocesses must be the same in both `notebook` and `drive.py`!

## Collecting Data

* You can collect data in Udacity Simulator. 3 laps in either direction is sufficient, but more makes for a much better driving.

## Importan note!

* You need to use `python-socketio==4.6.1` and `python-engineio==3.13.2` for communication between drive.py and simulation.

