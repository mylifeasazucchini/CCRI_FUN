# Repo for registering histology images from different microscopes

The current results can also be downloaded/viewed from this repo as well.

Good_Tile.png = Best candidate tile corresponding to the IMC image (this will be fed to the reg_help as source_img)

IMC.png = IMC Image (the image which will be found and will be fed to the reg_help as target_img)

Registered_CZI.png = Result of registeration between the above two 

## To replicate the code for your images:

#### Copy "Register_Cells.ipynb" and the "reg_help.py" file to your local dir
#### Install requirements as shown below:
pip install aicsimageio aicsimageio[czi] scipy scikit-image


#### Note that a number of factors affect the image registaration results such as the scale factor for resizing the CZI image, tile size, tile offset. I only played with about 3-4 settings due to limited time.

