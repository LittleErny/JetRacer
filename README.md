# JetRacer Road Following Project

This project, completed at Deggendorf Institute of Technology in SS24, showcases a high-performance AI-based racing car developed with the [JetRacer Pro AI Kit](https://www.waveshare.com/wiki/JetRacer_Pro_AI_Kit). The goal is to use computer vision and deep learning to train a model that autonomously navigates a track as quickly as possible. This project involves data collection, dataset labeling, model training, hardware setup, and testing on a real-world racetrack. 

I received a top grade (1.0) for this project and successfully passed the course.

## Project Overview

This project includes:

1. **Dataset Collection and Labeling:** 
   - Recording video from the car's camera in different positions to recreate different situations on the road that the car can see.
   - Splitting the video into frames & labeling the frames.
   
2. **Model Training (road_following_learning.ipynb):**
   - Training a road-following model in Google Colab. 
   - This notebook includes data preprocessing, model architecture setup, training, and evaluation.

3. **JetRacer Hardware Setup:**
   - Composing the Car(pretty much like Lego)
   - Installing Linux system & setting up the environment

4. **Testing on Track (racing.ipynb):**
   - Running the trained model on the JetRacer car.
   - Optimizing performance for smooth and fast navigation around a circular track.

## Files Included

- **`road_following_learning.ipynb`** - This notebook covers the training process in Google Colab.
- **`racing.ipynb`** - This notebook runs the trained model on the JetRacer car for testing and racing.

## Results

After training and testing, the JetRacer car successfully navigated the track autonomously, demonstrating reliable and fast performance.

## Usage

### Running the Training Notebook

1. **Clone the repository:**
   ```bash
   git clone https://github.com/LittleErny/JetRacer
   cd JetRacer
   ```

2. **Open `road_following_learning.ipynb` in Google Colab** (or another Jupyter environment).
   - Follow the steps in the notebook to set up the environment, load data, and train the model.

3. **Export the Trained Model:**
   - Save the trained model and transfer it to the JetRacer for real-world testing.

### Running the JetRacer

1. Transfer `racing.ipynb` to the JetRacer device.
2. Open `racing.ipynb` on the JetRacer and run.

## Demo

![JetRacer Racing GIF](images/jet_racing_demo.gif)

*To add the GIF in your README:*

## Acknowledgments

Special thanks to Deggendorf Institute of Technology for support and resources<3

