
# Driver Drowsiness Detection and Alert System using CNN and Fuzzy Logic

## Overview

This project develops a driver drowsiness detection and alert system using Convolutional Neural Networks (CNNs) and fuzzy logic.

The system analyzes eye states and mouth/yawning patterns to estimate signs of driver fatigue and generate an appropriate alert.

## Objectives

- Classify eye images as open or closed using a CNN.
- Classify mouth images as yawning or not yawning using a second CNN.
- Combine eye-closure and yawning indicators using fuzzy logic.
- Categorize the driver's state as Normal, Warning, or Drowsy.

## Methodology

1. **Dataset preparation:** Download and organize the eye and mouth image datasets.
2. **Eye CNN:** Train a CNN to classify open-eye and closed-eye images.
3. **Mouth CNN:** Train a separate CNN to classify yawning and non-yawning images.
4. **Fuzzy logic:** Combine the indicators to estimate the drowsiness state.
5. **Scenario testing:** Evaluate the combined system using simulated scenarios and generate alerts.
6. **Model and results export:** Save the trained CNN models and export scenario results to CSV.

## Technologies Used

- Python
- Google Colab
- TensorFlow and Keras
- NumPy and Pandas
- Matplotlib
- scikit-fuzzy
- KaggleHub

## Project Files

- `driver-drowsiness-detection.ipynb` — Main project notebook.

## How to Run

1. Open the notebook in Google Colab.
2. Run the cells in sequence.
3. Allow the dataset download and preparation steps to complete.
4. Install any required dependencies when prompted.
5. Train the eye and mouth CNN models.
6. Execute the fuzzy logic and scenario-testing sections.
7. Review the generated alerts and results.

The notebook downloads the dataset through KaggleHub. Dataset access and the Colab runtime may require additional setup.

## Team Members

**Department of Computer Science and Engineering**  
**Netaji Subhas University of Technology**

- Varnit Bansal
- Prisha Yadav
- Dishita Gupta
- Tanishka Kumar

## Limitations

The notebook's combined-system testing uses simulated scenarios. Further testing on real-world driving data is needed before making claims about real-time performance or practical road safety.

## Acknowledgements

The team acknowledges the dataset source and the open-source libraries used in this project.

