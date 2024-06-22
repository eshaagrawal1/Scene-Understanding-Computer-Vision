# Scene-Understanding-Computer-Vision
Scene understanding involves perceiving, analyzing, and interpreting a 3D dynamic scene using a network of sensors. This process matches sensor data with human cognitive models to add and extract semantics from the scene. The scenes, ranging from brief events to prolonged periods, can involve various interacting objects like people and vehicles, observed through sensors such as cameras, microphones, and radars.
Key functionalities include detection, localization, recognition, and understanding, extending beyond visual features to meaningful physical world information. Scene understanding requires cognitive abilities like learning, adaptation, and strategy development to achieve robust and adaptable vision functionalities. It should anticipate events, adapt to new environments, predict future configurations, and communicate effectively with other systems. This domain intersects with robotics and multimedia document analysis, offering diverse application possibilities.
This project explores advanced scene understanding techniques, aiming to enhance real-time interpretation and interaction within dynamic environments.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Git

### Installation

To get started with the project, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/Scene-Understanding-Computer-Vision.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd Scene-Understanding-Computer-Vision
    ```

3. **Install the dependencies:**

    ```bash
    pip install opencv-python tensorflow keras numpy
    ```

4. **Start the project:**

    ```bash
    python Detector.py
    python run_me.py
    ```

## DATA ANALYSIS
Dataset
Tensorflow is a collection of detection models pre-trained on the COCO 2017 dataset. These models can be useful for out-of-the-box inference. there are many categories already in those datasets.

![Screenshot 2024-06-21 220825](https://github.com/eshaagrawal1/Scene-Understanding-Computer-Vision/assets/90109712/30e7713d-870b-4412-afa6-7c552025b3bb)

## Approach
Understanding the images in the scene may be obtained with text in the images. When text could be located and recognized properly they could provide a better visualization.2D images may be analyzed by content based or semantically. 

![Screenshot 2024-06-21 220930](https://github.com/eshaagrawal1/Scene-Understanding-Computer-Vision/assets/90109712/fa274f6d-206e-4643-a97e-7a251ceb9923)

## Results
![Screenshot 2024-06-21 221049](https://github.com/eshaagrawal1/Scene-Understanding-Computer-Vision/assets/90109712/a643fe47-233b-480b-9d04-19e418e35b61)

![Screenshot 2024-06-21 221114](https://github.com/eshaagrawal1/Scene-Understanding-Computer-Vision/assets/90109712/b8be2898-33c2-4c22-8ca7-48bce4c0e0be)

We have used coco.names library from where the names are fetched and tensorflow handles the rest part.This model also runs for video simulation. 
