# OpenCV DNN Summary

The Deep Neural Network (DNN) module in OpenCV provides a high-level API for using pre-trained deep learning models for various computer vision tasks.

## Key Steps for Using a DNN Model

1.  **Load the model:** Use one of the `readNet` functions to load a pre-trained model from a file. OpenCV supports models from various frameworks, including:
    *   Caffe (`readNetFromCaffe`)
    *   TensorFlow (`readNetFromTensorflow`)
    *   ONNX (`readNetFromONNX`)
    *   Darknet (`readNetFromDarknet`)

2.  **Prepare the input:** Use the `blobFromImage` function to convert an image to a 4-dimensional "blob" that can be fed into the network. This function can also perform necessary preprocessing steps, such as:
    *   Resizing
    *   Cropping
    *   Mean subtraction
    *   Scaling

3.  **Set the input:** Use the `setInput` method of the `Net` object to set the input blob for the network.

4.  **Perform inference:** Use the `forward` method of the `Net` object to run the model and get the output.

5.  **Process the output:** The format of the output depends on the specific model and task. For example:
    *   **Classification:** The output is typically a vector of probabilities for each class.
    *   **Object Detection:** The output is usually a set of bounding boxes for the detected objects, along with their class labels and confidence scores.
    *   **Segmentation:** The output is a mask that assigns a class label to each pixel in the input image.

## High-Level APIs

The DNN module also provides high-level APIs for common tasks, which can simplify the process of using a model. These include:

*   `ClassificationModel`
*   `DetectionModel`
*   `SegmentationModel`
*   `KeypointsModel`
*   `TextDetectionModel`
*   `TextRecognitionModel`

These classes provide a more abstract and user-friendly interface for their respective tasks, handling many of the details of model loading, input preprocessing, and output processing automatically.
