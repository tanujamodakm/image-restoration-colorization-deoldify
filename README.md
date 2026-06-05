# Image Restoration and Colorization using DeOldify

This project demonstrates the restoration and colorization of black-and-white photographs using DeOldify, a deep learning-based image colorization model. The notebook allows users to upload a grayscale image, generate a colorized version, compare the results, and download the final output.

The goal of this project is to explore how artificial intelligence can bring old and monochrome photographs to life by automatically predicting realistic colors while preserving image details.

## Sample Results

### Original Image

![Original Image](sample_input.png)

### Colorized Output

![Colorized Output](sample_output.png)

### Side-by-Side Comparison

![Comparison](result_comparison.png)

## How It Works

1. Upload a black-and-white image.
2. Process the image using the DeOldify model.
3. Generate a colorized version.
4. Compare the original and output images.
5. Download the result.

## Technologies Used

* Python
* PyTorch
* DeOldify
* Google Colab
* PIL
* Matplotlib

## Acknowledgement

This project utilizes the DeOldify image colorization framework originally developed by Jason Antic. The implementation in this repository applies a pre-trained DeOldify model through Google Colab to restore and colorize black-and-white photographs.

Original Project:
https://github.com/jantic/DeOldify

Colab-Compatible Fork Used:
https://github.com/mmaithani/DeOldify

## License

This project is licensed under the MIT License.
