# Installation
pip3 install -r requirements.txt

# Model Selection
### Movenet
MoveNet is an ultra fast and accurate model that detects 17 keypoints of a body. The model is offered on TF Hub with two variants, known as Lightning and Thunder. Lightning is intended for latency-critical applications, while Thunder is intended for applications that require high accuracy. Both models run faster than real time (30+ FPS) on most modern desktops, laptops, and phones, which proves crucial for live fitness, health, and wellness applications. For those reason I chose Lightning as I'm running on CPU. 

# References
- https://www.tensorflow.org/lite/examples/pose_estimation/overview
- https://www.iieta.org/journals/ts/paper/10.18280/ts.390111

