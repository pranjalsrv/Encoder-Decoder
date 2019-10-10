# An Autoencoder-Decoder Model to encrypt and compress images.


The Autoencoder encodes (128 x 128 x 3) images into a latent image of dimensions (8 x 8 x 64), hereby compressing the images.
The Decoder model then decodes the latent space images with reversed weights to regenerate the supplied image
