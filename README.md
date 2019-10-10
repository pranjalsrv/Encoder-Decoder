# An Autoencoder-Decoder Model to encrypt and compress images.


The Autoencoder encodes (128 x 128 x 3) images into a latent image of dimensions (16 x 16 x 8), hereby compressing the images.
The Decoder model then decodes the latent space images with reversed weights to regenerate the supplied image


## Here are the input images to the Autoencoder model, followed by its corresponding regenerated output image by the Decoder model:
![Encoder_decoder_output](/images/rgb_outputs.PNG)

## Here are their corresponding latent space visualization (these are technically not images. They are (16 x 16 x 8) matrices, transposed to produce a visual image)
![Latent_space_visualization](/images/rgb_latent_space.PNG)
