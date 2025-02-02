# k-means-clustering
 
A Python-based implementation of K-means clustering algorithms focusing on image processing applications.

## Project Overview
This repository contains Jupyter notebooks demonstrating K-means clustering applications in image processing:
- Image compression
- Color quantization
- Image segmentation
- Image Classification

## Project Structure
- [k-means-copmressing.ipynb](k-means-copmressing.ipynb) - Image compression using K-means
- [k-means-segmentation.ipynb](k-means-segmentation.ipynb) - Image segmentation implementation
- [detect-number-with-mnist](detect-number-with-mnist/) - MNIST digit recognition using K-means

## Requirements
- Python 3.x
- NumPy
- OpenCV (cv2)
- scikit-learn
- Matplotlib

## Features
- Image compression with configurable number of colors (K clusters)
- RGB color space clustering
- Interactive visualization of results
- Support for different image formats (jpg, jpeg)

## Usage
1. Open the Jupyter notebooks
2. Run the cells sequentially
3. Modify parameters like `n_clusters` to experiment with different results

## License
This project is released into the public domain - see the [LICENSE](LICENSE) file for details.

## Example Results
The notebooks demonstrate:
- Color reduction from millions to 8 colors
- Before/after comparisons of compressed images
- Visual representation of clustering results