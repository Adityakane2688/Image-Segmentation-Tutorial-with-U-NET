# Image-Segmentation-with-U-NET
This Project is on image segmentation using the U-Net architecture. Image segmentation is a computer vision task that involves dividing an image into meaningful segments or regions. U-Net is a popular neural network architecture for semantic and instance segmentation tasks.

for testing you can download the dataset from here:
https://www.kaggle.com/competitions/carvana-image-masking-challenge/data


# Setting Up Data Folders for Training and Validation

To organize your data for training and validation, follow these steps:

1. Create a folder named 'data'.

2. Inside the 'data' folder, create four subfolders with the following names:
   - `train_images`
   - `train_masks`
   - `val_images`
   - `val_masks`

3. Place the `train.zip` files inside the `train_images` folder. This is where your training images will be stored.

4. Put the `train_masks.zip` files inside the `train_masks` folder. This is where your training masks will be stored.

5. Select some files from the `train_images` folder and move them to the `val_images` folder. These images will be used for validation.

6. Similarly, move corresponding mask files from the `train_masks` folder to the `val_masks` folder. These masks will be used for validation as well.



