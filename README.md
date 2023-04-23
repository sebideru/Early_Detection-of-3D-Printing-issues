# Early detection of 3D printing issues
## Build a ML model to predict if there are any issues with the 3D print job based on close-up pictures taken by nozzle camera

### Community Prediction Competition

**3D printing** is an innovative way to fabricate parts from any 3D geometry model. However, 3D printing is also known to be prone errors. Most of these errors are visible via a close-up camera mounted right near the printer nozzle.

The goal of this competition is to predict 1 specific kind of error - under extrusion.
**Data Provided**-Training and Test Images came in 7 printer folders,Train and test CSV's given. Training images **(81,060)** ,Test Images **(25,279)**.
**Steps taken:- **
  1.Separation and merging of training and test files coming from the 7 printers into their respective folders.
  2.Separation of train,valdiation and test images from the training sets of images.
  3.Separation of images into their classes i.e. into has under extrusion or doesn't have under extrusion images for each image input.Train,Validation & test 2 classes each. 


