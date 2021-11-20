# Generate a street sign image using ML

WTF am I trying to do?
* collect image data (actual vector graphics, not photos)
* modify the images to make them more consistent for training (automated cropping/resizing?)
* train a generative adversarial network to generate images based on the likeness
* tune it to produce something more "real" (I have no idea what this will produce as this is a learning exercise for me)

## Dataset ideas
* Signs based on Canada or Ontario road signs ([Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:SVG_road_signs_in_Canada))
* Olympic games pictograms (what imaginative games can an AI come up with?) ([Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Olympic_pictograms))
* AIGA images ([Wikimedia Commons](https://commons.wikimedia.org/wiki/AIGA_Images), [AIGA source](https://www.aiga.org/resources/symbol-signs))


## Things to do
- [ ] Create the initial dataset
- [ ] Normalize the data (resize smaller images to fit within the largest "canvas" size ie. expand the dimensions to match the largest image). [scikit](https://scikit-image.org/)
- [ ] Convert the raw image data into numpy arrays. [numpy basics](https://numpy.org/doc/stable/user/basics.creation.html)
- [ ] Generate an image from a GAN. [Tensorflow DCGAN tutorial](https://www.tensorflow.org/tutorials/generative/dcgan)

## Misc
* Need to host the dataset somewhere. Some sort of cloud storage ie Dropbox, Drive, etc. Really, anywhere that is accessible via a notebook. 
* Create a notebook on a cloud service? Not rely on my local hardware. Some options:
  - [Google Colab](https://colab.research.google.com)
  - [Kaggle](https://www.kaggle.com/code)

