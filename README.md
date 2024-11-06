# Image Processing Techniques Project
This project demonstrates several fundamental image processing techniques in Python, implemented as part of a Digital Image Processing course assignment.

### Project Overview

This project demonstrates several fundamental image processing techniques in Python, implemented as part of a Digital Image Processing course assignment. The goal is to manipulate and enhance images using a variety of methods to achieve better visual quality and highlight important details within the images.


### Installation

To run this project, you’ll need Python and a few essential packages. You can install the required packages using:

```{p} pip install numpy matplotlib opencv-python```

### Project Structure

* Histogram Plotting: Visualizes the pixel distribution within the image.
* Histogram Equalization: Enhances contrast by redistributing pixel intensity values.
* Bicubic Interpolation (Image Enlargement): Doubles the image size for a clearer view.
* Unsharp Masking & High-Boost Filtering: Sharpens the image by emphasizing high-frequency components.
* DFT Shifting: Applies Discrete Fourier Transform and shifts to center the low frequencies.
* Gaussian Filter: Applies a Gaussian filter to smooth or blur the image.
* Inverse DFT: Reverts the DFT transformation, displaying the final enhanced image.
* Visualization: Combines all the processed images and histograms into a single plot.


### Techniques Used

1. Histogram Equalization
Enhances image contrast by redistributing the pixel intensity distribution, resulting in clearer details.
2. Bicubic Interpolation
Resizes the image to double its original size for improved clarity.
3. Unsharp Masking and High-Boost Filtering
Sharpens the image by subtracting a blurred version, making edges and details more pronounced.
4. Fourier Transform and Gaussian Filtering
Transforms the image into the frequency domain to analyze and enhance specific features.
5. Inverse Fourier Transform
Applies the inverse transformation to display the final, processed image in the spatial domain.

### Results

The final output is a collection of enhanced images and histograms that illustrate the effects of each processing technique. Each step is plotted for clear visualization and comparison.

### License

This project is for educational purposes and is available under the MIT License.