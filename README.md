# Image Processing Assignment - EN3160

This repository contains Jupyter Notebooks and relevant resources for the EN3160 Assignment 1, focusing on intensity transformations and neighborhood filtering in image processing. The tasks involve a series of operations such as histogram equalization, gamma correction, vibrance adjustment, Sobel filtering, and zooming of images, with each step aiming to manipulate and enhance image features.

## Project Overview

This assignment covers the following tasks:

1. **Intensity Transformation**: Implementation of intensity transformations on images to enhance or alter their appearance based on specified criteria.
   
2. **Gamma Correction**: Applying gamma correction to images in the L\*a\*b\* color space and comparing the original and adjusted histograms.

3. **Vibrance Adjustment**: Adjusting the vibrance of an image by transforming the saturation plane to achieve a visually pleasing result.

4. **Histogram Equalization**: Implementation of custom histogram equalization for both the entire image and the foreground separately to enhance contrast.

5. **Sobel Filtering**: Application of Sobel filters to detect image gradients, including a custom implementation.

6. **Zoom Functionality**: Implementation of zoom functionality using both nearest-neighbor and bilinear interpolation methods. The performance of the zoom function is evaluated by comparing results using the normalized sum of squared differences (SSD).

7. **Image Segmentation**: Use of the GrabCut algorithm to segment the image and produce an enhanced version with a blurred background.

## Files and Structure

- **Adjust the vibrance of a photograph.ipynb**: This notebook processes an image by splitting it into its hue, saturation, and value (HSV) planes. It then applies a vibrance adjustment on the saturation plane to enhance color intensity and recombines the planes to produce the final image.

- **Gamma Correction.ipynb**: This notebook applies gamma correction to an image in the L*a*b* color space. It adjusts the brightness and contrast using a gamma value and compares the histograms of the original and adjusted images to highlight the correction effect.

- **Histogram Equalization.ipynb**: This notebook performs custom histogram equalization to enhance the contrast of an image. It shows the image's histogram before and after the equalization process, providing a clearer contrast-enhanced result.

- **Implementing Zoom Function.ipynb**: This notebook implements image zooming functionality using two methods: nearest-neighbor interpolation and bilinear interpolation. It tests the scaling function by zooming out and then scaling back up, comparing the result using the normalized sum of squared differences (SSD).

- **Intensity Transformation.ipynb**: This notebook performs intensity transformation based on a specific input-output intensity curve, allowing for the enhancement or manipulation of the image's appearance according to the transformation parameters.

- **Sobel Filter.ipynb**: This notebook applies the Sobel filter for edge detection. It compares the built-in `filter2D` method with a custom implementation, which manually applies the Sobel operator to compute gradients and detect edges in the image.

- **Segmentation.ipynb**: This notebook uses the GrabCut algorithm for image segmentation, separating the foreground from the background. It further processes the image by blurring the background while preserving the clarity of the foreground.


## Usage

### To run the notebooks:

```bash
# Clone the repository
git clone https://github.com/DinukaMadhushan1234/Intensity-Transformations-and-Neighborhood.git

# Navigate into the repository folder
cd Intensity-Transformations-and-Neighborhood
```
### Requirements
- Python 3.x
- Jupyter Notebook
- OpenCV
- NumPy
- Matplotlib

### Install the required dependencies
```bash
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

## Results
The results of each task are displayed as outputs in the corresponding Jupyter Notebooks. For more details, refer to the included report PDF.

## Author
This project was completed by Dinuka Madhushan as part of the EN3160 module of ENTC at University of Moratuwa.
