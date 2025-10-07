# Mini Wall Display Project

## Project Objective
The main objective of this project is to create a display wall. We have explored two different approaches:

### Approach 1: Real-time Data Visualization via Parallel Processing
- Simulate the data using parallel processing with multiple processes on the server node.
- Divide the generated data into 4 parts.
- Transmit each part to different client nodes for visualization.
- Since data is processed at different time steps, the visualization will be real-time.

### Approach 2: Image Partitioning and Visualization
- Construct images in the server node itself after data generation.
- Partition the generated image.
- Send the image partitions to different client nodes for visualization.

## Project Structure
- **Task1_code/**: Contains code and README for Approach 1.  
- **Task2_code/**: Contains code and README for Approach 2.  
- **Working_Demo/**: Contains a working demo of the implementation.  

## How to Run
Please refer to the README files inside `Task1_code` and `Task2_code` for detailed instructions on setting up and running each approach.
