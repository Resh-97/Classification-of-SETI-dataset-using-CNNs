# Classification of SETI dataset using CNNs
The SETI dataset consists of 2-Dimensional spectrograms of radio signals from space collected at the SETI Institute by the Allen Telescope Array. The  objective  is  to classify the radio signals from outer space into one of four classes.

### Tasks Performed:

  * Prepare a detailed python notebook using CNN for classifying the radio signals from deep space using Keras from the SETI Dataset
  * Load and Pre-process the dataset
  * Visualize the dataset
  * Create Training and Validation Data Generators
  * Design a Convolutional Neural Network (CNN) Model
  * Train the Model
  * Evaluate the Model 
  
### Dataset:

The spectrograph images were converted into their raw pixel intensity values and normalized so the values lie between 0 and 1. They are then converted into an array by stretching them. Therefore each row of the CSV file corresponds to a single image.

- https://www.dropbox.com/sh/pwbc7gvqqmn9fzk/AAAL2Tpy1Bx151AtjnbCIedma?dl=0

Each Row Corresponds to an image.
The label were found to be one hot encoded in to a vector of 1,4(no. of classes).

    * 1,0,0,0 is squiggle
    * 0,1,0,0 is Narrow-band signal
    * 0,0,1,0 is Noise
    * 0,0,0,1 is Narrow-band-drd signal
