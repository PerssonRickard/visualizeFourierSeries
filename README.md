# VisualizeFourierSeries

## Introduction
Complex functions are two dimensional in the sense that they have both a real and an imaginary part. Complex functions may therefore be used to draw images in the complex plane since the real and imaginary parts can represent the x- and y-coordinates respectively of the drawn image. This application lets the user draw an image (which can be thought of as a complex function) and then approximates the complex function described by the image using a complex fourier series. In the same way a real valued function can be approximated by sinusoids with different frequencies, a complex valued function can be approximated by complex exponentials with different frequencies. These complex exponentials can be visualized as rotating vectors and since the complex fourier series is a sum of these complex exponentials the complex fourier series may also be visualized.

## Examples

<p align="center">
  <img src="demoWithCircles.gif">
</p>

The above image shows the circle boundaries which each vector is constricted to rotate within. The image below shows the same image being drawn but without the circle boundaries.

<p align="center">
  <img src="demoWithoutCircles.gif">
</p>

The user may draw any image and the application will find the corresponding complex fourier series.

<p align="center">
  <img src="drawing.gif">
</p>
