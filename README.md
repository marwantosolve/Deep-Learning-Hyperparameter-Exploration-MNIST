# Supervised Learning Project – CNN & ANN on MNIST (Spring 2025)

## Team Information
- **Team Members**:  
  - Marwan Osama          : 20220324
  - Ammar Mohamed Mahmoud : 20220216  
  - Ahmed Abdelaziz       : 20220025
  - Rana Esmail           : 20220131

## Project Description
This project investigates the performance of different ANN and CNN architectures on the MNIST dataset using Keras (TensorFlow backend). We experimented with various hyperparameters and model structures to evaluate their impact on training/testing performance, accuracy, and efficiency.

## Tools & Environment
- Language: Python  
- Framework: Keras (TensorFlow backend)  
- Platform: Google Colab  
- Dataset: MNIST  
- Loss Function: Categorical Cross-Entropy  

## Implementation Summary
The study was carried out in the following steps:
1. Implemented a basic ANN and an SVM model.
2. Built initial CNN models using ReLU, 2D MaxPooling (2x2), and tested over different epoch counts.
3. Tuned learning rates.
4. Adjusted the number and size of CNN and FC layers.
5. Tested different batch sizes.
6. Switched activation functions (included sigmoid and two others).
7. Evaluated optimizers (SGD + two others).
8. Applied dropout layers in two different positions with two different rates.
9. Finalized the best model.

## Model Evaluation Criteria
For each model, we recorded:
- Final accuracy and accuracy over the first 5 epochs
- Number of parameters
- Avg. training time per epoch
- Avg. testing time per epoch
- Model architecture (layers and activation functions)
- Learning rate and optimizer configuration
- Dropout configuration (if any)
- Observations and rationale for selected parameters

## Constraints Followed
- Batch size: 32 ≤ size ≤ 250  
- CNN Kernel Size: Max 5x5  
- Max CNN channels: 128  
- Max FC layer size: 512  
- Max CNNs: 3, Max FC Layers: 4  
- Dropout: ≤ 85%

## File Structure
- `20220324_20220216_20220025_20220131.ipynb`: Complete notebook with all model implementations and outputs
- `20220324_20220216_20220025_20220131.pdf`: Full report including model configurations, analysis, and observations

## How to Run
1. Open the notebook in Google Colab.
2. Ensure GPU is enabled (`Runtime > Change runtime type > GPU`).
3. Run all cells sequentially to execute all model tests and print results.

## Final Notes
- All members contributed to running, testing, and understanding the models.
- The best model was selected based on a trade-off between accuracy and computational efficiency.
- We recommend starting with the final model section for insights on the most optimal configuration.
