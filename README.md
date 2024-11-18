# Object Tracking Algorithm Comparison

This project evaluates three object tracking algorithms — **Mean Shift**, **CSRT (Channel and Spatial Reliability Tracking)**, and **DeepSort with YOLOv8** — across various scenarios to understand their performance under different conditions.

## Algorithms Compared

1. **Mean Shift** - A mode-seeking algorithm often used for clustering and object tracking, which relies on color histograms.
2. **CSRT (Channel and Spatial Reliability Tracking)** - An advanced tracking algorithm known for its accuracy, utilizing spatial reliability maps to better handle occlusions.
3. **DeepSort** - An enhanced tracking algorithm that combines a deep learning-based detector with the Simple Online and Realtime Tracking (SORT) algorithm, improving object identification across frames.

## Experiment Setup

The experiments were conducted with different camera and object movement setups to evaluate the tracking algorithms' robustness and adaptability. The setups are as follows:

1. **Moving Camera with Static Object** - Testing the algorithms' performance when the camera moves while the object remains stationary.
2. **Moving Camera with Moving Object** - Assessing tracking accuracy when both the camera and the object are in motion.
3. **Static Camera with Moving Object** - Evaluating tracking stability with a stationary camera and a moving object.
4. **Varying Object Velocity** - Testing the algorithms under different object speeds by selectively skipping frames to simulate increased speed.

Each experiment aims to highlight the strengths and limitations of each algorithm under real-world-like conditions.

## RESULTS

## Future Work

Potential areas for improvement and further experimentation include:
- Testing additional tracking algorithms
- Optimizing algorithms for specific scenarios
- Incorporating environmental factors such as lighting and occlusion
