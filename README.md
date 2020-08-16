# image-classification
Basic Image Segmentation and Classification Using Superpixel Segmentation and K-means classification. Just a fun side project to try out some image classification techniques in and afternoon. 

# Summary

I downloaded a Eastern Washington RGB GeoTiff and used several superpixel algorithms to segment the landscape. Then basics statistics (mean, min, max, variance, skew...) were computed for each of the red, green, and blue bands within the segements. K-means classification was then used to define groupings within the segments and colored accordingly. 

- Numpy
- Gdal
- sci-kit learn

# First Test Results

### Original Download
![Original](https://github.com/metostom/image-classification/blob/master/Orginal.JPG)

### Classified Image
![Classified](https://github.com/metostom/image-classification/blob/master/Segmented.JPG)

# Thoughts

This simple method appears to correctly classify some areas but really does not seem to capture many finer differences in the landscape. Would be interested to apply this to a larger image with more variable landcover. Would need devote more time to accurately segment but not bad for an afternoon!
