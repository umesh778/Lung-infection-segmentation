### Instructions for Running the Code

#### Prerequisites:
1. Install required libraries:

   pip install tensorflow keras segmentation-models numpy matplotlib pandas sklearn nibabel imgaug opencv-python
2. Place dataset files and metadata.csv in the specified directory.

3. To download and unzip the extracted dataset, use the download_and_extract_files .

#### Training the Models:
1. **Lung Segmentation using U-Net**:
   - Run 'lung_segmentation_unet.py' to train the U-Net model.
   - The best model checkpoint will be saved as 'unet_lung_segmentation.h5'.

2. **Infection Segmentation using U-Net**:
   - Modify the script to load infection masks and train the U-Net model.
   - Save the checkpoint as 'unet_infection_segmentation.h5'.

3. **Lung Segmentation using DeepLabV3+**:
   - Train the DeepLabV3+ model with the dataset and save the checkpoint as 'lung_segmentation_with_deeplabv+.h5'.

#### Testing the Models:
1. Ensure model checkpoints are in the same directory as the script.
2. Run testing functions to evaluate models and visualize predictions.

#### Results:
- Metrics (Dice, IoU, etc.) and visualizations will be displayed or saved for review.

