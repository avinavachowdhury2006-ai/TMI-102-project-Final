# TMI-102-project-Final
# Mobile-Drone Based System for Disease Detection in Plants

## Project Overview
This project aims to design and develop an autonomous, mobile-drone system equipped with imaging sensors and trained via deep learning. The system is capable of identifying plant diseases at early stages, monitoring crop health, and providing farmers with actionable data to reduce devastating losses. The ultimate objective is to provide a cost-effective, labor-saving, and precise solution utilizing advanced convolutional neural networks and control systems.

## Team & Affiliation
* **Authors:** Avinava Chowdhury.
* **Faculty Supervisor:** Prof Dr. D. K. Ojha (Dept. of Chemical Engineering).
* **Institution:** Indian Institute of Technology Roorkee.
* **Course Info:** TMI-102 (Tinkering & Mentoring)

## Tech Stack & Libraries
The analysis application was built using Python 3.10.15 and leverages a powerful stack of libraries:
* **Machine Learning Framework:** TensorFlow (v2.10.0) was used for model building, training, and evaluation.
* **User Interface:** Streamlit was used for the interactive prototype.
* **Data Handling & Evaluation:** Pandas (v2.1.0), NumPy (v1.23.5), and Scikit-learn (v1.3.0).
* **Visualizations:** Matplotlib (v3.7.2) and Seaborn (v0.13.0).

## Dataset & Training Methodology
* The model targets 60 diseases across 17 plant species, including crops like tomatoes, potatoes, maize, and apples.
* The dataset was sourced from a diverse, augmented Kaggle dataset.
* **Dataset Split:** The project utilized a total of 153,103 images.
* The split consisted of 105,874 training images, 47,172 validation images, and 57 testing images.
* Training was conducted for 10 epochs on an NVIDIA RTX 4060 GPU.
* The evaluation metrics prioritized maximizing "hits" and minimizing "misses," as False Negatives (FN) are considered the most costly error for farmers.

## Workflow Architecture
* **Image Input:** The farmer selects a high-resolution image of a plant leaf or fruit.
* **Pre-Processing & Local Analysis:** The machine learning model performs complex analysis locally on the Streamlit web app.
* **Instant Diagnosis:** Within seconds, the application identifies the most likely disease or confirms the plant is healthy.
* **Key Design Feature:** The 100% local processing is the single most important feature, ensuring actionable diagnosis for farmers while they are still in the field.

## Results & Performance
* The model achieved a final training accuracy of 93.85%.
* The model achieved a final validation accuracy of 88.71%.
* The overall final accuracy was 91.44%.
* **Proof of Concept:** A random test of 57 images (52 from the web and 5 from ground research) achieved a true-positive output for 44 images.
* <img width="825" height="735" alt="image" src="https://github.com/user-attachments/assets/8ba41bf5-a891-4b65-a0dd-ee99d451ba9d" />


## Limitations
* **Lack of Full Integration:** There is currently an absence of integration between the drone hardware and the software engine, meaning the workflow remains manual.
* **Environmental Variability:** The model has yet to address challenges related to variable outdoor lighting conditions.
* **Dataset Diversity:** A dataset with greater "in-the-field" diversity is needed to improve the model's robustness.

## Future Vision
1. Automated Crop Mapping & Data Collection.
2. Intelligent Diseased Zone Isolation.
3. Precise Disease Identification.
4. Automated Disease Severity Estimation.
5. Actionable Solution & Treatment Recommendation.
6. Expanding the Diagnostic Knowledge Base.
