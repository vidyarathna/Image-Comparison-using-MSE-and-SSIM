### Image-Comparison-using-MSE-and-SSIM

This repository contains a Python script (`compute_ssim.py`) that compares images using MSE (Mean Squared Error) and SSIM (Structural Similarity Index). It utilizes OpenCV, NumPy, skimage.metrics, and matplotlib libraries.

### Features

- **Mean Squared Error (MSE)**: Calculates the error between two images based on pixel differences.
- **Structural Similarity Index (SSIM)**: Measures the similarity between two images based on luminance, contrast, and structure.
- **Visualization**: Generates visual comparisons between images using matplotlib.

### Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)
- scikit-image (`pip install scikit-image`)
- Matplotlib (`pip install matplotlib`)

### Usage

To compare images using MSE and SSIM, run the script with the following command:

```bash
python compute_ssim.py
```

### Example

Ensure that your script loads images from the specified paths (`input_images/jp_gates_original.png` and `input_images/jp_gates_contrast.png`) and performs comparisons as demonstrated in the script.

### Notes

- Make sure to have the required libraries installed (`opencv-python`, `numpy`, `scikit-image`, `matplotlib`) before running the script.
- Adjust paths and filenames according to your specific file locations and naming conventions.
