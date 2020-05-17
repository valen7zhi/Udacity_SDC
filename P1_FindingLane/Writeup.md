# **Finding Lane Lines on the Road** 

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.
Basically the idea of implementation of this project is apply everthing I've learned from the corresponding course content.

First, I converted the images to grayscale, then I smoothed the image.

Then apply the canny algorithm from the OpenCV library to the processed image. After this, the original draw_line function is capable of generating decent output. 

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by implement an algorith that separate the sides of line segments and then calculate intercepts by the condition statements. 

[//]: # (Image References)
[image1]: ./before1.png "Before"
[image2]: ./after1.png "After"

Using original algorithm

![alt text][image1]

After implementing the new algorithm

![alt text][image2]



