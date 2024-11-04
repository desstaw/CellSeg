# Cell Segmentor Dashboard

The **Cell Segmentor Dashboard** is a web application designed for automated cell nuclei segmentation from microscopy images. Built using a U-Net++ deep learning model, it provides researchers and scientists with an intuitive tool for analyzing cell structures. The application is particularly useful in biological image analysis, offering precise segmentation of cell nuclei, even in complex, overlapping cellular structures.

## What It Does

- **Automated Nuclei Segmentation**: Upload microscopy images, and the application will automatically segment cell nuclei with high accuracy.
- **Refined Separation for Overlapping Nuclei**: Utilizes watershed and distance transform techniques to carefully separate overlapping nuclei.
- **Interactive Visualization**: Each segmented nucleus is labeled, allowing users to explore properties interactively.
- **Custom Drawing and Analysis**: Users can manually draw regions on an image for additional, customized shape analysis.

## Model and Dataset

- **Model Architecture**: The application uses a U-Net++ model, a type of convolutional neural network designed for biomedical image segmentation. U-Net++ improves traditional U-Net by adding nested convolutions and enhanced skip connections, which enhance segmentation accuracy, particularly in challenging images.
  
- **Dataset**: The model was trained on the **Data Science Bowl 2018** dataset, a widely-used dataset in biomedical research. The images were preprocessed with contrast enhancement and resizing for optimal performance. This dataset provides diverse cell image examples, making it ideal for developing robust segmentation models.

The Cell Segmentor Dashboard is designed to be a practical, user-friendly tool for towards the initial steps for advancing research in cellular biology.
