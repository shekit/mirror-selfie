# Mirror-selfie
Removing the phone from the notorious mirror selfie using deep learning

# Demo Video

![](no-phone.gif)

# How to run

The notebooks were created and run in Google colab. A google colab runtime resets every 12 hours. You can link it to your google drive to help with file persistence.

- **mirror_selfie.ipynb** - detect masks and do inpainting based on your trained model
- **training_inpainting.ipynb** - train the inpainting model on your own dataset

## Code is based on the following work:

- https://github.com/matterport/Mask_RCNN
- https://github.com/MathiasGruber/PConv-Keras
