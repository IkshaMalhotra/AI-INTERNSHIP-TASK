# Facial-Expression-Recognition Model

A Python-based deep learning project to recognize human facial expressions (e.g., Happy, Sad, Angry) in real-time using OpenCV, CNN models, and a webcam.

Dataset used : https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset

## Features

- Real-time face detection using webcam
- Facial expression classification with a CNN
- Preprocessing using OpenCV
- Live prediction display with bounding boxes and labels

---

## Recognized Emotions

- Happy 😀  
- Sad 😢  
- Angry 😠  
- Neutral 😐  
- Surprise 😲  
- Fear 😨  
- Disgust 😒

---

## Requirements

Install dependencies using:

```bash
pip install -r requirements.txt ```

---

# MODEL TRAINING
The model was trained using `trainmodel.ipynb` and saved in two parts:

- `emotiondetector.json` — contains the model architecture
- `emotiondetector.h5` — contains the trained model weights

The current model was trained with limited resources and reached only **~25% accuracy**, primarily due to **lack of GPU** support.

> ⚠️ **Important:**  
> To achieve reliable predictions, retrain the model using a properly preprocessed dataset and GPU acceleration.  
> Aim for at least **60–80% accuracy** or higher. Once trained well, `realtimedetection.py` will give correct and consistent predictions.





