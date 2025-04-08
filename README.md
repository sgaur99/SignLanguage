# Hand Gesture Recognition using Leap Motion Dataset

This project demonstrates a hand gesture recognition system using the [LeapGestRecog dataset](https://www.kaggle.com/gti-upm/leapgestrecog/version/1), which contains 20,000 images of 10 different gestures from 10 subjects. The system uses TensorFlow for building a deep learning model capable of classifying hand gestures accurately.

## Project Details

- 📁 Dataset: LeapGestRecog (Leap Motion Controller)
- 🤖 Model: CNN using TensorFlow/Keras
- 🔍 Tasks:
  - Data preprocessing and visualization
  - Model training and evaluation
  - Confusion matrix analysis

## Hand Gestures Mapped

| Gesture           | Label |
|------------------|-------|
| Thumb down        | 0     |
| Palm (Horizontal) | 1     |
| L                 | 2     |
| Fist (Horizontal) | 3     |
| Fist (Vertical)   | 4     |
| Thumbs up         | 5     |
| Index             | 6     |
| OK                | 7     |
| Palm (Vertical)   | 8     |
| C                 | 9     |

## How to Run

1. Install dependencies:
pip install -r requirements.txt

2. Ensure you have the dataset downloaded and extracted in your working directory.

3. Run the notebook:

jupyter notebook SignLang.ipynb


## Acknowledgments

Dataset by GTI-UPM: https://www.kaggle.com/gti-upm/leapgestrecog

## License

This project is for academic use.
