# Generate a street sign image using ML

WTF am I trying to do?
* collect a large enough dataset of street signs (not photos but actual vector graphics)
* modify the images to make them more consistent for training (automated cropping/resizing?)
* train a generative adversarial network to generate a single image of a "sign"
* tune it to produce something more "real" (I have no idea what this will produce as this is a learning exercise for me)

## Things to do
- [ ] Create the initial dataset ([Wikimedia Commons seems like a good place to start](https://commons.wikimedia.org/wiki/Category:SVG_road_signs_in_Canada))
- [ ] Normalize the data (resize smaller images to fit within the largest "canvas" size ie. expand the dimensions to match the largest image). [scikit](https://scikit-image.org/)
- [ ] Convert the raw image data into numpy arrays. [numpy basics](https://numpy.org/doc/stable/user/basics.creation.html)
- [ ] Generate an image from a GAN. [Tensorflow DCGAN tutorial](https://www.tensorflow.org/tutorials/generative/dcgan
)
