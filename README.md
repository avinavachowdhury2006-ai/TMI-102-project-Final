# TMI-102-project-Final
# Mobile-Drone Based System for Disease Detection in Plants[cite: 1]

## Project Overview
This project aims to design and develop an autonomous, mobile-drone system equipped with imaging sensors and trained via deep learning[cite: 1]. The system is capable of identifying plant diseases at early stages[cite: 1], monitoring crop health[cite: 1], and providing farmers with actionable data to reduce devastating losses[cite: 1]. The ultimate objective is to provide a cost-effective, labor-saving, and precise solution utilizing advanced convolutional neural networks and control systems[cite: 1].

## Team & Affiliation
* **Authors:** Paras Agarwal, Avinava Chowdhury, Dhruv Upadhyay, Krish Rawat[cite: 1].
* **Faculty Supervisor:** Prof Dr. D. K. Ojha (Dept. of Chemical Engineering)[cite: 1].
* **Institution:** Indian Institute of Technology Roorkee[cite: 1].
* **Course Info:** TMI-102 (Tinkering & Mentoring), Presentation Slot #1, POSTER ID CH-6[cite: 1].

## Tech Stack & Libraries
The analysis application was built using Python 3.10.15 and leverages a powerful stack of libraries[cite: 1]:
* **Machine Learning Framework:** TensorFlow (v2.10.0) was used for model building, training, and evaluation[cite: 1].
* **User Interface:** Streamlit was used for the interactive prototype[cite: 1].
* **Data Handling & Evaluation:** Pandas (v2.1.0)[cite: 1], NumPy (v1.23.5)[cite: 1], and Scikit-learn (v1.3.0)[cite: 1].
* **Visualizations:** Matplotlib (v3.7.2)[cite: 1] and Seaborn (v0.13.0)[cite: 1].

## Dataset & Training Methodology
* The model targets 60 diseases across 17 plant species[cite: 1], including crops like tomatoes, potatoes, maize, and apples[cite: 1].
* The dataset was sourced from a diverse, augmented Kaggle dataset[cite: 1].
* **Dataset Split:** The project utilized a total of 153,103 images[cite: 1].
* The split consisted of 105,874 training images[cite: 1], 47,172 validation images[cite: 1], and 57 testing images[cite: 1].
* Training was conducted for 10 epochs on an NVIDIA RTX 4060 GPU[cite: 1].
* The evaluation metrics prioritized maximizing "hits" and minimizing "misses," as False Negatives (FN) are considered the most costly error for farmers[cite: 1].

## Workflow Architecture
* **Image Input:** The farmer selects a high-resolution image of a plant leaf or fruit[cite: 1].
* **Pre-Processing & Local Analysis:** The machine learning model performs complex analysis locally on the Streamlit web app[cite: 1].
* **Instant Diagnosis:** Within seconds, the application identifies the most likely disease or confirms the plant is healthy[cite: 1].
* **Key Design Feature:** The 100% local processing is the single most important feature, ensuring actionable diagnosis for farmers while they are still in the field[cite: 1].

## Results & Performance
* The model achieved a final training accuracy of 93.85%[cite: 1].
* The model achieved a final validation accuracy of 88.71%[cite: 1].
* The overall final accuracy was 91.44%[cite: 1].
* **Proof of Concept:** A random test of 57 images (52 from the web and 5 from ground research) achieved a true-positive output for 44 images[cite: 1].

## Limitations
* **Lack of Full Integration:** There is currently an absence of integration between the drone hardware and the software engine[cite: 1], meaning the workflow remains manual[cite: 1].
* **Environmental Variability:** The model has yet to address challenges related to variable outdoor lighting conditions[cite: 1].
* **Dataset Diversity:** A dataset with greater "in-the-field" diversity is needed to improve the model's robustness[cite: 1].

## Future Vision
1. Automated Crop Mapping & Data Collection[cite: 1].
2. Intelligent Diseased Zone Isolation[cite: 1].
3. Precise Disease Identification[cite: 1].
4. Automated Disease Severity Estimation[cite: 1].
5. Actionable Solution & Treatment Recommendation[cite: 1].
6. Expanding the Diagnostic Knowledge Base[cite: 1].
