# SDP_GenAI
This is my SDP project, an implementation of CycleGAN for unpaired image-to-image translation, enabling style transfer and domain adaptation without the need for paired datasets.

Overview
CycleGAN (Cycle-Consistent Generative Adversarial Network) is a deep learning model that performs unpaired image-to-image translation by using two generators and two discriminators. It eliminates the need for paired datasets by utilizing cycle consistency loss, ensuring that a transformed image can be reconstructed back to its original form. This makes CycleGAN ideal for applications such as style transfer, domain adaptation, and artistic transformations (e.g., converting real-world photos into paintings in the style of famous artists).

Features
Unpaired Image Translation: No paired datasets required.
Bidirectional Transformation: Two generators for converting between source and target domains.
Cycle Consistency: Ensures the transformed image can be converted back to its original form.
Ideal for Style Transfer: Can convert real images into various artistic styles like Monet, Van Gogh, etc.

Loss Functions
The model is optimized using three key loss functions:

Adversarial Loss: Encourages the generator to produce realistic images.
Cycle Consistency Loss: Ensures the transformed image can be converted back to the original domain.
Identity Loss: Preserves essential features of the original image.
