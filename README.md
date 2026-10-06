# Face and Emotion Recognition — AGH Fundamentals of Computer Science Project

Academic project focused on face recognition and facial emotion recognition using computer vision and neural networks.

The application uses a webcam to detect faces, recognize known people and classify facial expressions using a trained convolutional neural network.

## Project overview

The project combines computer vision, machine learning and web application development.

Main features include:

- real-time face detection and recognition
- facial emotion recognition
- webcam-based image processing
- training a convolutional neural network on labeled facial images
- image preprocessing and classification
- integration of recognition functionality into a web application

The model was trained on a facial emotion dataset from Kaggle, which is not included in the repository. A pre-trained model is provided and can be loaded by the application.

## Project preview

### Welcome page

![Welcome page](images/preview/welcome-page.png)

### Adding a face

![Adding a face](images/preview/adding-face.png)

### Face recognition

![Face recognition](images/preview/face-recognition.png)

### Emotion recognition

![Emotion recognition](images/preview/emotion-recognition.png)

## Running the project

### Setup virtual environment

```bash
python -3.11 -m venv .venv
.venv\Scripts\activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the backend

```bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```