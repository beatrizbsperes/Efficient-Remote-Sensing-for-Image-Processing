# Efficient-Remote-Sensing-for-Image-Processing
On this repository you'll find the notebooks used for practicing for the course of Efficient Remote Sensing for Image Processing.

1. **Notebook 1**: Basic operations with raster data using `rasterio` and `numpy`. It covers reading, writing and manipulating raster datasets. You can find that notebook [here](task1_handling_images.ipynb).

2. **Notebook 2**: Folowing the introduction from the previous notebook we will:
    - Load an image
    - Compute its negative
    - Without & with a LUT, apply a gamma correction (report the efciency gain)
    - Code the histogram equalization function
    - Check if `histeq(negative(image))==negative(histeq(image))`
    - Perform a contrast stretch clipping the 5% extrema
    - Play with multi-image operators (NDVI extraction)
    
    You can find the notebook [here](task2_point_based_processing.ipynb).