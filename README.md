SDU-net
This project implements a deep learning model, SDU-net, for image segmentation tasks using PyTorch. The model is trained and evaluated on the UHCS dataset, which includes images, labels, and processed SAM results.

Setup
First, ensure you have installed the required dependencies. You can install them using the following command:
pip install torchsummary

The dataset consists of the following folders:

    Images: Original images
    SAM_background: Processed background images
    SAM_foreground: Processed foreground images
    Labels: Label images
    
Running the Experiment

You can train and evaluate the model by running SDU-net.ipynb. Ensure that the dataset paths are set to your local paths.

Contributing
If you have any suggestions for improvements or encounter any issues, please feel free to open an issue or submit a pull request.

Note
Code for academic purpose only
