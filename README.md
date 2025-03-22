# Image Processing with Filters

This repository contains a set of image processing tools that implement various filters and techniques to analyze and manipulate images. The primary functionalities include applying Gaussian filters, edge detection, and highlighting specific areas in images based on color differences.

## Key Features

### Filters Class
The `Filters` class provides various methods to apply image filters, including:

- **Gaussian Filters**: Create 1D and 2D Gaussian kernels for blurring images.
- **Edge Detection**: Implement edge detection algorithms (Sobel, Prewitt, Roberts) to identify edges in images.
- **Custom Filters**: Generate custom filters for specific use cases.
- **Mono Filtering**: Apply a mono-dimensional filter to an image.
  
### Utility Functions
- **color_distance**: Calculate the Euclidean distance between the input image and a specified color.
- **highlight**: Overlay a specified color on areas of an image that meet certain criteria (e.g., based on a mask).
- **transform_in_gray**: Convert an RGB image to grayscale.
- **show_image**: Display images with optional sizing parameters.

Just run the notebook in a Google Collab environment.