
License Plates - v4 Augmented License Plates
==============================

This dataset was exported via roboflow.ai on April 18, 2021 at 4:52 AM GMT

It includes 2555 images.
Plates are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 10 versions of each source image:
* 50% probability of horizontal flip
* Randomly crop between 0 and 20 percent of the image
* Random rotation of between -15 and +15 degrees
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically
* Random exposure adjustment of between -25 and +25 percent
* Salt and pepper noise was applied to 5 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* Random brigthness adjustment of between -25 and +25 percent
* Random exposure adjustment of between -25 and +25 percent
* Random Gaussian blur of between 0 and 10 pixels
* Salt and pepper noise was applied to 5 percent of pixels


