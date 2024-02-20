# Preprocessing steps:

- Original image had 2048*1532 for each image. This is a large size to process.
- Original dataset had 20 to 23 images for each classes.
- Cropped all possible 640*640 from the original image. Leading to 6 patches per image.
- To reduce quality loss during the preprocess technique of the patches, interpolation method is used.
