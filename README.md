# Project: Liquid Soap Anomaly Detection System

## Introduction
This project serves as the final endeavor for the "Pengenalan Pola" course within the "Teknik Komputer" major. The primary objective is to develop an anomaly detection system, specifically aimed at identifying substandard or defective products within a commercial liquid soap production environment. The system is designed to be deployed at a soap factory, utilizing data from a color sensor TCS34725 and an alcohol sensor MQ-3. The data acquisition process involves an ESP32 acting as a sensor reader, collecting information from the sensors and transmitting it to a laptop using serial communication.

## Components
The main components of this project include:
- Color Sensor TCS34725
- Alcohol Sensor MQ-3
- ESP32 microcontroller
- Laptop for data processing

## Data Collection
The color and alcohol sensors gather relevant data regarding the quality of the liquid soap as it passes through the production line. The ESP32 microcontroller serves as the data collection unit, transferring the gathered information to a connected laptop via serial communication for further analysis.

## Anomaly Detection Algorithm
The heart of this system lies in the implementation of a Gaussian Naive Bayes algorithm, powered by the scikit-learn library. This algorithm processes the collected data to ascertain the probability of the product being defective or non-defective based on the sensor readings. The efficient application of this algorithm aims to enhance the overall product quality control process within the soap production environment.

## Deployment
Upon completion, the anomaly detection system will be deployed within the soap factory environment. It will continuously monitor the production line, analyzing the data in real-time and provide valuable insights into the quality of the liquid soap being manufactured.

## Conclusion
This project aligns with the core principles of "Pengenalan Pola" by applying pattern recognition techniques to real-world industrial processes. It serves as a testament to the practical application of machine learning algorithms for quality control and anomaly detection within the manufacturing sector. Furthermore, this endeavor reflects the intersection of computer engineering and industrial automation, showcasing the potential for technological advancements in enhancing product quality and operational efficiency.  
