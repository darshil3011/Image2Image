# Remove watermark from images using Deep learning

This github repo is an illustration of my medium blog - ["How and Why to train Image to Image deep learning models"](https://thinkinbytes.medium.com/how-and-why-to-train-image-to-image-deep-learning-models-5770bea0cab1)

Image to Image model takes an image as an input and generates a modified or reconstructed version of that image as an output. That is why it is also known as generative networks.

### Industry usecases :
  - Denoising Medical Xrays
  - Denoising satellite and astronomical images 
  - Reconstructing distorted/blurry images 
  - Removing obstacles from images
  - Colourizing black and white images
  - Generating architechtural designs from floor plans (Coming Soon on my Github!)

I have covered a unique use-case here which will be appreciated by graphic designers and Photoshop users. I am going to remove watermark on the images using deep learning. I will demonstrate the same using two models.
  - Autoencoder based CNN Model
  - Pyramid Real Image Denoising Network (PridNET)

I have included both the model architechtures in the notebook. You can choose whichever model you want to train. The model is computationally heavy, so make sure to modify batch_size and steps_per_epoch as per your preference. Due to computational and time limitations, I could only train it for 10 epochs. You can observe that watermark has not completely removed but it has blended into the image and its intensity is quite low. If you train this with huge dataset for more number of training epochs, it will definately provide impactful results.

### Results :

![Watermark removal using PRIDNet](https://github.com/darshil3011/Image2Image/blob/main/results/Screenshot%20from%202022-06-03%2013-31-24.png)

![Watermark removal using PRIDNet](https://github.com/darshil3011/Image2Image/blob/main/results/Screenshot%20from%202022-06-03%2013-31-48.png)

![Watermark removal using PRIDNet](https://github.com/darshil3011/Image2Image/blob/main/results/Screenshot%20from%202022-06-03%2013-32-07.png)


### Connect with me: 

- Github - https://github.com/darshil3011
- Medium - https://thinkinbytes.medium.com
- LinkedIn - https://linkedin.com/in/darshil-modi3011
