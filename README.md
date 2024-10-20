
# Machine Unlearning for Social Media Image Models

This project investigates the application of **machine unlearning** techniques to social media image models, aiming to enhance user privacy by selectively removing the influence of specific user images from trained models. The goal is to preserve model performance while ensuring that sensitive data is no longer identifiable in the model's predictions.

## Datasets:
- **CIFAR-10**
- **CIFAR-100**

## Objectives:
1. **Data Removal**: Effectively remove sensitive user images from trained models.
2. **Performance Retention**: Ensure the model retains high accuracy on general image recognition tasks.
3. **Privacy Protection**: Reduce the model's ability to identify removed user images, enhancing privacy.

## Methods:
- **Selective Synaptic Dampening (SSD)**: A post-hoc, retrain-free method utilizing the Fisher information matrix to dampen synaptic connections related to sensitive data.

## Expected Outcomes:
- Effective unlearning of specific images from models with minimal impact on overall accuracy.
- Enhanced privacy protection by reducing the model's ability to classify unlearned user images.

## Conclusion:
Machine unlearning offers a promising solution to address privacy concerns on social media platforms by selectively removing sensitive data from deep learning models without requiring full retraining.

## Credit
This project incorporates code from [selective-synaptic-dampening](https://github.com/if-loops/selective-synaptic-dampening)
