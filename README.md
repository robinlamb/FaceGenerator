# Face Generator
A deep convolutional GAN for generating faces

This is a project created using PyTorch that has two neural networks, a generator that creates pictures of faces, and a discriminator that goes through the pictures of faces made by the generator and determines if they are real photos of faces or fake ones produced by the generator.  The discriminator is trained on a dataset of real photos of celebrities' faces.  Here is a sample of the photos in the training set:

![Sample face photos](/Assets/input_faces.jpg)

As the generator and discriminator train, the discriminator gets better at determining whether a photo produced by the generator looks like a face from the real data set, and the generator gets better at producing more realistic looking faces.  Here is a sample of the face images produced by the generator, after training both the descriminator and the generator:

![Generated face images](/Assets/generated_faces.jpg)
