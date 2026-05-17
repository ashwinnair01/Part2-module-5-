# Part2-module-5
Computer Vision Problem Formulation and CNN Prototype

Task 6 CNN Concept Explaination
What is Convolution?

Convolution is a process where small filters scan across an image to detect patterns such as:
edges
textures
shapes
The CNN automatically learns these filters during training.
___________________________________________________________________________________________________________________________________
Why is Pooling Used?

Pooling reduces image size while keeping important features.
Benefits:
reduces computation
prevents overfitting
helps model focus on important patterns

Common example:
Max Pooling
____________________________________________________________________________________________________________________________________
Why is ReLU Commonly Used?

ReLU:
f(x) = max(0, x)

Advantages:
faster training
avoids vanishing gradients
introduces non-linearity
______________________________________________________________________________________________________________________________________
Why are CNNs Better Than Regular Feed-Forward Networks for Images?

CNNs:
preserve spatial information
detect local patterns
use fewer parameters
work efficiently on images

Feed-forward networks flatten images and lose spatial structure.
_______________________________________________________________________________________________________________________________________
Task 7: Business Use Case Mapping
Example: Healthcare

CNN-based image classification can be used in medical imaging.

Example Applications:
detecting pneumonia from X-rays
identifying tumors in MRI scans
diabetic retinopathy detection

Benefits:
faster diagnosis
reduced workload for doctors
early disease detection
improved healthcare accessibility
