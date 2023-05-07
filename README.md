Download Link: https://assignmentchef.com/product/solved-homework-1-csci-381-780-image-processing
<br>
<ol>

 <li>Write a script in Python to compute the histogram of a color image (<strong>Note: do not use any predefined function like </strong><strong>calcHist() or np.histogram() to obtain the histogram</strong>). The script also has to plot the histograms of each band of the image separately (Read, Green, and Blue), as well as the gray level intensity image resulting of averaging the color bands. Use OpenCV, numpy,  and Matplot to load, process,  and visualize the information.</li>

</ol>

Capture two images (one underexposed, and one overexposed) using your cell phone or digital camera from the same scene. Use the developed program to plot the histograms from the captured images. Describe briefly the differences in the histograms.

<ol start="2">

 <li>Capture an image with a uniform background, then put an object on the scene and get a second image of the scene. Create a program to process the previous two images; the script has to generate a binary image, where the pixels belonging to the object (foreground) take values of one and pixels from the background takes values of zero respectively. To do this, use the subtraction operator to obtain the difference between the first image and the second image, and then apply a thresholding process to generate the binary image.</li>

</ol>

Test different values for the threshold until obtaining the best results. Quantify the number of pixels that belong to the object of interest.  Visualize histograms and the binary image.  Describe briefly the results.

<ol start="3">

 <li>Develop a script in Python to generate an image in false color using the hyperspectral image “TIPJUL1.LAN”—which is composed of 7 bands; the 4<sup>th</sup> band corresponds to the infrared region, and the 3<sup>th</sup> and 2<sup>nd</sup> bands represent the visible red and green color respectively.

  <ul>

   <li>For the false color image, use the following combination of bands:</li>

  </ul></li>

</ol>

o Red color: band 4  o Green color: band 3  o Blue color: band 2

(Note: the resulting image should show vegetation in red color)

<ul>

 <li>Generate the NDVI image from the hyperspectral image, and then use cosine( ) or sine( ) functions to obtain a color image from the NDVI image (see Figure 1).</li>

 <li>Display the color scale image, which is an image that shows the range of colors generated using the color transformation (see Figure 2). Do not use any build-in function.</li>

</ul>







Figure 1. Color Transformation







Figure 2. Color scale




<ol start="4">

 <li>Write a python script to obtain the raster of the Lidar image “17258975.las”. The resolution of the Lidar image is 2ppm, and the units of Longitude, Latitude, and altitude are in meters. Use 8m for the length of each cell in the raster.</li>

</ol>


