# SDL-Optical-Detector-Assignment
Optical Detector Assignment for Space Detector Lab

This assignment involved two independent tasks.

The first was to calibrate Hubble images. To do so, I had to follow these steps:
Mask invalid data with MASKFILE
Remove bias level with BLEVFILE
Remove bias image with BIASFILE
Subtract dark with DARKFILE
Flatfield correction with FLATFILE
Photometry calibration with PHOTTAB,
and then compare my results with the science-ready files.

I carried out this comparison by calculating the mean of the values and the correlation between the three files, two at a time.
In addition, I calculated the magnitude of one specific point in one of the files, which I assume is a star, to check how similar the value was.

In the second task, I had to plot the area covered by vegetation and the land area over time, using Sentinel files and Google Earth images.
Afterwards, I made plots of those images for a visual comparison.
Finally, I compared the means and, again, the correlations between the manually processed Sentinel files and the science-ready files such as NDVI.

The conclusions of the comparisons can be found at the end of the respective code notebooks.
