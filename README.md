# Eyes-for-blind-Image-Captioning
using Image captioning (neural networks) to create eyes for blind which will explain the details of an image to a visually impaired person using text to speech 

This project uses Pre-Trained Inception-V3 CNN. To extract features from an image and classify them into one of the thousand classes.
We will use transfer learning. Using feature extraction from a pretrained CNN and then train the model according to our needs to classify them into classes. Instead of using CNN (Convolutional Neural Network) we will be using RNN (Recurrent Neural Network). Which will not only be able to predict the objects in the image but also be able to spot the relation between these objects.

Use Jupyter Notebook to Execute.
Required Libraries:
  1. Numpy
  2. Keras
  
Steps :
  1. Place the project into the current directory of jupyter notebook.
  2. Open Testing_InceptionV3.pynb
  3. Goto In[4] and add the address to the image.
  4. Start executing line by line.
  5. After executing In[7], Out[7] is generated, these are the top five prediction of objects in the image.
  6. After executing In[8], an output image is generated and also stored in the same directory as the source image.
  7. Executing In[9], resulting image that was generated previously id displayed.
  
  
ImageCaptioning.pynb is an RNN to produce caption for image. This file is not in running condition.
Which require following Libraries :
  1. Keras 1.2.2
  2. Tensorflow 0.12.1
  3. tqdm
  4. numpy
  5. pandas
  6. matplotlib
  7. pickle
  8. PIL
  9. glob
