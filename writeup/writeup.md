# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:

* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report

<!---
your comment goes here
-->

[//]: # (Image References)

[image1]: ../test_images_output/i_gray.png "Gray"
[image2]: ../test_images_output/i_blurred.png "Blurred Gray"
[image3]: ../test_images_output/i_canny.png "Canny Edge Detection"
[image4]: ../test_images_output/i_mask1.png "Canny Edge Detection (Mask applied)"
[image5]: ../test_images_output/i_mask2.png "Mask Lines"
[image6]: ../test_images_output/i_hough.png "Lines Detected (Hough Transform)"
[image7]: ../test_images_output/solidWhiteCurve_1.jpg "solidWhiteCurve_1"
[image8]: ../test_images_output/solidWhiteRight_1.jpg "solidWhiteRight_1"
[image9]: ../test_images_output/solidYellowCurve2_1.jpg "solidYellowCurve2_1"
[image10]: ../test_images_output/solidYellowCurve_1.jpg "solidYellowCurve_1"
[image11]: ../test_images_output/solidYellowLeft_1.jpg "solidYellowLeft_1"
[image12]: ../test_images_output/whiteCarLaneSwitch_1.jpg "whiteCarLaneSwitch_1"
[image13]: ../test_images_output/solidWhiteCurve_2.jpg "solidWhiteCurve_2"
[image14]: ../test_images_output/solidWhiteRight_2.jpg "solidWhiteRight_2"
[image15]: ../test_images_output/solidYellowCurve2_2.jpg "solidYellowCurve2_2"
[image16]: ../test_images_output/solidYellowCurve_2.jpg "solidYellowCurve_2"
[image17]: ../test_images_output/solidYellowLeft_2.jpg "solidYellowLeft_2"
[image18]: ../test_images_output/whiteCarLaneSwitch_2.jpg "whiteCarLaneSwitch_2"
---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

* My pipeline consisted of 6 steps: 
	1. First, I converted the input image to gray-scale, a necessary prior process to compute the gradient and the edge-detection later. An illustration is shown in the next figure:
       
        ![alt text][image1]
        
 	1. Next, 
 
* In order to draw a single line on the left and right lanes, I modified the draw_lines() function by ...

<!---
![alt text][image1]  ![alt-text][image2]
-->

### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...
