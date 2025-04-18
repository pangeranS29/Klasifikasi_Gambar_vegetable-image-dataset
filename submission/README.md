# 🥦 Vegetable Classification with CNN - TensorFlow Project

This project is a deep learning model for image classification of 15 types of vegetables using Convolutional Neural Networks (CNN) and TensorFlow.

## 📁 Project Structure

## 🧠 Model Summary
- Model is trained with `ImageDataGenerator` from Keras
- Trained to classify the following 15 vegetable classes:
  - Bean
  - Bitter_Gourd
  - Bottle_Gourd
  - Brinjal
  - Broccoli
  - Cabbage
  - Capsicum
  - Carrot
  - Cauliflower
  - Cucumber
  - Papaya
  - Potato
  - Pumpkin
  - Radish
  - Tomato

## 📦 Model Formats
| Format | Path | Description |
|--------|------|-------------|
| `SavedModel` | `submission/saved_model/` | For general use with TensorFlow |
| `TFLite` | `submission/tflite/model.tflite` | For mobile/embedded use |
| `TFJS` | `submission/tfjs_model/` | For web applications using TensorFlow.js |

## 📥 How to Use
- You can use `tflite/model.tflite` with TensorFlow Lite interpreter on mobile
- `tfjs_model/` can be used directly in web apps with `@tensorflow/tfjs`

## 📝 Requirements
See `requirements.txt` for package dependencies.