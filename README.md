# Image-Processing
Image processing Using openCV

Image Processing Implementations in OPENCV

Step 1: load the image and convert it to a grayscale image
After compiling the example code in Section II, in this section, you now have to fill the missing parts in
the file “imgprocessing.py”. For this purpose, open “imgprocessing.py” from your IDE or with any text
editor.
In this step, you will load the image and assign it to a variable (e.g. “img”), then convert it to a grayscale
image.
When compiling this program, similar to the example code introduced in Section II, you will click on the
button “Run file” if you are working on an IDE or, if you are working on the prompt, you will go to the
location of your folder

Step 2: apply Histogram Equalization
In this step, you will apply histogram equalization to the grayscale image (Output of Step 1).
You might use the following functions: cv2.equalizeHist

Step 3: flip the image; first turn the image upside down and then reflect the
image in the x direction
In this step, you will apply upside down operation and reflection in the x direction to the image for which
histogram equalization is applied (Output of Step 2) and show the images computed.
You might use the following functions: cv2.flip

Step 4: apply filtering
In this step, first, you will apply some filtering (atleast 3) to the image for which histogram equalization
is applied (Output of Step 2) and show the image computed.
You might use the following functions: cv2.medianBlur, cv2.GaussianBlur, cv2.bilateralFilter (non
exhaustive)

Step 5: apply Operator to compute Edge Image
In this step, first, you will apply operators to the filtered image (Output of Step 4) and show the resultant
edge image (atleast 2 edge detection methods).
You might use the following functions: cv2.Laplacian, cv2.Canny, cv2.Sobel (non exhaustive),
cv2.convertScaleAbs, cv2.addWeighted
