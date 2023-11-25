# Vehicle Trajectory Prediction using Generative Adversarial Networks (GANs)
## Overview
This project proposes a novel approach to vehicle trajectory prediction using Generative Adversarial Networks (GANs). The model leverages the partial history of vehicles and learns the intricate behaviors exhibited by vehicles in diverse scenarios. By feeding the model with sequences of vehicle positions obtained from a traffic scene, it generates probabilistic predictions for future vehicle positions. The predictions are based on factors such as vehicle velocities, prioritization, and both social and physical considerations.

## Key Features
* The project uses Generative Adversarial Networks to capture and replicate the complex behaviors of vehicles in traffic scenes.
* Partial History Utilization is used to enhance the model's ability to predict trajectories, considering factors such as:
- Vehicle size
- Driver behavior
- Obstacle avoidance
- Inter-vehicle distance.
* The model provides probabilistic predictions for future vehicle positions, offering a nuanced understanding of potential scenarios in traffic.
* The model is designed to learn various vehicle behaviors, such as overcoming obstacles, merging, etc., making it adaptable to diverse traffic scenarios.

## Evaluation Metrics
The performance of the model is assessed using the following metrics:
- Average Displacement Error: Quantifies the average error between predicted and actual vehicle positions over the evaluation dataset.
- Final Displacement Error: Measures the error in predicting the final positions of vehicles, providing insights into the model's accuracy in capturing long-term trajectories.

## Dataset
The project utilizes aerial views of traffic data, including the VisDrone dataset and the TRAF dataset, to train and evaluate the trajectory prediction model.
