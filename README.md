Questions:
1. Does it matter whether the picture has been taken by a 1Mpx camera or a 12Mpx camera? How?
   - However, at different resolutions of the image, the scale of objects in the image changes.
   - For example, at higher resolutions, the image contains more details, and objects may be shown with a higher level of detail.
   - So increasing the resolution can lead to a more accurate corner detection while also adding more noise or weak features to the detection,
   - and it will also increase the computational load when computing Harris corners
2. If we increased the resolution of the camera, what would you change in the current algorithm?
   - To compensate for the downsides of increasing the image resolution, it is necessary to adjust the threshold value to filter out weak features,
   - as well as increase the window size used for computing Harris corners to enhance performance and cover a larger area at once.





