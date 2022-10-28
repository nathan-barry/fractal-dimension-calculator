# fractal-dimension-calculator

This is a jupyter notebook that allows you to calculate the fractal dimension of any image you input.

## Process
1. Reads image from given URL
2. Converts it to gray scale
3. Crops to 1024x1024 from the center
4. Calculate average grayscale value of matrix
5. Threshold matrix by average value
6. Box counts the matrix via iterating scale size by powers of two while counting number of boxes with fractal pattern
7. Feed results through power regression model
