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
    - For a given spatial operator, compare the ltering effect and CPU time when increasing the kernel size.
    - For a given spatial operator, compare the ltering effect and CPU time for a 2D separable kernel and its 1D alternatives.
    - Compare the results of different smoothing operators.
    - Compare the results of different sharpening operators.
    - Compare the results of different edge detection operators.
    - Are smoothing/sharpening operators invertible?
    - Compare the linear and nonlinear ltering operators.
    - Propose separable implementations of nonlinear operators.
    - Verify the ability of edge-preserving smoothing lters.
    
    You can find the notebook [here](task3_spatial_based_processing.ipynb).