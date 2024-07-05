# Posture-Correction-Assistant

Posture Correction Assistant, a mHealth application that tracks the user’s posture and can help them correct bad posture through reminders. This can greatly help the user’s health by fixing bad posture, which can help reduce overall back pain or damage.

# Required Elements

Used Sensors: Accelerometer and gyroscope. With these two sensors, we can detect the user’s posture by classifying the movement and orientation of the device, which can allow us to correct the user towards good posture.
Signal Processing Plans: Deviation (gyroscope), Dynamic Time Warping, Range (accelerometer and gyroscope), Orientation/Magnitude of gyroscope, Similarity-Based Attributes/Gait.
Data Delivery: One way we can deliver the data is we can classify the posture and then report it via visualization on a laptop.

Outcome
- The accuracy rates for the data is quite great, although more data needs to be introduced to make sure this extrapolates well to use for a real application.
- At first, features surrounding each individual x/y/z of the gyroscope were going to be implemented alongside the gyroscope magnitude, but the model works well with just gyroscope magnitude, it would be overkill. However, if with more data the accuracy and precision drops, then this could be one way to improve the model.
