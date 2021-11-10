**CNN Classifier to recognize and classify handwritten digits:**
- MNIST dataset
- 60,000 training images, 10,000 test images.
- Plots greyscale images.
- Preprocessing involved: 
  <pre>
  -> re-shaping into 4D to make it compatible with Keras
  -> type conversion to float
  -> normalization using max. RGB value
  <pre>
- Sequential model with 6 Layers:
  <pre>
  -> Conv2D
  -> MaxPooling2D
  -> Flatten
  -> Dense
  -> Dropout
  -> Dense
  <pre>
- trained for 10 epochs
- computes with adam optimizer and sparse categorial entropy as loss
- test accuracy of 98.46
