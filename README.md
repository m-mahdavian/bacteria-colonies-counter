# bacteria-colonies-counter
This Python code has been developed for counting the bacteria colonies in the presence and absence of a bactericide.
# Overview
This program utilizes image processing techniques with OpenCV to count bacterial colonies in an image. It preprocesses the input image, identifies colonies through contour detection, and generates a visual representation of the results.

## Features
- Load grayscale images for analysis.
- Apply Gaussian blur to reduce noise in the image.
- Use thresholding to separate colonies from the background.
- Detect and filter contours based on area to exclude noise.
- Count and display the number of detected colonies.
- Highlight detected colonies with green contours in the output image.
- Save the processed result image for reference.

## Usage
1. Provide the correct file path to the image you want to analyze by updating the `image_path` variable in the script.
2. Run the program.
3. The program will output the number of detected colonies in the console and save the result image (`colonies_detected.jpeg`) in the same directory.

## Preprocessing the Input Image
Examples of the original image (`reference.jpeg`) and a preprocessed version (`reference-modified.jpg`) are provided. Preprocessing may be necessary depending on the quality of the input image. Enhancing the contrast between colonies and their surroundings can improve the program’s detection performance.

For preprocessing, you can use tools like Photoshop:
- Use selection tools combined with adjustment layers (available in the Layers menu) to tweak brightness/contrast, vibrance, hue, and saturation.
- Modify specific sections of the image by utilizing the Color Range option in the Select menu and replacing or enhancing colors as needed.

## Credits
This program leverages OpenCV for image processing and NumPy for array manipulations.

## License
This program is open-source. Feel free to modify and use it as needed.
