Download Link: https://assignmentchef.com/product/solved-ee440-assignment-4-generate-a-noisy-version-of-an-image-by-adding-the-salt-and-pepper-noise
<br>
<ul>

 <li><strong> </strong><strong>bmp</strong> is a clean image, please generate a noisy version of it by adding the salt-and-pepper noise, with 15% of the pixels being altered by the noise. Use two different filters to reduce the noise. Show the original image, the generated noisy image, and two denoised results. Compare and write your comments on these two denoised results.</li>

</ul>

<strong><em>Hint:</em></strong><strong>  </strong>

<ol>

 <li>In adding the salt-and-pepper noise, pixels altered by the noise are randomly set to either black or white. For this problem, 50% of the altered pixels are set to black, and 50% of altered pixels are set to white.</li>

 <li>You could use a low pass filter and a median filter.</li>

 <li>You can use <em>imread</em> to read .bmp files. Other useful commands are<em> median</em>,</li>

</ol>

<strong>       </strong>

<ul>

 <li><strong> </strong>Write a program to sharpen <strong>bmp</strong> using a high boost filter. You can choose the scale factor by yourself.</li>

</ul>




<strong><em>Hint:</em></strong> 1. Useful MATLAB commands: <em>rgb2hsv</em>, <em>hsv2rgb</em>, and <em>conv2</em>.