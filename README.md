# Desk Object Sorter

## Overview
This project uses Google’s Teachable Machine to create a machine learning model that can recognize common objects in my bedroom. The purpose is to learn the fundamentals of supervised image classification, including collecting and labeling training data, training and testing a model, iterating and refining, understanding bias in AI, and exporting and managing models with GitHub.

## Classes My Model Will Recognize
- PS4 Controller
- Nintendo Switch
- Keys
- Wallet
- Phone
- AirPods

## Discussion & Reflection

1. **Model Performance & Iteration**
- First trained model accuracy: Low accuracy initially
- Steps to improve performance: Took better pictures from improved distances, providing clearer views of the objects
- Effect on accuracy/confidence scores: Accuracy improved significantly with clearer and better-angled images

2. **Challenges & Observations**
- Easiest objects to recognize and why: Objects with clear, distinct features and good lighting
- Hardest objects to recognize and why: Objects viewed from different angles or in low-light conditions
- Behavior with untrained objects: Model struggled and often misclassified objects it hadn’t seen

3. **Bias in AI**
- Bias from training only one version of an object: Model performs well only on the specific version it was trained on (e.g., one color or one angle)
- Effects of lighting or angles: Variations in lighting or angles can significantly reduce accuracy

4. **Model Limitations & Usefulness**
- Model limitations: Limited by the small number of objects and reliance on good lighting conditions
- Why exporting model files is useful: Allows deployment across platforms, sharing, and further testing

5. **Real-World Applications & Ethics**
- Applications:
  1. Inventory management – recognize and locate products efficiently
  2. Smart home devices – identify objects for automation
  3. Augmented reality – enhance AR experiences by recognizing real-world objects
- Ethical Consideration: Privacy concerns if recognizing individuals, and potential bias from limited or unrepresentative training data

## Repository Contents
- model.json
- weights.bin
- metadata.json
- README.md (this file)
