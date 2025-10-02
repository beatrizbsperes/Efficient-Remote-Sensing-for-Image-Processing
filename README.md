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

3. **Notebook 3**: For this new chapter we will focus on spatial operations, such as:
    - Code the correlation/convolution operator
        - with loops, without relying on Python convolution function
        - using functions available in Python (like `NumPy` and `SciPy`)
    - Apply correlation/convolution with basic kernels
        - `W = 0`, `W = Id`, `W = 1`
        - `|W|` lower/greater/equal to 1, equal to 0 (with some `wi` negative)
    
    You can find the notebook [here](task3_spatial_based_processing.ipynb).