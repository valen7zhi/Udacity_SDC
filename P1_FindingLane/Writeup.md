# **Finding Lane Lines on the Road** 

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I smoothed the image.

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by implement an algorith that separate the sides of line segments and then calculate intercepts by the condition statements. 

Using original algorithm
[image1]: ./before1.png

After implementing the new algorithm
[image2]: ./after1.png




