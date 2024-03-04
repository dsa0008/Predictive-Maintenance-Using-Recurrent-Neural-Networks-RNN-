# Predictive-Maintenance-Using-Recurrent-Neural-Networks-RNN-

# Prognostics and Health Management (PHM) Dataset Analysis

## About this Dataset

### Context
This dataset originates from a representative practice-relevant degradation process for Prognostics and Health Management (PHM) applications, focusing on the clogging of filters during the separation of solid particles from gas using a test bench that performs automated life testing of filter media.

### Detailed Specification
For in-depth information about the operation and components used, refer to the description file "Prognosis based on Varying Data Quality Data Set.pdf".

### Data Situation
Data quality is influenced by sensors, sensor location, and peripherals, leading to different biases and noise levels. This dataset simulates such variations to reflect real-world conditions where data quality differs due to technical systems marketed with diverse sensor setups.

### Task
The goal is to predict the Remaining Useful Life (RUL) of censored filter test cycles in the test data, considering the challenges posed by varying data qualities. The dataset supports the integration of physical knowledge/models in data-driven models for accurate predictions.

### Acknowledgement
Special thanks to Simon Hagmeyer and Marcel Braig for their contribution to the dataset creation.

### Data Set Creator
Hochschule Esslingen - University of Applied Sciences, Research Department Reliability Engineering and Prognostics and Health Management.

### Data Set Citation
Hagmeyer, S., Mauthe, F., & Zeiler, P. (2021). Creation of Publicly Available Data Sets for Prognostics and Diagnostics Addressing Data Scenarios Relevant to Industrial Applications. International Journal of Prognostics and Health Management, Volume 12, Issue 2.

## Dataset Analysis and Model Development

This analysis involves exploring the provided dataset and developing a Recurrent Neural Network (RNN) model to predict the RUL of industrial filter systems. The dataset includes training and test data, simulating filter clogging processes under varying data quality conditions.

### Key Findings
- The RNN model demonstrates promising results in predicting RUL based on historical sensor data, despite the challenges posed by different data qualities.
- Temporal patterns in historical sensor readings are crucial for accurate prognostics.
- The model's performance suggests potential for optimizing maintenance schedules, highlighting the importance of predictive maintenance in PHM applications.

### Model Performance and Impact
- The model's ability to handle real-world data complexities emphasizes the need for robust preprocessing and architecture.
- Further validation on additional datasets and real-world scenarios is necessary to fully ascertain the model's capabilities.

### Conclusion
The development of the RNN model and its application to the PHM dataset showcases the potential of machine learning in predictive maintenance and equipment health management, contributing valuable insights to the PHM field.

## Getting Started
To replicate this analysis and model development, ensure you have the following libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- keras

Explore the dataset, perform preprocessing, and develop the RNN model following the methodology outlined in this repository.
