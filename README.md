# Musculoskeletal Abnormalities Detection Using Deep Learning

This project utilizes deep learning techniques to detect abnormalities in X-ray images of various body parts, including the wrist, finger, humerus, forearm, and hand. The application is developed using **Flask** and leverages TensorFlow/Keras for model inference, offering an intuitive web-based interface for medical professionals or researchers.

![Home Screen](home.jpg)
*Home Page of the Application*

---

## Features
- **X-ray Image Analysis:** Upload X-ray images and receive predictions for abnormalities with high accuracy.
- **Pre-trained Models:** Specialized deep learning models trained on datasets for detecting abnormalities in:
  - Wrist (XR_WRIST)
  - Finger (XR_FINGER)
  - Humerus (XR_HUMERUS)
  - Forearm (XR_FOREARM)
  - Hand (XR_HAND)
- **Confidence Score:** Each prediction includes a confidence level to gauge the reliability of the result.
- **User-friendly Interface:** Simple and responsive design for easy interaction.
- **Detailed Results Page:** Provides predictions with accompanying visual and textual feedback.

![Prediction Page](predict.jpg)
*Prediction Results Page*

---

## Technologies Used
### Backend:
- **Flask:** Lightweight framework for serving the application.
- **TensorFlow/Keras:** Framework for loading and running pre-trained deep learning models.

### Frontend:
- **HTML, CSS, and Bootstrap:** Responsive and clean user interface design.

### Image Processing:
- **scikit-image:** For image preprocessing and transformations.

---

## How to Run the Application
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/musculoskeletal-abnormalities-detection.git
