
# Image Brightness Calculator

Consider a grayscale image represented as a 2D matrix where each element represents a pixel value between 0 (black) and 255 (white):

$$
Image = \begin{pmatrix}
p_{11} & p_{12} \\
p_{21} & p_{22}
\end{pmatrix}
$$

The average brightness is calculated as:

$$
Brightness = \frac{\sum_{i=1}^{m} \sum_{j=1}^{n} p_{ij}}{m \times n}
$$

Where:

1) $p_{ij}$ is the pixel value at position $(i,j)$  
2) $m$ is the number of rows  
3) $n$ is the number of columns  

### Things to Note:

1) All pixel values must be between 0 and 255  
2) The image matrix must be well-formed (all rows same length)  
3) Empty or invalid images return -1  
