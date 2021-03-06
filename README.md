# python-face_recognition
Building a basic facial recognition model while learning to do so.

### Explanation of use:
 - Photos stored in the ./known folder are used as references for identification.
 - Photos stored in the ./unknown folder are analyzed and compared to the photos of the ./known folder,
   and will either be labeled as known, with the correct name applied, or unknown. NOTE: the distance of 
   accuracy for your matches can be displayed with the second command in this readme.
 - The names of the photos in the ./known folder are what will be used to label potential matches, it's
   essential to use meaningful and/or accurate names for known photos.

## To run the basic comparison
 -      face_recognition ./known ./unknown

## To run the comparison and display the percentage of difference/accuracy/distance
 -      face_recognition --show-distance true ./known ./unknown
