# Waste Classification AI Model

This project is an AI-based web application that classifies images of waste. It categorizes waste into four types:  
1. **Organic Waste** (food scraps, fruit peels, leaves)  
2. **Recyclable Waste** (plastic bottles, paper, cardboard, glass, metal cans)  
3. **Hazardous Waste** (batteries, medical waste, chemicals, e-waste)  
4. **General Waste** (non-recyclable plastic, contaminated paper, mixed waste)

## Setup

1. **Install Required Dependencies**  
   Ensure all necessary libraries and tool are installed in your development environment.

2. **Prepare the Dataset**  

```
dataset/
    train/
        organic/
        recyclable/
        hazardous/
        general/
    validation/
        organic/
        recyclable/
        hazardous/
        general/
```

## Model Training

Train the AI model using image data. The system is based on a Convolutional Neural Network (CNN) that learns to identify and classify different types of waste from the images.

## Image Prediction

The web application allows users to upload an image of waste. The trained model analyzes the image and returns a prediction, classifying the waste into one of the four categories.

## Model Specifications

- **Input Format**: RGB Images of size 224x224  
- **Output Categories**: Organic, Recyclable, Hazardous, General  
- **Target Accuracy**: More than 85%

## Features

- Supports real-world waste images  
- Differentiates between similar-looking items  
- Can identify multiple objects within a single image  
- Provides prediction results in a structured (JSON) format, suitable for integration with web interfaces

