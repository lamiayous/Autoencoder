# Autoencoder
The autencoder is composed of an encoder and decoder. The decoder takes the dimensions from the encoder and tries to generate and image. 

##Encoder:

The encoder was first trained by adding a decoder. The decoder in this case is used to validate the enocder. Essentially, the encoder returns a 256 dimension feature space, the decoder takes those number and tries recontrsuct an image. 

The image below shows how the image is passed through the encoder.

<p align="center">
<img width="671" alt="img_FindMe" src="https://github.com/lamiayous/FindMe/assets/124199862/ede24929-504e-4fe5-965a-f87b417aa606">
<p align="center">
                                            Encoder

##Decoder 
The decoder in it's architecture is the exact mirror image of the encoder as shown below. The decider, as explained above, is fundamentally used for "image recotruction part of the Project.

#Image Reconstruction 

Below you can see the original input image and the recontructed image.

<p align="center">

<img width="124" alt="orig" src="https://github.com/lamiayous/Autoencoder/assets/124199862/11c6c3f6-fbbe-466e-91f7-a2fee574e66e"> <img width="124" alt="reconstructed" src="https://github.com/lamiayous/Autoencoder/assets/124199862/7f6c3857-31a3-4c9a-8768-ca199ca0d3d7"> 
<p align="center">
