# Bearing-faults-classification-and-prediction-from-vibration-data-for-Induction-Motor
A Machine Learning Model: Bearing faults classification and prediction from vibration data for Induction Motor

In industrial settings, the reliable operation of motor equipment is paramount to maintaining
continuous operations and ensuring safety. Motors are essential components in
various machinery and systems, and their vibrations can serve as valuable indicators of
their operational health. These vibrations encompass a spectrum of conditions, ranging
from normal operational states to potentially critical faults or anomalies.
Accurately detecting and classifying these vibration patterns is crucial for implementing
effective predictive maintenance strategies. Machine learning models, particularly those
designed for anomaly detection using motor vibration data, play a pivotal role in this
process. By analysing the complex patterns within vibration data, these models can
identify deviations from normal operating conditions that may signify impending issues
such as bearing wear, misalignment, or structural defects.
In essence, the development and deployment of machine learning models for anomaly detection
in motor vibration data not only enhance predictive maintenance capabilities but
also contribute significantly to overall operational efficiency, safety, and cost-effectiveness
in industrial environments. By harnessing the power of data analytics, industries can
move towards more proactive and sustainable maintenance practices, ensuring the reliability
and longevity of critical motor equipment.
# Objectives
The primary objectives of the Machine Learning project were:
• To preprocess and standardize the motor vibration data to ensure consistency
• To train and evaluate the One-Class SVM model on multiple datasets
• To perform a comprehensive evaluation of the model using various metrics, including
accuracy, precision, recall, and F1-score
• To identify the dataset that best matches the new data based on the F1-score
# Data Collection
The dataset includes triaxial vibration data of bearing of induction motor operated under
different load conditions along the axes x, y, and z.
It includes triaxial vibration datasets of motor in healthy condition with and without
pulley.
Moreover, the faulty conditions of bearings include inner race and outer race faults of:
• 0.7mm
• 0.9mm
• 1.1mm
• 1.3mm
• 1.5m
• 1.7mm
The bearings with these fault severity levels were operated under different load conditions
including 100W, 200W, and 300W.
There is total 38 datasets of the bearing conditions. The data was acquired at the
sampling rate of 10 kHz at the rate of 1000 samples per channel. 
The link to the data can be found below:
https://data.mendeley.com/datasets/fm6xzxnf36/2 
# Workflow
![workflow](https://github.com/hridoy69/Bearing-faults-classification-and-prediction-from-vibration-data-for-Induction-Motor/assets/56862433/56444d37-0ec7-4ed2-bc67-35b47d072aaa)


