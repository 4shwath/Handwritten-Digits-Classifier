**CNN Classifier to recognize and classify handwritten digits:**
- Uses MNIST dataset with 60,000 training images and 10,000 test images.
- Plots greyscale images using matplotlib.
- Preprocessing involved: 
  <pre>
  -> re-shaping into 4D to make it compatible with Keras API
  -> type conversion to float
  -> normalization using max. RGB value
  <pre>
- A Sequential model was used. 6 Layers were added:
  <pre>
  -> Conv2D
  -> MaxPooling2D
  -> Flatten
  -> Dense
  -> Dropout
  -> Dense
  <pre>
- The model has an accuracy of 98.58.
- It uses *adam* optimizer, *sparse categorial entropy* loss and displays its *accuracy*.
- Training was done for 10 epochs.
