# Electrical-Faults-Detection-and-Classification-using-Machine-Learning
This project focuses on developing a machine learning model to classify various electrical fault types in a transmission line. The model utilizes voltage and current measurements as inputs to identify and categorize faults such as open-circuit faults, single-line-to-ground faults, line-to-line faults, and three-phase faults.


![transmition](https://github.com/AoufNihed/Electrical-Faults-Detection-and-Classification-using-Machine-Learning/assets/112959070/169fac9c-c855-4d0a-8cab-26d764288b9a)
The reliable and efficient operation of power systems is crucial for modern society. However, these systems are susceptible to various electrical faults that can disrupt power delivery, damage equipment, and pose safety hazards. Early detection and accurate classification of these faults are essential for minimizing downtime, ensuring equipment protection, and maintaining system stability.

-This project investigates the application of machine learning for electrical fault detection and classification in a power transmission line. The document details the exploration of a dataset containing voltage and current measurements, the implementation of various machine learning models, and the analysis of their effectiveness in identifying different fault types.

These faults can be categorized based on the phases involved and their connection to ground:

Open-circuit fault: A complete interruption of current flow in one or more conductors.
Short-circuit fault: An abnormal connection between phases or a phase and ground, resulting in a sudden increase in current.
Symmetrical faults: All phases are involved, leading to balanced fault currents. (Less common)
Asymmetrical faults: Involve one or two phases, causing unbalanced currents. These are more frequent and include:
Single-line-to-ground (LG) fault: A phase conductor comes into contact with ground.
Line-to-line (LL) fault: Two phases come into direct contact.
Double line-to-ground (LLG) fault: Two phases contact ground simultaneously.
Three-phase fault (LLL): All three phases come into contact with each other or with ground (most severe type).
![Screenshot 2024-04-08 171752](https://github.com/AoufNihed/Electrical-Faults-Detection-and-Classification-using-Machine-Learning/assets/112959070/86b5b305-5b59-4ef8-a9bd-cf673711c9a5)

-Machine Learning Models
Several supervised machine learning algorithms are trained and evaluated for fault detection and classification:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
XGB Classifier
Support Vector Machines

-Model Evaluation
Model performance is evaluated based on accuracy and efficiency in fault detection. The following results are obtained:

Random Forest, Decision Tree Classifier, and XGB Classifier achieve the highest accuracy of 100%.
Logistic Regression performs poorly compared to other models.

-Conclusion
The Random Forest, Decision Tree Classifier, and XGB Classifier models demonstrate superior performance in fault detection and classification. These models can accurately predict different types of faults in transmission lines, contributing to the reliability and stability of the power grid.
